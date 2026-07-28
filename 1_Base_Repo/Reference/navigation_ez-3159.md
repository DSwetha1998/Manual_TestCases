### UI and form validation
1.On the information screen, the "Named Insured"field value should be fetched from UWD.
2.On the coverages tab, under Annual Aggregate Limits of Insurance, dropdown should be
present to select TERM or Annual Agg limits for the two coverages 
3.On coverages extensions tab, under the coverages, in Limit of Insurance field, if $0 is entered as 
the limit, then the quote/policy printed documents should show ‘Not Insured’ when $0 is entered for the limit.
4.In Schedule of Rates tab, after clicking on add button, if "Builders Risk Property" is selected as scheduls rate type and from description dropdown, if coverage extensions option is selected and premium is entered,  ‘Rating Base’ and ‘Monthly Rate per $100’ should just show as empty – as in nothing should show under them on the quote/policy.
5.For Delay in Completion Coverage Endst Form – ZC 6538, 
a.If no value is entered for the number of days waiting, or if 0 is entered, then the quote/policy should show ‘Not Insured’ for these items in the printed documents. 
b.Also, the Delay Aggregate Limit of Insurance should sum up the limit entered for Business Interruption, Rental Value and Soft Costs; 
that limit should show as the Agg Limit in ezdocs and on the quote quote/policy for the Delay Aggregate Limit of Insurance in the UI and printed documents

### EZ-3159
Login to ez docs application.
Select Construction LOB.
Reterive submission with effective date as 10/09/2026.
Select Project Builders Risk as product from th eproduct dropdown.
Continue the validation without uploading the rater file.
Fill the all the mandatory fields.
Proceed with quote, binder and policy transactions.