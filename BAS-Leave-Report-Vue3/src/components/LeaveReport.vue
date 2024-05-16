<template>
    <div class="my-4 px-4">
      <div class="row">
        <!-- Left sidebar -->
        <div class="col-lg-2 col-md-4 order-md-2">
          <div class="sticky-top">
            <div class="card p-3" id="filterSection">
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
  import Table from './Table.vue'
  export default {
    name: 'LeaveReport',
	components: { Table },
   
  };
  </script>
  
  <style scoped>
  /* Add your styles here */
  </style>
  