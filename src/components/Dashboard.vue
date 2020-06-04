<template>
    <div>
        <Header />        
        <div class="container-body">
            <div class="side-bar">
                <div class="header-home-icon">
                    <i class="fas fa-home"></i>
                </div>
                <div class="dekstop-profile">
                    <div class="dekstop-image">
                        <img src="../assets/images/cat.jpg" alt="user images" class="user-images"/>
                    </div>
                    <div class="setting-icon">
                        <img src="../assets/images/setting.png" alt= "setting images" class="setting-images"/>
                    </div>
                    <div class="username">Tushar Jain</div>
                    <div class="designation">Developer</div>
                </div>
                <div class="functions">
                    <div class="margin-row">
                        <div class="dashboard-dropdown">
                            <div class="dashboard-icon">
                                <i class="fab fa-buromobelexperte"></i>
                            </div>
                            <div class="dashboard-heading">
                               <span> Dashboard </span>
                                <div class="dashboard-subhead">
                                    <div class="subhead-1">Page Visitors</div>
                                    <div class="subhead-2">Post Performance</div>
                                    <div class="subhead-3">Team Overall</div>
                                </div>
                            </div>
                            <div class="angle-down">
                                <i class="fas fa-angle-down"></i>
                            </div>
                        </div>
                        <div class="calendar">
                            <div class="calendar-icon">
                                <i class="far fa-calendar"></i>
                            </div>
                            <div class="calendar-heading">
                                Calendar
                            </div>
                        </div>
                        <div class="inbox">
                            <div class="inbox-icon">
                                <i class="fas fa-inbox"></i>
                            </div>
                            <div class="inbox-heading">
                                Inbox
                            </div>
                            <div class="angle-up-down">
                                <i class="fas fa-angle-up"></i>
                                <i class="fas fa-angle-down"></i>
                            </div>
                        </div>
                        <div class="invoicing">
                            <div class="invoicing-icon">
                                <i class="fas fa-suitcase"></i>
                            </div>
                            <div class="invoicing-heading">
                                Invoicing
                            </div>
                        </div>
                        <div class="lab">
                            <div class="lab-icon">
                                <i class="fas fa-thermometer-three-quarters"></i>
                            </div>
                            <div class="lab-heading">
                                Lab / Experimental
                            </div>
                        </div>
                        <div class="recently-viewed">
                            <span>Recently viewed</span>
                            <div class="recently-viewed-item">
                                <div class="items">Overall Performance</div>
                                <div class="arrow">→</div>
                            </div>
                            <div class="recently-viewed-item">
                                <div class="items">Invoice: #940</div>
                                <div class="arrow">→</div>
                            </div>
                            <div class="recently-viewed-item">
                                <div class="items">Customer: Minerva Viewer</div>
                                <div class="arrow">→</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="dashboard">
                <div class="dashboard-header">
                      <div class="row-1">
                          <div class="heading-bold">
                              Dashboard
                          </div>
                          <div class="countries">
                              <div class="box-1">
                                <div class="flag">
                                    <img src="https://www.transparentpng.com/thumb/hindu-flag/india-flag-icon-13.png" alt="india flag icon @transparentpng.com">
                                </div>
                                <div class="country-name">
                                    IND
                                </div>
                                <div class="angles">
                                    <i class="fas fa-angle-up"></i>
                                    <i class="fas fa-angle-down"></i>
                                </div>
                              </div>
                         </div>
                      </div>
                </div>
                <div class="dashboard-page">
                        <div class="db-marginbox">
                            <div class="graph-box">
                                <div class="graph-box-header">
                                    <div class="graph-box-margin">
                                        <div class="graph-box-heading">Daily Visitors</div>
                                        <div class="month-year-box">
                                            <div class="month-box">
                                                <select>Month
                                                    <option>January</option>
                                                    <option>Feburary</option>
                                                    <option>March</option>
                                                    <option>April</option>
                                                    <option>May</option>
                                                </select>
                                            </div>
                                            <div class="year-box">
                                                <select>Year
                                                    <option>2020</option>
                                                    <option>2019</option>
                                                    <option>2018</option>
                                                    <option>2017</option>
                                                    <option>2016</option>
                                                </select>
                                            </div>
                                        </div>
                                        </div>
                                    </div>
                                        <div class="graph">
                                            <div class="graph-margin">
                                                <div class="graph-image">
                                                    <img src="../assets/images/Bargraph.png" alt="bar graph image">
                                                <!-- <Barchart xKey="name" yKey="amount" :data="barChartData" /> -->
                                                </div>
                                            </div>
                                        </div>
                                    <div>
                                </div>
                            </div>
                        </div>
                        <div class="analytics-summary-boxes">
                            <div class="summary-margin-boxes">
                                <div class="summary-box-1">
                                    <div class="summary-text">Realtime users</div>
                                    <div class="summary-value">56</div>
                                    <div class="summary-amt-diff">
                                        <span>+9.8%</span>
                                        <i class="fas fa-external-link-square-alt"></i>
                                    </div>
                                    <div class="summary-chart">
                                        <img src="../assets/images/wave1.svg" alt="line graph">
                                    </div>
                                </div>
                                <div class="summary-box-2">
                                    <div class="summary-text">Total visits</div>
                                    <div class="summary-value">54598</div>
                                    <div class="summary-amt-diff">
                                        <span>-11.9%</span>
                                        <i class="fas fa-external-link-square-alt"></i>
                                    </div>
                                    <div class="summary-chart">
                                        <img src="../assets/images/wave (3).svg" alt="line graph">
                                    </div>
                                </div>
                                <div class="summary-box-3">
                                    <div class="summary-text">Bounce rate</div>
                                    <div class="summary-value">73.67%</div>
                                    <div class="summary-amt-diff">
                                        <span>+12.2%</span>
                                        <i class="fas fa-external-link-square-alt"></i>
                                    </div>
                                    <div class="summary-chart">
                                        <img src="../assets/images/wave2.svg" alt="line graph">
                                    </div>
                                </div>
                                <div class="summary-box-4">
                                    <div class="summary-text">Visit Duration</div>
                                    <div class="summary-value">1m 4s</div>
                                    <div class="summary-amt-diff">
                                        <span>+19.6%</span>
                                        <i class="fas fa-external-link-square-alt"></i>
                                    </div>
                                    <div class="summary-chart">
                                        <img src="../assets/images/wave (4).svg" alt="line graph"> 
                                    </div>
                                </div>
                            </div>
                        </div> 
                        <div class="analytics-traffic">
                            <div class="card-1">
                                <div class="most-visited">
                                    <div class="most-visited-heading">most visited pages</div>
                                    <table>
                                        <thead>
                                            <tr>
                                                <th>Page Name</th>
                                                <th>Visitors</th>
                                                <th>Unique page visits</th>
                                                <th>Bounce rate</th>
                                            </tr>
                                        </thead>
                                        <tbody>
                                            <tr>
                                                <td>
                                                    <div class="pages-name">
                                                        /store/
                                                        <i class="fas fa-external-link-alt"></i>
                                                    </div>
                                                </td>
                                                <td>4,890</td>
                                                <td>3,985</td>
                                                <td>
                                                    <div class="bonus-rate">
                                                        81.56%
                                                        <div class="line-chart">
                                                            <img src="../assets/images/wave2.svg" alt="line graph">
                                                        </div>
                                                    </div>
                                                </td>
                                            </tr>
                                            <tr>
                                                <td>
                                                    <div class="pages-name">
                                                        /store/symbols-styleguides
                                                        <i class="fas fa-external-link-alt"></i>
                                                    </div>
                                                </td>
                                                <td>3,785</td>
                                                <td>3,182</td>
                                                <td>
                                                    <div class="bonus-rate">
                                                        62.56%
                                                        <div class="line-chart">
                                                            <img src="../assets/images/wave1.svg" alt="line graph">
                                                        </div>
                                                    </div>
                                                </td>
                                                
                                            </tr>
                                            <tr>
                                                <td>
                                                    <div class="pages-name">
                                                        /store/dashboard-ui-kit
                                                        <i class="fas fa-external-link-alt"></i>
                                                    </div>
                                                </td>
                                                <td>2,985</td>
                                                <td>2,115</td>
                                                <td>
                                                    <div class="bonus-rate">
                                                        58.76%
                                                        <div class="line-chart">
                                                            <img src="../assets/images/wave1.svg" alt="line graph">
                                                        </div>
                                                    </div>
                                                 </td>
                                                
                                            </tr>
                                            <tr>
                                                <td>
                                                    <div class="pages-name">
                                                        /store/webflow-cards.html
                                                        <i class="fas fa-external-link-alt"></i>
                                                    </div>
                                                </td>
                                                <td>2,440</td>
                                                <td>1,789</td>
                                                <td>
                                                    <div class="bonus-rate">
                                                        39.59%
                                                        <div class="line-chart">
                                                            <img src="../assets/images/wave2.svg" alt="line graph">
                                                        </div>
                                                    </div>
                                                </td>
                                                
                                            </tr>
                                        </tbody>
                                    </table>
                                </div>

                            </div>
                            <div class="card-2">
                                <div class="social-traffic">
                                    <div class="traffic-heading">social media traffic</div>
                                    <table>
                                        <thead>
                                            <tr>
                                                <th>Network</th>
                                                <th>Visitors</th>
                                            </tr>
                                        </thead>
                                        <tbody>
                                            <tr>
                                                <td>Instagram</td>
                                                <td>
                                                    <div class="traffic-progress-data">
                                                        3,550
                                                        <div class="users-line">
                                                            <div class="total-users" style="width:70%" aria-valuemax="100" aria-valuemin="0" aria-valuenow="70%" role="progressbar"></div>
                                                        </div>
                                                    </div>
                                                </td>
                                            </tr>
                                            <tr>
                                                <td>facebook</td>
                                                <td>
                                                    <div class="traffic-progress-data">
                                                        2,236
                                                        <div class="users-line">
                                                            <div class="total-users" style="width:50%" aria-valuemax="100" aria-valuemin="0" aria-valuenow="50%" role="progressbar"></div>
                                                        </div>
                                                    </div>
                                                </td>
                                            </tr>
                                            <tr>
                                                <td>Twitter</td>
                                                <td>
                                                    <div class="traffic-progress-data">
                                                        1,795
                                                        <div class="users-line">
                                                            <div class="total-users" style="width:40%" aria-valuemax="100" aria-valuemin="0" aria-valuenow="40%" role="progressbar"></div>
                                                        </div>
                                                    </div>
                                                </td>
                                            </tr>
                                            <tr>
                                                <td>linkedin</td>
                                                <td>
                                                    <div class="traffic-progress-data">
                                                        62
                                                        <div class="users-line">
                                                            <div class="total-users" style="width:10%" aria-valuemax="100" aria-valuemin="0" aria-valuenow="10%" role="progressbar"></div>
                                                        </div>
                                                    </div>
                                                </td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </div>

                            </div>

                        </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import Header from "./Header.vue"
// import Barchart from "./charts/Barchart.vue"

export default {
    name: 'Dashboard',
    components:{
        Header,

    },
    data: () => ({
    barChartData: [
      {
        name: "Roses",
        amount: 25
      },
      {
        name: "Tulips",
        amount: 40
      },
      {
        name: "Daisies",
        amount: 15
      },
      {
        name: "Narcissuses",
        amount: 9
      },
      {
        name: "ABS",
        amount: 10
      },
      {
        name: "Law",
        amount: 20
      },
      {
        name: "bs",
        amount: 5
      },{
        name: "ab",
        amount: 10
      },{
        name: "bc",
        amount: 15
      },{
        name: "cd",
        amount: 20
      },{
        name: "lapa",
        amount: 25
      },{
        name: "rs",
        amount: 30
      }
    ]
  })
};
    

</script>

<style scoped>


    
</style>