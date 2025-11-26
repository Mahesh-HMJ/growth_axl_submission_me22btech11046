# growth_axl_submission_me22btech11046
Task Submission
Flag 1 is 2226d68638b2f6af6538f88abb31b0924993a7d2a9c8ce6436c7660f5a7b1fb2
Flag 2 is 34bc6d750b9595abb932c71428f734163f0d571e779b85ff69fac23fa3138aa6

1) First of all loaded the datasets into two dataframes.
2) Checked what columns were present in the dataframes.
3) Calculated the hash for my unique id.
4) In the reviews dataframe I have searched for my hash in the text column.
5) I have found one review containing my hash.
6) I noticed there was a column named 'asin' matching in the both dataframes but for my target review it is NaN but there is a field named 'parent_asin' and I tried to match that parent_asin in the books dataframe.
7) I found one book with that parent_asin.
8) So I have successfully found the first two flags. 
