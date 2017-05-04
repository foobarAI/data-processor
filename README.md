# data-processor
Data pre processing- currently working
1. Subject lines and body are bounded by (50, 20) words respectively
2. Subject lines and body follow sentence boundaries
3. Body does not include salutations/ signature
TODO
1. Remove unwanted characters like "?", ".?", "[image]" etc
2. Normalization: Replace infrequent words like personal names, URLs, email addresses, phone numbers etc. with special tokens like "UNK"
3. Quotation removal: Remove all quoted text
4. Replace cliche sentences like "How are you doing?", "hope you are doing well", "happy friday" etc. with UNK
5. Language detection: Ignore any language other than english
