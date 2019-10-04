# TestNGParllelExcelDataProviderResultUpdater
 Parllel TestNG Test Result update in MS Excel (Used as DataProvider) Using POI
 Here is highlights about repositoryL:-
1. Generic Data Provider :- To read testData from MSExcel.
2. TestNG @Test method will send the results to the ConcurrentMap Provided at class level.
3. After completion of Suite @AfterSuite method of TestNG will update the Excel file with result by taking enteries from ConcurrentMap.
