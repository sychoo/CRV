<!-- CSS Configuration -->
<style>
  .red {
      width: 10px;
      height: 10px;
      -webkit-border-radius: 25px;
      -moz-border-radius: 25px;
      border-radius: 25px;
      background: red;
      display: inline-block;
      /* margin-left: 10%; */
  }

  .yellow {
      width: 10px;
      height: 10px;
      -webkit-border-radius: 25px;
      -moz-border-radius: 25px;
      border-radius: 25px;
      background: gold;
      display: inline-block;
  }

  .green {
      width: 10px;
      height: 10px;
      -webkit-border-radius: 25px;
      -moz-border-radius: 25px;
      border-radius: 25px;
      background: green;
      /* float: left; */
      display: inline-block;
  }

  /* tr {
    border-bottom: 1px solid black;
    border-top: 1px solid black;
    border-collapse: collapse;
  }

  td .priority {
    text-align: center
  } */
</style>

# Incidents

 | Priority | Name | Category | Year |
 |   :-:    | :--  | :--      | :-:  |
 | <div class="red"></div> | [Florida water treatment plant cyberattack](/src/fwt/) | critical infrastructure | 2021 |
 | <div class="red"></div> | [Colonial Pipeline cyberattack](/src/cpc/) | critical infrastructure | 2021 |
 | <div class="yellow"></div> | [Mars Polar Lander landing failure](/src/mpl/) | critical infrastructure | 2021 |

[Colonial Pipeline cyberattack](/src/cpc/) 
[Colonial Pipeline cyberattack](/src/cpc) 
[Colonial Pipeline cyberattack](/src/cpc/README.md) 

##### *The incidents are displayed in reverse-chronological order
# Contributing
- In the index page, each entry much display the following information
  - Priority Level 
    - <span style="color:green"> **green** </span>, <span style="color:yellow"> **yellow** </span>, or <span style="color:red"> **red** </span>
  - Name
    - concise, descriptive and understandable name of the incident.
  - Category
    - multiple category is allowed
  - Year
- Please refer to the [template](/src/tpl/README.md) when adding detailed page for the new incidents.
- Each newly added incidents should be assigned 3 priority level
  - <span style="color:green"> **green** </span>: did not cause injuries or life losses; low-level property damages, and non-significant economic impact
  - <span style="color:yellow"> **yellow** </span>: caused non-life threatening injuries, but did not cause life losses; medium-level property damages, somehow significant economic impact
  - <span style="color:red"> **red** </span>: caused life-threatening injuries, and life losses; high-level property damages (complete destruction), and very significant economic impact
- For the level assigned to the contributed incident, please justify the assignment by documenting references of credible statements from trusted media, academic publications, or witness accounts.

<!-- TODO: State why this project is helpful -->