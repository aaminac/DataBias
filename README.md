# DataBias
In this assignment, I used the Perspective API to evaluate and test my hypothesis and the toxicity of comments, specifically focusing on death threats and insults. 

**Code Overview:**
- I used the Perspective API with my API key to assess the toxicity of comments.
- I categorized the comments into two groups: death threats and insults.
- I also set a toxicity threshold (toxic_base) at 0.5 and analyzed each comment to determine if it was toxic or not.

**Hypothesis:**
My initial hypothesis was that death threats would be more toxic than insults.

**Results:**
The results were that both death threats and insults received high toxicity scores above 0.90, and there wasn't a significant difference in toxicity scores between the two categories. I did not expect this outcome because I thought that death threats would be rated significantly higher in toxicity compared to insults since they are more harmful.

**Analysis and Reflection:**
I think that the model's inability to differentiate between the severity of death threats and insults might be because of certain biases in the data used for training. Biases in the training data may not accurately represent the real-world harm caused by death threats. Additionally, biases could be linked to the way the model perceives the severity of certain words. For example, the model might see words like "complete" as more intense and increase an insult's toxicity.

I have a theory that the model's limitations in understanding the context, intent, and subjectivity of toxicity could contribute to its inability to distinguish between different forms of harmful content. Furthermore, I think that the model's understanding of toxicity may not understand the way human's do, having a different perspective than humans, and is out of touch with reality considering the model is trained on data. 

In conclusion, my analysis raises questions about the model's performance in measuring the toxicity of different types of content, especially in distinguishing between the severity of insults and death threats. I want to emphasize the importance of further investigation into the biases and limitations of AI content moderation models and their impact on real-world applications.
