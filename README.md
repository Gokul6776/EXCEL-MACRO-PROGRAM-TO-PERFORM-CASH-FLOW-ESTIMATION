# EXCEL-MACRO-PROGRAM-TO-PERFORM-CASH-FLOW-ESTIMATION
Sub EstimateCashFlow()
Dim ws As WorksheetDim lastRow As LongDim lastColumn As LongDim startColumn As LongDim totalInflows As DoubleDim totalOutflows As DoubleDim netCashFlow As DoubleDim col As Integer' Set the worksheetSet ws = ThisWorkbook.Sheets("Sheet1")' Find the last row in column AlastRow = ws.Cells(ws.Rows.Count, "A").End(xlUp).Row' Find the last column in row 1lastColumn = ws.Cells(1, ws.Columns.Count).End(xlToLeft).Column' Start column (assuming first column contains descriptions or dates)startColumn = 2' Initialize totalstotalInflows = 0totalOutflows = 0
Sub EstimateCashFlow()Dim ws As WorksheetDim lastRow As LongDim lastColumn As LongDim startColumn As LongDim totalInflows As DoubleDim totalOutflows As DoubleDim netCashFlow As DoubleDim col As Integer' Set the worksheetSet ws = ThisWorkbook.Sheets("Sheet1")' Find the last row in column AlastRow = ws.Cells(ws.Rows.Count, "A").End(xlUp).Row' Find the last column in row 1lastColumn = ws.Cells(1, ws.Columns.Count).End(xlToLeft).Column' Start column (assuming first column contains descriptions or dates)startColumn = 2' Initialize totalstotalInflows = 0totalOutflows = 0
