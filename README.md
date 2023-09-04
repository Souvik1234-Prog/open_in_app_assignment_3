# open_in_app_assignment_3
its a given assignment for ai_ml engineer intern


To achieve the desired functionality of translating a given text into Hinglish format while preserving keywords, you can follow these steps:

Use a transformer model to translate the text into Hindi.
Use the spaCy NLP module to find keywords in the original text.
Tokenize the translated text and original text to perform keyword matching.
If a token from the original text matches a keyword, keep it as is; otherwise, translate it into Hinglish.
Combine the translated tokens to form the final Hinglish text.



While using pretrained models is a valuable approach, it's essential to consider domain-specific or fine-tuning needs, depending on the specific requirements of your translation task. Fine-tuning on a smaller Hinglish dataset, if available, can further enhance the model's performance for your specific use case.

i don't have a dataset to train the model so thats why i have used pretarined model and complete the task,
