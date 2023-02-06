| [home page](README.md) | [visualizing debt](visualizing-government-debt) | critique by design | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design


## Chosen Visualization

<img src="resources/Signal_Table_Data_Visualization.png" alt="Table" width="300"/>

The following visualization shows the results of the user testing performed by Wu et al. in the following research paper: ["Something isn't secure, but I'm not sure how that translate into a problem": Promoting autonomy by designing for understanding in Signal](https://www.usenix.org/conference/soups2019/presentation/wu). In summary, Wu et al. sought to demonstrate how their redesign of Signal's warning notifications improves user comprehension and empowers them "to make personal trade-offs between perceived risk and response cost." This data visualization is presented to showcase their positive findings.

## Critique

### Usefulness
**Score: 10**. Overall, this data visualization is very useful. Since this is a part of a research paper, the primary use of this table is for the authors to be able to back up their claims with concrete numbers. As mentioned in the paper, "This table reveals that comprehension of the purpose of the authentication ceremony and of the significance of matching and non-matching numbers visibly improved with our redesign." Therefore, by showing how more users received correct answers for their redesign when compared to Signal, this table adequately accomplishes the authors' goals.

### Completeness
**Score: 4**. The completeness of this data visualization depends on the audience. If the audience is someone who read the entire paper and sees this chart after being directed to it and given a thorough explanation (for example, 'see Table 2, which shows ...'), then the table is relatively complete. It shows, for the three types of questions asked, how many users, both actual numbers and percentages, answered correctly, partially correctly, and incorrectly for both designs. However, it would likely take the reader a few moments to realize that each of the three boxes labeled 'Auth. cerem.,' 'Matching,' and 'Non-matching' corresponds to the questions regarding 'the purpose of the authentication ceremony' and 'the meaning of the matching or non-matching result.'

On the other hand, given that many readers simply skim through research papers to quickly decide whether they should read the whole paper, then the chart is arguably very incomplete. Not only would it be unclear that each box corresponds to the responses given to different questions, but also the meaning of especially 'matching' and 'non-matching' would be difficult to understand. Furthermore, it would likely take a while for the reader to realize that the text represents the general ideas present in answers that were given the corresponding category, and it would be difficult to argue that all of that text is necessary in the first place. 


### Perceptibility
**Score: 3**. In general, this data visualization requires the readers to compare small numbers to understand the overall takeaway that the authors' redesign resulted in more correct answers. However, some effective choices made were showing the original Signal data in the left column and the redesign in the right column. Not only does this clearly separate the two types of data, but it also somewhat aligns with the general notion of time advancing towards the right. Furthermore, correct, partially correct, and incorrect are color coded with the appropriate green, yellow, and red colors accordingly. Despite this, actually decoding which warning design is better requires the reader to look at the relatively small, bolded numbers/percentages and compare the two values not only between the two designs, but also between the three questions, which this design makes relatively difficult.

### Truthfulness
**Score: 9**. Overall, this data visualization is accurate and valid. The only slight confusion come from the fact that while it seems as though there were 25 participants answering questions about the original Signal design and 16 for the redesign, it is unclear and unclarified in the paper why the total number of partially correct responses for the matching question for Signal is 26. 

### Intuitiveness
**Score: 7**. A table is a very familiar, simple, and intuitive data visualization. However, as mentioned earlier, it is a unclear that the three section correspond to three different research questions and the user's responses to each.

### Aesthetics
**Score: 3**. There is nothing special or particularly aesthetic about this design. While the colors do add to the visualization, a table is a very plain and simple way to display data.

### Engagement
**Score: 4**. Similarly to aesthetics, there is nothing particularly engaging about a table of words and numbers. While there is not much that distracts from the data, the table's primary purpose seems to be to show the data rather than engage the reader in any meaningful manner. 

### Overall Observations 
Overall, this data visualization adequately showcases the data that the authors of this paper collected during the user studies conducted. Besides including all of the user's individual, complete responses, which would have likely been an overwhelming amount of data, the authors included all data that may be wanted. Furthermore, the overall design of the table is relatively well done, with clean columns and appropriately color-coded rows. 

However, the key aspect of this data visualization that can be improved is the presentation of the data. The key data points are in small numbers that are very difficult to compare, both between the designs and between questions. If I were to do something differently, I would create a visualization that would allow for easier comparisons of the data through the use of, for example, bar charts or scatter plots. This would not only lower the reader's cognitive load, but it would also allow them to quickly verify that the message articulated in the paper is in fact supported by the data. 

### Primary Audience
The primary audience includes anyone who chooses to read this paper, including academics and students. More specifically, this paper is a part of the Symposium on Usable Privacy and Security (SOUPS), so most readers would have knowledge of privacy and security or would like to learn more about the topic. For this audience, this data visualization adequately showcases the data that the authors collected. Furthermore, the primary takeaway that the authors wanted to convey, that being that their redesign increased user understanding of the authentication ceremony using Signal, is directly stated in the paper itself so the table is simply a way to show the data collected that backs up this claim. This conclusion that the table is only truly effective for those want the raw data is supported by the fact that it is quite difficult to verify the author's claim and compare the small numbers that count the number of participants in each category.

However, many individuals don't read each paper in detail. Instead, many focus on the abstract, conclusion, and the visualizations to gain a basic understanding of the research conducted and conclusions reached in order to decide if reading the entire paper is worthwhile. In those cases, this visualization is not as effective since the data points are difficult to compare and the meaning behind 'Auth. cerem.,' 'Matching,' and 'Non-matching' is unclear without having read the entire paper. 


### Final Thoughts
Overall, this method for evaluating data visualizations seems quite effective. In particular, it allows for specifically quantifying how the data visualization succeeds and struggles on a variety of parameters. Instead of generically stating that something was 'good' or 'bad,' this method allows for further granularity. For example, this method highlights how this visualization succeeded in metrics such as usefulness and truthfulness but not aesthetics or engagement. Therefore, when it comes to redesigning, it can perhaps be easier to find which areas need improvement.

However, the Good Charts method helped in the transition from general ideas to specific observations. By starting with what was seen first then moving to likes/dislikes before finally identifying things to change, it was easier to formulate more specific thoughts overtime instead of having to truly understand the positive/negatives of a chart at first glance. Therefore, what may be a helpful approach is a blend of the two. The critique could begin with the Good Charts method in order to gain a better understanding of the visualization and once this understanding is attained, then the conclusions can be categorized based on the above method.  


In conclusion, my primary recommendation for this chart would be to allow for meaningful comparisons between data points through the use of, for example, bar charts or scatter plots. Furthermore, the labels could be more descriptive to help readers understand this chart without having to read and understand the entire paper.

## Sketches

<img src="resources/Redesign_Sketch.jpeg" alt="Table" width="600"/>

# ADD MORE HERE ABOUT THE SKETCH?!?!?!?

## User Tests

### Results
The overall feedback for the redesigned data visualization was relatively positive. Both users, either initially or after a few moments of exploration, quickly came to the conclusion that green signified something positive. Moreover, they both realized on their own that one of the key takeaways from this chart is that the redesign performed better. 

However, the two users mentioned different aspects of the visualization that initially confused them. For one user, they found that comparing the data for the partially correct (and incorrect) data was a bit difficult due to lack of alignment and percentages. However, the other user did not pay as much attention to that data since they believed that the percentage of correct answers was most important and the rest of the data was there more to provide some context for the rest of the answers given. What the other user did comment on though was that it took them a while to realize that the gray bars were for the original and the black were for the redesign. This didn't seem to be a problem for the first user, but it was definitely something that took a bit to notice as the colors drew their attention at first. 

One aspect of the user testing to note is that some background context regarding key terms in the paper were given before showing the visualization. While ideally the visualization could speak for itself, it would take a lot of words to adequately explain what 'Signal,' 'authentication ceremony,' 'matching,' and 'non-matching' meant in this context. Although one user did mention wanting some more clarification for the differences between 'matching' and 'non-matching' in particular, this visualization would likely be seen in the context of a research paper and many of these terms are explained in the paper's abstract and conclusion, so users who skim the paper would likely still understand at least the basics. Finally, the key idea that the redesign performed better is still very clear even if the specific security/privacy terms are not known. 

Some design changes that may make sense include adding percentages for all categories but in a lighter color for partially correct/incorrect. This would keep the focus on the green/correct answers while still providing concrete numbers for the other categories if the reader wants it. Also, the label for the legend can be made clearer to emphasize percentages. Finally, the next iteration of this chart could highlight the difference between the original data and the redesign data in a clearer manner. 


### Notes taken 

#### User 1
- Green stands out
- Likes seeing the green get bigger between the two sets of bars
- Originally thinks of 'yay, great' when looking at the green and the legend supports that conclusion
- Overall, the visualization is showcasing the redesign's improvement 
- Find the partially correct (and incorrect) bars harder to compare because they are not aligned like the green is and doesn't include specific percentages that could help out
- A key takeaway they had from the visualization was that while the user-focused redesign improved a lot, there is still more to improve on
- Seems like a visualization focused on comparing the two designs
- Found labeling the chart with questions as a bit strange 
- Suggested putting percentages for all bars, but lighter for the partially correct/incorrect responses
- Also suggested relabeling 'Answers: ' to 'Accuracy of understanding' to clarify the data, especially the meaning of the percentages
- When shown the original table after, their first thought was that it was very confusing and unpleasant to look at
- Found it very difficult to compare the data and while they wanted to use the sizes of the various rows to help with the comparison, they soon realized that the sizes were variable only because of the number of categories within the section 

#### User 2
- The three bars highlighted in black stand out initially
- Believed the graph was showing if people understand the warnings' purpose, with green meaning that they get it
- The authors seem to be suggesting that the redesign is better, or at the very least is more clear to the users
- The difference between 'matching' and 'non-matching' is confusing
- Likes the percentages only on the green bars, as the main point is whether people understand the design
- Took a while to realize that the gray bars were the original and the black were the redesign
- When shown the original table after, their first reaction was that it was really bad 
- While they liked the colors, they were immediately overwhelmed and found the numbers really hard to find


## Redesign
