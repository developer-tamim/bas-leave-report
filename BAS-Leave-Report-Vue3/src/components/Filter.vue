<template>
  <div>
    <div class="card-body">
      <div class="filter-dropdown mb-3" @click="toggleFilters">
        <h3 class="bold">Filter</h3>
      </div>
      <transition name="fade">
        <div v-show="showFilters || isLargerScreen">
          <div class="form-group mb-3">
            <label for="attend" class="bold">Attend</label><br />
            <select id="attend" class="form-control">
              <option value="All">All</option>
              <option value="Mohammed Kaium Uddin">Mohammed Kaium Uddin</option>
              <option value="Abu Zahin">Abu Zahin</option>
            </select>
          </div>
          <div class="form-group mb-3">
            <label for="from" class="bold">From</label><br />
            <input type="date" id="from" value="2024-01-01" class="form-control" />
          </div>
          <div class="form-group mb-3">
            <label for="to" class="bold">To</label><br />
            <input type="date" id="to" value="2024-01-30" class="form-control" />
          </div>
          <div class="form-group mb-3">
            <label for="team" class="bold">Team</label><br />
            <select id="teamFilter" class="form-control">
              <option value="All">All</option>
              <option value="Team 1">Team 1</option>
              <option value="Team 2">Team 2</option>
            </select>
          </div>
          <div class="form-group mb-3">
            <button class="btn btn-danger me-2">Reset</button>
            <button class="btn btn-export">Export</button>
          </div>
        </div>
      </transition>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      showFilters: false,
      isLargerScreen: false,
    };
  },
  methods: {
    toggleFilters() {
      if (!this.isLargerScreen) {
        this.showFilters = !this.showFilters;
      }
    },
    checkScreenSize() {
      this.isLargerScreen = window.innerWidth >= 768; // Adjust the breakpoint as needed
    },
  },
  mounted() {
    this.checkScreenSize();
    window.addEventListener('resize', this.checkScreenSize);
  },
  beforeDestroy() {
    window.removeEventListener('resize', this.checkScreenSize);
  },
};
</script>

<style>
@media (min-width: 768px) {
  .filter-dropdown {
    cursor: default;
  }
}
</style>
