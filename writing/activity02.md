### cs301-F2021-Activity02-starter

### DUE: by 11:59PM EST, Tuesday, 19th October


### Name
OBC was here


### Instructions:
Please answer the following questions. Replace the `todo's` found under each question with your code and /or response. Note: It is highly recommended that you use an editor such as *Atom* at [see link](https://atom.io/), or similar, so that you can write your document in Markdown formatting whilst displaying the formatted content as you go.


Reference for questions: https://rpubs.com/MTrungDang/720311

###  Introduction


We will follow the two-sampled t-test which is discussed in the above link. In the explanation of the t-test, the researchers use the `iris` dataset (included in R). The `Sepal.Width` column is divided into two groups: `versicolor` and `virginica`. The t-test is then used to determine whether there is any significant difference between the means of these two groups (i.e., `versicolor` and `virginica` in relation to their `Sepal.Width` values).


In the experiment, the official null hypothesis is stated as there is no real difference in means of `sepal width` data sets for the two species. The alternative hypothesis: there is a difference.

The code used for the demonstration is shown below.

```
t.test(Sepal.Width ~ Species,
       iris,
       Species %in% c("versicolor", "virginica"),
       var.equal = T)
```


### Exercises

1. Create a similar t-test for `Sepal.Length` which has been divided into two groups for the species: `versicolor` and  `setosa`. Test for a significant difference between the means of these two groups.

 - What is the null hypothesis?
`TODO`

 - What is the alternative hypothesis?
`TODO`

 - Show your code.
`TODO`

 - What is your output?
`TODO`

 - Conclusion: Which hypothesis did you accept? Explain your reasoning.


2. Now, create a t-test for `Petal.Length` which has been divided into two groups for the species: `versicolor` and  `setosa`. Test for a significant difference between the means of these two groups.
 - What is the null hypothesis?

	`TODO`

 - What is the alternative hypothesis?

	`TODO`

 - Show your code.

	`TODO`

 - What is your output?

	`TODO`

 - Conclusion: Which hypothesis did you accept? Explain your reasoning.

		`TODO`

3. Comparison: In terms the two groups (i.e., `versicolor` and  `setosa`), what general inference(s) can you conclude about `Petal.Length` in relation to `Sepal.Length`?

	`TODO`


4. Complete an all-against-all correlation test (using ` method = "spearman"`) of the Iris columns;`Sepal.Length`, `Sepal.Width`, `Petal.Length`, and `Petal.Width`. Note: your code should produce a matrix of correlation values where the correlation values are shown for rows versus columns.
 - Enter your code below.

	`TODO`

 - Which two columns have the highest apparent correlation?

	`TODO`

 - In clear and meaningful language, please try to explain this correlation.

	`TODO`



(Did you remember to add your name above?)
