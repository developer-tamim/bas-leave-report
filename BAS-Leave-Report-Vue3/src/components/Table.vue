<template>
  <div class="class-name">
    <!-- Table -->
    <div class="table-container">
      <table class="table table-striped table-hover">
        <thead class="sticky-top">
          <tr class="tableheader" style="white-space: nowrap">
            <th>ID</th>
            <th>Name</th>
            <th>Designation</th>
            <th>Team</th>
            <th>Leave</th>
            <th>Home Office</th>
            <th>Late</th>
            <th>Year of Service</th>
            <th>Joining Date</th>
          </tr>
        </thead>
        <tbody>
          <!-- <tr v-for="(row, index) in rows" :key="index">
            <td>{{ row.id }}</td>
            <td>{{ row.name }}</td>
            <td>{{ row.designation }}</td>
            <td>{{ row.team }}</td>
            <td>{{ row.leave }}</td>
            <td>{{ row.homeOffice }}</td>
            <td>{{ row.late }}</td>
            <td>{{ row.yearsOfService }}</td>
            <td>{{ row.joiningDate }}</td>
          </tr> -->
        
          <tr>
            <td>ISL 12025</td>
            <td>Mohammed Shumon</td>
            <td>HR</td>
            <td>Appraisal</td>
            <td>5 day</td>
            <td>3 day</td>
            <td>1 day</td>
            <td>14 years</td>
            <td>02/26/2008</td>
          </tr>
          <tr>
            <td>ISL 12025</td>
            <td>Mohammed Shumon</td>
            <td>HR</td>
            <td>Appraisal</td>
            <td>5 day</td>
            <td>3 day</td>
            <td>1 day</td>
            <td>14 years</td>
            <td>02/26/2008</td>
          </tr>
          <tr>
            <td>ISL 12025</td>
            <td>Mohammed Shumon</td>
            <td>HR</td>
            <td>Appraisal</td>
            <td>5 day</td>
            <td>3 day</td>
            <td>1 day</td>
            <td>14 years</td>
            <td>02/26/2008</td>
          </tr>
          <tr>
            <td>ISL 12025</td>
            <td>Mohammed Shumon</td>
            <td>HR</td>
            <td>Appraisal</td>
            <td>5 day</td>
            <td>3 day</td>
            <td>1 day</td>
            <td>14 years</td>
            <td>02/26/2008</td>
          </tr>
         
        </tbody>
      </table>
    </div>

    <!-- pagination -->
    <div class="pagination">
      <button>&lt;</button>
      <button class="active">1</button>
      <button>2</button>
      <button>3</button>
      <button>4</button>
      <button>5</button>
      <button>&gt;</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Table",
  // data() {
  //   return {
  //     rows: [],
  //   };
  // },
  // mounted() {
  //   this.addRandomRows(30);
  // },
  // methods: {
  //   generateRandomRow() {
  //     const ids = [
  //       "ISL 12025",
  //       "ISL 12026",
  //       "ISL 12027",
  //       "ISL 12028",
  //       "ISL 12029",
  //     ];
  //     const names = ["Mohammed Kaium Uddin", "Abu Zahin"];
  //     const designations = [
  //       "Co-Originator",
  //       "Developer",
  //       "Designer",
  //       "Manager",
  //       "Analyst",
  //     ];
  //     const teams = ["Software", "Marketing", "Sales", "Finance", "Operations"];
  //     const leaves = ["1 Day", "2 Days", "3 Days", "4 Days", "5 Days"];
  //     const homeOffices = ["-", "1 Day", "2 Days", "3 Days", "4 Days"];
  //     const lates = ["Late", "On Time"];
  //     const yearsOfService = [
  //       "5 years",
  //       "6 years",
  //       "7 years",
  //       "8 years",
  //       "9 years",
  //     ];
  //     const joiningDates = [
  //       "01/25/2012",
  //       "03/14/2015",
  //       "07/02/2017",
  //       "09/10/2019",
  //       "12/30/2021",
  //     ];

  //     return {
  //       id: ids[Math.floor(Math.random() * ids.length)],
  //       name: names[Math.floor(Math.random() * names.length)],
  //       designation:
  //         designations[Math.floor(Math.random() * designations.length)],
  //       team: teams[Math.floor(Math.random() * teams.length)],
  //       leave: leaves[Math.floor(Math.random() * leaves.length)],
  //       homeOffice: homeOffices[Math.floor(Math.random() * homeOffices.length)],
  //       late: lates[Math.floor(Math.random() * lates.length)],
  //       yearsOfService:
  //         yearsOfService[Math.floor(Math.random() * yearsOfService.length)],
  //       joiningDate:
  //         joiningDates[Math.floor(Math.random() * joiningDates.length)],
  //     };
  //   },
  //   addRandomRows(numRows) {
  //     for (let i = 0; i < numRows; i++) {
  //       this.rows.push(this.generateRandomRow());
  //     }
  //   },
  // },
};
</script>
