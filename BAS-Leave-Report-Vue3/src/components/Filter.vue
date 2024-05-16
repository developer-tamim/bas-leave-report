<template>
  <div>
    <div class="card-body">
      <h4>Filters</h4>
      <div class="form-group mb-3">
        <label for="attend">Attend</label><br />
        <select id="attend" class="form-control">
          <option value="All">All</option>
          <option value="Mohammed Kaium Uddin">Mohammed Kaium Uddin</option>
          <option value="Abu Zahin">Abu Zahin</option>
        </select>
      </div>
      <div class="form-group mb-3">
        <label for="from">From</label><br />
        <input type="date" id="from" value="2024-01-01" class="form-control" />
      </div>
      <div class="form-group mb-3">
        <label for="to">To</label><br />
        <input type="date" id="to" value="2024-01-30" class="form-control" />
      </div>
      <div class="form-group mb-3">
        <label for="team">Team</label><br />
        <select id="teamFilter" class="form-control">
          <option value="All">All</option>
          <option value="Team 1">Team 1</option>
          <option value="Team 2">Team 2</option>
        </select>
      </div>
      <div class="form-group mb-3">
        <button class="btn btn-danger">Reset</button>
        <button class="btn btn-export">Export</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Filter",
};
</script>
