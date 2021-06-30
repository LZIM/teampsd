# Monthly Facility File Propagation

## DEV QA 
See TeamPSD > quant_workgroup > splash_pages > Splashpage_monthly_update_readme

## TEST & PROD QA 
- [ ] Open mtl.how/data.
- [ ] Choose 3 facilities actively engaged in *Modeling to Learn* across different visns.  
      ________________________________________  
      ________________________________________  
      ________________________________________  
      
- [ ] Choose 3 facilities not actively engaged in *Modeling to Learn* across different visns & in visns different from the ones in the previous step.
      ________________________________________  
      ________________________________________  
      ________________________________________  
- [ ] Open in the Excel app.

**Note:** "Test" of dropdowns and buttons include:
1. Presence: Check that they exist on the appropriate Excek tab and section
2. Interactability: Click on them and try filtering to different options
3. Accuracy: Check that the data is appropriate for selection (i.e. divisionname should match the facility selected, should not be seeing health factor teamplates in encounters)

### vizDiag
- [ ] Propagation spans two years on the table and graph through the previous month.
- [ ] "Reset Pivot Chart" button exists above the graph and resets the data when clicked after filtering in the table and graph in the following steps.
- [ ] No SSN

#### Table
  - [ ] Displays visit counts of 4 primary diagnoses of interest: PTSD, Depression, AUD, & OUD
  - [ ] Grab 5 data points and cross-reference on graph to make sure table <> graph rendering is working
  
      Test the dropdowns:
      - [ ] divisionname
      - [ ] locationname

#### Graph
  - [ ] Displays visit count trend lines of 4 primary diagnoses of interest: PTSD, Depression, AUD, & OUD

      Test the buttons:
       - [ ] divisionname
       - [ ] locatoinname
       - [ ] visitdatetime(Year)
       - [ ] visitdatetime(Month)


### vizEnc
- [ ] Propagation spans two years on the table and graph through the previous month.
- [ ] "Reset Pivot Chart" button exists above the graph and resets the data when clicked after filtering in the table and graph in the following steps.
- [ ] No SSN


### vizHF
- [ ] Propagation spans two years on the table and graph through the previous month.
- [ ] "Reset Pivot Chart" button exists above the graph and resets the data when clicked after filtering in the table and graph in the following steps.
- [ ] No SSN


### vizMeas
- [ ] Propagation spans two years on the table and graph through the previous month.
- [ ] "Reset Pivot Chart" button exists above the graph and resets the data when clicked after filtering in the table and graph in the following steps.
- [ ] No SSN



### dataEnc

### dataDiag

### dataHF

### dataMeas
