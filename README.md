![Reviews Analysis](https://github.com/adrofa/customer-reviews-analysis/raw/master/reviews_analysis_header.jpg)
# Reviews Analysis
The project was initiated by a large Italian cosmetic firm. This folder contains materials dedicated to the project. Some of the materials are modified (not to disclose confidential information).

## Project Description
Parse and analyze +7k reviews which customers left on a distributor's website (marketplace):
- extract essences, which are important for the customers;
- identify customers’ sentiment (positive/negative) to the extracted essences;
- define groups of essences and categorize/label the reviews;
- **preprocess reviews to let marketing specialists** (without coding background) **resume the analysis** (hence MS Excel files were also provided).

## Extracted Insights
In the order of importance/popularity among the customers:
- **Usage**: customers find the product especially useful in winter times;
- **Effect**: the most important effect for the customers is fresh/refreshed feeling in the morning after the night when the product was applied. Customers are satisfied with this. Also, the customers like that their skin is glowing. But some of the customers did not see any difference and the customers with sensitive skin do not like the product.
- **Feature**: it is very important for the customers, that the mask makes their skin soft and smooth, and the customers like it a lot. But some customers noticed and disappointed with the sticky and oily texture of the product. Also, it seems like the customers are not price-sensitive: if a customer says that the product is expensive, she is not disappointed with the product.
- **Aroma**: the product’s smell is a very important topic for the customers, they write a lot about it. The overall mark is low, it seems like the customers on average do not like the smell. It is highly recommended to pay more attention to this topic.
- **Hydration**: this topic is also very important for the customers – a lot of reviews are dedicated to hydrating. On average the customers are satisfied with the hydrating effect.
- **Package**: customers are not interested in a package and its design, but those, who wrote about it are satisfied. Some customers did not like that the sample is small.
- **Brand**: a brand topic is not interesting for the customers, but those who wrote about \<brand-name\> like the brand. It should be noted that usually, customers misspell the \<brand-name\>.

## Deliverables
- **Summary** | [pdf](https://github.com/adrofa/customer-reviews-analysis/blob/master/summary.pdf) | Analysis takeaways.
- **Notes** | [pdf](https://github.com/adrofa/customer-reviews-analysis/blob/master/notes.pdf) | The description of the analysis approach.
- **Code** | [NBViewer](https://nbviewer.jupyter.org/github/adrofa/customer-reviews-analysis/blob/master/code.ipynb) | Jupyter Notebook with all of the code related to the project.
- **Categorized Reviews** | [xlsx *(download)*](https://github.com/adrofa/customer-reviews-analysis/raw/master/reviews_categorized.xlsx) | Reviews texts with (1) group lables and (2) TOP-essence marks.
- **Tokens** | [xlsx *(download)*](https://github.com/adrofa/customer-reviews-analysis/raw/master/tokens.xlsx) | Extracted, annotated, labeled tokens with average star-rating.
- **Bigrams** | [xlsx *(download)*](https://github.com/adrofa/customer-reviews-analysis/raw/master/bigrams.xlsx) | Same as for "Tokens" (bigrams were used for tokens annotation).


### Previews
- **Categoried Reviews**<br/>![Categoried Reviews](https://github.com/adrofa/customer-reviews-analysis/raw/master/reviews_preview.png)
- **Tokens**<br/>![Tokens](https://github.com/adrofa/customer-reviews-analysis/raw/master/tokens_preview.png)
- **Bigrams**<br/>![Bigrams](https://github.com/adrofa/customer-reviews-analysis/raw/master/bigrams_preview.png)
