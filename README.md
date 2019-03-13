# Genetic Variants Capstone
data available at https://www.kaggle.com/kevinarvai/clinvar-conflicting/version/3
Genetic variations, or variants, are the differences that make each person’s genome unique. Some variants contribute to the differences between humans (such as different eye colors and blood types), others have been linked to diseases. However, most variants currently have unknown effects- discovering and documenting these variants remains a priority in the genetics community. This capstone focuses on an analysis of genetic variant classifications between labs, by using real world data provided by ClinVar to understand genetic variant classifications. Classifications exist between various laboratories and this capstone seeks to determine patterns in measured data that lead to agreements or disagreements in lab classifications. This analysis finds a signficant link between allele frequencies, as defined by two of the three participating labs, and the resulting state of classifications (agree or disagree). This phenonmenon suggests that the total 3 lab agreement hinged upon only two labs. If lab ExAC and lab TGP agreed on a genetic variants’ classification (due to their allele frequency measurement), the binary variable would likely take on a value of 0, meaning all three labs agreed on the classification (the third lab GO-ESP agreed on their classification).

Data Science techniques overview: implement data cleaning and processing techniques using Pandas, visualize feature variables with matplotlib and seaborn libraries, utilize chi-squared statistical significance testing with stats model, and apply feature engineering (label encoder and feature hashing) and machine learning models (Logistic Regression, Decision Trees, Gradient Boosting) through sci-kit learn.
