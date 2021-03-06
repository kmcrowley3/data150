# Gender Inequalities: Methodological Investigation of Bayesian Geostatistical Models and Neural Networks
Kaitlyn Crowley
Words (Content): 3512

# Introduction

Gender inequality is a pervasive human development topic, particularly in developing countries.  Inequalities among men and women can be traced back through history and are particularly prevalent in developing countries since traditional views of gender roles and responsibilities persist there in even more extreme forms than in developed countries.  When women are not treated as equals in society, two of the most significant harms are that they are often denied access to healthcare, specifically maternal health care, and they are not given equal access to education.  In Nepal, a primary example of a developing country, there are about 287,000 maternal deaths per year, resulting from complications both during pregnancy and during childbirth (Adhikari, 2016, p. 1).  In addition, 258 women die for every 100,000 live births each year in Nepal.  This is greater than even other developing countries in Southeast Asia such as India where 174 women die for every 100,000 live births each (Aryal et al., 2019).  In addition, in rural areas of Nepal, only 39% of women complete secondary schooling (Bosco et al., 2019).  Early marriage is also prominent, often making more girls drop out of school.  The inherent nature of the development process is that the extremely patriarchal societal structure and high levels of poverty throughout the country combine with traditional views to put women in a place of disadvantage that is more severe than in many other countries throughout the world (Bosco et al., 2019).

When women are not given access to these basic rights, they are not able to contribute to their society and participate fully in the economic, political, or even social spheres of life in the country.  Interestingly, not only does a patriarchal society perpetuate these unfreedoms, but the unfreedoms lead to a continuation of the strength of the patriarchy.  This further illustrates the inherent complex nature of gender inequality in addition to the fact that it is difficult to measure and quantify.  Bayesian geostatistical models are a data science method that has been applied to this issue in order to analyze and map the limited data that has been collected on gender inequality in developing countries at a higher resolution.  Neural networks are also being used to describe and model the complex process of gender inequality through learning relationships between linear and nonlinear data, which is essential given the complexity of gender inequality issues.  

The Bayesian model has been utilized to analyze different factors of gender inequality, including literacy rates and access to maternal health facilities, and then map this information at a higher resolution than maps created from pure survey or census data, taking in the varying levels of uncertainty that accompany the approximations of the data.  Through these more detailed maps, aid can then be directed to areas of greater need, therefore maximizing resources and results.  Neural networks perform a similar function, however they incorporate a process of deep learning, so the model is trained to make increasingly accurate predictions of various factors and can then be used to make predictions for unknown points of data. 

When addressing this topic, the broad central research question that I will be attempting to answer is: What is the impact of data collection methods on the ability to accurately measure gender inequalities in Nepal and how can a frictionless path of data collection be implemented to improve these measurements?

# Type of Inquiry

In this investigation into the issue of gender inequality, I will be seeking to answer an exploratory inquiry.  Through investigation of the effect of different data collection methods on issues of gender inequality and the effects that the inaccuracies and imprecision of these methods have on the issue, I will be seeking to uncover more about exactly what makes the topic of gender inequality so complex and how to measure this complexity.  The scope of this inquiry will be limited to the country of Nepal in order to focus on the complexities of the issue in one country before expanding to apply the findings to other countries.  Nepal is also a country where gender inequalities are especially pronounced, yet lack sufficient data quantifying them, pointing to the necessity for improvements in the measurements through a frictionless path.  The investigation will also seek to explore exactly what aspects of gender inequality are left out of collected data due to current methods of surveys and censuses.  

Currently, data collections are relatively limited in their ability to measure gender inequalities, particularly in a timely manner, again requiring exploration into new data collection methods that have the possibility of remedying this.  Since different data science methods are based on the data that is input, it is essential that this data is as up-to-date and accurate as possible, bringing in a temporal element to the investigation since more recent data will be the most accurate.  The human development process of attempting to move toward gender equality is inherently intricate, meaning that different factors of inequality may change at various rates, or even not have characteristics that can be addressed in a survey.  Due to this, the collection of the data must be completed on a frequent basis and in a wide enough variety of areas to gain a full picture of the issue.  

The investigation will involve exploring the ways that newer data collection technology, such as CDR data, could be used to improve the accuracy of the data science methods.  While this is partially evaluative because the investigation is, in a way, judging the effectiveness of new frictionless pathways, an exploratory approach is one that will allow for new methods of data collection to be combined with old ones by discovering why both processes do or do not work.  

This research inquiry will support the question of the impact of different data collection types on gender inequality measurements with its broad, investigative path.  This investigation is not seeking to judge whether or not old data collection methods are better than new ones, but rather explore the issues with the current methods and see whether or not new methods can remedy these problems.  Some sub-research questions for this investigation include: What current methods of data collection are being used to measure gender inequalities and why are these methods not adequate?  How are women negatively affected by the lack of methods to accurately measure their place in society and levels of inequality?  Why are women so often marginalized when it comes to current methods of data collection and how can these factors be addressed?  How can newer methods of data collection such as CDR data be implemented in the areas of gender inequality while still accurately disaggregating by sex and not solely focusing on migration patterns?  This final question is particularly interesting and involves extending the limited existing research on analyzing gender inequalities through CDR data.  

All of these sub-questions relate to the explorative inquiry, attempting to gather information about patterns and processes within the area of gender inequality.  Each question breaks down a more specific process within the investigation of exactly how to improve data collection about gender inequality. This creates a hierarchical process where the reasoning behind the inequalities is fully studied at a more specific scale before investigating methods that can be applied across the country and in what manner it would be best to apply them.  By narrowing the scope of the central research question, more specific explorations into the issue can take place.  The dynamics of these questions identify specific essential factors in this investigation, whose sum will form the beginning of an answer to the central question.

# Geospatial Datasets

Both Bayesian geostatistical models and neural networks rely on similar data sources, including covariates collected through data from censuses or surveys.  However, household surveys are conducted more regularly.  Some of the largest surveys are the Demographic and Health Surveys (DHS), Living Standard Measurement Survys (LSMS), and Multiple Indicator Cluster Surveys (MICS) (Bosco et al., 2017).  One of the main surveys that is used to measure gender inequality in Nepal is the Nepal Demographic Health Survey (NDHS).  This survey takes data from randomly chosen representative sampling populations within the boundaries of census enumeration areas (Gething et al., 2015).  Some of the important points of measurement include fertility rates, maternal and child mortality rates, access to health services, and levels of nutrition.  Authors and researchers can then use this data, when it is published, within the methods that they choose to analyze it with.

![](Table_1.png)
 
Figure 1. NDHS data collected on women and their access to antenatal care.  (Aryal et al., 2019, p. 13).

![](Table_2.png)
 
Figure 2. Additional NDHS data collected on women who had access to antenatal care visits. (Aryal et al., 2019, p. 14).

As demonstrated in Figures 1 and 2, the data has important spatial dimensions, including the distance from a health facility.  The NDHS also collects data about education, so distance from a school would also be another important spatial dimension.  The temporal dimension of the data is where issues of reliability occur.  Since the data for this survey is only published about every five years, it quickly becomes out of date.  While five years is more frequent data collection than many censuses, it is still too long for the data to remain completely accurate, especially when addressing a topic as dynamic as gender inequality.

In addition to the information collected in the NDHS, geographical data is required, often gathered from secondary sources of GIS data and remote sensing satellite data sets.  This data has clear spatial dimensions and the temporal dimensions are important, but not as crucial because satellite imagery is now so readily available that it can be updated relatively quickly.  GIS datasets can be centered on elements that are physical, social, or environmental.  Using AcrGIS, this data is processed and produced into layers of information, as shown in Figure 2 (Bosco et al., 2019).  Remote sensing data can be obtained from the United States Geological Survey and includes information about vegetation such as Gross Primary Productivity and Net Primary productivity and is verified with quality assurance layers (Bosco et al., 2017).  Both of these data sources are relatively valid and reliable due to advanced satellite imagery technology.  Having these additional data points allows for prediction of “the indicators at locations where survey data are not available” (p. 3) since there is often a clear correlative relationship between them and levels of gender inequality (Bosco et al., 2017). 

![](Covariates.png)

Figure 3. Geospatial covariates at 0.0083 decimal degrees resolution showing population count, distance to protected areas, distance to schools, and nighttime lights. (Bosco et al., 2019).
 
![](Remote Sensing.png)

Figure 4. Remote sensing covariates showing the mean Gross Primary Productivity and mean Normalized Difference Vegetation Index. (Bosco et al., 2017).

# Geospatial Data Science Methods

Bayesian Geostatistical Modeling

Bayesian geostatistical modeling is a method that is utilized in order to create a high resolution description of specific variables, especially in areas where there is a lack of data, taking uncertainty into account (Gething et al., 2015).  This method is one that is continuously evolving and often involves methods such as Kriging, Integrated Nested Laplace Approximation, and Empirical Bayesian Kriging, all of which have varying levels of accuracy, especially when taking spatial data into account.  

Y(s) = xT(s)B + w(s) +  ε(s)

The equation above is the basic geostatistical model.  The first term x(T)(s) represents the covariates that are entered into the model.  These covariates, in the scope of this research, are the data that is collected through the NDHS, GIS mapping, and remote sensing.  This vector of information is then multiplied by the “B vector of regression coefficients” (Gelfand & Banerjee, 2017, p. 2), which is the relationship between the two variables.  w(s) is the spatial component of the model, taking the location into account (Gelfand & Banerjee, 2017).  This value is often calculated through a Gaussian Process to calculate a random field (Gething et al., 2015), utilizing the randomly generated random spatial term.  The ε(s) is often known as “white noise” and serves to create more variance (Gelfand & Banerjee, 2017, p. 3).  These values can also be referenced as the “uncorrelated error terms” (Bosco et al., 2017, p. 5).  All of these elements added result in a vector representing a measurement at the location s (Y(s)).

The most important part of this process is the Bayesian inference, utilizing the result from the model.  

p(ΘE) = (p(Θ) × p(EΘ))/ p(E) 


Within this process, p(ΘE) is the “posterior belief in the parameters given the evidence” (Steinbuch et al., 2018, p. 401).  This is calculated by multiplying the likelihood of a relationship (p(EΘ)) by the prior parameter likelihood and dividing the product by the probability of the evidence collected, p(E), The evidence (E) is the Y(s) value from the in the basic geostatistical model (Steinbuch et al., 2018).  Through this Bayesian inference, the level of uncertainty of predictions of data can be calculated, providing an ability to create higher resolution maps or other data representations to take this uncertainty into account.

When applying this method, small samples collected through surveys like the NDHS can be utilized to then predict higher resolution observations based on the uncertainty calculated.  Figures 5 and 6 demonstrate how the Bayesian models allow for mapping of literacy rates across the whole country instead of just the select points where survey data is collected.

![](NDHS_Data.png)

Figure 5. Map of female literacy rates as collected through the NDHS. (Bosco et al., 2019). 
 
![](Disaggregated_Map.png)

Figure 6. Map of the proportions of female literacy using covariate data to predict areas where NDHS did not collect data.  (Bosco et al., 2019).

Neural Networks, Specifically Convolutional Neural Networks

Neural networks are methods of deep learning that allow for nonlinear boundaries to be learned through continuous training of the model (Wang et al., 2020, April 30).  While Artificial Neural Networks (ANNs) can be used, Convolutional Neural Networks (CNNs) add another layer of complexity and act as a classifier, extracting specific features from the image or data (Wang et al., 2020, April 30).  The basic structure of neural networks involves an input layer, hidden layer(s), and an output layer. 

Within the hidden feedforward layers of the CNN, the following formula can represent the final output of the first layer:

h(1) = g(1)(W(1)Tx + b(1))

In this equation, the input vector of specified data is entered and represented as x.  In the case of gender inequality, this input would be the data collected from the NDHS and the other covariates.  The activation function g(1) is an essential part of the formula because it allows for nonlinear analysis of the data, which is one of the most important features of neural networks.  The weights, which can also be known as the filter, are represented by the matrix W(1)T.   b represents the biases, which are initialized randomly in the feedforward process.  If there are multiple layers, this process will continue, with the output of the previous hidden layer acting as the input of the next layer. This would follow the general equation:
ŷ(x) = W(N)T  h(N-1) + b(N)
with ŷ(x) representing the output of the final hidden layer within the CNN (Wood, 2020, September 2).

Following the feedforward process, a process of backpropagation is completed.  In this process, the model attempts to update the weights to improve the accuracy of the method’s predictions (Wang et al., 2020, April 30).

Through this process, the neurons of the network build even more accurate connections, ultimately increasing the accuracy of the output.  Since the network is trained through this process, these connections can then be used later to analyze data or images.  Neural networks ultimately use probability to improve the end output, taking known points (x in the equation) and predicting the relationship between those points that will result in an output that is as accurate as possible.  Once this relationship involving a known value is computed, researchers can then predict data at an unknown point.

![](CNN.png)

Figure 7.  Illustration of the process of Convolutional Neural Networks.  (Wang et al., 2020, April 30)

Comparison

While both of these methods complete the task of accounting for some level of uncertainty in data and predicting values at unknown points, the Bayesian geostatistical models do not complete the process of learning that neural networks do.  Although some researchers in the area of gender inequality, including Bosco et al. in their research in 2017 and 2019 have found that Bayesian models “are considerably less time demanding” (p. 5), the potential benefits of the deep learning process of neural networks seem to outweigh this time constraint.  When analyzing gender inequality, the issue is incredibly complex, so finding a linear relationship between the variables is likely difficult.  Neural networks have the ability to predict relationships even between nonlinear data, making them an improvement when attempting to combine information on health care, education, and even various cultural factors that could impact gender inequalities.  

Various authors utilized these methods to specify their mapping of gender inequalities by predicting levels of inequality even where there is not data available.  Through this, a greater understanding of the broad scope of gender inequality in the country can be created instead of solely having information in areas where NDHS data was collected.

# Findings	

According to Bosco et al. (2017), in a study measuring the predictive ability of these two methods for measuring literacy, stunting, and use of modern contraceptives, the predictive abilities of the methods varied in different countries.  Although the two methods had similar predictive abilities given the input data provided, even when measuring the same factor, such as literacy for men in comparison to women, the predictive capacities between men and women were different.  Researchers found that different covariates also had varying predictive capabilities.  For example, temperature as a covariate often had a more direct correlation with stunting due to its connection to aridity and malnutrition.  Urbanization and road access had a greater correlation with literacy, while use of contraception methods correlated strongly with education levels (Bosco et al., 2017).  These associations make sense due to the fact that if, for example, a woman is more highly educated, she is likely to want to delay having children in order to advance her career or limit the number of children she has so she can continue working.  

When looking at these correlations, we are able to speculate future conditions based on the population and geographic patterns in the country.  However, these models do not have direct predictive power since their main function is to account for uncertainty and take that into account when processing current data.  When referring to the central research question of this investigation, this reinforces the need for a frictionless path of data since many of the covariates now did not have equal predictive abilities.  

Although they may not have direct predictive power, the researchers did validate their results.  They did this by calculating the root mean square error (RMSE) and the mean absolute error (MAE) (Bosco et al., 2017).  Since the research was based on two different methods, the method that had the most predictive capacity, and the one with the lowest RMSE and MAE was chosen to then create the final high resolution map with 1x1km resolution, similar to Figure 6 (Bosco et al., 2017).  Similar research was completed by Bosco et al. in 2019 and cross-validation through repeated sub-sampling was also implemented to attempt to ensure the validity of the data.

Similar research by various authors, including Gething et al. (2015) found data that supports the findings of Bosco et al.  Although the models had relatively high predictive abilities at some points, there were many times when the covariates were not relevant to measures of inequality.  For example, Gething et al. (2015) found that a measurement like access to HIV testing, which is a significant indicator of gender equality, was not predicted with accuracy when environmental covariates were utilized.  This demonstrates the importance of having up-to-data social data, which is almost always collected through surveys currently.

# Research Gap

Although Bayesian geostatistical models and neural networks are significant advances in the ability to measure and map gender inequality, the main gap is the fact that they are only as accurate as the data that is input.  There is a significant lack of current data in the field of gender inequality, especially in developing countries.  In answering the central research question of this investigation, further investigation is necessary in order to create a frictionless pathway of data collection, especially in developing countries in order to address issues of gender inequality more accurately.  Bosco et al., in their 2017 and 2019 reports, emphasize that more accurate and robust data is necessary in order to improve model performance.  Gething et al., (2015) assert the need for additional covariates.  However, newer data collection methods are not without their drawbacks, so it is necessary to investigate how methods of collection, such as CDR data, can be modified.  These modifications would involve improving the technology to disaggregate by sex and also making sure that the public actually has access to this data to be able to use it.  

In their 2019 report, Bosco et al. attempted to utilize CDR data as an additional covariate when mapping gender inequality indicators, but the frequency of SIM-card sharing meant that it was difficult to disaggregate the data by gender.  Additional research must be completed in order to determine if CDR data is a beneficial covariate to implement when evaluating gender inequality or whether another frictionless pathway must be developed for data collection.  Through this investigation, if it is successful, continuous data could be tracked and measured on the condition of women in developing countries like Nepal through CDR data.  This current data will mean that the models will have even more opportunity to update and account for gaps in the information.  With fewer gaps, the predictive abilities of the methods will improve, allowing for the issues of gender inequality to be mapped more accurately.  This in turn enables aid to be directed toward specific areas.  Data can only go so far to solve problems of inequality, but it can aid humans in solving problems facing women around the world.

References

Adhikari, R. (2016). Effect of Women’s autonomy on maternal health service utilization in Nepal: a cross sectional study. BMC Women's Health, 16(1), 26. 10.1186/s12905-016-0305-7

Aryal, K. K., Sharma, S. K., Khanal, M. N., Bista, B., Sharma, S. L., Kalfe, S., Steffen, M, M. (2019). DHS further analysis reports No. 118. Maternal Health Care in Nepal: Trends and Determinants.

Bosco, C., Watson, S., Game, A., Brooks, C., de Rigo, D, Qader, S., Greenhalgh, J., Nilsen, K., Ninneman, A, Wood, R., & Bengtsson, L. (2019). Towards high-resolution sex-disaggregated dynamic mapping. FlowMinder.org: FlowMinder. Retrieved from https://web.flowminder.org/publications/towards-high-resolution-sex-dissagregated-dynamic-mapping

Bosco, C., Alegana, V., Bird, T., Pezzulo, C., Bengtsson, L., Sorichetta, A., Steele, J., Hornby, G., Ruktanonchai, C., Ruktanonchai, N., Wetter, E., & Tatem, A. J. (2017). Exploring the high-resolution mapping of gender-disaggregated development indicators. J. R. Soc. Interface, 20160825. http://dx.doi.org/10.1098/rsif.2016.0825 

Brinda, E. M., Rajkumar, A. P., & Enemark, U. (2015). Association between gender inequality index and child mortality rates: a cross-national study of 138 countries. Biomed Central Public Health, 15(1), 97. doi:10.1186/s12889-015-1449-3

Garcia, D., Kassa Y. M., Cuevas, A., Cebrian, M., Moro, E., Rahwan, I., & Cuevas, R . (2018). Analyzing gender inequality through large-scale facebook advertising data. Proceedings of the National Academy of Sciences - PNAS, 115(27), 6958-6963. doi:10.1073/pnas.1717781115

Gething, P., Tatem, A., Bird, T., & Burgert-Brucker, C. R. (2015). Creating spatial interpolation surfaces with DHS data DHS spatial analysis reports no. 11. Rockville, Maryland, USA: ICF International.

Graetz, N., Woyczynski, L., Wilson, K. F., Hall, J. B., Hassen Abate, K., Abd-Allah, F., Adebayo, O. M., Adekanmbi, V., Afshari, M., Ajumobi, O., Akinyemiju, T., Alahdab, F., Al-Aly, Z., Elizabeth Alcalde Rabanal, J., Alijanzadeh, M., Alipour, V., Altirkawi, K., Amiresmaili, M., Hamed Anber, N., ... (2020). Mapping disparities in education across low- and middle-income countries. Nature, 577(7789), 235-238. 10.1038/s41586-019-1872-1

Jafarey, S., Mainali, R., & Montes‐Rojas, G. (2020). Age at marriage, social norms, and female education in Nepal. Review of Development Economics, 24(3), 878-909. 10.1111/rode.12692

Khanal, S. (2018). Gender discrimination in education expenditure in Nepal: Evidence from living standards surveys. Asian Development Review, 35(1), 155-174. 10.1162/adev_a_00109

Namasivayam, A., Osuorah, D. C., Syed, R., & Antai, D. (2012). The role of gender inequities in women's access to reproductive health care: a population-level study of Namibia, Kenya, Nepal, and India. International Journal of Women's Health, 4, 351-364. 10.2147/IJWH.S32569

Neal, S., Ruktanonchai, C. W., Chandra-Mouli, V., Harvey, C., Matthews, Z., Raina, N., & Tatem, A. (2019). Using geospatial modelling to estimate the prevalence of adolescent first births in Nepal. BMJ Global Health doi:10.1136/bmjgh-2018-000763

Sekine, K., & Hodgkin, M. E. (2017). Effect of child marriage on girls' school dropout in Nepal: Analysis of data from the Multiple Indicator Cluster Survey 2014. PloS One, 12(7), e0180176. 10.1371/journal.pone.0180176

Singh, Aishwarya. (2020, February 11). Demystifying the mathematics behind Convolutional Neural Networks (CNNs). Analytics Vidhya. https://www.analyticsvidhya.com/blog/2020/02/mathematics-behind-convolutional-neural-network/?utm_source=blog&utm_medium=cnn-vs-rnn-vs-mlp-analyzing-3-types-of-neural-networks-in-deep-learning

Steinbuch, L., Orton, T. G., & Brus, D. J. (2019). Model-based geostatistics from a bayesian perspective: Investigating area-to-point kriging with small data sets. Mathematical Geosciences, 52(3), 397-423. 10.1007/s11004-019-09840-6

Vaitla, B., Bosco, C., Alegana, V., Bird, T., Pezzulo, C., Hornby, G., Sorichetta, A., Steele, J., Ruktanonchai, C., Ruktanonchai, N., Wetter, E., Bengtsson, L., Tatem, A. J., Di Clemente R., Luengo-Oroz, M., González, M. C., Nielsen, R., Baar, O., Vacarelu, F., […] Wouter, E. (2017). Big data and the well-being of women and girls.” Data2X. Retrieved from https://www.openaire.eu/search/publication?articleId=od_348::84be43eb9164d5fbf098d9504feeb57d

Wang. J., Turko, R., Shaikh, O., Park, H., Das, N., Hohman, F., Kahng, M., Chau, P. (2020, April 30). Learn Convolutional Neural Network (CNN) in your browser. CNN Explainer. Retrieved November 10, 2020, from https://poloclub.github.io/cnn-explainer/

Wood, T. (2020, September 2). What is backpropagation? DeepAI. Retrieved November 10, 2020 from https://deepai.org/machine-learning-glossary-and-terms/backpropagation



