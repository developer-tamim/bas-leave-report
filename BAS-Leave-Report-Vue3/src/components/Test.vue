<template>
    <div>
      <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight">See details</button>

      <table class="table">
        <thead>
          <tr data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight">
            <th>Date</th>
            <th>Leave Type</th>
            <th>Status</th>
            <th>Approved/Rejected By</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>02/26/2024</td>
            <td>Sick Leave</td>
            <td>Approved</td>
            <td>Mohammed Shumon</td>
          </tr>
          <tr>
            <td>02/26/2024</td>
            <td>Sick Leave</td>
            <td>Approved</td>
            <td>Shimul Barua</td>
          </tr>
          <tr>
            <td>02/26/2024</td>
            <td>Married Leave</td>
            <td>Approved</td>
            <td>Mohammed Kaium Uddin</td>
          </tr>
          
        </tbody>
      </table>

<div class="offcanvas offcanvas-end" style="width:50%" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
  <div class="offcanvas-header">
    
    <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
  </div>
  <div class="offcanvas-body">
    <div class="card m-3" style="border:none">
      <div class="card-body">
          
        <!-- employee details -->
        <section>
          <div class="row">
            <div class="col-4">
              <div>
                <div class="rounded-container">
                    <img src="../assets/default_profile.png" class="rounded-circle rounded-image" alt="Profile Image">
                </div>
            </div>
            </div>
            <div class="col-8">
              <h5 class="bold">Mohammad Kaium Uddin</h5>
              <h5>CoOrdinator <span>(Software & Accounting Team)</span></h5>
              <span>ID: ISL 12025</span><br>
              <span>Chittagong, BD</span>
            </div>
          </div>
        </section>
        <!-- employee details -->

        <!-- employee sub details -->
        <section>
          <div class="row m-2">
            <div class="col-4">
              <div class="row my-3" >
                <div class="col-3">
                  <i class="fa-regular fa-clock" style="font-size: 25px;"></i>
                </div>
                <div class="col-9">
                  <span>01/05/2015</span><br>
                  <span>8 years</span>
                </div>
              </div>
            </div>
            <div class="col-4">
              <div class="row my-3">
                <div class="col-3">
                  <i class="fa-solid fa-phone-volume" style="font-size: 25px;"></i>
                </div>
                <div class="col-9">
                  <span>+880 1234 456789</span><br>
                  <span>kaium@gmail.com</span>
                </div>
              </div>
            </div>
            <div class="col-4">
              <div class="row my-3">
                <div class="col-3">
                  <i class="fa-solid fa-house" style="font-size: 25px;"></i>
                </div>
                <div class="col-9">
                  <span>Chittagong Branch</span><br>
                  <span>Day shift</span>
                </div>
              </div>
            </div>
           
          </div>
        </section>
        <!-- employee sub details -->

        <!-- tabs & date -->
        <section>
          <div class="row m-2">
           
            <div class="col-5">
              <div class="row">
                <div class="col-4">
                  <input type="radio" class="btn-check" name="options-outlined" id="success-outlined" autocomplete="off" checked>
<label class="btn btn-outline-success" for="success-outlined">Leave</label>
                </div>

                <!-- <div class="col-4">
                  <input type="radio" class="btn-check" name="options-outlined" id="success-outlined" autocomplete="on" checked>
<label class="btn btn-outline-success" for="success-outlined">Home</label>
                </div> -->

                <div class="col-4">
                  <input type="radio" class="btn-check" name="options-outlined" id="danger-outlined" autocomplete="off">
<label class="btn" for="success-outlined">Late</label>
                </div>

              </div>
            </div>
            <div class="col-2"></div>
            <div class="col-5">
              <div class="row">
                <div class="col-4 btn btn-danger">test</div>
                <div class="col-4 btn btn-danger">test</div>
                <div class="col-4 btn btn-danger">test</div>
              </div>
            </div>
           
          </div>
        </section>
        <!-- tabs & date -->
        
        <!-- table -->
        <div class="mt-4">
          <table class="table">
            <thead>
              <tr>
                <th>Date</th>
                <th>Leave Type</th>
                <th>Status</th>
                <th>Approved/Rejected By</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>02/26/2024</td>
                <td>Sick Leave</td>
                <td>Approved</td>
                <td>Mohammed Shumon</td>
              </tr>
              <tr>
                <td>02/26/2024</td>
                <td>Sick Leave</td>
                <td>Approved</td>
                <td>Shimul Barua</td>
              </tr>
              <tr>
                <td>02/26/2024</td>
                <td>Married Leave</td>
                <td>Approved</td>
                <td>Mohammed Kaium Uddin</td>
              </tr>
              
            </tbody>
          </table>
        </div>
        <!-- table -->
      </div>
    </div>
  </div>
</div>
    </div>
  </template>
  
  <script>
  export default {
     
  };
  </script>
  