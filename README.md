# Sales Dashboard for Fima
In this dashboard i make some graphics using a Store Procedure from an ERP call Global Shop making a conection with ODBC. 
Sales in Fima works with a register variable called RFQ, that it is posted in the ERP for the salers, them their define an state of the sale (Win, Lose, Closed, Current and Budgetary). When a RFQ it's win, this will converted into a Sale with the state variable in Win, and them the salers register the Sale with a code called SO_DocNum, a amoung of SO_DocTotal and a date called SO_DocDate. For all the others RFQS that they don't win we use the F_Cotizacion date variable to make the graphics. In some cases the SO_DocTotal it is not the same amoung of the Total because when the salers create a RFQ


For this year i used the last year to made comparative graphics between the total acumulate in the last year and in the present year using an objective defined with the Sales Assistant Manager. 

![image](https://github.com/alejandromz2/Sales-Dashboard-Fima/assets/30611516/d9560deb-396a-49cc-ab79-d9c0917842e2)
