# ECON398-applied-exam

The program ran a promotion in selected stores aiming to promote beer sales, starting in July. 

To evaluate its effectiveness, I used a difference-in-differences model, comparing the promotion effect before and after the promotion in the promoted and non-promoted stores, controlling for wine sales. This is because wines sales were not time-invariant in plots (also an evidence that it might distract customers.) The DD model estimates a promotion effect of 2.859 and it is statistically significant at 0.01 level. The evidence supporting the common trends assumption for the DD model holds visually and through regression analysis.

To improve the estimation, I also tried a triple difference model to further reduce the confounding bias. I used store type (whether specializes in beer) as a placebo variable, since it does not have interaction with the actual treatment effect (0.50, p=0.698), indicating the store type does not affect the differences in beer sales trends systematically across groups. Validation tests for the DDD identification assumptions also shows weak validation. The final DDD model with controls estimates the promotion’s effectiveness of 0.04128, both statistically and economically insignificant. However, due to a reduced sample size in the DDD model, the variance and the standard errors increased. 

The promotion effect on the total sales is also estimated using the DD model. Its CTA also holds based on the regression analysis, and the promotion statistically significantly reduced the total sales by 4.4.

In summary, results from DD and DDD models on beer sales and the DD model on total sales suggest that the promotion's effectiveness was not ideal, and even worse. The increase in beer sales was insufficient to offset the sharp decline in wine sales. It is probably due to that the promotion led to substitution behavior, shifting purchases away from wine to lower-priced beer, and that the wine sales are more sensitive to the market competition.
