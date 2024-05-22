<template>
  <div class="my-4 px-4">
    <div class="row">
      <!-- Left sidebar -->
      <div class="col-lg-2 col-md-4 order-md-2">
        <div class="sticky-top">
          <div class="card p-3">
            <!-- Filter -->
            <Filter/>
            <!-- Filter -->
          </div>
        </div>
      </div>

      <!-- Main content -->
      <div class="col-lg-10 col-md-8 order-md-1">
        <div class="card">
          <div class="card-body">
            <div class="row mb-2">
              <div class="col-sm-4 col-md-6 col-lg-9">
                <h4 style="font-weight: 600; text-transform: uppercase;">Employee Report</h4>
              </div>
              <div class="col-sm-8 col-md-6 col-lg-3">
                <div class="form-group" style="margin-left: auto;">
                  <input type="text" class="form-control" id="searchInput" placeholder="Search..." />
                </div>
              </div>
            </div>

            <!-- Table -->
            <Table/>
            <!-- Table -->

          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Table from './Table.vue';
import Filter from './Filter.vue';

export default {
  name: 'LeaveReport',
  components: { Table, Filter },
};
</script>

<style scoped>
@media (max-width: 767px) {
  .filter-dropdown {
    cursor: pointer;
  }
}
</style>
