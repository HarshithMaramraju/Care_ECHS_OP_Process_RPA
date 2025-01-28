The Care ECHS_OP Process with Document Understanding 
This process need to extract the data from the documents i.e, bill and doctor referral letter.
The main fields we need to extract from the bill document were: Bill Number, Bill Date, Bill Time, Bill Line Items, Bill Amount.
The main item we need to extract from the doctor referral letter were: Referral Number, Serviec Number:
---------------------------------------------------------------------------------------------------------------------------------------------------
Once the extraction is done we need to login to the echs website and the URL follows: https://www.echsbpa.utiitsl.com/ECHS/
Login to the portal with credentials which were already in Asset folder/windows credentials/Config file.
Once you logged in need to enter place of the polyclinic, referral number (last 6 digits) and Service Number from the Doctor Referral Letter.
Navigated to the admition page and Copy the claim ID.
Enter the bill number, bill date, bill time from the bill document and navigate to Bill Details and enter the line items respectively.
Once amount is tallyed with the bill amount then go forward to submit the bill else shouldn't be submitted.
Once amount is matched enter the Alinment details as per the bill or hospital remarks mentined by Recovery Team.
And Navigate to the Uplode Documents and uplode the bill as respectively selecting the type of document from the dropdown and uploade the bill
Then submit.
---------------------------------------------------------------------------------------------------------------------------------------------------
Output:
Need to contain an excel output with fields follows:
Category,Customer Name,Patient Name,Bill Number,IP/OP,BIll Date,Net O-S,Unit,Claim ID,Submitted Date, Status


For further more details please follow up PDD of the Process which is attached in the Document folder

