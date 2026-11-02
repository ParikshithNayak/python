WEBVTT

1
00:11:23.060 --> 00:11:24.409
Faculty (Olympus): Morning, everyone.

2
00:11:28.310 --> 00:11:28.980
Ann G. .: Bonic, sir.

3
00:11:28.980 --> 00:11:29.550
Dinesh Devnath Yadav .: provinces.

4
00:11:29.550 --> 00:11:30.240
Shraddha Aniruddha Mitragotri .: Morning.

5
00:11:31.280 --> 00:11:32.520
Amlan Sarkar .: Good morning.

6
00:11:55.150 --> 00:11:55.860
Faculty (Olympus): Oops.

7
00:13:00.460 --> 00:13:02.879
Faculty (Olympus): Okay, can you see my screen?

8
00:13:04.130 --> 00:13:05.080
Dinesh Devnath Yadav .: Yes, sir.

9
00:13:06.320 --> 00:13:06.930
Amlan Sarkar .: Yes, sir.

10
00:13:08.940 --> 00:13:09.620
Sameer Sawant .: Yes.

11
00:13:10.000 --> 00:13:15.550
Faculty (Olympus): Alright, so I still see there are not that many participants.

12
00:13:16.290 --> 00:13:19.040
Faculty (Olympus): Not even 100 people who've come from class.

13
00:13:20.380 --> 00:13:25.650
Faculty (Olympus): Anyone have any questions? Because I'd rather wait rather than start.

14
00:13:27.670 --> 00:13:28.530
Rahul Shrikrishna Joshi .: Sir,

15
00:13:29.020 --> 00:13:40.610
Rahul Shrikrishna Joshi .: One small question, actually. Sure. In the example which was related to that string chaining, when you are trying to fix the data in the data frame.

16
00:13:40.750 --> 00:13:50.259
Rahul Shrikrishna Joshi .: What weâ€¦ at least what onâ€¦ on my machine, I'm getting, like, firstâ€¦ after the first chaining, whenever we are replacing some values with the np.nan.

17
00:13:50.680 --> 00:13:51.879
Rahul Shrikrishna Joshi .: It is still.

18
00:13:51.880 --> 00:13:52.760
Faculty (Olympus): It'll give you an error.

19
00:13:52.760 --> 00:13:53.969
Rahul Shrikrishna Joshi .: Not working, yeah, yeah, yeah.

20
00:13:53.970 --> 00:14:01.869
Faculty (Olympus): Yeah, so don't do that. Don't set it to a NAND, because np.nan will change the data type from string to a floating point.

21
00:14:02.010 --> 00:14:03.690
Faculty (Olympus): And so that it will not allow.

22
00:14:04.170 --> 00:14:09.059
Faculty (Olympus): So, what you do is, you leave it until the last stage when you convert the, you know.

23
00:14:10.780 --> 00:14:16.909
Faculty (Olympus): So you do all your string processing, and the last operation you can basically set to convert it to, you know, none.

24
00:14:18.010 --> 00:14:23.229
Faculty (Olympus): Actually, no. In fact, no, you don't even have to do that. That will be a problem. So what you should do isâ€¦

25
00:14:25.090 --> 00:14:33.890
Faculty (Olympus): You just finish the conversion, and then you do a explicit conversion. You do PD.2, numeric, or 2, date time, whatever you want to convert it to.

26
00:14:34.010 --> 00:14:36.960
Faculty (Olympus): And there, you basically say coerce values.

27
00:14:38.090 --> 00:14:40.320
Faculty (Olympus): That's a safer way of doing it.

28
00:14:41.040 --> 00:14:50.950
Rahul Shrikrishna Joshi .: Correct, correct. But sir, when we do PD2numeric, panda.2 numeric, it will automatically make everything, whatever is not numeric as a, cannot be converted to numbers as IN, right.

29
00:14:50.950 --> 00:14:56.530
Faculty (Olympus): If you use errors as coars. The default is errors is race, and then it'll complain, but otherwise it shouldn't.

30
00:14:57.930 --> 00:14:58.560
Rahul Shrikrishna Joshi .: Thank you, sir.

31
00:14:59.540 --> 00:15:01.079
Faculty (Olympus): Alright, any other questions?

32
00:15:07.980 --> 00:15:12.479
Faculty (Olympus): Continence is very low today. Not even half the class is showing up.

33
00:15:12.700 --> 00:15:15.220
Faculty (Olympus): And here is where we're actually starting, Amel.

34
00:15:19.920 --> 00:15:29.249
Faculty (Olympus): Regression is your first entry point into machine learning. And today, if I finish this regression notebook, I'll actually get into an overview of machine learning.

35
00:15:30.080 --> 00:15:34.719
Faculty (Olympus): In the next class, hopefully I will look at, Scikit-learn.

36
00:15:34.910 --> 00:15:43.300
Faculty (Olympus): We look at Solving linear regression problems with Psychicron. That will be our initial entry point into this.

37
00:15:44.910 --> 00:15:46.790
Faculty (Olympus): Okay, Sameer?

38
00:15:47.380 --> 00:16:01.399
Sameer Sawant .: Yeah, Professor, just a quick question, as this is the base of the machine learning we're starting. Just trying to understand, see, the course does not look at ML ops, right? But as we're learning the basics of machine learning, and just from an experience, I work with ML flow.

39
00:16:01.580 --> 00:16:02.540
Faculty (Olympus): Soâ€¦

40
00:16:02.540 --> 00:16:11.280
Sameer Sawant .: how could you advise that between machine learning and MLOps, how can that journey be made if I wish to do it parallel with this?

41
00:16:13.330 --> 00:16:21.429
Faculty (Olympus): MLOps, if you don't want to understand what is going on, if you just know algorithmically what needs to be done, then it's just a matter of

42
00:16:22.280 --> 00:16:25.880
Faculty (Olympus): Operationally, how do you doâ€¦ You know, employment.

43
00:16:26.200 --> 00:16:28.809
Faculty (Olympus): So that is kind of a different thing thanâ€¦

44
00:16:29.000 --> 00:16:31.120
Faculty (Olympus): It's like, if you're aâ€¦ it's likeâ€¦

45
00:16:31.250 --> 00:16:34.780
Faculty (Olympus): The difference between, say, a system administrator and a web developer.

46
00:16:35.370 --> 00:16:36.850
Faculty (Olympus): Right, so if you're aâ€¦

47
00:16:37.020 --> 00:16:47.729
Faculty (Olympus): if you're a DevOps person, you may not know, okay, this is, like, in and out of Django, or, you know, Quasar, or whatever, Next.js, or, you know, ReactJS.

48
00:16:47.740 --> 00:16:59.789
Faculty (Olympus): front-end, back-end development, you may not know, but you may have general ideas of how to make sure that it's deployed, okay, what kind of NGINX or Apache or whatever you want, so in that context. Same way with MLOps.

49
00:17:00.390 --> 00:17:05.950
Faculty (Olympus): It is, like, how do you make sure you can deploy ML? So that's, like, a very different, domain.

50
00:17:06.310 --> 00:17:06.700
Sameer Sawant .: Okay.

51
00:17:06.700 --> 00:17:11.530
Faculty (Olympus): In fact, I think your first four courses will not even touch Menoms. They're all aboutâ€¦

52
00:17:11.650 --> 00:17:15.839
Faculty (Olympus): No theory and implementation, or understanding that.

53
00:17:15.849 --> 00:17:23.189
Sameer Sawant .: feature engineering, can I consider that when we are at machine learning, the feature engineering will be able to do it much better, because,

54
00:17:23.190 --> 00:17:27.689
Faculty (Olympus): If you understand, yes. But feature engineering, so usually, if you look at standard ML,

55
00:17:27.859 --> 00:17:33.410
Faculty (Olympus): original, classical ML, not deep-driven networks, then feature engineering becomes extremely important.

56
00:17:33.530 --> 00:17:40.170
Faculty (Olympus): And in the rest of this course, the second half of this course, plus a Vinay will spend lots of time on feature interior, as in.

57
00:17:40.170 --> 00:17:40.770
Sameer Sawant .: Okay.

58
00:17:40.770 --> 00:17:51.699
Faculty (Olympus): feature engineering for numerical values, which we will look at, we'll sort of touch upon it when we do regression with non-numerical values. Then the next thing would beâ€¦

59
00:17:52.480 --> 00:17:56.840
Faculty (Olympus): If you want to do images, if you want to deal with audio, if you want to deal with text.

60
00:17:57.010 --> 00:18:09.200
Faculty (Olympus): what kind of feature engineering do you need to do in order to run a traditional machine learning model on it? So that, you will be looking, actually, in the second half of this course. In fact, so Roshan Vinay will not be doing any programming. He'll be like, no, you know programming.

61
00:18:09.500 --> 00:18:13.900
Sameer Sawant .: So, it means, for feature engineering, it's very important to know these algorithms very much thoroughly.

62
00:18:13.900 --> 00:18:16.070
Faculty (Olympus): Not very much. It is like, you know.

63
00:18:18.390 --> 00:18:23.400
Faculty (Olympus): It's like, again, if you take a web developer, does the web developer understand kernels?

64
00:18:23.970 --> 00:18:35.159
Faculty (Olympus): operating system kernels. No, they may not. In fact, they may not know anything about it, they may not know anything about compilers, but still, they'll use V8 or whatever if they're writing JavaScript on the front end, right? And it depends on what they write.

65
00:18:35.610 --> 00:18:51.520
Faculty (Olympus): So, they may not know concurrency, they'll know only basic concurrency to whatever extent they know. So, the idea with a lot of these things is there's abstraction layers, right? So, it always helps to know a little bit deeper, but sometimes people don't know that much deeper. And the more deeper you know, the better it is, but

66
00:18:51.650 --> 00:18:58.200
Faculty (Olympus): It's a trade-off, it's again an optimization problem. If you know more details, then you can't build a lot of things.

67
00:18:59.510 --> 00:19:03.319
Faculty (Olympus): Right? Because then you'reâ€¦ you're, you understand

68
00:19:03.460 --> 00:19:06.779
Faculty (Olympus): A lot more at the lower level, that takes time.

69
00:19:07.020 --> 00:19:18.770
Faculty (Olympus): On the other hand, MLOps will change, right? So there'll be this thing, this framework, that framework, this framework, then what to do, cybersecurity, there are some new things, and AI is starting to change, all of those. So, you'll have to worry about those things.

70
00:19:19.700 --> 00:19:22.720
Faculty (Olympus): So, it depends on how much time you have, what you're willing to invest.

71
00:19:23.600 --> 00:19:25.270
Faculty (Olympus): Soâ€¦

72
00:19:25.270 --> 00:19:29.559
Sameer Sawant .: I think, I think I'll take it, like, that the feature engineering is at least the next course which will help us. Not next course.

73
00:19:29.560 --> 00:19:30.729
Faculty (Olympus): This second half of this.

74
00:19:30.730 --> 00:19:33.139
Sameer Sawant .: Yes, I can, of course. Okay.

75
00:19:33.140 --> 00:19:47.809
Faculty (Olympus): in the next semester, for example, you may do some feature engineering in your classical ML. In your deep neural networks and generative AI course, you will not do MLOps, as in, you will, again, look at methods, all, you know, various basic,

76
00:19:47.940 --> 00:19:56.569
Faculty (Olympus): ML, you know, deep learning-related ML models you're looking at. In the classical course, we'll focus on that, in which case they will also touch upon, you know, features.

77
00:19:57.680 --> 00:19:58.960
Sameer Sawant .: Okay, thank you, thank you.

78
00:20:00.240 --> 00:20:08.909
Faculty (Olympus): Okay, so let's get started. It's level 10. So I'll quickly summarize what we looked at in the last class. So the idea is, you have something, like.

79
00:20:10.230 --> 00:20:11.420
Faculty (Olympus): Is that a question?

80
00:20:15.480 --> 00:20:21.829
Faculty (Olympus): So, you have something like a linear relationship here. So, please note that this is a linear relationship that is assumed.

81
00:20:21.940 --> 00:20:33.100
Faculty (Olympus): So this is what is called a model. So let's say you have some phenomenon where you have a bunch of independent variables, like this X1.2XR, so X1, X2, X3, X4, X5. For example, you have five variables.

82
00:20:33.230 --> 00:20:46.509
Faculty (Olympus): And you're claiming that there is a linear relationship between what you're measuring, some output, which is Y, right? And then that becomes this linear model, which is some constant plus some constant times the first variable, so on and so forth, in the last variable.

83
00:20:46.760 --> 00:20:57.139
Faculty (Olympus): So, the problem is, that you're trying to solve, is your model is basically this linear model, the X1 to XR are known quantities, and very often you have measurements for the Y.

84
00:20:57.490 --> 00:21:10.760
Faculty (Olympus): So, using the measurements for known values of response variable and the known variables, right, X1 to XR, that you already know, you would like to be able to come up with a model. So your simplest model could be, like, a linear model.

85
00:21:11.180 --> 00:21:21.149
Faculty (Olympus): So if I want to have a model, an actual model, to give predictions, then I want to know these constants. So the only way to calculate these constants is to

86
00:21:22.970 --> 00:21:31.260
Faculty (Olympus): do regression. So regression is the process of identifying these constants from the data that you have measured. That's the basic idea.

87
00:21:31.630 --> 00:21:50.829
Faculty (Olympus): But once again, you have to remember that this is not going to necessarily be an exact model. So very often, you're going to have some noise, and the assumption that we will make is that this noise is zero bias, which means the mean of this noise is zero. And therefore, if I were to take the expected value for my response variable.

88
00:21:51.490 --> 00:21:54.249
Faculty (Olympus): This noise fellow will drop off, and you'll end up with this model.

89
00:21:56.520 --> 00:22:08.969
Faculty (Olympus): So this is called your linear regression equation, and the beta I are called your regression coefficients. And then there's one more term called simple linear regression, which is simple regression is just R is 1, which means there's a single variable, beta naught plus beta 1x1.

90
00:22:09.260 --> 00:22:14.190
Faculty (Olympus): If r is greater than 1, it's called multilinear, or multiple regression equation.

91
00:22:14.640 --> 00:22:25.710
Faculty (Olympus): Then I talked to you about what an estimator is. An estimator is basically a formula that gives you an estimate for a statistical parameter based on data.

92
00:22:28.780 --> 00:22:42.220
Faculty (Olympus): And the simple example that I cited was, if I took the coin tossâ€¦ so if I take a coin toss, and I want to find the probability of getting success, and let's say success is measured as if I get a head or something, tail, whatever you define.

93
00:22:42.550 --> 00:22:43.840
Faculty (Olympus): How would I do this?

94
00:22:43.910 --> 00:22:50.650
Faculty (Olympus): So, if I want to give youâ€¦ I cannot tell you the true value of this. The only thing I can do is toss this many, many times.

95
00:22:50.660 --> 00:23:09.329
Faculty (Olympus): And hope that there is some formula that I can create, which will estimate this value of P. So the value of P that we commonly use, that we think is intuitively obvious, is called, you know, the average. So if X is 0 if it is a failure, X is 1 if it's a success, that's a Bernoulli trial. You do N of these, and then you look at

96
00:23:09.810 --> 00:23:13.980
Faculty (Olympus): the average value that you get. And it turns out that this is an estimate of rupee.

97
00:23:14.310 --> 00:23:20.869
Faculty (Olympus): Andâ€¦ When you look at your statistics, you will find that it's also called the maximum likelihood Estimator.

98
00:23:21.080 --> 00:23:22.790
Faculty (Olympus): For a burner leak parent.

99
00:23:23.380 --> 00:23:35.050
Faculty (Olympus): Okay, so you will look at the theory for this later on. Essentially, what the maximum likelihood estimator is, it maximizes the likelihood, which is a probability density function, for a given set of measurements.

100
00:23:35.340 --> 00:23:36.170
Faculty (Olympus): Okay?

101
00:23:37.510 --> 00:23:41.090
Faculty (Olympus): for a parameter peak, in this case. So once you do that.

102
00:23:41.420 --> 00:23:50.330
Faculty (Olympus): you can actually formally prove that this is the maximum likelihood estimate. That is, P is equal to Xi divided by. Okay, so this is an important connection that you will see later on.

103
00:23:50.430 --> 00:23:55.039
Faculty (Olympus): Have you done maximum likelihood estimators so far? I don't think you have even done estimator, right?

104
00:23:55.870 --> 00:23:57.079
Varun Kumar .: Oh, it is not able to.

105
00:23:57.080 --> 00:24:05.670
Faculty (Olympus): You will come to it at some point, okay? So, when you do that, remember that this is what it does. But at the end of the day, forget about that. The idea is.

106
00:24:06.390 --> 00:24:07.760
Faculty (Olympus): You have a formula.

107
00:24:08.190 --> 00:24:21.430
Faculty (Olympus): that uses the data values, that is, what is the data values we have? If I do 10 coin process, it'll be 0110111 whatever, right? Those set of values. Using those data values, can you give me a formula to give me P? This is an estimate.

108
00:24:22.220 --> 00:24:28.020
Faculty (Olympus): Now, ideally, your estimator should be such that the expectation value for that

109
00:24:29.090 --> 00:24:33.120
Faculty (Olympus): estimator, this formula, should be the true value.

110
00:24:33.300 --> 00:24:34.470
Faculty (Olympus): Which means?

111
00:24:34.680 --> 00:24:35.879
Faculty (Olympus): In the limit ofâ€¦

112
00:24:36.250 --> 00:24:43.500
Faculty (Olympus): infinite number of measurements, you will get the correct path. That's called a unbiased estimator, which meansâ€¦

113
00:24:44.190 --> 00:24:49.419
Faculty (Olympus): And you take the averages, you do lots of these, your estimator will go towards your profile.

114
00:24:51.250 --> 00:24:56.290
Faculty (Olympus): Which brings us to least squares estimator of parameters. Gaurav?

115
00:24:57.860 --> 00:25:06.819
Gaurav Singh .: Yeah, Professor, like, the probability which we are calculating here, is the probability of excite variable, or what is the link?

116
00:25:07.350 --> 00:25:09.309
Faculty (Olympus): Probability of success in a coin toss.

117
00:25:09.560 --> 00:25:10.599
Faculty (Olympus): It's written here.

118
00:25:10.990 --> 00:25:11.990
Gaurav Singh .: Okay.

119
00:25:13.830 --> 00:25:19.550
Faculty (Olympus): Same coin, I'm tossing, I want to know the probability of success. If I know this, I know the probability density function, or probability mass function.

120
00:25:19.950 --> 00:25:23.599
Faculty (Olympus): then I can look at binomial or Bernoulli, whatever, I canâ€¦

121
00:25:24.130 --> 00:25:34.139
Faculty (Olympus): I can predict everything, I can predict in the sense that statistically, I can make projections, I can do all of those things once I know this value of P. But if I don't know this value of P, I cannot do much.

122
00:25:34.570 --> 00:25:38.390
Gaurav Singh .: Okay, got it. It was with respect to the point.

123
00:25:38.390 --> 00:25:43.110
Faculty (Olympus): With respect to the coin toss, if I want to coin toss, you want to tell me whether it's fair or unfair, right?

124
00:25:43.440 --> 00:25:44.530
Gaurav Singh .: Got it, got it.

125
00:25:44.710 --> 00:25:47.349
Faculty (Olympus): So, alright, so we need to do experiments.

126
00:25:49.480 --> 00:26:09.219
Faculty (Olympus): All right, so that brings us to what's called a least squares estimator. So when we did this linear model, right, so let's take a very simple single linear regression, which is Y is equal to alpha plus some beta X, okay? I've changed this from beta naught to beta, doesn't matter, but I have two parameters. This is a constant, this is a slope, right? It's a single straight line. That's my model.

127
00:26:09.540 --> 00:26:12.189
Faculty (Olympus): Now, if this is the true model.

128
00:26:12.440 --> 00:26:17.890
Faculty (Olympus): I can only estimate these parameters, right? Alpha and beta, you can only estimate. How do you estimate it? Using data.

129
00:26:18.680 --> 00:26:20.040
Faculty (Olympus): So, therefore.

130
00:26:20.400 --> 00:26:34.300
Faculty (Olympus): every time you make a computation using some Yi and Xi values, all you are going to get are estimators. So they use a different symbol, and so we call it as A and B. Let them be estimators for these two parameters, alpha and B. Okay?

131
00:26:34.730 --> 00:26:39.510
Faculty (Olympus): And so, therefore, your linear model actually becomesâ€¦

132
00:26:42.760 --> 00:26:47.500
Faculty (Olympus): You'reâ€¦ So your, linear model actually becomes Y.

133
00:26:48.330 --> 00:26:58.610
Faculty (Olympus): is equal toâ€¦ sorry, I didn't connect myâ€¦ like that, so A plusâ€¦ B?

134
00:27:01.540 --> 00:27:06.040
Faculty (Olympus): Stuff to write when I know. Okay, times X.

135
00:27:08.490 --> 00:27:09.330
Faculty (Olympus): Okay?

136
00:27:09.650 --> 00:27:12.389
Faculty (Olympus): Maybe I should not have put X like that, but it's okay.

137
00:27:12.870 --> 00:27:13.840
Faculty (Olympus): Windows 10.

138
00:27:17.260 --> 00:27:18.269
Faculty (Olympus): This is this?

139
00:27:21.610 --> 00:27:26.850
Faculty (Olympus): And this is capital B. So this is myâ€¦ this is my whatever, so if I look at it as YI,

140
00:27:27.710 --> 00:27:28.620
Faculty (Olympus): Right?

141
00:27:28.740 --> 00:27:32.809
Faculty (Olympus): is equal to some B times eta A plus B times Xi.

142
00:27:33.670 --> 00:27:34.949
Faculty (Olympus): This is my model.

143
00:27:36.980 --> 00:27:48.890
Faculty (Olympus): Okay, and what I want to do is I want to findâ€¦ so, okay, my model is actually this true model, but I want to find an estimate for this, right? So I want to find this A, and I want to find this B, using the values of Xi and Y.

144
00:27:49.430 --> 00:27:50.710
Faculty (Olympus): That'sâ€¦ that's what I want.

145
00:27:52.560 --> 00:28:13.729
Faculty (Olympus): All right, so what we have is, I haveâ€¦ so let's say I do N experiments, okay? Which means I give you a known value of X. So, for example, in our pendulum experiment, I give you a value of the length, and then I take my watch, and I say, okay, so many times for an oscillation. Or I do 5 oscillations and divide by 5, and say average time for a period of oscillation is so much. I measure that, T,

146
00:28:13.730 --> 00:28:15.060
Faculty (Olympus): And one? L.

147
00:28:15.060 --> 00:28:16.899
Faculty (Olympus): So I get two numbers, okay?

148
00:28:17.130 --> 00:28:18.570
Faculty (Olympus): or T squared.

149
00:28:18.700 --> 00:28:24.829
Faculty (Olympus): And L. I know this. And I know that it's a linear model from my physics, okay? From my knowledge of physics, I tell you this.

150
00:28:25.080 --> 00:28:30.120
Faculty (Olympus): So now I have, say, 100 measurements, so 10 measurements, okay?

151
00:28:30.750 --> 00:28:41.239
Faculty (Olympus): If I had only two measurements, then I can easily fit one straight line. But what I want to do is, I don't have two measurements, I have many measurements, and I want to find the best fit. Okay, so how do you define best fit?

152
00:28:41.520 --> 00:28:50.020
Faculty (Olympus): So the least squares approach is to basically say, your model is going to predict A plus BXL, right? This is your model's prediction.

153
00:28:50.470 --> 00:28:59.239
Faculty (Olympus): Given an XI value, your model should be A plus DXI. I take Yi, which is the true value, so this is your true value, right? This fellow is true.

154
00:29:03.800 --> 00:29:04.950
Faculty (Olympus): Oh, boy.

155
00:29:06.380 --> 00:29:14.580
Faculty (Olympus): Sorry, okay? So this is your true value, right? This is your actual measured time period squared, or whatever quantity, okay? And this is the length, for example.

156
00:29:14.580 --> 00:29:27.810
Faculty (Olympus): So I know this value, and I can predict this value based on my model. I take the difference of these two, square them, add them all. And that is called the sum of the squares of the differences between the model prediction and your actual value.

157
00:29:27.890 --> 00:29:31.019
Faculty (Olympus): And then what you do is, you want to minimize SS.

158
00:29:31.160 --> 00:29:33.160
Faculty (Olympus): Minimize with respect to what?

159
00:29:33.670 --> 00:29:47.200
Faculty (Olympus): What are the parameters we have in this SS formula? Yi is a number, Xi is a number, a set of numbers, N is a number. The only two quantities you have are A and B. So you want to find A and B that minimize SS.

160
00:29:47.670 --> 00:29:50.540
Faculty (Olympus): That is what is called the least squares estimate of the parameter.

161
00:29:51.180 --> 00:29:52.070
Faculty (Olympus): Okay?

162
00:29:52.250 --> 00:29:55.840
Faculty (Olympus): Soâ€¦ I hope that is, clear.

163
00:29:56.930 --> 00:30:02.200
Faculty (Olympus): So let me quickly take some questions, yes.

164
00:30:03.440 --> 00:30:04.270
Faculty (Olympus): Potom.

165
00:30:05.350 --> 00:30:11.369
Varun Kumar .: So, Professor, this A and B is already an estimator, and that we get from a lot of data, correct?

166
00:30:11.370 --> 00:30:13.650
Faculty (Olympus): No, which isâ€¦ what is the estimator? Sorry, come again?

167
00:30:13.840 --> 00:30:15.939
Varun Kumar .: A and B are the estimators, correct?

168
00:30:15.940 --> 00:30:17.710
Faculty (Olympus): Yes, A and B are the estimators, correct.

169
00:30:18.040 --> 00:30:19.739
Varun Kumar .: For, you know.

170
00:30:19.740 --> 00:30:21.909
Faculty (Olympus): Alpha and beta. For Alpha and Beta.

171
00:30:22.040 --> 00:30:26.710
Varun Kumar .: Yeah, but how we get estimated is by looking into multiple and multiple data.

172
00:30:27.630 --> 00:30:32.250
Faculty (Olympus): Yeah, so you have multiple measurements. I have Xi values, and I have YA values. Yes, corresponding YA values.

173
00:30:32.250 --> 00:30:36.100
Varun Kumar .: Yeah, after calculating that A and B, afterâ€¦

174
00:30:36.100 --> 00:30:38.600
Faculty (Olympus): No, no, we have not come there yet.

175
00:30:38.900 --> 00:30:42.260
Faculty (Olympus): Now I say, I have this linear model, I don't know A and B.

176
00:30:43.410 --> 00:30:44.570
Faculty (Olympus): You understand?

177
00:30:44.690 --> 00:30:47.790
Faculty (Olympus): I have A plus BXI as my model.

178
00:30:47.980 --> 00:31:02.520
Faculty (Olympus): But I have no idea what is A, what is B, I have no idea. How do I find A and B? I don't know. So I need to come up with estimators. Hang on, hang on. So I need to create an estimator formula for A, I need to create an estimator formula for B, and that is the next step.

179
00:31:02.650 --> 00:31:06.570
Faculty (Olympus): I want you to understand, at this point, I still have not found a formula. I don't have

180
00:31:06.700 --> 00:31:08.939
Faculty (Olympus): the estimator. I'm sayingâ€¦ I'm saying it

181
00:31:09.270 --> 00:31:11.910
Faculty (Olympus): A is some estimator, which means

182
00:31:12.690 --> 00:31:18.249
Faculty (Olympus): For some given set of values, I will give you A. For some given set of values, I will give B.

183
00:31:18.530 --> 00:31:20.439
Faculty (Olympus): But I still don't know, it's like a variable.

184
00:31:22.450 --> 00:31:25.970
Varun Kumar .: But then if A and B are still unknown, fine.

185
00:31:26.110 --> 00:31:29.100
Varun Kumar .: Then how we will get any value, any numericâ€¦

186
00:31:29.100 --> 00:31:34.190
Faculty (Olympus): It's called the variable now? How, if I give you some linear equation, I give you two followers. I give you Y and X.

187
00:31:34.560 --> 00:31:44.319
Varun Kumar .: My question is, here I have to calculate from i to n, I have to calculate value, and that will give me some, you know, minimized value of a square difference.

188
00:31:44.320 --> 00:31:47.179
Faculty (Olympus): Where did you minimize anything? We have not done anything yet.

189
00:31:47.610 --> 00:31:48.970
Faculty (Olympus): I just told you this is the.

190
00:31:50.550 --> 00:31:51.939
Varun Kumar .: Have you not done anything yet.

191
00:31:52.470 --> 00:31:53.180
Varun Kumar .: Okay.

192
00:31:53.180 --> 00:31:55.840
Faculty (Olympus): I am just now telling you the f- how you're setting it up.

193
00:31:56.780 --> 00:31:58.810
Varun Kumar .: Okay, fine.

194
00:31:58.810 --> 00:32:01.100
Faculty (Olympus): Next, next step is what is the important thing.

195
00:32:01.310 --> 00:32:02.910
Faculty (Olympus): Varun Gaurav?

196
00:32:03.680 --> 00:32:05.830
Gaurav Singh .: Yeah, Professor, first of all, like,

197
00:32:06.310 --> 00:32:11.700
Gaurav Singh .: if I see a pattern, like, by drawing Y versus Xi.

198
00:32:11.830 --> 00:32:24.459
Gaurav Singh .: Then I will be deciding that, hey, look, it looks like a linear model, and should I make a linear regression model for this? That's how we usually go for it, orâ€¦

199
00:32:24.460 --> 00:32:25.110
Faculty (Olympus): Yeah.

200
00:32:25.490 --> 00:32:28.720
Faculty (Olympus): Yes, you could. You could do that. That's a good way of doing it.

201
00:32:29.170 --> 00:32:30.010
Gaurav Singh .: Mhmhm.

202
00:32:30.010 --> 00:32:30.690
Faculty (Olympus): Right?

203
00:32:31.040 --> 00:32:34.000
Faculty (Olympus): Or you could also say, you know, a man with a hammer.

204
00:32:34.300 --> 00:32:39.200
Faculty (Olympus): everything is a nail, right? So, you know linear regression, you start everything with linear regression.

205
00:32:39.200 --> 00:32:39.600
Gaurav Singh .: Okay.

206
00:32:39.600 --> 00:32:43.860
Faculty (Olympus): Right? So, there are multiple ways to look at it. So, the thing is, supposing you have

207
00:32:43.980 --> 00:32:45.990
Faculty (Olympus): 10 input variables.

208
00:32:47.280 --> 00:32:51.150
Faculty (Olympus): It's very difficult to make sense of, hey, okay, you know, it's linear.

209
00:32:52.390 --> 00:32:52.890
Gaurav Singh .: Hmm.

210
00:32:52.890 --> 00:32:53.879
Faculty (Olympus): You don't know.

211
00:32:54.130 --> 00:32:59.149
Faculty (Olympus): And sometimes it'll beâ€¦ it'll have funny behavior, supposing you have a quantity that's not a numerical quantity.

212
00:33:00.130 --> 00:33:00.830
Gaurav Singh .: Hmm.

213
00:33:00.830 --> 00:33:03.089
Faculty (Olympus): Right? Supposing I tell you, malesâ€¦

214
00:33:03.260 --> 00:33:09.739
Faculty (Olympus): do something, okay, gender-based, okay? Or adults versus children, okay? Programmers versus non-programmers.

215
00:33:10.390 --> 00:33:10.770
Gaurav Singh .: Am I.

216
00:33:10.770 --> 00:33:12.660
Faculty (Olympus): quantities, not a floating point number.

217
00:33:12.830 --> 00:33:13.350
Gaurav Singh .: Yeah.

218
00:33:13.350 --> 00:33:20.860
Faculty (Olympus): Now, you still can do a linear model. We'll come to this later. But right now, our assumption is the Xi's and Yi's are numbers.

219
00:33:21.400 --> 00:33:21.790
Gaurav Singh .: Understood.

220
00:33:21.790 --> 00:33:25.029
Faculty (Olympus): They have floating point numbers. We'll come to the generalizations later on.

221
00:33:25.610 --> 00:33:36.299
Gaurav Singh .: One more question. Like, weâ€¦ in NumPy, we have seen, probabilistic, I think, programming, where we were generating random numbers and all.

222
00:33:36.300 --> 00:33:36.700
Faculty (Olympus): Hello.

223
00:33:36.700 --> 00:33:49.080
Gaurav Singh .: Of, according to a given distribution. So, for, for our, you know, research perspective, can we do something like that? We create XIs and Yi's?

224
00:33:49.080 --> 00:33:50.290
Faculty (Olympus): Yeah, very good.

225
00:33:50.290 --> 00:33:51.500
Gaurav Singh .: Absolutely.

226
00:33:51.800 --> 00:34:00.639
Faculty (Olympus): Absolutely. So, when you want to generate fake data, right? Fake data, I don't mean as in bad things you do and all. I mean, supposing you want to test something out.

227
00:34:00.860 --> 00:34:17.100
Faculty (Olympus): This is routinely done. So if you look at, you know, you want to say, okay, I want to get a model, and I want to createâ€¦ so we will actually do that in this class. Hopefully, we'll get to that point, and I'll generate synthetic data. Then I'll use the numerical, you know, random number generators to actually generate those data points.

228
00:34:17.370 --> 00:34:21.449
Faculty (Olympus): And then see how well this thing works, and things like that. Can we look at this.

229
00:34:22.120 --> 00:34:23.790
Gaurav Singh .: Understood. Thanks a lot.

230
00:34:23.790 --> 00:34:25.580
Faculty (Olympus): Sure. Sknit?

231
00:34:25.969 --> 00:34:31.570
Faculty (Olympus): Actually, you know, unless you have questions up to the understanding at this point,

232
00:34:31.870 --> 00:34:36.830
Faculty (Olympus): Because I still have to finish some theory, and then you can maybe wait for answers. But okay, Swapnil, quickly.

233
00:34:36.830 --> 00:34:41.519
Swapnil Sankla .: Professor, are we doing the square to accommodate both positive and negative residuals?

234
00:34:41.520 --> 00:34:47.910
Faculty (Olympus): Yes, you're also doing it for other reasons, because it makes it mathematically easier, amenable for analysis. That's all.

235
00:34:48.310 --> 00:34:51.650
Faculty (Olympus): When you do squares, it's a nice, smooth, continuous function. You can take

236
00:34:52.350 --> 00:34:53.979
Faculty (Olympus): Whatever we're going to do next.

237
00:34:53.989 --> 00:34:54.539
Swapnil Sankla .: Okay.

238
00:34:54.800 --> 00:34:55.510
Faculty (Olympus): Okay?

239
00:34:55.659 --> 00:34:56.570
Faculty (Olympus): Shirley?

240
00:34:57.060 --> 00:35:06.100
Shirley Menezes .: So I wanted to understand what you meant by whatâ€¦ by the term true value. Is it, like, the actual value of Y, or it's the substitution when you put the value?

241
00:35:06.100 --> 00:35:12.230
Faculty (Olympus): So, True Values isâ€¦ True in as much as that is bereft of a model.

242
00:35:12.340 --> 00:35:30.330
Faculty (Olympus): So, if I did pendulum experiment, let me see if I have this cover, right? I'm doingâ€¦ I do pendulum experiment, right? This is a bad pendulum, it's not straight enough, but imagine I was doing pendulum experiment. I measure the length exactly, and then I will measure the time period of oscillation. I fully understand that my measurement will have some errors. Okay, that's fine.

243
00:35:30.870 --> 00:35:35.800
Faculty (Olympus): Right? But the actual measurement I'm going to hold as a true value. That is the truth value.

244
00:35:36.040 --> 00:35:38.450
Faculty (Olympus): It's not a prediction based on some model.

245
00:35:40.230 --> 00:35:43.490
Faculty (Olympus): Whereas the right-hand side here, Isa?

246
00:35:43.890 --> 00:35:50.240
Faculty (Olympus): prediction. So I give you a length. If I give you two constants, A and B, you can tell me what the time period squared should be.

247
00:35:51.540 --> 00:35:53.630
Faculty (Olympus): And so this may be completely off.

248
00:35:54.120 --> 00:35:58.060
Faculty (Olympus): Right? But this is the value that you have measured, so as far as you're concerned, that is your truth.

249
00:35:58.290 --> 00:35:59.419
Faculty (Olympus): Is that okay?

250
00:36:00.580 --> 00:36:02.139
Shirley Menezes .: So it's much clearer now.

251
00:36:02.640 --> 00:36:16.549
Faculty (Olympus): Alright, so I take the experiment, I take a length, I measure the time period. So my time period squared is Yi, my length is Xi. And I keep repeating, I increase the length, increase the length, increase the length, and for each of these, I get a measurement. And I get 100 of these measurements.

252
00:36:16.800 --> 00:36:25.110
Faculty (Olympus): Okay, now what we're asking is, can I give you an estimator for A and an estimator for B? That's what we want to set up. When we do least squares estimators, that's what we're doing.

253
00:36:25.570 --> 00:36:33.699
Shirley Menezes .: So, would it be right to say, sir, that while I'm actually doing the experiment, A plus BXI is basically just my assumption that.

254
00:36:33.700 --> 00:36:34.350
Faculty (Olympus): Yes.

255
00:36:34.350 --> 00:36:35.049
Shirley Menezes .: This is just an example.

256
00:36:35.050 --> 00:36:38.840
Faculty (Olympus): It is your model, so whenever you makeâ€¦ so there's a famous quotation which Iâ€¦

257
00:36:39.080 --> 00:36:42.339
Faculty (Olympus): Said in the last class. All models are wrong, some are useful.

258
00:36:42.490 --> 00:36:59.469
Faculty (Olympus): Okay, so everything that is a model, in principle, may not capture every single aspect, right? There may be errors in my measurement, my scale may not be very accurate, right? Or I may look at it not properly, I may look at it slightly. There's a parallax error in measuring the length. My time period before, I may not have exactly measured it when it goes off.

259
00:36:59.470 --> 00:37:05.509
Faculty (Olympus): So now you can design more and more and more sophisticated experiments, right? I say, look, I have this length, which is perfectly measured to

260
00:37:05.510 --> 00:37:09.980
Faculty (Olympus): 10 to the minus 3, okay? 1 millimeter Thakurai, I measured it exactly, right?

261
00:37:09.980 --> 00:37:10.570
Shirley Menezes .: Okay.

262
00:37:10.870 --> 00:37:20.669
Faculty (Olympus): or you take a microscope and go nuts and make it even finer, but then you'll start making a decision saying, I don't need to invest so much money because theâ€¦ I'm not interested in those quantities to that level of accuracy.

263
00:37:21.000 --> 00:37:34.689
Faculty (Olympus): Right? So there is obviously going to be some errors that you're going to introduce on both sides. But as far as you're concerned, the Y does not involveâ€¦ the time period square involves absolutely no modeling. It's just an experiment, I got these numbers.

264
00:37:34.690 --> 00:37:37.189
Shirley Menezes .: Okay, okay, fair enough. Thank you, sir.

265
00:37:37.190 --> 00:37:54.289
Faculty (Olympus): Yeah, and what we are trying to do is, let's say we don't know why, okay? For example, Y could be some stock market, you know, some whatever value of some share or something, right? Of course, a linear model is not going to work. If it did, you know, would not be such a big deal, right? A linear model probably will definitely not work, but

266
00:37:54.570 --> 00:38:04.729
Faculty (Olympus): Assuming, right? So it's some quantity, and I want to say, hey, based on this parameter, what's the next value going to be? That's your model. Your model can be totally absurd, can be wrong, can be super, right? Depends.

267
00:38:05.330 --> 00:38:23.469
Faculty (Olympus): All right, now our goal is very simple. Given these Xi's and Yi's, can I come up with a formula for A and B? Which is, can I come up with estimators for A? That's what we want to do. And so, to do that, we construct it in a very specific fashion, where we look at Yi minus A and minus PXI, the whole squared, add them up for all values.

268
00:38:23.930 --> 00:38:24.900
Faculty (Olympus): Niraj?

269
00:38:27.000 --> 00:38:37.760
Niraj Kumar Mishra .: Sir, I have a very basic question. Actually, I didn't understand this formula, the SSR equal to, sum of i equal to 1 upon n, and then Yi minus A.

270
00:38:37.760 --> 00:38:40.769
Faculty (Olympus): So, I have 100 values for length and t squared.

271
00:38:41.480 --> 00:38:46.810
Faculty (Olympus): Given a length, my model was going to say A plus length squared, sorry, A plus B times length.

272
00:38:52.640 --> 00:38:53.939
Faculty (Olympus): Do you understand that?

273
00:38:57.680 --> 00:38:58.180
Faculty (Olympus): Hello.

274
00:38:58.180 --> 00:38:59.060
Niraj Kumar Mishra .: Get it, sir.

275
00:39:02.520 --> 00:39:04.259
Soumen Deb .: So it's like a straight line.

276
00:39:04.260 --> 00:39:12.570
Faculty (Olympus): No, no, no, no, I'll explain some of them. So, you know, so let's say I have thisâ€¦ I have aâ€¦ I have a simple pendulum experiment. I know they are linearly related. Do you understand what that means?

277
00:39:15.250 --> 00:39:16.070
Niraj Kumar Mishra .: Yes.

278
00:39:16.750 --> 00:39:18.239
Faculty (Olympus): What does it mean? Can you explain?

279
00:39:25.340 --> 00:39:26.809
Niraj Kumar Mishra .: So,

280
00:39:28.920 --> 00:39:31.899
Faculty (Olympus): It's okay, I don't want to put you on the spot. If you don't understand what you say it, don't understand, I'll explain.

281
00:39:31.900 --> 00:39:35.050
Niraj Kumar Mishra .: Yeah, I mean, I didn't understand, sir, I don't understand.

282
00:39:35.050 --> 00:39:39.930
Faculty (Olympus): So, if I give you a linear model, what it means is, I have some constant, Right?

283
00:39:39.930 --> 00:39:40.370
Niraj Kumar Mishra .: Mhmh.

284
00:39:40.370 --> 00:39:41.519
Faculty (Olympus): some slope.

285
00:39:41.670 --> 00:39:47.679
Faculty (Olympus): times that value, it's exactly what I've written here, right? I have some response variable, which is your time period squared.

286
00:39:47.900 --> 00:39:54.260
Faculty (Olympus): is equal to some constant plus oneâ€¦ another constant times the length. That's all it is.

287
00:39:54.660 --> 00:39:55.869
Faculty (Olympus): That's a linear model.

288
00:39:56.430 --> 00:40:05.979
Faculty (Olympus): So if I have length of the string, as someone has pointed out, as I increase the length, or reduce the length, the time period is going to change in a linear fashion.

289
00:40:06.240 --> 00:40:07.970
Faculty (Olympus): And isn't it? They're proportional?

290
00:40:08.730 --> 00:40:10.340
Faculty (Olympus): Do you understand or don't understand?

291
00:40:12.410 --> 00:40:16.360
Faculty (Olympus): This is just straight mathematics. Y is equal to some constant times X.

292
00:40:17.140 --> 00:40:19.630
Niraj Kumar Mishra .: Okay. Okay, I, I will, I willâ€¦

293
00:40:19.630 --> 00:40:20.229
Faculty (Olympus): Thanks so much.

294
00:40:20.230 --> 00:40:23.270
Niraj Kumar Mishra .: No, sir. I don't understand this.

295
00:40:23.270 --> 00:40:29.139
Faculty (Olympus): If you do not understand this, then you're in deep trouble. Because this is just a straightforward mathematical equation, I'm telling you.

296
00:40:29.660 --> 00:40:31.720
Niraj Kumar Mishra .: Yes, I didn't understand, so I will take.

297
00:40:31.720 --> 00:40:36.870
Faculty (Olympus): So wait, okay, then let me take a different example. Maybe you don't understand this time period and pendulum model.

298
00:40:36.870 --> 00:40:37.720
Niraj Kumar Mishra .: Yeah, itâ€¦

299
00:40:37.720 --> 00:40:42.440
Faculty (Olympus): Let us say, I say that your weight is proportional to your diamondâ€¦ to the,

300
00:40:43.750 --> 00:40:46.279
Faculty (Olympus): To the square of your,

301
00:40:47.030 --> 00:40:49.780
Faculty (Olympus): Circumference. So I take a tape measure.

302
00:40:50.260 --> 00:40:53.440
Faculty (Olympus): Right? Imagine this is a tape measure. You know what a tape measure is, right?

303
00:40:53.620 --> 00:40:54.340
Niraj Kumar Mishra .: Yeah, yeah.

304
00:40:54.340 --> 00:41:03.320
Faculty (Olympus): So I put a tape measure, put it around the waist, at a specific location, because there are many points in the waist, at the minimum point of your waist, or maximum point of your waist.

305
00:41:03.560 --> 00:41:10.060
Faculty (Olympus): I measure that, and say, hey, your waist is, some say, 80 centimeters, 90 centimeters, something, okay?

306
00:41:10.060 --> 00:41:10.770
Niraj Kumar Mishra .: Mhmhm.

307
00:41:10.970 --> 00:41:18.379
Faculty (Olympus): I claim that there's a linear model, which is square of your This diameter, this, sorry, circumference.

308
00:41:20.190 --> 00:41:21.670
Faculty (Olympus): Do you understand what I'm saying?

309
00:41:22.710 --> 00:41:23.100
Niraj Kumar Mishra .: Yes.

310
00:41:23.100 --> 00:41:28.790
Faculty (Olympus): Square of your diameter, of your weight, 80 centimeters square, into some constant, that is going to be your weight.

311
00:41:29.350 --> 00:41:29.950
Niraj Kumar Mishra .: Okay.

312
00:41:29.950 --> 00:41:32.040
Faculty (Olympus): Plus some constant. Plus some constant.

313
00:41:32.920 --> 00:41:34.309
Niraj Kumar Mishra .: Okay, understood now.

314
00:41:35.230 --> 00:41:45.550
Faculty (Olympus): Now, I take every student in class, I measure all your weights according to that correct location, maximum point, your belly button, or something, okay? I get all these numbers, I put one column.

315
00:41:46.850 --> 00:41:48.940
Faculty (Olympus): I have another column which has your weights.

316
00:41:51.610 --> 00:41:58.420
Faculty (Olympus): Okay, and I take the square of these fellows, 80 centimeters, whatever, square, okay, square, square, square, square. I get these numbers, I get the weight numbers.

317
00:42:00.160 --> 00:42:04.360
Faculty (Olympus): So that means the square of your,

318
00:42:05.660 --> 00:42:09.220
Faculty (Olympus): Yours. Your circumference, I'll call it your circumference, right, is exile.

319
00:42:09.220 --> 00:42:09.880
Niraj Kumar Mishra .: Excellent.

320
00:42:09.880 --> 00:42:11.779
Faculty (Olympus): circumference squared is Xi. Square of.

321
00:42:11.780 --> 00:42:12.220
Niraj Kumar Mishra .: Okay.

322
00:42:12.220 --> 00:42:16.549
Faculty (Olympus): It's not just the score, right? That is equal to weight.

323
00:42:17.560 --> 00:42:20.990
Niraj Kumar Mishra .: People do it, okay. And A, A is constant.

324
00:42:20.990 --> 00:42:26.750
Faculty (Olympus): is some conâ€¦ some constant number. It's like your Y intercept, so it's a straight line, so it may not be zero.

325
00:42:27.040 --> 00:42:35.440
Faculty (Olympus): See, what your baseâ€¦ in our case, clearly, when your circumference is zero, I won't find any human being like this, right? No circumference means human being nahi.

326
00:42:36.070 --> 00:42:36.630
Niraj Kumar Mishra .: Inward.

327
00:42:36.630 --> 00:42:40.370
Faculty (Olympus): Imagine the case that there's no circumference, maybe A should be 0, right?

328
00:42:41.760 --> 00:42:53.740
Faculty (Olympus): Okay, but there might be some, you know, some other thing involved, right? For example, don't take a waste. Well, I can'tâ€¦ there's nothing which goes to zero, no? No one body, which, you know, I can't represent.

329
00:42:57.040 --> 00:42:58.440
Niraj Kumar Mishra .: Yes, it's okay, Sarah, hang on.

330
00:42:58.440 --> 00:43:02.449
Faculty (Olympus): Okay, so you got this. So there's some constant here, there's some constant, both of these are, I don't know.

331
00:43:02.630 --> 00:43:07.759
Faculty (Olympus): What I would like is a way by which I can calculate A and B from these X and Ys.

332
00:43:07.760 --> 00:43:08.770
Niraj Kumar Mishra .: Baja, okay.

333
00:43:08.770 --> 00:43:24.309
Faculty (Olympus): Because once I know those two constants, I don't need to do any more measurements. Because from my model, I can say, oh, if your weight is so much, if your thing is, you know, SSR is, sorry, square of your weight, circumference is some number, I plug it into this formula, and I'll tell you your weight.

334
00:43:25.900 --> 00:43:26.410
Niraj Kumar Mishra .: Hmm.

335
00:43:26.410 --> 00:43:45.479
Faculty (Olympus): So, for example, if you look at the body mass index, that's a bit more complicated. You know, let's say your health index is some, you know, whether do you smoke, what is your weight, how overweight are you, you know, what is your BP, something, you know, have some complicated formula, and all of them are linearly related. In which case.

336
00:43:45.840 --> 00:43:47.729
Faculty (Olympus): You know, I can get something like this.

337
00:43:48.260 --> 00:44:02.230
Faculty (Olympus): I can set it up like a formula like this, and I plug in these values, and I can tell you, your health is good, your health is bad, or not quiteâ€¦ your health is, you know, it'll be a number, it'll be any number, based on minus infinity plus infinity. Okay, and then from that, I can read off some number.

338
00:44:02.350 --> 00:44:08.859
Faculty (Olympus): And say, okay, if you're above zero, you're good. If you're less than zero, you're not good. Something like that I can come up with. Does that make sense?

339
00:44:09.260 --> 00:44:10.119
Niraj Kumar Mishra .: Yeah, for confession.

340
00:44:10.120 --> 00:44:16.380
Faculty (Olympus): So all this is is just a model. My question now is, how do you find A and B from Xi and Y? That's what we're trying to do.

341
00:44:17.210 --> 00:44:21.230
Niraj Kumar Mishra .: Okay, thanks, sir. Thanks for explaining this, and sorry for asking so.

342
00:44:21.230 --> 00:44:38.160
Faculty (Olympus): No, no, no, no, it's fine, it's important. That's why I wanted you toâ€¦ that's why I asked you the cross-question, because I need to know whether you understood. If you didn't understand, there'll be many other people who also don't understand. So you need to be absolutely clear what this is. And this is the heart of all of your modeling that you're going to do subsequently, so you need to really understand this. Angshuman.

343
00:44:41.300 --> 00:44:42.390
Angshuman Nandi .: Good morning, Professor.

344
00:44:42.390 --> 00:44:43.150
Faculty (Olympus): Good morning.

345
00:44:43.150 --> 00:44:45.200
Angshuman Nandi .: My first question in this class.

346
00:44:47.060 --> 00:44:47.740
Faculty (Olympus): Sure.

347
00:44:49.320 --> 00:44:54.360
Angshuman Nandi .: here, what you told, I understood what you told, but oneâ€¦ one fiction I just want toâ€¦

348
00:44:54.510 --> 00:44:56.859
Angshuman Nandi .: clarify from you.

349
00:44:57.040 --> 00:45:01.720
Angshuman Nandi .: And going back to our first class, where Professor Nikhil told.

350
00:45:02.410 --> 00:45:07.370
Angshuman Nandi .: Statistics provides a model that says how data is generated.

351
00:45:07.760 --> 00:45:10.289
Angshuman Nandi .: So, basically, it is a backward engine.

352
00:45:11.490 --> 00:45:12.470
Faculty (Olympus): Okay?

353
00:45:12.490 --> 00:45:18.739
Angshuman Nandi .: And second thing is probabilities data generation, where we provide the model, which is a forward engine.

354
00:45:20.240 --> 00:45:21.160
Faculty (Olympus): Okay.

355
00:45:21.400 --> 00:45:27.510
Angshuman Nandi .: Now, hereâ€¦ here, we have Y value, we have X value.

356
00:45:28.300 --> 00:45:32.479
Angshuman Nandi .: And our target is to keep the SSR list.

357
00:45:32.830 --> 00:45:36.760
Angshuman Nandi .: Based on that, we will find the base value of A and B.

358
00:45:37.710 --> 00:45:38.540
Faculty (Olympus): Yes.

359
00:45:38.950 --> 00:45:43.099
Angshuman Nandi .: That is what we try toâ€¦ we have to calculate, that is the estimator that will come out.

360
00:45:43.100 --> 00:45:45.999
Faculty (Olympus): That is what's called the least squares estimator, correct?

361
00:45:46.230 --> 00:45:48.310
Angshuman Nandi .: Thank you, sir. So that means we are

362
00:45:49.030 --> 00:45:57.630
Angshuman Nandi .: unconsciously or unknowingly, we are building our first model. Fundamentally, it is the first model we are building in our life, is the model that we are building.

363
00:45:58.040 --> 00:45:59.000
Faculty (Olympus): Absolutely.

364
00:45:59.340 --> 00:46:03.750
Faculty (Olympus): In fact, even the very process of doing a least squares estimator is also a model.

365
00:46:03.860 --> 00:46:14.650
Faculty (Olympus): Right? Because you're assuming that somehow thisâ€¦ minimizing the sum of square differences is going to give you a best answer. That's why, you know, many people will put it in best in quotes, right?

366
00:46:15.120 --> 00:46:15.790
Angshuman Nandi .: Thank you so much, sir.

367
00:46:15.790 --> 00:46:22.739
Faculty (Olympus): It's like CGPI, or whatever. It's some measure, it's some model of your intelligence, or whatever, how well you perform in class, or whatever, right?

368
00:46:23.040 --> 00:46:24.040
Faculty (Olympus): Tomorrow.

369
00:46:24.340 --> 00:46:25.050
Angshuman Nandi .: Thank you.

370
00:46:25.050 --> 00:46:30.429
Faculty (Olympus): And as they say, all models are wrong, some are useful, all right? So, that'sâ€¦ that's all it is.

371
00:46:30.920 --> 00:46:31.440
Angshuman Nandi .: Thanks.

372
00:46:32.730 --> 00:46:35.610
Faculty (Olympus): All right. Devendra?

373
00:46:36.270 --> 00:46:41.399
Devendra Rajeevsingh Parmar .: Yes, so just wanted to confirm the noise term, we have assumed it to be zero, right?

374
00:46:41.400 --> 00:46:49.800
Faculty (Olympus): No, you have assumed that it has zero mean, that its expectation is zero. Because the point is, if the expectation was not zero, I'll try and absorb it into my beta model.

375
00:46:50.860 --> 00:46:51.650
Devendra Rajeevsingh Parmar .: Okay.

376
00:46:53.110 --> 00:46:53.650
Devendra Rajeevsingh Parmar .: Okay, sir.

377
00:46:53.650 --> 00:46:56.029
Faculty (Olympus): Thank you. That's an intuitive way of looking at it.

378
00:46:56.250 --> 00:46:59.209
Faculty (Olympus): Alright, so I'm gonna clear out my annotations.

379
00:46:59.590 --> 00:47:01.160
Faculty (Olympus): observing focus.

380
00:47:01.290 --> 00:47:07.220
Niraj Kumar Mishra .: One more question. So, the expectationâ€¦ expected value is equal to mean value, is it?

381
00:47:07.550 --> 00:47:08.060
Faculty (Olympus): No.

382
00:47:08.060 --> 00:47:08.390
Niraj Kumar Mishra .: to.

383
00:47:08.390 --> 00:47:09.299
Faculty (Olympus): No, no, no.

384
00:47:09.640 --> 00:47:15.380
Faculty (Olympus): Soâ€¦ so, expected value is not the name, in the sense that

385
00:47:15.700 --> 00:47:18.569
Faculty (Olympus): Expected value is like the true expectation.

386
00:47:19.290 --> 00:47:30.110
Faculty (Olympus): Which is the true population. So the mean, the sample mean, which means I do 100 measurements, I'll get some estimates, right, using the estimator. So if I do 100 coin tosses, I'll get some value of P.

387
00:47:30.360 --> 00:47:32.080
Faculty (Olympus): That's only one estimate of peak.

388
00:47:33.310 --> 00:47:35.740
Faculty (Olympus): So this P also is going to be a random variable.

389
00:47:36.310 --> 00:47:37.450
Faculty (Olympus): In that sense.

390
00:47:37.710 --> 00:47:40.770
Faculty (Olympus): Every time I take a measurement, I'll get a slightly different value of P.

391
00:47:41.580 --> 00:47:42.390
Faculty (Olympus): This is aâ€¦

392
00:47:42.390 --> 00:47:46.669
Niraj Kumar Mishra .: Every, every experiment, probability multiplied byâ€¦

393
00:47:46.950 --> 00:47:50.350
Niraj Kumar Mishra .: The mean value will be the expected value.

394
00:47:50.670 --> 00:47:51.949
Faculty (Olympus): No, no, no, no, no, no.

395
00:47:52.170 --> 00:47:58.810
Faculty (Olympus): Mean of all the measurements will give you the expectationâ€¦ will give you an approximation to the expectation of that parameter.

396
00:48:01.870 --> 00:48:07.389
Faculty (Olympus): So, another way to put it, if I do infinite experiments, T is going to be

397
00:48:07.500 --> 00:48:09.270
Faculty (Olympus): Tending towards this number.

398
00:48:16.910 --> 00:48:20.789
Faculty (Olympus): I said this in the last class. Imagine you have this class distribution of weights.

399
00:48:21.160 --> 00:48:24.290
Faculty (Olympus): I want you to tell me what is the true mean of your class weights?

400
00:48:24.600 --> 00:48:26.339
Faculty (Olympus): Can you ever tell me that number?

401
00:48:28.220 --> 00:48:29.929
Faculty (Olympus): You can never tell me that number.

402
00:48:30.860 --> 00:48:32.329
Faculty (Olympus): By just doing computation.

403
00:48:32.940 --> 00:48:37.509
Faculty (Olympus): Why? Because you'll have to wait for all possible classes, every day, every minute.

404
00:48:37.750 --> 00:48:40.410
Faculty (Olympus): I breathe in, breathe out, my weight is changed, right?

405
00:48:41.540 --> 00:48:43.569
Faculty (Olympus): You'll have to measure all of those values.

406
00:48:44.280 --> 00:48:55.570
Faculty (Olympus): It's not possible, right? So every time you do a measurement, and you actually do a computation, it's going to be a finite number of numbers. So when you add up those numbers, all you get is an approximation to that true value.

407
00:48:57.350 --> 00:48:58.050
Niraj Kumar Mishra .: Okay.

408
00:49:00.320 --> 00:49:01.400
Faculty (Olympus): Niraj, is that clear?

409
00:49:01.400 --> 00:49:02.470
Niraj Kumar Mishra .: Yeah, clearly it's a clip.

410
00:49:02.470 --> 00:49:03.390
Faculty (Olympus): Okay, fine.

411
00:49:04.000 --> 00:49:05.820
Faculty (Olympus): Okay, so let's move on.

412
00:49:06.250 --> 00:49:13.300
Faculty (Olympus): So now our task is, from this SSR, can I find A and B? Can I find a formula for A and B involving Y A and B? The answer isâ€¦

413
00:49:13.490 --> 00:49:17.990
Faculty (Olympus): Straightforward, you differentiate the SS with respect to A and B, and set them to 0.

414
00:49:18.170 --> 00:49:22.129
Faculty (Olympus): And of course, you look at the second derivative and make sure that second derivative isâ€¦

415
00:49:22.670 --> 00:49:34.810
Faculty (Olympus): positive, right? So that is a minimum, okay? So you do that, you'll end up with this set of equations. You'll get sigma Yi is n times a plus b times sigma Y xi. Here, all sigmas are from 1 to n, okay?

416
00:49:34.980 --> 00:49:41.280
Faculty (Olympus): And then, for the other term, square term, right, for B, because it's square,

417
00:49:42.240 --> 00:49:43.319
Faculty (Olympus): What do you get?

418
00:49:43.890 --> 00:49:48.760
Faculty (Olympus): you'll get Xiyyi is equal to A times Xi plus B of Xi squared.

419
00:49:49.690 --> 00:49:59.709
Faculty (Olympus): Alright, so if you just take this and simply do differentiation of this with respect to A and B, partial derivatives, set them to zero, you'll get these two equations. These are called the normal equations.

420
00:49:59.950 --> 00:50:12.839
Faculty (Olympus): And notice that they are linear in A and B. So I have A intoâ€¦ this is a known number, sigma Yi is known, Xi Yi is known, Xi sigma is known, sigma Xi is known, sigma Xi squared. All of these quantities are known.

421
00:50:13.440 --> 00:50:25.850
Faculty (Olympus): So now I have two unknowns, two equations. I can solve it, okay? And so now, if I set Y bar is sigma Yi by N, X bar is Xi by N. Say average value of your X measurements, average value of your Y measurements.

422
00:50:25.850 --> 00:50:33.979
Faculty (Olympus): The solution simply becomes B is sigma Xi capital Yi minus NX bar Y bar divided by Xi squared minus NX bar squared.

423
00:50:34.480 --> 00:50:36.870
Faculty (Olympus): Just solving these two equations simultaneously.

424
00:50:37.020 --> 00:50:42.369
Faculty (Olympus): And then Y is nothing but Y bar minusâ€¦ B times X bar.

425
00:50:43.180 --> 00:50:47.780
Faculty (Olympus): Alright, so which means your straight line is going to pass through the average value of X bar and y.

426
00:50:48.000 --> 00:50:49.170
Faculty (Olympus): Please notice.

427
00:50:50.850 --> 00:50:55.229
Faculty (Olympus): Alright? Straight line passes through this point, and you just need to fix one more point.

428
00:50:55.780 --> 00:50:57.439
Faculty (Olympus): Homo, which is your beep.

429
00:50:58.270 --> 00:51:09.409
Faculty (Olympus): Is that okay, everyone? So these two fellows here, A and B formula that we have here, these are your least squares estimators for alpha and beta parameters.

430
00:51:10.490 --> 00:51:11.920
Faculty (Olympus): These two fellows here.

431
00:51:12.550 --> 00:51:13.370
Faculty (Olympus): Okay?

432
00:51:14.000 --> 00:51:25.289
Faculty (Olympus): So now, you can also look at certain other quantities, okay? So if you look at what's called SXX, it's simply Xi minus X bar squared. What does this look like? XXX, what does this look like?

433
00:51:25.500 --> 00:51:27.070
Gaurav Singh .: Variance of X.

434
00:51:27.070 --> 00:51:35.030
Faculty (Olympus): looks like the variance, but we have not divided by N or N-1, okay? So this does look like it's related to the variance. SYY looks like the variance of Y.

435
00:51:35.350 --> 00:51:39.290
Faculty (Olympus): Okay? And SXY, what does SXY look like? You've seen this.

436
00:51:39.640 --> 00:51:40.750
Gaurav Singh .: covariance.

437
00:51:40.750 --> 00:51:49.060
Faculty (Olympus): This looks like the covariates, okay? Now, it turns out, when you look at all of this, B is nothing but the covariance divided by variance of S.

438
00:51:50.350 --> 00:51:55.150
Faculty (Olympus): Or related to that quality. Of course, constant sitting outside. Does it make sense?

439
00:51:55.820 --> 00:52:13.950
Faculty (Olympus): And then, you come up with this identity, which SSR is nothing but SXXSYY into SXY squared by SXX. It's just useful for mathematical manipulation. You don't have to remember, I don't expect you to memorize any of these quantities, okay? Maybe your stats instructors will do it, but I want you to understand the procedure that we follow, okay?

440
00:52:14.030 --> 00:52:21.609
Faculty (Olympus): So here is a situation where we have minimized some error, okay? We have minimized this error, total error.

441
00:52:21.930 --> 00:52:27.059
Faculty (Olympus): and obtained estimators of A and B. So this is your first ML model.

442
00:52:27.350 --> 00:52:34.850
Faculty (Olympus): Ever, hopefully, that you have looked at, and this is an ML model. You have actually solved two parameters based on some input data.

443
00:52:36.620 --> 00:52:37.450
Faculty (Olympus): Okay?

444
00:52:39.380 --> 00:52:46.249
Faculty (Olympus): All right, so I will stop here for any questions very quickly. Any questions so far? Is whatever we have done clear?

445
00:52:46.720 --> 00:52:47.970
Faculty (Olympus): Alright, Rahul.

446
00:52:48.650 --> 00:52:54.480
Rahul Shrikrishna Joshi .: In this, in this, process, if there are few measurements, which are

447
00:52:54.760 --> 00:52:59.260
Rahul Shrikrishna Joshi .: we call it as outliers. We're far too high or far too low. They canâ€¦

448
00:52:59.620 --> 00:53:01.740
Rahul Shrikrishna Joshi .: dominate the model, right? Yes.

449
00:53:01.740 --> 00:53:03.390
Faculty (Olympus): Absolutely. They can.

450
00:53:03.690 --> 00:53:05.039
Faculty (Olympus): So you have to be careful.

451
00:53:05.360 --> 00:53:08.390
Faculty (Olympus): And that is a judgment call that the modeler has to make.

452
00:53:12.800 --> 00:53:16.730
Faculty (Olympus): Right? You have to break a judgment call. That's so far an outlier.

453
00:53:17.700 --> 00:53:21.880
Rahul Shrikrishna Joshi .: And so, can you just explain this differentiation process once, like, how you canâ€¦

454
00:53:21.880 --> 00:53:23.469
Faculty (Olympus): I think this is standard minimization.

455
00:53:23.650 --> 00:53:26.389
Faculty (Olympus): If I minimize a continuous function of A and B.

456
00:53:27.840 --> 00:53:30.050
Rahul Shrikrishna Joshi .: We should differentiate with theâ€¦

457
00:53:30.630 --> 00:53:32.840
Faculty (Olympus): How do you find the minimum of some function?

458
00:53:33.930 --> 00:53:36.130
Rahul Shrikrishna Joshi .: Yeah, differentiate it with that variable.

459
00:53:36.130 --> 00:53:39.159
Faculty (Olympus): Basically, minimum means the slope should be zero, soâ€¦

460
00:53:39.260 --> 00:53:49.599
Faculty (Olympus): Partial derivative of that is set to 0. That becomes your extrema. And then to actually ascertain that it is a minimum, you have to look at the second derivative and show that it's positive, so that it's actually like this.

461
00:53:50.440 --> 00:53:51.230
Faculty (Olympus): Yep.

462
00:53:51.400 --> 00:53:52.360
Faculty (Olympus): That's all.

463
00:53:53.220 --> 00:53:54.230
Faculty (Olympus): Soumen?

464
00:53:55.170 --> 00:54:01.859
Soumen Deb .: Yeah, so one question, though. So, you mentioned, Mane will be taken, right?

465
00:54:01.860 --> 00:54:03.020
Faculty (Olympus): Where is the link taken?

466
00:54:04.310 --> 00:54:06.510
Soumen Deb .: So, because.

467
00:54:06.510 --> 00:54:06.830
Faculty (Olympus): Yeah.

468
00:54:06.830 --> 00:54:08.290
Soumen Deb .: VFs, yeah.

469
00:54:08.640 --> 00:54:11.529
Faculty (Olympus): So the sample mean of Y sample mean of X, okay.

470
00:54:11.860 --> 00:54:13.459
Soumen Deb .: Okay, so, so are we notâ€¦

471
00:54:13.630 --> 00:54:20.059
Soumen Deb .: Sort of going to refer to median later, rather than mean, because means have outliers, medians don't have aâ€¦

472
00:54:20.440 --> 00:54:21.969
Faculty (Olympus): No, in this process.

473
00:54:22.780 --> 00:54:29.439
Faculty (Olympus): We have not usedâ€¦ there's no notion of medium, or there's notion of medium. There's no hint of any medium showing up anywhere.

474
00:54:29.770 --> 00:54:32.649
Faculty (Olympus): Medians will not show up when you do a least squares approximation.

475
00:54:34.060 --> 00:54:39.249
Faculty (Olympus): So, least squares approximation areâ€¦ Sensitive to outliers.

476
00:54:39.690 --> 00:54:42.940
Faculty (Olympus): So your outlier can basically mess up your coefficients.

477
00:54:43.170 --> 00:54:43.960
Faculty (Olympus): They can.

478
00:54:44.470 --> 00:54:47.210
Faculty (Olympus): It's an inherent downside of doing least squares approximity.

479
00:54:48.340 --> 00:54:54.240
Soumen Deb .: Okay? Because the Y-bar calculation itself is like aâ€¦ mean calculation, right?

480
00:54:54.240 --> 00:55:00.599
Faculty (Olympus): No, no, this is just aâ€¦ this is just a substitution. I'm justâ€¦ these are the actualâ€¦ these are the two quantities to find A and B.

481
00:55:00.920 --> 00:55:09.840
Faculty (Olympus): It's aâ€¦ it's aâ€¦ it's a, you know, estimator for A and B, for alpha and beta. A and B are estimators for alpha and beta. We have given you now a closed-form expression.

482
00:55:10.100 --> 00:55:14.829
Faculty (Olympus): If I give you a set of X values, set of Y values, you can tell me end. One shot.

483
00:55:15.940 --> 00:55:30.000
Soumen Deb .: Okay, so, so, so just to look at this, these two points A and B, so because we have Yi is measured and Xi is also, so using that, we will calculate the coefficients of A and B. That's what we are doing.

484
00:55:30.000 --> 00:55:33.300
Faculty (Olympus): So, see, original goal was, I don't know A and B,

485
00:55:33.410 --> 00:55:37.509
Faculty (Olympus): I will now give you a methodology or a process by which you can find AN.

486
00:55:38.430 --> 00:55:46.270
Faculty (Olympus): This is the methodology. You takeâ€¦ minimize the sum of the squares of differences. And the reason we do this is because it's mathematically easier to do.

487
00:55:47.980 --> 00:55:50.800
Soumen Deb .: Yeah, sort of linear algebra, right? Something like that.

488
00:55:50.920 --> 00:55:54.340
Faculty (Olympus): Yeah, and actually, the answer becomes an Indian algebra question, yeah.

489
00:55:54.340 --> 00:55:55.860
Soumen Deb .: Oh, cool, thanks, thanks.

490
00:55:56.430 --> 00:55:57.370
Faculty (Olympus): Ang Soumen?

491
00:55:58.350 --> 00:56:09.519
Angshuman Nandi .: Another question, onceâ€¦ now, now in the step, moving forward, we estimate, or we, we have done with the estimated of the model. So, basically, we have created the model, no?

492
00:56:09.800 --> 00:56:28.700
Angshuman Nandi .: One question, sir, fundamentally, does that mean that residue of my data, so basically, it is correlated to my data. So, if I share this model with someone, he should have some inference of my data out of this. I mean, here it comes, or it is independent of the data.

493
00:56:29.650 --> 00:56:38.220
Angshuman Nandi .: It is just a formula we are establishing with the data, or it will have precipitation of my data, I mean, someâ€¦

494
00:56:38.220 --> 00:56:48.729
Faculty (Olympus): It does. It does distill your data into that, whatever the model is. So, for example, if I did, you know, I was trying to measure the constant G, or, you know, the time period of oscillation from that, I'll get two values.

495
00:56:48.980 --> 00:56:50.469
Faculty (Olympus): And those values?

496
00:56:50.670 --> 00:56:54.219
Faculty (Olympus): will be representative of that experiment. It will not apply to some other experiment.

497
00:56:55.360 --> 00:56:55.900
Angshuman Nandi .: Okay.

498
00:56:56.410 --> 00:57:00.900
Faculty (Olympus): So, therefore, they do encode the behavior of that specific experiment that you're looking at.

499
00:57:03.010 --> 00:57:03.840
Angshuman Nandi .: Thank you, sir.

500
00:57:03.840 --> 00:57:09.540
Faculty (Olympus): Right? But that does not mean that somebody else who does the same experiment is going to get the same numbers. No, not at all.

501
00:57:11.850 --> 00:57:13.850
Angshuman Nandi .: Why, last sentence, why, why not?

502
00:57:13.850 --> 00:57:21.429
Faculty (Olympus): somebody else does another experiment, the numbers they get will be different. That is natural, because it's justâ€¦ there is stochasticity in the measurements.

503
00:57:21.720 --> 00:57:22.250
Angshuman Nandi .: Fuck.

504
00:57:23.170 --> 00:57:28.259
Faculty (Olympus): There is noise in the measurements. The way in which they've done those measurements, their time measurements.

505
00:57:28.370 --> 00:57:31.370
Faculty (Olympus): The numbers that you actually get every time will be slightly different.

506
00:57:31.780 --> 00:57:40.919
Faculty (Olympus): But they will still encode this linear relationship, which has to do with your understanding of the phenomenon, saying that the time period squared is proportional to the length of the printer.

507
00:57:43.500 --> 00:57:44.809
Angshuman Nandi .: Thanks, sir. Thank you so much.

508
00:57:47.480 --> 00:58:04.740
Faculty (Olympus): All right, so next thing we look at is, we look at two quantities, sorry, one major quantity is called the coefficient of determination, and this is a means with which you can tell how much of your model is being explained by the

509
00:58:05.200 --> 00:58:10.400
Faculty (Olympus): model. How much of your, sorry, how much of your outputs is being explained by your model and the inputs?

510
00:58:11.010 --> 00:58:17.790
Faculty (Olympus): So, if you compute based on this identity of SSR, you canâ€¦ I'm not going to explain, you know, I'm not going to go into this calculation.

511
00:58:18.580 --> 00:58:29.820
Faculty (Olympus): But, just to recall, SYY is the variation of the set of values. Why? SSR is the variation in the responses after considering the inputs. What does this mean? You have Yi, you've taken out.

512
00:58:30.170 --> 00:58:38.360
Faculty (Olympus): A plus BXI, right? Whatever YI you have, you've taken out this fellow, that's the difference. So it's like the residual for every measurement, right? Look at Yi.

513
00:58:38.840 --> 00:58:47.760
Faculty (Olympus): This is my model prediction, this is my actual value. So, whatever is through your linear model you have explained, I am removing from this YI, and whatever is left

514
00:58:47.910 --> 00:58:58.150
Faculty (Olympus): that is unexplained by my model, I'm going to stick the square of this, okay? So what it is, is it's the variation in responses after considering all of the inputs through your model, okay?

515
00:58:58.340 --> 00:59:14.589
Faculty (Olympus): And so now, SYY minus SSR is the variation in response explained purely by the inputs alone, okay? So SYY minus SSR is the variation explained purely by the inputs. So the coefficient of determination is simply the ratio of these two, SYY minus SSR divided by SYY.

516
00:59:14.960 --> 00:59:22.290
Faculty (Olympus): And so you can clearly see that, supposing R squared, this R squared quantity, goes towards 1, It meansâ€¦

517
00:59:22.580 --> 00:59:26.760
Faculty (Olympus): All of your measurements are explained purely by the inputs.

518
00:59:27.270 --> 00:59:31.030
Faculty (Olympus): There's nothing else. That means your linear model is an excellent model for this model.

519
00:59:31.250 --> 00:59:36.830
Faculty (Olympus): Okay? And you can easily see that this is this 1 minus SSR by S1, okay?

520
00:59:37.520 --> 00:59:42.989
Faculty (Olympus): Andâ€¦ This R squared, you can prove, is always going to be between 0 and 1.

521
00:59:43.820 --> 00:59:53.810
Faculty (Olympus): And it turns out that this is something you have already seen in the Pearson's correlation. Pearson's correlation coefficient is simply square root ofâ€¦ positive square root of this R-scope.

522
00:59:54.710 --> 00:59:58.389
Faculty (Olympus): So, there's a deep connection between your correlation coefficient.

523
00:59:58.560 --> 01:00:07.770
Faculty (Olympus): And this coefficient of determination. Essentially, they're just the square root. One is this other. Square root of your coefficient of determination is your Pearson's coefficient.

524
01:00:08.090 --> 01:00:16.919
Faculty (Olympus): Which is why, when you remember when I told you about the correlation coefficient, I told you that the correlation coefficient is a measure of how well

525
01:00:17.250 --> 01:00:20.950
Faculty (Olympus): These two quantities are linearly related.

526
01:00:21.410 --> 01:00:23.560
Faculty (Olympus): Okay, so all of that comes out from here.

527
01:00:24.910 --> 01:00:30.059
Faculty (Olympus): And so if R squared is very close to 1, means you have a great linear model.

528
01:00:32.480 --> 01:00:33.360
Faculty (Olympus): Soumen?

529
01:00:33.870 --> 01:00:35.490
Soumen Deb .: Yeah, sorry. Soâ€¦

530
01:00:35.840 --> 01:00:41.449
Soumen Deb .: If they are related, only then you can model. If they are not regionally related, they are, like.

531
01:00:41.450 --> 01:00:46.279
Faculty (Olympus): So, this is where they say, correlation isâ€¦ causation, does not hold.

532
01:00:46.660 --> 01:00:53.979
Faculty (Olympus): See, it may be that this variable is some side variable that isâ€¦ you're not ascertaining that one is dependent in that strict sense.

533
01:00:55.390 --> 01:00:57.140
Faculty (Olympus): You're saying that?

534
01:00:58.400 --> 01:01:04.139
Faculty (Olympus): Mathematically, this and this are very well related by this linear model. That's all you're saying.

535
01:01:04.560 --> 01:01:05.279
Soumen Deb .: Soâ€¦

536
01:01:06.000 --> 01:01:07.510
Faculty (Olympus): You're not saying there's causation.

537
01:01:08.330 --> 01:01:09.889
Soumen Deb .: Yes, okay.

538
01:01:09.890 --> 01:01:14.770
Faculty (Olympus): More, that requires more analysis, butâ€¦ That's all.

539
01:01:14.770 --> 01:01:24.670
Soumen Deb .: Ashishâ€¦ So basically, that's what we are going ahead in modeling it on the basis of assumptions that it will model, right? So it's something like that.

540
01:01:24.670 --> 01:01:26.519
Faculty (Olympus): All models are going to do this, right?

541
01:01:26.520 --> 01:01:28.300
Soumen Deb .: Assumptions.

542
01:01:28.300 --> 01:01:44.470
Faculty (Olympus): Based onâ€¦ so how good those assumptions are the questions you're going to ask? How good is this model? How useful is this model? Right? That's what you're trying to assess. And this R-squared tells you that. R-squared basically says, hey, that model is very good because I'm able to explain everything. All of my measurements, I'm able to explain based on this model.

543
01:01:44.500 --> 01:02:01.430
Faculty (Olympus): Does that make sense? Again, you'll see this when I actually show you, so this is not just theory, this whole notebook talks only about linear regression, but it tries to sort of walk through this using, you know, numbers. I'm going to show you code to actually walk through this, generate fake data, and stuff like that.

544
01:02:01.600 --> 01:02:16.760
Soumen Deb .: Correct, so one last point, and what I want to ask is, see, everything cannot be done in two dimensions, because there'll be n dimensions also added. So how will we know that the model that we have done is really close? Is it by this calculation, or something more?

545
01:02:16.760 --> 01:02:19.619
Faculty (Olympus): So, supposing you have R squared is very close to 1, it's likeâ€¦

546
01:02:19.880 --> 01:02:23.950
Faculty (Olympus): Excellent. I can measure, I can basically predict everything with your model.

547
01:02:24.950 --> 01:02:27.179
Soumen Deb .: Yeah, so it's like, you know, we'll haveâ€¦

548
01:02:27.180 --> 01:02:33.720
Faculty (Olympus): See, this is what's fun. The variation in the set of Y's, Y values, is fully predicted by your model.

549
01:02:33.990 --> 01:02:35.330
Faculty (Olympus): Then what do you have to do?

550
01:02:37.670 --> 01:02:38.740
Soumen Deb .: Okay, Anchorâ€¦

551
01:02:38.740 --> 01:02:40.289
Faculty (Olympus): modeling. Have a great one.

552
01:02:40.290 --> 01:02:41.210
Soumen Deb .: One last question.

553
01:02:41.210 --> 01:02:41.599
Faculty (Olympus): But yes.

554
01:02:41.600 --> 01:02:41.989
Soumen Deb .: How are you doing?

555
01:02:41.990 --> 01:02:43.369
Faculty (Olympus): You may have multiple variables.

556
01:02:43.370 --> 01:02:44.259
Soumen Deb .: That's a great question.

557
01:02:44.260 --> 01:02:51.990
Faculty (Olympus): can do multiple variables. So this SSR can be applied for not just single linear. This is the simplest example, to give you an idea and a flavor for linear amounts.

558
01:02:52.200 --> 01:02:57.850
Faculty (Olympus): Which, by the way, in the next semester, when you do your Excel ML course, they will do a lot more theory of this, and it'sâ€¦

559
01:02:58.300 --> 01:03:02.370
Faculty (Olympus): In fact, regression, you will do a lot more detail in stats course also.

560
01:03:03.080 --> 01:03:04.410
Soumen Deb .: Okay, okay.

561
01:03:04.560 --> 01:03:09.380
Soumen Deb .: So this is two variables, but n variables extension is also there. That is where we'll validate.

562
01:03:09.380 --> 01:03:14.079
Faculty (Olympus): extension is there, you have to do it a little carefully, but you can do the extension. Yes, that is correct.

563
01:03:14.830 --> 01:03:16.680
Soumen Deb .: Okay. Oh, thank you.

564
01:03:18.730 --> 01:03:23.569
Faculty (Olympus): We will have to do an adjusted coefficient of determination with the number of variables, but that's not a big deal.

565
01:03:23.730 --> 01:03:25.740
Faculty (Olympus): We'll probably look at that later on.

566
01:03:25.870 --> 01:03:26.800
Faculty (Olympus): Ashish?

567
01:03:27.490 --> 01:03:37.259
Ashish Kumar .: Listen, my doubt is, this value SYY minus SSR, if the model is close to the actual values, then this will tend to 0, this, the numerator part.

568
01:03:38.990 --> 01:03:40.330
Faculty (Olympus): Becauseâ€¦

569
01:03:40.330 --> 01:03:43.880
Ashish Kumar .: values of Fourier, if it is close to the model, the actual values.

570
01:03:43.880 --> 01:03:46.429
Faculty (Olympus): No, no, SYY willâ€¦ no, no, no, no.

571
01:03:46.610 --> 01:03:53.480
Faculty (Olympus): SSR is the variation in the responses after considering the inputs. So remember that it is YI minus

572
01:03:53.620 --> 01:03:54.980
Faculty (Olympus): K plus BXI.

573
01:03:56.280 --> 01:03:57.110
Ashish Kumar .: Okay.

574
01:03:58.230 --> 01:04:00.940
Ashish Kumar .: So, so that is not taking into the fact.

575
01:04:00.940 --> 01:04:03.539
Faculty (Olympus): So, SSR is like the noise in your data.

576
01:04:04.040 --> 01:04:06.280
Faculty (Olympus): Okay. As per this model, what is lift?

577
01:04:07.550 --> 01:04:24.140
Faculty (Olympus): If the noise is very small, no, your model is basically accounted for every variation, then SSR goes towards zero. If SSR goesâ€¦ in fact, that's what you want, right? You want the errors in your model to go towards zero. In which case, this fellow will go towards 1, right? Because SSR is going to 0, and SYY is going to be whatever it is.

578
01:04:24.920 --> 01:04:36.569
Ashish Kumar .: Okay, sir, right, right, right. Got it, got it. Sure. Sir, one more doubt. Sir, if for many experiments, if we see that the expected value is close to the true mean, then

579
01:04:36.570 --> 01:04:45.919
Ashish Kumar .: instead of considering the SSR to minimize the SSR, we can take that prediction also, like, if we, for many experiments, if the expected value goes to the true mean.

580
01:04:46.020 --> 01:04:46.800
Ashish Kumar .: So, in thatâ€¦

581
01:04:46.800 --> 01:04:50.060
Faculty (Olympus): Hereâ€¦ no, no, here we don't know anything, right? I don't know A and B.

582
01:04:50.540 --> 01:04:57.070
Faculty (Olympus): Look, at this point, in this part of the notebook, how do you know A and B? There's just some variables, I have no idea how they are.

583
01:04:57.070 --> 01:05:09.699
Ashish Kumar .: So I guess I'm countering the point that if we have got outliers, so if our model considers a lot of experiments, and if the expected value in that case comes to the true mean, in that case, we have negated the value of the outliers.

584
01:05:09.700 --> 01:05:16.530
Faculty (Olympus): No, so that is going to be true always if your distribution of your points is reasonable, let's say it's normally distributed. The outliers are going to be small.

585
01:05:16.860 --> 01:05:31.840
Faculty (Olympus): So in the limit of infinite measurements, you're good. That, you may have to wait a long way. The problem is, you're squaring this fellow. So there's one outlier, and you have a finite number of measurements, and one fellow has one horrible outlier. He'll comeâ€¦ he canâ€¦ has the chance of skewing it, because you're squaring that one.

586
01:05:32.940 --> 01:05:38.820
Ashish Kumar .: Okay, sir. So that can beâ€¦ that can be negative if we take the expected value to close to the true mean.

587
01:05:39.180 --> 01:05:41.969
Faculty (Olympus): No. Again, it will onlyâ€¦ so, again.

588
01:05:42.310 --> 01:05:49.099
Faculty (Olympus): if I give you an outlier, will the expected value be close, or rather, will this sample mean be close to the true meme?

589
01:05:49.420 --> 01:05:52.280
Ashish Kumar .: But if you increase the number of samples taken.

590
01:05:52.280 --> 01:06:02.970
Faculty (Olympus): You have to increase theâ€¦ no, no, I'm saying you fixed the number of samples. I already told you. There's infinite samples, yeah, you're good. Nothing to worry about. The reality is, you're not going to have infinite samples.

591
01:06:03.300 --> 01:06:04.740
Ashish Kumar .: Alright, Sil, right.

592
01:06:05.240 --> 01:06:07.039
Faculty (Olympus): Right? And then it becomes a problem.

593
01:06:07.420 --> 01:06:08.990
Faculty (Olympus): We'll have small samples.

594
01:06:11.490 --> 01:06:12.520
Ashish Kumar .: Local city.

595
01:06:12.520 --> 01:06:13.070
Faculty (Olympus): Yep.

596
01:06:13.190 --> 01:06:14.130
Faculty (Olympus): Sameer?

597
01:06:14.660 --> 01:06:21.580
Sameer Sawant .: So, Professor, so if the R-square is 0, it means we can't define any relationship between all the samples, right?

598
01:06:21.580 --> 01:06:22.880
Faculty (Olympus): Davens are a lousy model.

599
01:06:23.060 --> 01:06:23.640
Faculty (Olympus): Basically.

600
01:06:23.850 --> 01:06:27.939
Sameer Sawant .: Okay, and let's say if the R squared is 1, or we say plus or minus 1, the R squared.

601
01:06:27.940 --> 01:06:33.340
Faculty (Olympus): Close to a knot, exactly. It'll never be exactly zero, it'll never be 1 knot, so it'll be somewhere in the range.

602
01:06:33.460 --> 01:06:39.909
Faculty (Olympus): Close to 1 means great model. I'll show you, when you see thatâ€¦ when you see the code in action, it'll sort of make a lot more sense.

603
01:06:40.130 --> 01:06:56.659
Sameer Sawant .: Yeah, and when we sayâ€¦ when we say R squared is 1, or the actual R, Pearson coefficient is plus minus 1, it does tell us that, okay, like we said, right, if X increases, Y increases, or X increases, Y reduces. Can we eventually go to that level of Pearson coefficient to sayâ€¦ Yeah, it is.

604
01:06:56.660 --> 01:07:04.719
Faculty (Olympus): In fact, it is exactly that. So, in fact, it's basically telling you that Pearson's correlation coefficient is close to 1, means there's a strong chance you have a good linear model. Yes?

605
01:07:06.450 --> 01:07:07.710
Sameer Sawant .: Okay, okay, thank you.

606
01:07:07.710 --> 01:07:16.949
Faculty (Olympus): So if you see, you do a scatterplot, you see fellows, like, just banding beautifully around a straight line. You have a good chance of modeling that to the straight line. That's all. In fact, it is a straight line.

607
01:07:17.110 --> 01:07:21.709
Faculty (Olympus): In fact, you do not want to model all the noise. That's too much. That's overmodeling, that's overfitting.

608
01:07:23.460 --> 01:07:26.739
Sameer Sawant .: And the slope will tell us whether it's a direct or an indirect.

609
01:07:26.740 --> 01:07:31.080
Faculty (Olympus): Exactly. So when the slope is negative means, as this fellow increases, that will go down. Yes?

610
01:07:31.240 --> 01:07:31.770
Sameer Sawant .: Okay.

611
01:07:32.170 --> 01:07:33.060
Sameer Sawant .: Yes.

612
01:07:33.210 --> 01:07:33.820
Faculty (Olympus): Yes.

613
01:07:34.320 --> 01:07:38.799
Faculty (Olympus): Sameer, I think you just finished, right? Okay. Gaurav?

614
01:07:40.170 --> 01:07:41.780
Gaurav Singh .: Yeah, so,

615
01:07:41.780 --> 01:07:44.719
Faculty (Olympus): Oh, Same isâ€¦ Sameer is dumb, yeah, okay, sorry, Gaurav.

616
01:07:45.020 --> 01:08:01.730
Gaurav Singh .: Yeah, so, ourâ€¦ where you have, mentioned the R-square thing, right? Can, can be good. So, coefficient of determination. First of all, I didn't understand, like, YSYY minus SSR divided by SYY, I mean.

617
01:08:01.920 --> 01:08:03.000
Gaurav Singh .: While we areâ€¦

618
01:08:03.000 --> 01:08:07.430
Faculty (Olympus): That is confusing, look at this fellow. 1 minus SSR by SYY, does that make sense?

619
01:08:07.690 --> 01:08:09.130
Faculty (Olympus): SSR is what?

620
01:08:09.680 --> 01:08:12.420
Gaurav Singh .: SSR is the difference,

621
01:08:12.420 --> 01:08:14.620
Faculty (Olympus): Between your model prediction and your true value.

622
01:08:14.620 --> 01:08:15.610
Gaurav Singh .: Exactly.

623
01:08:15.610 --> 01:08:19.769
Faculty (Olympus): Right. So supposing your model is an empathetic model, everything is zero, right?

624
01:08:19.779 --> 01:08:20.499
Gaurav Singh .: Mhmhm.

625
01:08:21.010 --> 01:08:24.799
Faculty (Olympus): Pathetic model. That means yourâ€¦ that SSR will be SYY.

626
01:08:25.740 --> 01:08:29.710
Faculty (Olympus): Why? Because this A plus BXI is 0. This one is going to be sigma.

627
01:08:29.939 --> 01:08:31.029
Faculty (Olympus): Y squared.

628
01:08:31.760 --> 01:08:32.559
Faculty (Olympus): So theâ€¦

629
01:08:32.569 --> 01:08:34.849
Gaurav Singh .: EXI will be zero, okay?

630
01:08:36.040 --> 01:08:38.670
Faculty (Olympus): So if it's a pathetic model, really horrible model.

631
01:08:38.920 --> 01:08:41.649
Faculty (Olympus): Then you won't explain any of the variation in the data.

632
01:08:42.060 --> 01:08:44.520
Faculty (Olympus): So this quantity here is going to be close to 1.

633
01:08:45.580 --> 01:08:46.410
Gaurav Singh .: Okay.

634
01:08:47.279 --> 01:08:48.270
Gaurav Singh .: Okay.

635
01:08:50.710 --> 01:08:51.629
Faculty (Olympus): So that's it.

636
01:08:53.590 --> 01:08:58.709
Gaurav Singh .: Basically, instead of minimizing, it will be maximizing that difference. That's what you were trying to say.

637
01:08:58.710 --> 01:09:08.850
Faculty (Olympus): No, no, no, no, no, no, no, there'sâ€¦ you're confusing a lot of things here. No, no, no, there's no minimization, I'm not talking of anything here. I amâ€¦ see, your process of finding the estimators does the minimizers.

638
01:09:09.160 --> 01:09:13.859
Faculty (Olympus): A and B are the minimizers of this residue. Correct. That's how I got this formula.

639
01:09:14.199 --> 01:09:14.919
Gaurav Singh .: Mhmh.

640
01:09:15.359 --> 01:09:16.509
Faculty (Olympus): Now, forget about all that.

641
01:09:16.700 --> 01:09:18.599
Gaurav Singh .: Yeah, nowâ€¦ I give you a.

642
01:09:18.609 --> 01:09:23.429
Faculty (Olympus): model, I give you a model, A plus BXI. Yeah. I give you some rotten coefficients.

643
01:09:23.569 --> 01:09:28.789
Faculty (Olympus): Useless coefficients, okay? You use that model. How do you assess this model?

644
01:09:29.949 --> 01:09:37.269
Faculty (Olympus): Yeah. So youâ€¦ this method gives you a mechanism by which you can assess this model. So you compute SSR, who compute SYY, find SYY minus SSR,

645
01:09:37.799 --> 01:09:39.509
Faculty (Olympus): And divide that by SYY.

646
01:09:39.889 --> 01:09:42.459
Faculty (Olympus): You will always get a number that's between 0 and 1.

647
01:09:44.419 --> 01:09:57.799
Faculty (Olympus): If it's close to 1, so the reason this isâ€¦ this works is because SYY is the variation of the set of values, SSR is the variation in the responses after considering the inputs. What does that mean? Right? It's because it's YEI minus your model fellow, right?

648
01:09:57.800 --> 01:09:59.570
Gaurav Singh .: modelâ€¦ Salvayarani.

649
01:09:59.570 --> 01:10:01.529
Faculty (Olympus): Difference between your predictions and your actual value.

650
01:10:01.530 --> 01:10:02.500
Gaurav Singh .: Yeah, yeah.

651
01:10:02.500 --> 01:10:07.099
Faculty (Olympus): So therefore, SYY minus SSR is the variation in the response explained by the inputs.

652
01:10:07.890 --> 01:10:08.740
Gaurav Singh .: Okay.

653
01:10:08.950 --> 01:10:14.730
Faculty (Olympus): Right? So, which means it's super explanation. Fantastic, everything is answered, that SY1 and SSR will be SYV.

654
01:10:15.830 --> 01:10:16.520
Gaurav Singh .: Hmm.

655
01:10:16.520 --> 01:10:19.189
Faculty (Olympus): So it means inputs are explaining all of the outputs.

656
01:10:19.740 --> 01:10:21.500
Faculty (Olympus): But supposing, no, it's not so great.

657
01:10:21.980 --> 01:10:33.619
Faculty (Olympus): only half of these numbers are being, you know, expressed properly. It's like, okay, sort of fit. This number will not be, you know, close to SSY. So you divide these two, you'll get a number that's not close to 1.

658
01:10:34.200 --> 01:10:34.720
Gaurav Singh .: Hmm.

659
01:10:34.720 --> 01:10:43.920
Faculty (Olympus): So, in fact, more easy than this quantity is this right-hand side, right? This 1 minus SSR by S5Y is very clear and easy to understand. If you have a fantastic model, your SSR will be very small.

660
01:10:44.490 --> 01:10:45.260
Gaurav Singh .: Yeah.

661
01:10:45.500 --> 01:10:46.180
Faculty (Olympus): Right?

662
01:10:46.820 --> 01:10:50.280
Faculty (Olympus): So this goes to zero means you have an amazing model.

663
01:10:50.460 --> 01:10:55.950
Faculty (Olympus): So R squared is going to be close to 1. So whenever you do this, you do some any model. You find R squared.

664
01:10:56.220 --> 01:11:00.170
Faculty (Olympus): Right? A linear model in this case. One parameter. We do R squared.

665
01:11:00.380 --> 01:11:02.979
Faculty (Olympus): If R squared is close to 1, you're in good shape.

666
01:11:03.700 --> 01:11:04.240
Gaurav Singh .: Hmm.

667
01:11:04.240 --> 01:11:07.940
Faculty (Olympus): R-squared is close to zero, your model has to be seriously reconsidered.

668
01:11:09.030 --> 01:11:09.790
Gaurav Singh .: Okay.

669
01:11:10.580 --> 01:11:11.130
Gaurav Singh .: Sure.

670
01:11:11.130 --> 01:11:15.679
Faculty (Olympus): As in, you have not explained enough. You need to maybe incorporate additional variables.

671
01:11:16.850 --> 01:11:17.620
Gaurav Singh .: Understood.

672
01:11:18.260 --> 01:11:19.000
Faculty (Olympus): Okay.

673
01:11:21.020 --> 01:11:23.799
Faculty (Olympus): Alright, so, building on this, Rahul.

674
01:11:23.800 --> 01:11:25.469
Rahul Shrikrishna Joshi .: Justin, I have a question. Yeah, yeah.

675
01:11:25.690 --> 01:11:42.889
Rahul Shrikrishna Joshi .: Sir, just to, if you go to that coefficient of determination, let's say if Y1 and Y2 are my actual measurements, okay? And then, by calculating the A and B, means after A and B is calculated, model is designed, and if I put the measured X, I'm getting, let's say, M1 and M2.

676
01:11:43.260 --> 01:11:47.420
Rahul Shrikrishna Joshi .: So Y1 and Y2 is actual measured value, M1 and M2 is calculated by a model.

677
01:11:47.540 --> 01:11:51.050
Rahul Shrikrishna Joshi .: then why the formula should not be just Y1 minus M1 upon Y1?

678
01:11:53.360 --> 01:11:57.400
Faculty (Olympus): Because I have multiple measurements. I have only one measurement and two measurements.

679
01:11:57.400 --> 01:11:57.990
Rahul Shrikrishna Joshi .: Absolutely.

680
01:11:57.990 --> 01:11:58.600
Faculty (Olympus): bummer's.

681
01:11:59.040 --> 01:12:00.620
Rahul Shrikrishna Joshi .: I'm gonna say something like that.

682
01:12:00.620 --> 01:12:05.720
Faculty (Olympus): You want a model to predict everything, right? If you want your model to just predict one quantity, it's like a bad model.

683
01:12:06.050 --> 01:12:21.199
Rahul Shrikrishna Joshi .: No, no, so what I'm trying to ask is, let's say if you have 220 measurement, doesn't matter, okay? But every time, whatever is my actual measurement and a value given by my model, okay, we want to minimize the difference between the two. Then only it is a best.

684
01:12:21.200 --> 01:12:26.130
Faculty (Olympus): Not for every single thing. You want to predictâ€¦ you want to minimize the totality of the model.

685
01:12:27.020 --> 01:12:32.200
Faculty (Olympus): Look at this again. SSR is defined as the sum of all these errors. It's not just one single point.

686
01:12:35.170 --> 01:12:40.249
Rahul Shrikrishna Joshi .: But, say, in the coefficient of measurement, it's a single value, right? R is a single value, right? R squared, whatever is that.

687
01:12:40.250 --> 01:12:42.909
Faculty (Olympus): Of my model, with respect to all my data.

688
01:12:43.490 --> 01:12:47.969
Rahul Shrikrishna Joshi .: Yeah, so, let's say if I have 10 data points, how to exactly calculate SYY?

689
01:12:48.260 --> 01:12:48.890
Rahul Shrikrishna Joshi .: Amanda.

690
01:12:48.890 --> 01:12:52.539
Faculty (Olympus): Already, it's been given here, right? This formula is given here. I don't understand what the question is.

691
01:12:52.640 --> 01:12:53.230
Rahul Shrikrishna Joshi .: swim.

692
01:12:53.230 --> 01:12:55.520
Faculty (Olympus): A minus way above the whole squared, sigma.

693
01:12:56.870 --> 01:12:58.350
Rahul Shrikrishna Joshi .: Okay, okay, so that isâ€¦

694
01:12:58.350 --> 01:13:04.240
Faculty (Olympus): Right? So, all of these quantities are for all your data. It's not for just one subset of your data, not for a single point.

695
01:13:05.040 --> 01:13:06.430
Rahul Shrikrishna Joshi .: Okay, okay, got it, yeah.

696
01:13:06.830 --> 01:13:15.039
Faculty (Olympus): Right, so A and B, all of these, the idea is you want to take all your data and want to be able to somehow calculate A and B appropriately, and there are many ways of doing A and B.

697
01:13:15.220 --> 01:13:19.680
Faculty (Olympus): So this is only one way of computing these estimators. This is called a least squares estimate.

698
01:13:21.520 --> 01:13:22.120
Rahul Shrikrishna Joshi .: Mhmhm.

699
01:13:22.260 --> 01:13:23.189
Faculty (Olympus): Is that okay?

700
01:13:24.060 --> 01:13:27.310
Rahul Shrikrishna Joshi .: Let me think over it, sir, yeah. Give me a few minutes here.

701
01:13:27.310 --> 01:13:36.949
Faculty (Olympus): And coefficient of determination is just saying, look, given all the measurements and all the values, true values, this is the total variation in the set of values, this is the total variation

702
01:13:37.300 --> 01:13:45.849
Faculty (Olympus): You know, explained by the inputs, and this is the ratio of those two. So you explained all of your outputs with your model, you have a good model.

703
01:13:52.480 --> 01:13:53.390
Faculty (Olympus): Gaurav?

704
01:13:54.100 --> 01:14:16.070
Gaurav Singh .: Yeah, professors, again, coming back to that SSR divided by SYY, sigma, Yi minus A minus BXI chi-square, and the summation of that is SSR, and SYY is Yi minus Y bar Kaholi square, and the summation, right? So, mathematically, Y bar

705
01:14:16.480 --> 01:14:28.539
Gaurav Singh .: is basically, for that sample, the mean of that Y is right, and in the above SSR is never going to be Y bars, right?

706
01:14:28.540 --> 01:14:30.550
Faculty (Olympus): this equation? What is the equation of A?

707
01:14:32.540 --> 01:14:35.110
Gaurav Singh .: A is Y bar minus BX bar, yeah.

708
01:14:35.110 --> 01:14:38.499
Faculty (Olympus): So it means your best fit line is going to pass through the origin.

709
01:14:38.640 --> 01:14:41.120
Faculty (Olympus): So, pass through your X bar and Y bar.

710
01:14:41.670 --> 01:14:42.380
Gaurav Singh .: Credit.

711
01:14:43.600 --> 01:14:44.390
Gaurav Singh .: Hmm.

712
01:14:44.540 --> 01:14:48.210
Faculty (Olympus): What does that mean? If I give you X bar value, it's going to predict Y bar, exactly.

713
01:14:48.840 --> 01:14:53.569
Gaurav Singh .: But in SSR, that is not X bar, right? What we are subtracting from YI.

714
01:14:53.710 --> 01:14:54.940
Gaurav Singh .: I've calculated.

715
01:14:54.940 --> 01:14:57.389
Faculty (Olympus): I have calculated A and B like this.

716
01:14:58.060 --> 01:14:59.229
Faculty (Olympus): When I do this.

717
01:15:01.510 --> 01:15:08.400
Faculty (Olympus): See, if you give me some terrible model, yeah, naturally your SSR will be junk, right? This value is going to be zero.

718
01:15:09.420 --> 01:15:10.090
Gaurav Singh .: Hmm.

719
01:15:12.140 --> 01:15:16.330
Gaurav Singh .: Okay, okay, I'llâ€¦ I'll go more deep into it.

720
01:15:16.330 --> 01:15:26.359
Faculty (Olympus): Youâ€¦ I mean, I think, I don't know, maybe you've not worked through this. You need to work through this, and you'll understand it. You've not looked at this material. So please look at the material again, you'll make sense of it.

721
01:15:27.110 --> 01:15:34.039
Faculty (Olympus): Sure. And you'll be doing this again in your stats course. So, again, I don't want to spend way too much time. You've already spent so much time on this theory.

722
01:15:35.360 --> 01:15:43.580
Faculty (Olympus): I want you to understand at the high level what is going on, not the gory details. So don't expect me to prove why this is between 0 and 1. I'm not going to prove it here, okay?

723
01:15:44.810 --> 01:15:49.919
Faculty (Olympus): Then I'll have to take two courses for you in the span of a quarter of the course. Can't do that.

724
01:15:51.320 --> 01:16:08.230
Faculty (Olympus): But what I wanted to spend time today is the actual numericals for this, not the actual theory, okay? So I wanted to give you the big picture, and then we'll look at the numerics so you have some feel for this, so you can actually do simulation. Now, Rahul, I've already answered, I'm not going to answer any more, no more questions now, I need to finish thisâ€¦

725
01:16:08.780 --> 01:16:16.270
Faculty (Olympus): slide today, okay? So I'm not going to take any more questions until I finish some reasonable amount of it. Please hold your questions, okay? I'll come back to you later.

726
01:16:16.660 --> 01:16:27.099
Faculty (Olympus): So once they understand this, you know, we need to now assess this linear model. So there areâ€¦ this is one way. Finding this R-squared is one way of doing it, okay?

727
01:16:27.260 --> 01:16:43.510
Faculty (Olympus): Another way to do this, this is something I cannot explain when you do your stats course, you will understand why we need to do this. You will find that, finding SSR byâ€¦ sorry, square root of SSR by N minus 2 is actually an estimator for your variance in your errors.

728
01:16:43.840 --> 01:16:51.579
Faculty (Olympus): So this becomes yourâ€¦ sorry, your standard deviation of your errors is square root of SSR by N minus 2, okay? Soâ€¦

729
01:16:51.720 --> 01:17:05.650
Faculty (Olympus): if you think about this, Yi minus A plus BXI, so assuming your data is truly linear, you know, supposed to be in a linear model, and assuming that you have some errors in your measurement, Y minus A plus BXI should only be some error. It should be some noise.

730
01:17:05.870 --> 01:17:25.199
Faculty (Olympus): Right? And ideally, that noise should be nice, you know, normally distributed noise, okay? If that is the case, this fellow becomes, like, some standard, normal variable, okay? And you're dividing this by a standard deviation to give you YI minus A plus BXI should be normally distributed.

731
01:17:26.650 --> 01:17:36.880
Faculty (Olympus): And the reason this comes about is, implicitly, we are assuming that E is normally distributed. I haven't stated it here, but when you do your theory, you will actually make that assumption.

732
01:17:37.060 --> 01:17:46.120
Faculty (Olympus): If you know that your errors are normally distributed, then you can find that the residuals are also going to be normally distributed, which is really what it's saying, after you've done the fitting.

733
01:17:46.570 --> 01:17:50.230
Faculty (Olympus): And this gives you what are called standardized residues, okay?

734
01:17:50.750 --> 01:17:56.959
Faculty (Olympus): So, if I were to give you a standardized residual, if I tell you that the residual should look like a normal distribution, standardized.

735
01:17:58.130 --> 01:18:04.390
Faculty (Olympus): In what width of your data will you be seeing, say, 90% of your data?

736
01:18:07.640 --> 01:18:08.660
Abhineet Bansal: Six Sigma.

737
01:18:08.940 --> 01:18:10.000
Abhineet Bansal: That's minus.

738
01:18:10.000 --> 01:18:13.069
Faculty (Olympus): 6 sigma will give me 10 to the minus 3.

739
01:18:13.290 --> 01:18:15.269
Faculty (Olympus): Six Sigma is Six Sigma.

740
01:18:16.590 --> 01:18:17.560
Faculty (Olympus): 2 sigma.

741
01:18:17.880 --> 01:18:18.599
Abhineet Bansal: Oh yeah, sorry.

742
01:18:18.600 --> 01:18:22.079
Faculty (Olympus): Actually, one sigma. One sigma will give me 65%.

743
01:18:23.340 --> 01:18:28.370
Faculty (Olympus): 2 sigma will give meâ€¦ About 95%.

744
01:18:30.490 --> 01:18:32.530
Faculty (Olympus): Okay, Six Sigma is, like, veryâ€¦

745
01:18:32.990 --> 01:18:34.839
Abhineet Bansal: Yeah, yeah, it's 3 in a million.

746
01:18:37.940 --> 01:18:40.310
Faculty (Olympus): of my water welcome. One second.

747
01:18:42.500 --> 01:18:44.150
Faculty (Olympus): I spilled some water here.

748
01:18:50.390 --> 01:18:51.180
Faculty (Olympus): Lovely.

749
01:18:51.400 --> 01:19:04.479
Faculty (Olympus): So Six Sigma is way far away. So what I'm saying is, if I just look at 2 sigma to the left and right, most of the residual values, okay, should be between plus and minus 2, 95% of your population. So if you have, like, 100 points, 5 fellows will lie outside.

750
01:19:04.850 --> 01:19:18.899
Faculty (Olympus): So the way to look at assessment of a linear model is, you look at these values. So, if I give you for every Yi, and tell you every XI, I can compute this quantity, right? I give you a column of Yi's, give you a column of Xi's. I found the value of A and B through my least pairs.

751
01:19:18.930 --> 01:19:27.069
Faculty (Olympus): I know SSR, I know N, so I know all of these quantities. So I now create this new column of values, which is Yi minus A plus BXI,

752
01:19:27.190 --> 01:19:29.770
Faculty (Olympus): Divided by SSR by N minus 2 square root.

753
01:19:30.060 --> 01:19:33.280
Faculty (Olympus): Right? And now, I just do a scatter plot of this.

754
01:19:33.890 --> 01:19:45.409
Faculty (Olympus): Okay, I will find that these values, most of them should lie between plus minus 2. If that is the case, then it's very likely that your data is alsoâ€¦ the noise in your data is also roughly normally distinct, okay?

755
01:19:46.170 --> 01:19:51.980
Faculty (Olympus): So, one way to assess this linear model is, you compute the residuals, find the standardized residuals, and plot it.

756
01:19:52.970 --> 01:20:12.439
Faculty (Olympus): The second thing you look for is, there should be no pattern seen in the plot, okay? And I'll show you some examples, okay, of this. So we'll look atâ€¦ we'll use this mechanism to assess the linear model. So we'll look at R-squared, and we'll also look at doing this standardized residuals to understand how this looks when I change things in my model. We'll play with this now.

757
01:20:13.240 --> 01:20:28.630
Faculty (Olympus): Something else I wanted to keep in mind is, when you minimize this SSR, it's the same as finding the maximum likelihood estimator for parameters, assuming a normal distribution. This will be something that's covered in your course. When you look at statistics, this will be something that's covered, so just

758
01:20:28.720 --> 01:20:42.580
Faculty (Olympus): Bear in mind that these concepts, when you come across MLE, many of you will be like, yeah, yeah, yeah, MLE. It's very important, and there's a deep connection between maximum likelihood estimators and your regression, okay? And that's the reason it's super important. Soâ€¦

759
01:20:42.860 --> 01:20:56.220
Faculty (Olympus): So there are deep connections. And when you do this maximum likelihood estimator, in fact, when you're even findingâ€¦ you take a deep neural network and you find the minimum, you're essentially trying to find something like a maximum likelihood. Okay, so you can always treat

760
01:20:56.220 --> 01:21:04.800
Faculty (Olympus): your operations that you're doing on a neural network in terms of some statistical analog. So, again, these concepts are useful. When you do it in your stats course, you will see it very soon.

761
01:21:05.520 --> 01:21:11.469
Faculty (Olympus): We've already seen that there's a connection between Pearson's correlation and R-squared. In fact, square root of R squared is the Pearson's correlation.

762
01:21:12.220 --> 01:21:16.539
Faculty (Olympus): Alright, so the next thing is, you'reâ€¦ many of you are going to assume that, oh, this

763
01:21:16.920 --> 01:21:34.919
Faculty (Olympus): not very useful, this regression, because I can only do linear models. The answer is no, you can do anything where the coefficients are going to be linear. So, for example, if I have some model, which I expect to be like this, W is C times e to the minus 18. So T is myâ€¦ is one of the variables, W is my response variable.

764
01:21:35.020 --> 01:21:40.489
Faculty (Olympus): How do I transform this so it can become linear? I simply take log on both sides, I get log W isâ€¦

765
01:21:40.680 --> 01:21:41.790
Faculty (Olympus): Log C.

766
01:21:42.000 --> 01:21:43.700
Faculty (Olympus): minus A times T.

767
01:21:43.940 --> 01:21:50.070
Faculty (Olympus): So, I need to now find A and C, so I can now useâ€¦ fit a linear model to this, and give you back.

768
01:21:50.070 --> 01:22:04.360
Faculty (Olympus): Okay, so you can do this. Same way you can do things like this. So in many cases, if you know that there is a, you know, there is a relationship that can be transformed into something that's linear, you can apply linear regulation, okay? The only thing you are expecting is that these coefficients are linear.

769
01:22:04.700 --> 01:22:16.309
Faculty (Olympus): Okay, it means it'sâ€¦ it's not C squared times e to the minus 8. Some C. And because they're all constants, you can always map them into something that is a module. That is, you know, it's notâ€¦ it is going to be linear in that one.

770
01:22:17.340 --> 01:22:21.000
Faculty (Olympus): Right? So there are lots of equations that we can apply this to.

771
01:22:21.330 --> 01:22:30.739
Faculty (Olympus): In particular, you can also do something like polynomial regression. So imagine that you have two variables, Y and some dependent variableâ€¦ sorry, independent variable X, okay?

772
01:22:30.810 --> 01:22:45.860
Faculty (Olympus): And now you're saying, look, I don't like this linear model, I want to treat it as a nonlinear model. In fact, we already did this implicitly. I took the square of the time period, right? In principle, this is not really a linear model in the time period. It is a linear model in the time period square, okay?

773
01:22:45.960 --> 01:22:57.590
Faculty (Olympus): But you can easily imagine that I can have a polynomial case, where I have beta naught plus beta 1x plus dot dot dot beta R to the power XR. Now, notice there's only one independent variable, X, but I've taken

774
01:22:58.080 --> 01:23:02.380
Faculty (Olympus): Like, X, X squared, X cubed, so all the way to higher powers of X.

775
01:23:03.110 --> 01:23:12.050
Faculty (Olympus): Now, you're not restricted to just X to the power X. You can use sine, some constant times sine of x, also fine, okay? So the idea is.

776
01:23:12.050 --> 01:23:31.140
Faculty (Olympus): You can generalize what we have learned here, then you can apply this to even more complicated models. The only thing is, you must know to some extent, you must know the functional form, right? That is, you should know that you should have an idea that, hey, this is related to the sine of this quantity, or this is related to the square of this quantity.

777
01:23:31.160 --> 01:23:31.940
Faculty (Olympus): Nope.

778
01:23:32.090 --> 01:23:35.520
Faculty (Olympus): Because otherwise, how do you know what to pick and what to choose? You don't.

779
01:23:35.740 --> 01:23:47.599
Faculty (Olympus): So you may have to, you know, do some attempts at trial and error and things like that. In fact, there are sophisticated things where you can actually do things like that. You can try and do trial and error and find a functional form for some relationship between functions.

780
01:23:47.720 --> 01:23:50.250
Faculty (Olympus): But, what I want to point out here is.

781
01:23:50.460 --> 01:23:53.980
Faculty (Olympus): Unlike what we wrote out here, which is just a simple linear model.

782
01:23:54.200 --> 01:24:01.799
Faculty (Olympus): This same simple linear model can be applied to other, not necessarily linear models, so long as you can transform them to a linear.

783
01:24:02.440 --> 01:24:04.449
Faculty (Olympus): And you can also do Pond Navito.

784
01:24:05.740 --> 01:24:06.680
Faculty (Olympus): No.

785
01:24:06.890 --> 01:24:10.470
Faculty (Olympus): The last thing, theory, that I'm going to do, before we do,

786
01:24:10.960 --> 01:24:18.850
Faculty (Olympus): this time, is multilinear regression. So, multiple linear regression is basically not just a single variable, but multiple such variables.

787
01:24:19.600 --> 01:24:21.929
Faculty (Olympus): So you can model this in this following fashion.

788
01:24:22.040 --> 01:24:29.280
Faculty (Olympus): So, again, maybe I will do an annotation. So, let me say I have Yi, Okay?

789
01:24:29.500 --> 01:24:36.650
Faculty (Olympus): And then I have multiple, you know, linear, you know, multiple values.

790
01:24:38.220 --> 01:24:45.059
Faculty (Olympus): Soâ€¦ So I have multiple of these Xi, so I have XI1, so each of these, like this.

791
01:24:45.580 --> 01:24:47.550
Faculty (Olympus): So maybe, okay, ignore that.

792
01:24:48.250 --> 01:24:49.860
Faculty (Olympus): Clear all the drawings.

793
01:24:51.740 --> 01:24:55.280
Faculty (Olympus): Now, let'sâ€¦ so if I look at this as one measurement, right?

794
01:24:55.540 --> 01:24:59.189
Faculty (Olympus): This is the second measurement, Y1, Y2, and this is the nth measurement.

795
01:25:00.050 --> 01:25:08.870
Faculty (Olympus): And now, on my X, onâ€¦ think of this X variable, but we'll generalize this to multiple quantities. So this is

796
01:25:10.800 --> 01:25:12.429
Faculty (Olympus): Measurement number one.

797
01:25:12.590 --> 01:25:14.400
Faculty (Olympus): with K variables.

798
01:25:14.920 --> 01:25:18.489
Faculty (Olympus): This is, again, measurement number 2 with KA variables.

799
01:25:19.190 --> 01:25:21.780
Faculty (Olympus): Okay, so look at it, it's 1, which is a constant.

800
01:25:22.250 --> 01:25:29.709
Faculty (Olympus): X21, X22 dot dot dot dot, X2K. So this is the second measurement. This is the n-length measurement with K variants.

801
01:25:30.060 --> 01:25:33.859
Faculty (Olympus): Does it make sense? So now you can think of this as a spreadsheet.

802
01:25:34.240 --> 01:25:37.809
Faculty (Olympus): Panda's data frame, where you have a constant column.

803
01:25:38.640 --> 01:25:45.199
Faculty (Olympus): Okay? And then you have variable 1, variable 2, variable 3, variable 4, variable 5, variable K, all k variables.

804
01:25:45.360 --> 01:25:49.750
Faculty (Olympus): And this fellow is your column ofâ€¦ response variables.

805
01:25:51.340 --> 01:25:53.039
Faculty (Olympus): Is the structure of this clear?

806
01:25:54.820 --> 01:25:58.420
Faculty (Olympus): So now what we can do isâ€¦ It is thisâ€¦

807
01:26:03.890 --> 01:26:13.730
Faculty (Olympus): It turns out that the solution to this system, the least squared solution to this, you can write this as, first, the model can be written as Y is X times B plus E, where B are your coefficients.

808
01:26:14.250 --> 01:26:27.740
Faculty (Olympus): Okay, in fact, B is a vector of coefficient at B. Beta naught plus beta 1 plus beta 2 plus beta 3, or whatever. That's your true coefficient, so you'll call it B0, B1, B2, B3, and B4. So again, I can annotate this and say this B fellowâ€¦

809
01:26:27.910 --> 01:26:45.870
Faculty (Olympus): So remember, this is aâ€¦ Y is a single column vector. This is a N cross k matrix, right? I haveâ€¦ sorry, n cross k plus 1. I have k plus 1 coefficients, and I have, n measurements, okay? So B is basically going to be something like this. I have B is equal toâ€¦

810
01:26:46.720 --> 01:26:48.030
Faculty (Olympus): I'm Parihi off.

811
01:26:48.700 --> 01:26:51.509
Faculty (Olympus): Beta naughtâ€¦ sorry, D0.

812
01:26:53.570 --> 01:26:54.320
Faculty (Olympus): blah blah.

813
01:26:55.690 --> 01:26:58.539
Faculty (Olympus): dot dot dot dot dot, all the way to B,

814
01:27:01.530 --> 01:27:04.190
Faculty (Olympus): What is this gonna be? N or K?

815
01:27:04.690 --> 01:27:05.260
Soumen Deb .: Anita.

816
01:27:05.530 --> 01:27:05.980
Sameep Jain .: Andâ€¦

817
01:27:06.670 --> 01:27:08.289
Faculty (Olympus): No, it's gonna be K.

818
01:27:09.200 --> 01:27:10.799
Faculty (Olympus): These are your coefficients.

819
01:27:16.830 --> 01:27:30.809
Faculty (Olympus): So, X times B is going to be Y. What does that mean? So, if I put B here, it's going to be row times column. So, this fellow times this fellow. So this first measurement is going to be Y1 is equal to beta B0, plus

820
01:27:31.520 --> 01:27:43.170
Faculty (Olympus): X11 times B1, X12 times B2, X13 times B3, dot dot dot dot dot, X1KBK. Does it make sense?

821
01:27:44.680 --> 01:27:50.480
Faculty (Olympus): So B is going to be a K plus 1 Column.

822
01:27:50.950 --> 01:27:52.080
Faculty (Olympus): Is that okay?

823
01:27:54.070 --> 01:27:54.480
Rahul Shrikrishna Joshi .: Yep.

824
01:27:54.480 --> 01:27:55.060
Faculty (Olympus): Bolder.

825
01:27:55.510 --> 01:28:03.170
Faculty (Olympus): It turns out that this can be solved, again, using the same least squares idea. So what you do now, I have to minimize for every one of these fellows, so I'll get

826
01:28:03.350 --> 01:28:17.569
Faculty (Olympus): K plus 1 equations, and you can solve this system by simply writing it as X transpose XB is equal to X transpose Y, and so B is nothing but the inverse of this, right? I mean, I'm using the formal inverse here, not theâ€¦

827
01:28:19.290 --> 01:28:29.749
Faculty (Olympus): You're not going to compute the inverse. You'll solve this system of equations. X transpose XV is equal to X transpose Y. And you'll get these coefficients, and these are the least squares multilinear coefficients.

828
01:28:30.040 --> 01:28:36.080
Faculty (Olympus): And that's it. So now we have covered all of your, you know, all different types of regression. Now we'll start looking at the code.

829
01:28:36.320 --> 01:28:40.640
Faculty (Olympus): Rahul, if you have a quick question, I will answer, but if it's something long-winded, we'll wait for 10 minutes.

830
01:28:40.640 --> 01:28:58.580
Rahul Shrikrishna Joshi .: Yes, just one question, sir. So, in that example of coefficient of determination, is it a correct understanding that if I know the Y can vary between, let's say, 0 to 100 as a, let's say, weight example, and somehow I write my model, let's say, hardcode it to give always the Y bar.

831
01:28:58.810 --> 01:29:03.069
Rahul Shrikrishna Joshi .: Will it always give you the best result, then, in terms of coefficient?

832
01:29:03.090 --> 01:29:04.180
Faculty (Olympus): Obviously not.

833
01:29:05.740 --> 01:29:12.349
Rahul Shrikrishna Joshi .: Because, sir, this is a variation between Y minus Y bar against Y minus calculated value, right?

834
01:29:13.000 --> 01:29:14.700
Rahul Shrikrishna Joshi .: Squares, both of squares, right?

835
01:29:14.910 --> 01:29:20.639
Faculty (Olympus): No, no, no, you think about what you're saying. What you're saying is all Vyas are the same as YBA. They're very different things you're saying.

836
01:29:21.660 --> 01:29:23.619
Rahul Shrikrishna Joshi .: No, no, what I meant to say, in order.

837
01:29:23.620 --> 01:29:29.489
Faculty (Olympus): No, no, no, no, no, no, you please re-evaluate this and come back to me. Do your homework, right? What you're saying is wrong.

838
01:29:31.130 --> 01:29:34.849
Faculty (Olympus): If you just say, my model is simply Y bar, Yi is Y bar.

839
01:29:35.830 --> 01:29:40.669
Faculty (Olympus): With respect to your mean, it is the best predictor, yes, but not with respect to the variance.

840
01:29:43.220 --> 01:29:45.270
Rahul Shrikrishna Joshi .: But here, variance we are not considering, right?

841
01:29:45.270 --> 01:29:47.590
Faculty (Olympus): Absolutely, SYY is the variance.

842
01:29:48.530 --> 01:29:52.459
Faculty (Olympus): That's why I'm saying you please go back and revisit this before you make those statements.

843
01:29:55.750 --> 01:30:05.070
Faculty (Olympus): And I have to push back, because I've answered lots of questions today. I need toâ€¦ I want to finish a little bit more of this, okay? In fact, I'm going to leave the rest of this notebook for you folks to explore.

844
01:30:05.690 --> 01:30:16.889
Faculty (Olympus): So I'm now going to do everything with code, okay? There's no more theory. I'm now going to set up stuff, so I'm going to simply create PLT, NumPy, Pandas, and ApiWidgets, okay?

845
01:30:16.930 --> 01:30:32.799
Faculty (Olympus): And just setting things up so that we do this. I'm going to quickly show you a recap of earlier material. We had this set of equations, and then we quickly foundâ€¦ we read this pendulum data, we found T squared, I did a scatter plot, and then I did, you know, set this thing up.

846
01:30:32.800 --> 01:30:42.169
Faculty (Olympus): I solved this system, I got these coefficients, and I did this best fit. So we already did this 2-3 classes ago, okay? When we did NumPy, I told you this, okay?

847
01:30:42.420 --> 01:30:54.789
Faculty (Olympus): So, my claim is that this and that are going to give me the same result, okay? So now what we'll do is, in this class, we looked at this. We found these best-fit equations, right? What did we do? So.

848
01:30:54.890 --> 01:31:00.289
Faculty (Olympus): If you remember this, what have I done in this setup? I've simply said T squared is L1N plus C, right?

849
01:31:00.560 --> 01:31:09.389
Faculty (Olympus): T2 squared is L2M plus C. That is what I set up. And then, the key part here is, I did lean as dot LSTSQ, which is the least square solution of

850
01:31:09.790 --> 01:31:14.399
Faculty (Olympus): this set of equations. And that gave me some coefficients, and I'm saying this is the best fit.

851
01:31:14.600 --> 01:31:23.950
Faculty (Olympus): Now, what I'm doing is I'm doing nothing different, and simply recomputing whatever we did earlier. We found Yi is B0 plus B1X, right? This is my linear model.

852
01:31:24.700 --> 01:31:34.740
Faculty (Olympus): I compute SXX, SYY, SXY, right? And I find B1 isâ€¦ this is my estimator forâ€¦ remember, A and B, I've now changed this to A, this is B0.

853
01:31:34.850 --> 01:31:38.960
Faculty (Olympus): This is capital B earlier, I've changed this to B1, that's the only change, yeah?

854
01:31:39.610 --> 01:31:43.010
Faculty (Olympus): I'm now calculating this with Python code. I'm saying np.me.

855
01:31:43.130 --> 01:31:53.040
Faculty (Olympus): YB is Y bar, X bar, Y bar, XXX, SYY, B1, B0, okay? And now I'm going to show you all of these values. They're exactly the same.

856
01:31:53.860 --> 01:31:56.789
Faculty (Olympus): Okay, first thing. So what I told you earlier.

857
01:31:56.900 --> 01:32:01.549
Faculty (Olympus): Same thing, you end up when we did this minimization by distance. So that is why

858
01:32:01.860 --> 01:32:06.339
Faculty (Olympus): When we do this with NumPy, it is called the least squares solution.

859
01:32:06.970 --> 01:32:09.530
Faculty (Olympus): Because, essentially, it's the same as this.

860
01:32:11.110 --> 01:32:17.839
Faculty (Olympus): And if you really want to understand how it is computing this in NumPy, it is just solving this system, because that is the least squared solution.

861
01:32:18.670 --> 01:32:21.189
Faculty (Olympus): Okay, it is doing this solution for us.

862
01:32:21.920 --> 01:32:23.350
Faculty (Olympus): So, no magic here.

863
01:32:24.900 --> 01:32:42.749
Faculty (Olympus): Now, it turns out, in NumPy, there is actually a polynomial fitting routine that is available to you. You please look at the documentation, it'll tell you more about this. In fact, this will do polynomial fits, which means not just linear models, okay? So it takes 3 arguments, it takes more, but the most important positional arguments are X,

864
01:32:42.750 --> 01:32:48.680
Faculty (Olympus): which is your X values, Y, which is your Y values, and here is the degree of the polynomial that you want to fit.

865
01:32:48.720 --> 01:33:00.869
Faculty (Olympus): And so now, we have a linear model. I'm saying it is B0 plus B1X, okay? So now I'll find the coefficients for the L values. What is L? L is the length of the pendulum. T squared is the time period squared.

866
01:33:01.490 --> 01:33:05.300
Faculty (Olympus): And now I'm just going to look at the coefficients, and this will also give me the same thing.

867
01:33:05.780 --> 01:33:17.939
Faculty (Olympus): So there are multiple different ways to do the same thing. They're all essentially doing the same thing. They're all giving me the least square solution. So when you do polyfit, polyfit actually does a least squares best fit to your data.

868
01:33:18.040 --> 01:33:20.889
Faculty (Olympus): Given a specific polynomial order.

869
01:33:21.650 --> 01:33:29.079
Faculty (Olympus): Okay? So very quickly, you can just solve this. You don't have to set up the matrix, you don't have to do all of this stuff. One shot, and I'll give you the coefficient.

870
01:33:30.310 --> 01:33:31.180
Faculty (Olympus): Okay.

871
01:33:31.380 --> 01:33:35.829
Abhineet Bansal: It's a number of decimal places, and every answer is different, so is there some kind of a setting for that?

872
01:33:35.830 --> 01:33:42.349
Faculty (Olympus): Because I have printed the value, so if I were to print it, for example, NumPy will change the way it prints, number of decimal places.

873
01:33:42.600 --> 01:33:53.199
Faculty (Olympus): Right, so you can set the number of, you know, print decimals. There's a way by which you can do it with NumPy, but they're actually the same number. For example, I can say NP.allclose.

874
01:33:54.190 --> 01:33:56.729
Faculty (Olympus): B1N, or both.

875
01:33:56.900 --> 01:33:58.060
Faculty (Olympus): Super good luck.

876
01:33:59.030 --> 01:34:00.229
Faculty (Olympus): Yeah, it's true.

877
01:34:01.350 --> 01:34:02.220
Faculty (Olympus): Okay.

878
01:34:03.220 --> 01:34:04.400
Faculty (Olympus): Oh, damn.

879
01:34:05.180 --> 01:34:10.900
Abhineet Bansal: No, no, they're saying that that is fine, so just figuring out how to control the number of decimal places withoutâ€¦

880
01:34:10.900 --> 01:34:11.339
Faculty (Olympus): Yeah, they're here.

881
01:34:11.340 --> 01:34:13.230
Abhineet Bansal: Any input for that?

882
01:34:14.290 --> 01:34:23.820
Faculty (Olympus): But why do you want to see so many decimal places? We want toâ€¦ there is a way to control it. I think np.setPrecision or something is there. PrintPrecision, there is something which you'll have to search for and find out.

883
01:34:23.960 --> 01:34:36.360
Faculty (Olympus): But there's a way by which you can make it print, but usually you don't want it to print so much, because NumPy arrays are never two fellows. You'll have hundreds of fellows, when you see so many decimal places, it starts getting disoriented. So that's why they use some sensible default.

884
01:34:36.610 --> 01:34:43.020
Faculty (Olympus): But if you really want to print it, you can either print those explicit values, or, you know, you can set NumPy to set the

885
01:34:43.980 --> 01:34:49.080
Faculty (Olympus): Anyway, coming back, I'm also gonna written some code here to calculate the coefficient or determinant.

886
01:34:49.420 --> 01:34:52.770
Faculty (Olympus): Right? And so, if I want to set

887
01:34:52.920 --> 01:35:04.000
Faculty (Olympus): you know, coefficient or determination. Again, nothing new here. I've just put this in NumPy form. The same fellows I've put in NumPy form, and now this fellow will tell me SSR, SYY, and R squared.

888
01:35:04.070 --> 01:35:22.600
Faculty (Olympus): So notice that our model that we have just fit for this pendulum data, it tells me SSR is 0.63, it tells me SYY is 104, and it tells me that the coefficient of determination, R squared, is 0.9939. What does that tell you? It tells you that it's a great model for the data.

889
01:35:24.470 --> 01:35:38.350
Faculty (Olympus): Okay, so now what I'm going to do is, I'm going to run through this. Savalo, please wait. I will come to all questions at the end of this, right? So I'm going to just generate some data, so that I show you everything in place together, so that you can understand this with some data.

890
01:35:38.740 --> 01:35:40.630
Faculty (Olympus): So I'm going to take 20 points.

891
01:35:40.820 --> 01:35:50.649
Faculty (Olympus): I'm going to artificially construct some error magnitude. So this is like a scale that tells me how much noise I'm putting into my data. I'm making this data up. This is not real data.

892
01:35:50.650 --> 01:36:04.279
Faculty (Olympus): I am concocting this data so that I can test, and this is exactly what somebody asked me, right, earlier, that I can generate random numbers in order to simulate and then look at how my modeling works. I'm doing this so that it's a teaching exercise, I guess.

893
01:36:04.280 --> 01:36:10.699
Faculty (Olympus): So I'm giving you a magnitude of error, to some extent, to give you some scaling for this error. I'm setting it to 0.2.

894
01:36:10.830 --> 01:36:30.109
Faculty (Olympus): Now I create my data, which is link space, straightforward, link space points, n points, 0 to 1, and now I come to my model, and my model is 2 times X plus 0.25, which means I know the model. So now I will do add noise and find the regression values, and then see how close they are to 2 and 0.25. Is this clear?

895
01:36:30.140 --> 01:36:33.070
Faculty (Olympus): We are doing testing for my techniques.

896
01:36:33.450 --> 01:36:46.910
Faculty (Olympus): And now I'm going to add some noise. YN isâ€¦ Y plusâ€¦ this is the noisy Y is Y plus some noise, which is normally distributed with zero mean, and a scale, which is your standard deviation, is equal to 0.2.

897
01:36:47.470 --> 01:36:50.960
Faculty (Olympus): And I'm generating 20 part shares. So this will give meâ€¦

898
01:36:51.030 --> 01:37:08.530
Faculty (Olympus): all of these quantities. And now I write these little functions, I say fit X and Y, which will simply return to me the polynomial coefficients, which is for a linear model, for X and Y, right? Remember, polyfit just means give me the coefficients. You can do this in any which way you want, but I'm going to use polyfit because I can play with this however I want.

899
01:37:09.210 --> 01:37:21.480
Faculty (Olympus): Then I will say, this is my prediction. Given the coefficients that you have fit, right, and your X values, I can return the prediction from your model as coefficient of 0 times X plus coefficient of 1. This is simply my linear model.

900
01:37:21.630 --> 01:37:27.640
Faculty (Olympus): So this isâ€¦ so for any value of X, given a specific coefficient that you have computed using your least squares model.

901
01:37:27.770 --> 01:37:30.189
Faculty (Olympus): I can return predictor values.

902
01:37:31.130 --> 01:37:39.359
Faculty (Olympus): Now, what I'll do is I have written a level function to compute R squared, so that I can plot this R squared and tell you theâ€¦ or predict this R squared value and tell you how good the model is.

903
01:37:39.510 --> 01:37:56.239
Faculty (Olympus): So I just compute SSR, so given Y and Y predicted, so this is Y is the true values, this Y is the predicted values. SSR is nothing but predicted value minus the true value, the whole squared. And, of course, you could write it as Y minus X in my equations, doesn't make a difference, because I'm taking the square.

904
01:37:56.460 --> 01:37:57.910
Faculty (Olympus): Then I find Y bar.

905
01:37:58.170 --> 01:37:59.440
Faculty (Olympus): And I find this one.

906
01:38:00.010 --> 01:38:16.749
Faculty (Olympus): And now I simply return 1 minus SSR by S5. All straightforward, just simple coding of everything we have written. Now what I'm doing is, instead of writing a separate fit and a separate predict, I'm doing fit predict in one shot. So I give you X and Y. What it'll do is it'll fit the model to this, finds the coefficient, does this.

907
01:38:17.170 --> 01:38:26.999
Faculty (Olympus): then finds the R-squared by finding, you know, the R-squared error, returns the predicted values, the R squared, and the coefficients in one shot, so that I can use this reason.

908
01:38:27.400 --> 01:38:39.279
Faculty (Olympus): Now, I will write a little plotting routine, where I plot the actual values, plot the best fit line, compute the R squared, okay, and also plot the standardized residuals, okay?

909
01:38:40.070 --> 01:38:59.189
Faculty (Olympus): So now, I will generalize this further, and make the data also a general function. So I can give it n, any set of values n, and also specify the errors. So remember, I started with creating the data, so I set the number of points n, set the amount of error I wanted, the noise I wanted to use with some parameter error.

910
01:38:59.240 --> 01:39:04.400
Faculty (Olympus): And this fellow is just generalizing, okay? And the model is inside here, says 2 times X plus 0.25.

911
01:39:04.630 --> 01:39:05.990
Faculty (Olympus): Are we good so far?

912
01:39:06.150 --> 01:39:08.840
Faculty (Olympus): The rest is just same old, same old plotting business.

913
01:39:09.000 --> 01:39:13.359
Faculty (Olympus): I run this, and now I'll show you a simple example. I'm going to take 10 data points.

914
01:39:13.580 --> 01:39:16.710
Faculty (Olympus): This one is going to give me the X values and the noise, okay?

915
01:39:17.500 --> 01:39:35.230
Faculty (Olympus): Then I would fit predict this fellow and give you the Y predicted, the R squared, and the coefficient. I'll print it, and then show these results. So I run this, and we get our nice plot. So this tells me that the R squared, which printed here, is 0.97. The coefficients are 1.85 and 0.31, whatever, that's fine.

916
01:39:35.550 --> 01:39:44.810
Faculty (Olympus): Why are these coefficients useful? Because remember that the model should be 2x plus 0.25. So this fellow should be something close to 2, this fellow should be something close to 0.25.

917
01:39:45.990 --> 01:39:48.980
Faculty (Olympus): Okay? And notice, this is the set of dots.

918
01:39:49.260 --> 01:39:56.740
Faculty (Olympus): And this is your least squares plot. I can't see too much of a pattern, right? It's like doing someâ€¦ some crazy thing over there.

919
01:39:57.680 --> 01:40:02.250
Faculty (Olympus): Now what I've done is I've just made this a little interactive function, so that we can

920
01:40:02.360 --> 01:40:07.580
Faculty (Olympus): do this. In change in, change error, there's just 3 lines of code with this interact.

921
01:40:08.580 --> 01:40:16.540
Faculty (Olympus): So again, all of this is stuff you've seen before many, many times, so I've just used all those building blocks to actually study this. So now let's increase N.

922
01:40:18.290 --> 01:40:19.559
Faculty (Olympus): And you can see this.

923
01:40:20.480 --> 01:40:24.639
Faculty (Olympus): Notice that there's no pattern or structure that you can discern over here.

924
01:40:24.940 --> 01:40:31.229
Faculty (Olympus): And notice that all the points are between minus 2 and plus 2, so it means this noise is normally distributed, which is what really we found, okay?

925
01:40:31.510 --> 01:40:32.360
Faculty (Olympus): Oh.

926
01:40:32.910 --> 01:40:39.270
Faculty (Olympus): Now, the fit for this is 0.946. Now, let me reduce the error. If I reduce the error.

927
01:40:39.460 --> 01:40:47.000
Faculty (Olympus): It's getting better and better. Of course, if it goes to 0, it's gonna beâ€¦ r squared is going to be 1. But as I increase the amount of noise.

928
01:40:49.200 --> 01:40:51.009
Faculty (Olympus): Notice what happens to R squared.

929
01:40:51.240 --> 01:40:53.199
Faculty (Olympus): R squared now is 0.5.

930
01:40:54.860 --> 01:40:59.350
Faculty (Olympus): So it's not so great a fit. Why? Because there's so much noise in the data.

931
01:40:59.740 --> 01:41:02.030
Faculty (Olympus): It still suggests that there's a linear fit.

932
01:41:02.430 --> 01:41:07.599
Faculty (Olympus): Even though you're getting small r-squared, there is this linear relationship, but there's something else happening.

933
01:41:08.180 --> 01:41:24.460
Faculty (Olympus): Now, the second plot you see here is the residual plot, okay? If you remember the show code, this is the actual thing itself, the plot of the actual points, the best fit line, and this is your residual plots. The residual plots are Y minus YP divided by your sigma, which is

934
01:41:24.620 --> 01:41:26.070
Faculty (Olympus): SSR by?

935
01:41:26.300 --> 01:41:28.440
Faculty (Olympus): N minus 2, the whole undersquare.

936
01:41:28.560 --> 01:41:30.619
Faculty (Olympus): So this gives me, if you remember.

937
01:41:33.920 --> 01:41:35.120
Faculty (Olympus): Let me block this.

938
01:41:37.040 --> 01:41:44.150
Faculty (Olympus): Okay? So, this, at a glance, tells you that there is, you know, look at it, there's no real structure to look at.

939
01:41:46.350 --> 01:41:49.849
Faculty (Olympus): Okay, I'm gonna take 2 more minutes, I'm sorry.

940
01:41:50.950 --> 01:41:57.560
Faculty (Olympus): Just give me 2 more minutes, I'll just finish this. So what I'm gonna do now is I'm gonna say, I'll introduce a new function called makedata1.

941
01:41:58.210 --> 01:42:00.840
Faculty (Olympus): Where I give you a notâ€¦

942
01:42:01.120 --> 01:42:05.770
Faculty (Olympus): linear model, I give you a parabolic model, X squared plus X plus 0.25.

943
01:42:06.190 --> 01:42:15.309
Faculty (Olympus): Here, I doâ€¦ the rest of it is the same. Nothing else has changed. So I make this data, and this fellow is also the same. I fit a linear model, okay?

944
01:42:15.520 --> 01:42:18.849
Faculty (Olympus): And I have the same interact, you know, function here.

945
01:42:19.040 --> 01:42:22.460
Faculty (Olympus): Are youâ€¦ instead of calling NayakData, I'm calling NayakData1.

946
01:42:23.620 --> 01:42:27.039
Faculty (Olympus): And now I'm gonna run this, and now you'll say something interesting.

947
01:42:27.410 --> 01:42:31.530
Faculty (Olympus): Again, when error is small, right, 0.2,

948
01:42:38.070 --> 01:42:42.599
Faculty (Olympus): Okay, fine. Okay, so errorâ€¦ so maybe instead of 0 to 1, let me make itâ€¦

949
01:42:48.070 --> 01:42:53.749
Faculty (Olympus): Alright, so as we move this fellow, so I get slightly betterâ€¦ okay, so 0.1â€¦

950
01:42:57.000 --> 01:42:58.740
Faculty (Olympus): White flavor's not so great.

951
01:43:01.590 --> 01:43:07.440
Faculty (Olympus): Sorry. Okay. Soâ€¦ I'm going to increase the number of points.

952
01:43:08.950 --> 01:43:11.369
Faculty (Olympus): Notice that this fit is still pretty good.

953
01:43:11.870 --> 01:43:14.679
Faculty (Olympus): R squared is 0.96, very close to 1.

954
01:43:15.470 --> 01:43:17.550
Faculty (Olympus): But notice your residuals.

955
01:43:17.920 --> 01:43:24.719
Faculty (Olympus): It's not just arbitrary noise. You clearly see there's some sort of a parabolic variation in this.

956
01:43:25.890 --> 01:43:32.620
Faculty (Olympus): Okay, and this is why plotting these residuals is very useful, because it sort of tells you, and you can see this here also, you know, there's some variation here.

957
01:43:34.300 --> 01:43:37.459
Faculty (Olympus): Okay, so this tells you that this is not an entirely linear model.

958
01:43:56.110 --> 01:43:56.840
Faculty (Olympus): It's part.

959
01:43:56.840 --> 01:43:58.170
Savalo Naroji: Sir, you're muted.

960
01:43:59.820 --> 01:44:02.669
Faculty (Olympus): What is the fault.

961
01:44:06.070 --> 01:44:06.900
Faculty (Olympus): Yes.

962
01:44:07.680 --> 01:44:09.029
Faculty (Olympus): Savalo?

963
01:44:11.270 --> 01:44:15.349
Savalo Naroji: I had a question regarding multiple linear regression. Sure.

964
01:44:15.540 --> 01:44:16.670
Savalo Naroji: Can you scroll?

965
01:44:17.220 --> 01:44:17.820
Faculty (Olympus): Yep.

966
01:44:18.780 --> 01:44:26.120
Savalo Naroji: So, when we say here X11, X12, these are two different measurements, right?

967
01:44:27.560 --> 01:44:28.810
Savalo Naroji: Or it's a measurement.

968
01:44:28.810 --> 01:44:33.700
Faculty (Olympus): Yeah, so Eâ€¦ this is one measurement with theseâ€¦ see, I have K variables, right?

969
01:44:34.670 --> 01:44:38.090
Faculty (Olympus): So X, this first index, tells you which measurement this is.

970
01:44:38.480 --> 01:44:42.290
Faculty (Olympus): The second index is your variable in that particular index.

971
01:44:45.210 --> 01:44:45.899
Faculty (Olympus): Is that okay?

972
01:44:46.330 --> 01:44:51.680
Savalo Naroji: Meaning X11, X21 are the measurement of oneâ€¦

973
01:44:52.070 --> 01:44:58.290
Savalo Naroji: thing, and X12, X22 are the measurement of another thing, right? Like that it is, right?

974
01:45:00.660 --> 01:45:04.519
Savalo Naroji: Or they are the measurement of only one thing.

975
01:45:06.890 --> 01:45:12.919
Faculty (Olympus): They're not a measurement of only one thing. So notice, if I have a multinear model, I have multiple dependent variables.

976
01:45:13.630 --> 01:45:24.710
Faculty (Olympus): So this is one variable. So this could be, you know, weight, your height, your age, your whatever, you know, bunch of parameters. So thisâ€¦ the row represents one record, as you threw in.

977
01:45:24.910 --> 01:45:27.870
Faculty (Olympus): Okay? Yeah. Yeah. And you have any such records.

978
01:45:28.580 --> 01:45:29.539
Savalo Naroji: Yep, got it.

979
01:45:29.870 --> 01:45:32.670
Faculty (Olympus): Great. Kedar?

980
01:45:33.740 --> 01:45:44.879
Kedar Digambar Gokhale .: Similar to parabolic examples, sir, I'm just wondering, can it also deterâ€¦ help us to identify the periodicity or cyclic nature ofâ€¦ within the range.

981
01:45:44.880 --> 01:45:53.470
Faculty (Olympus): No, no, no, so I have not given you any tools to do all this periodicity business. All I'm saying is, if you have some data, and you threw a linear model at it.

982
01:45:53.700 --> 01:46:08.370
Faculty (Olympus): Don't just say, it looks good and all that. Look at the standardized normals, because that's a good way to look at your data and see, oh, there's this structure, oh, I've missed certain parameters. You will naturallyâ€¦ it'll give you a tool with which you can evaluate how good your model is, that's all.

983
01:46:08.770 --> 01:46:12.610
Kedar Digambar Gokhale .: Okay, so we don't need to find out the patterns.

984
01:46:12.610 --> 01:46:14.649
Faculty (Olympus): Oh, you do when you're doing the modeling part.

985
01:46:14.750 --> 01:46:18.360
Faculty (Olympus): But as far as we are concerned here, I'm showing you how to do linear regression.

986
01:46:18.650 --> 01:46:20.489
Faculty (Olympus): Right? So now, when you do modelingâ€¦

987
01:46:20.720 --> 01:46:26.330
Faculty (Olympus): you won't basically say, okay, I do a modeling, and I have linear model, and I'm finished.

988
01:46:27.090 --> 01:46:32.039
Faculty (Olympus): We want you to be having mechanisms and tools with which you can assess how good your measurements are.

989
01:46:32.830 --> 01:46:36.570
Kedar Digambar Gokhale .: Hmmâ€¦ Get some intuitions for the next segment or so.

990
01:46:38.500 --> 01:46:39.880
Kedar Digambar Gokhale .: Okay, thank you.

991
01:46:47.240 --> 01:46:49.590
Faculty (Olympus): Folks, just give me one minute, just one second, complete it.

992
01:47:19.690 --> 01:47:20.430
Faculty (Olympus): Yeah.

993
01:47:20.920 --> 01:47:24.109
Faculty (Olympus): Sorry, what was the next question?

994
01:47:28.480 --> 01:47:29.799
Faculty (Olympus): Okay, Rahul?

995
01:47:30.020 --> 01:47:33.150
Rahul Shrikrishna Joshi .: So if you go to the coefficient of determination.

996
01:47:33.150 --> 01:47:33.740
Faculty (Olympus): Oh.

997
01:47:33.740 --> 01:47:34.659
Rahul Shrikrishna Joshi .: Just one time.

998
01:47:34.660 --> 01:47:35.380
Faculty (Olympus): Yeah.

999
01:47:38.130 --> 01:47:45.059
Rahul Shrikrishna Joshi .: slightly above, or slightly further up, yeah, yeah, yes, yeah. So the Y bar here, in this one is absolute one value, right?

1000
01:47:45.920 --> 01:47:48.030
Faculty (Olympus): Yeah, Y bar is a single number, sigma Y ain.

1001
01:47:48.490 --> 01:47:57.929
Rahul Shrikrishna Joshi .: Correct. So, here, what we are checking is that SYY means how your actual Y is deviated apart from the mean, right? That is what it is reflecting.

1002
01:47:58.420 --> 01:48:02.360
Faculty (Olympus): That is a very vague statement, right? It's actually whyâ€¦ this is the equation for SYY.

1003
01:48:03.120 --> 01:48:03.440
Rahul Shrikrishna Joshi .: That's right.

1004
01:48:03.440 --> 01:48:10.280
Faculty (Olympus): can be computed in infinite ways, right? This is a very specific way of computing the deviation. It's actually the variance.

1005
01:48:10.780 --> 01:48:25.960
Rahul Shrikrishna Joshi .: Agreed, agreed. But it isâ€¦ so what I'm trying to ask is that whenever it's a linear equation between X and Y, higher the value of X, let's say higher the value of Y as an example, okay, if theâ€¦ it's a positive correlation.

1006
01:48:25.960 --> 01:48:26.880
Faculty (Olympus): Okay, okay.

1007
01:48:26.880 --> 01:48:39.110
Rahul Shrikrishna Joshi .: Okay? In that case, some Ys will be very small, some Ys will be very high, depending on what value of X, okay? But here, we are actually calculating the value for every Y against its mean.

1008
01:48:39.270 --> 01:48:42.080
Rahul Shrikrishna Joshi .: Which mean is a single value, right? Which will be somewhere in the middle.

1009
01:48:42.830 --> 01:48:44.290
Faculty (Olympus): Okay, so what's your point?

1010
01:48:44.610 --> 01:48:51.699
Rahul Shrikrishna Joshi .: So my point is, if your model, let's say, is hard-coded to give the Y bar, then this will match, right, every time.

1011
01:48:51.810 --> 01:48:53.630
Faculty (Olympus): Oh, Rahul.

1012
01:48:53.950 --> 01:49:00.799
Faculty (Olympus): If I give you Y bar, you're telling me that Yi minus Y bar, the whole squared is going to be 0?

1013
01:49:01.660 --> 01:49:03.170
Rahul Shrikrishna Joshi .: No, it won't be zero, it will beâ€¦

1014
01:49:03.290 --> 01:49:06.719
Rahul Shrikrishna Joshi .: It will be, value, right? Some value, but same value will be there even more.

1015
01:49:06.720 --> 01:49:12.219
Faculty (Olympus): I give you some data set, I give you X, some random variable, I give you K times that random variable.

1016
01:49:12.380 --> 01:49:13.680
Faculty (Olympus): I don't know, I give youâ€¦

1017
01:49:14.320 --> 01:49:18.080
Faculty (Olympus): A plus some random variable. Constant plus some random variable.

1018
01:49:18.520 --> 01:49:20.000
Faculty (Olympus): What'll happen to the variants?

1019
01:49:21.140 --> 01:49:22.569
Rahul Shrikrishna Joshi .: Sorry, say it again, sir, sorry.

1020
01:49:22.940 --> 01:49:24.380
Faculty (Olympus): I give you a random variable X,

1021
01:49:24.510 --> 01:49:26.319
Faculty (Olympus): The variance of the random variable.

1022
01:49:27.800 --> 01:49:30.199
Faculty (Olympus): Right? Thisâ€¦ let's call it sigma squared.

1023
01:49:31.890 --> 01:49:34.140
Faculty (Olympus): I take X minus some constant.

1024
01:49:35.470 --> 01:49:37.400
Faculty (Olympus): What is the variance of X minus constant?

1025
01:49:41.570 --> 01:49:42.240
Faculty (Olympus): Yikes.

1026
01:49:42.240 --> 01:49:44.819
Rahul Shrikrishna Joshi .: Minus constant bracket square, right?

1027
01:49:45.650 --> 01:49:48.179
Faculty (Olympus): What will the value be with respect to sigma squared?

1028
01:49:51.240 --> 01:49:53.519
Rahul Shrikrishna Joshi .: Sorry, I did not get the question properly, sorry.

1029
01:49:53.710 --> 01:49:56.929
Faculty (Olympus): If you add a constant to a random variable, the variance does not change.

1030
01:49:58.660 --> 01:50:00.020
Rahul Shrikrishna Joshi .: Yeah? Yeah?

1031
01:50:01.080 --> 01:50:02.569
Faculty (Olympus): So that should answer your question.

1032
01:50:07.740 --> 01:50:08.690
Faculty (Olympus): Rathi?

1033
01:50:10.000 --> 01:50:11.480
Faculty (Olympus): Rahul, you come back, you think about.

1034
01:50:11.480 --> 01:50:11.820
Rahul Shrikrishna Joshi .: Yo.

1035
01:50:11.820 --> 01:50:24.270
Faculty (Olympus): You can come back at the end of this class, that's fine. So you think about this. I think you're getting very confused. I think you're trying to substitute some numbers, you have some idea, and you're trying to sort of force-fit that logic into this. Don't do things like that.

1036
01:50:26.780 --> 01:50:28.370
Faculty (Olympus): Because you'reâ€¦ you're reallyâ€¦

1037
01:50:29.110 --> 01:50:36.260
Faculty (Olympus): you're basically telling me that if you subtract this somehow, if you predict only Y bar, you'll get some great model. You're not going to get a great model.

1038
01:50:37.280 --> 01:50:38.729
Rahul Shrikrishna Joshi .: No, I'm not, I'm not saying thatâ€¦

1039
01:50:38.730 --> 01:50:43.609
Faculty (Olympus): You'll get a better model than something which is constant, which is not the mean. That's fine.

1040
01:50:44.050 --> 01:50:46.069
Faculty (Olympus): But it's still a lousy model.

1041
01:50:46.070 --> 01:50:51.130
Rahul Shrikrishna Joshi .: It's a lousy model, sir, but it will give the coefficient of determination will be perfect in that case.

1042
01:50:51.130 --> 01:50:52.770
Faculty (Olympus): No. Wrong.

1043
01:50:54.060 --> 01:50:55.880
Faculty (Olympus): Please calculate it and come back to me.

1044
01:50:56.040 --> 01:50:57.870
Rahul Shrikrishna Joshi .: Oh, yeah, let me think over it.

1045
01:50:58.260 --> 01:50:59.550
Faculty (Olympus): It's definitely wrong.

1046
01:51:01.090 --> 01:51:01.970
Faculty (Olympus): Rathi?

1047
01:51:02.620 --> 01:51:16.049
Lad Prachikumari Vijaykumar .: Yes, sir. Sir, I want to give one feedback, sir. Most of the class today, we have spent behind this question-answer, and, you know, in last 20 minutes, we have covered so much thing, and in, you know, in very much high speed, we covered everything.

1048
01:51:16.050 --> 01:51:21.249
Faculty (Olympus): So, let me, let me repeat, the last 20 minutes is everything you've done before. Nothing is new here.

1049
01:51:21.510 --> 01:51:26.080
Faculty (Olympus): Everything that's done here is justâ€¦ this expression, numpy equivalent.

1050
01:51:26.480 --> 01:51:27.369
Faculty (Olympus): You'll takeâ€¦ if you.

1051
01:51:27.370 --> 01:51:27.810
Lad Prachikumari Vijaykumar .: Good morning.

1052
01:51:27.810 --> 01:51:33.080
Faculty (Olympus): minutes to read this, it's just 2 minutes to read this. This class has to be homework.

1053
01:51:33.240 --> 01:51:41.900
Faculty (Olympus): A lot of this has to be homework, because if you're going to expect me, everybody to go at this space, Professor Vinay will not go at this pace. Prosever Vinay will say, you ask AI to tell you the answer.

1054
01:51:42.050 --> 01:51:43.899
Faculty (Olympus): And that's gonna be the code you're gonna generate.

1055
01:51:44.210 --> 01:51:46.449
Faculty (Olympus): There will be no explanation about that code.

1056
01:51:48.680 --> 01:51:49.590
Lad Prachikumari Vijaykumar .: But eventsâ€¦

1057
01:51:49.590 --> 01:51:56.030
Faculty (Olympus): halfâ€¦ No, no, no, no, the next half of the course is going to be regression?

1058
01:51:56.230 --> 01:51:57.680
Faculty (Olympus): Classification.

1059
01:51:58.110 --> 01:52:01.939
Faculty (Olympus): Feature engineering, there will be no time spent on the Python code.

1060
01:52:05.400 --> 01:52:07.650
Lad Prachikumari Vijaykumar .: No, sir, I'm not talking about the code.

1061
01:52:07.650 --> 01:52:08.070
Faculty (Olympus): Nightly.

1062
01:52:08.070 --> 01:52:13.080
Lad Prachikumari Vijaykumar .: But at least we can follow whatever you are speaking, at least we can follow, but, you know, the.

1063
01:52:13.080 --> 01:52:13.400
Faculty (Olympus): Yeah, sure.

1064
01:52:13.400 --> 01:52:15.810
Lad Prachikumari Vijaykumar .: it is, you know, I cannot follow anything.

1065
01:52:16.150 --> 01:52:29.129
Faculty (Olympus): So, you don't follow anything, because there's nothing much to follow here. All I'm saying is, everything we looked at in the theory, that's the reason I didn't spend anything, because there's nothing fantastic in this code. It's stupid code. This code is a straightforward translation of SSR.

1066
01:52:29.130 --> 01:52:38.479
Faculty (Olympus): This is straightforward translation ofâ€¦ the first three parts is, okay, how do you find the coefficient? There are three different ways. The second part is coefficient of determination, straight code.

1067
01:52:38.760 --> 01:52:46.570
Faculty (Olympus): Then, all I have done is, this is the only thing that is maybe interesting, is I'm now coming up with a model. I'm adding noise to that model, and I'm generating data.

1068
01:52:47.120 --> 01:53:02.019
Faculty (Olympus): This also is stuff we have looked at from class 5, where we looked at probabilistic programming. We're looking at generated data sets, we took at such intendulkar scores, and we sampled from that Such intended scores. Same way, I'm just saying, I have a linear model here, 2x plus 0.25, I'm adding noise to it.

1069
01:53:02.710 --> 01:53:14.499
Faculty (Olympus): Right? You should be able to understand at the pace I covered this. If you did not, then you're in trouble for your Mitsum, because this was all covered for a long time at great length, with 50, 60 problems that have been given to you.

1070
01:53:15.010 --> 01:53:15.780
Faculty (Olympus): After that.

1071
01:53:15.780 --> 01:53:16.250
Lad Prachikumari Vijaykumar .: Yeah, this would beâ€¦

1072
01:53:16.250 --> 01:53:30.209
Faculty (Olympus): them in functions, nothing else, okay? So I'm justâ€¦ since if you found it fast to go, I'm repeating this. There's nothing new to this. I've just put all of the same code, SSR, find this. The only thing here is there are two plots here, which is sigma, which is your

1073
01:53:30.560 --> 01:53:33.280
Faculty (Olympus): SSR by N minus 2 square root.

1074
01:53:33.490 --> 01:53:44.859
Faculty (Olympus): And I found this standardized residues, which I have done. I mentioned this over here. I know I'm moving fast here, right? I said, how do you assess the linear model? So you compute the standardized residues, okay?

1075
01:53:45.590 --> 01:53:48.910
Faculty (Olympus): And scroll back down, this is the implementation of that.

1076
01:53:49.570 --> 01:53:59.939
Faculty (Olympus): Then I put everything in one nice thing, so you can, like, put the slider, drag, and then say, oh, this is my original data on the left-hand side. Original data, this is my best fit line.

1077
01:53:59.940 --> 01:54:12.310
Faculty (Olympus): This is my R squared, okay? On the right-hand side is the standardized numbers. That's all. So I've not done anything new at all in all of these plots. All of this is, like, you spend 5 minutes, you'll have written this problem yourself.

1078
01:54:12.460 --> 01:54:13.250
Faculty (Olympus): Okay.

1079
01:54:13.610 --> 01:54:21.780
Faculty (Olympus): Then I did something interesting. I said, okay, I will not give you linear model, I will change this to a non-linear model. My only point was, you'll see patterns showing up here.

1080
01:54:22.180 --> 01:54:26.619
Faculty (Olympus): When I looked at this plot, you see it's, like, garbage. I can't make out if there's a pattern.

1081
01:54:27.120 --> 01:54:31.439
Faculty (Olympus): Especially if you increase the number of points, right? So I make it 50 or 100, it's likeâ€¦

1082
01:54:31.540 --> 01:54:32.899
Faculty (Olympus): Looks like noise.

1083
01:54:33.570 --> 01:54:38.730
Faculty (Olympus): Whereas here, if I increase this, you'll still get the same kind of structure. You see this parabolic structure.

1084
01:54:39.320 --> 01:54:53.499
Faculty (Olympus): So what I'm trying to say is, when you have a model, there should be a way to assess the model. The first thing you can use is this R squared quantity. R squared is close to 1, model is good, but even if it is good, you may have missed certain higher order terms.

1085
01:54:53.610 --> 01:55:00.120
Faculty (Olympus): If you see a pattern in your standardized normals, it tells you you've missed something, maybe. And now, as a modeler.

1086
01:55:00.530 --> 01:55:13.169
Faculty (Olympus): you must use your insight of the data and the domain to say, oh, this may be, you know, that maybe this looks like a parabola. Now, how does a parabola look? Well, you have lin space, you can simply do X squared, plot that thing. You understand?

1087
01:55:13.310 --> 01:55:14.310
Faculty (Olympus): So, you.

1088
01:55:14.310 --> 01:55:14.690
Lad Prachikumari Vijaykumar .: Ian.

1089
01:55:14.690 --> 01:55:17.330
Faculty (Olympus): Have a feel for these things, and then you plug this in.

1090
01:55:17.460 --> 01:55:18.750
Faculty (Olympus): That's all I've covered.

1091
01:55:20.410 --> 01:55:29.320
Faculty (Olympus): That's all I've done so far. Okay, so I went through this fast, assuming that this isâ€¦ there's nothing new in the programming. So yes, I did go fast, but I don't have a choice.

1092
01:55:30.600 --> 01:55:31.440
Lad Prachikumari Vijaykumar .: Okay.

1093
01:55:31.840 --> 01:55:32.920
Lad Prachikumari Vijaykumar .: Yes, sir.

1094
01:55:33.230 --> 01:55:52.479
Faculty (Olympus): But it's important that the modeling part is understood, because thisâ€¦ I know your statistics instructor will do it, but statistics instructor will put it with random variables, which I know for a fact, when I've taught random variables and statistics many, many times, even IIT Bombay students will struggle with it to understand. Half the class won't understand properly, because random variable, the instant you say, everybody's blind book.

1095
01:55:52.670 --> 01:55:53.520
Faculty (Olympus): Blows up.

1096
01:55:53.960 --> 01:56:10.729
Faculty (Olympus): So, that's why I said you do this multiple times in this course, then you do regression, you'll see it again in statistics, then maybe it's easier for you to understand. Some concepts areâ€¦ they're necessarily difficult, so it takes multiple times, then you get used to it, right? In fact, there's this famous quote on thermodynamics.

1097
01:56:10.830 --> 01:56:14.590
Faculty (Olympus): Another firm thing, he said, first time I read Thermodynamics.

1098
01:56:14.830 --> 01:56:20.310
Faculty (Olympus): Like, veryâ€¦ I understood everything. Second time I read thermodynamics, I didn't understand anything. Third time I read thermodynamics.

1099
01:56:20.550 --> 01:56:22.490
Faculty (Olympus): I became comfortable with it.

1100
01:56:23.500 --> 01:56:31.799
Faculty (Olympus): It is difficult, so some subjects are difficult. So the reason I'm spending time on this is to give you, like, okay, you're gonna see this in the future.

1101
01:56:32.090 --> 01:56:33.579
Faculty (Olympus): But it's not very difficult.

1102
01:56:34.920 --> 01:56:35.760
Lad Prachikumari Vijaykumar .: A.S.

1103
01:56:36.290 --> 01:56:38.850
Faculty (Olympus): Okay, and what I want to really give you isâ€¦

1104
01:56:38.980 --> 01:56:47.009
Faculty (Olympus): the confidence that you can actually program some of these and get some insight yourself by setting these simple things. That's all.

1105
01:56:47.920 --> 01:57:03.650
Faculty (Olympus): But yes, I'm sorry, this is inherently going to be like this, and when Roshan Vinay starts teaching, he will say a lot of things, but whether you can digest and actually put it into practice will take a lot of effort. So he will give you several assignments. I strongly recommend you do those assignments sincerely.

1106
01:57:05.240 --> 01:57:06.820
Lad Prachikumari Vijaykumar .: Yeah, sir. Sure, sir.

1107
01:57:07.760 --> 01:57:09.109
Faculty (Olympus): Yeah. Raghuv.

1108
01:57:09.110 --> 01:57:09.970
Lad Prachikumari Vijaykumar .: Yeah, thank you.

1109
01:57:10.800 --> 01:57:13.209
Faculty (Olympus): Sorry, I'm gonna have to keep myâ€¦

1110
01:57:13.210 --> 01:57:15.150
Rahul Shrikrishna Joshi .: I'll go ahead andâ€¦ No, you'll go ahead.

1111
01:57:15.150 --> 01:57:19.260
Faculty (Olympus): I hear some noise from her, but I can only hold her off so far.

1112
01:57:19.720 --> 01:57:23.179
Rahul Shrikrishna Joshi .: No, sir, I just wanted to show you something. I'll go at the end.

1113
01:57:23.300 --> 01:57:24.859
Faculty (Olympus): Sure. Andâ€¦

1114
01:57:26.760 --> 01:57:28.790
Soumen Deb .: Spoke now. Anne already spoke now, yeah?

1115
01:57:28.790 --> 01:57:34.420
Faculty (Olympus): Oh, great, okay, fine. Rajivâ€¦ Devendra story.

1116
01:57:35.530 --> 01:57:36.670
Devendra Rajeevsingh Parmar .: Yes, sir.

1117
01:57:36.680 --> 01:57:37.380
Faculty (Olympus): Oh.

1118
01:57:37.380 --> 01:57:41.929
Devendra Rajeevsingh Parmar .: Sir, my question is with regards to the multivariable matrix X,

1119
01:57:42.790 --> 01:57:51.250
Devendra Rajeevsingh Parmar .: So, the first term is 1, right? So, when we multiply the matrix of coefficient, B0 up to BK.

1120
01:57:51.250 --> 01:57:53.500
Faculty (Olympus): Yeah, so you need B0 is a constant.

1121
01:57:53.620 --> 01:58:00.170
Faculty (Olympus): So for the model, it's going to be Y1 is equal to B0, plus B1X11 plus B2X12.

1122
01:58:00.290 --> 01:58:02.720
Faculty (Olympus): plus B3, X13, so on and so forth.

1123
01:58:03.420 --> 01:58:06.830
Faculty (Olympus): So that D0 is represented, so you multiply it by parts.

1124
01:58:07.680 --> 01:58:13.350
Faculty (Olympus): Because there's noâ€¦ there is no, what do you call it, independent variable associated with the constant.

1125
01:58:14.550 --> 01:58:16.870
Devendra Rajeevsingh Parmar .: Perfect. Okay. Thank you, sir.

1126
01:58:16.870 --> 01:58:18.280
Faculty (Olympus): Sure. Abhishek?

1127
01:58:22.050 --> 01:58:29.709
Abhishek Raghuvanshi .: Oh, I think we took, the error component, we simulated the error component as normal.

1128
01:58:29.710 --> 01:58:30.110
Faculty (Olympus): Yes.

1129
01:58:30.110 --> 01:58:34.249
Abhishek Raghuvanshi .: And finally, we plotted the errors, is what I understood.

1130
01:58:34.350 --> 01:58:35.090
Faculty (Olympus): Yes.

1131
01:58:35.410 --> 01:58:40.699
Abhishek Raghuvanshi .: So it'sâ€¦ you said it's goingâ€¦ ideally, because if the model is right, then it would be very random?

1132
01:58:40.870 --> 01:58:41.510
Faculty (Olympus): No.

1133
01:58:41.970 --> 01:58:47.790
Abhishek Raghuvanshi .: Okay, but you said normal as well, so the normality is not showing in the graph, so I'm a bit confused in terms of what.

1134
01:58:47.790 --> 01:59:03.280
Faculty (Olympus): You won't see it, you will not see the normality in this graph, so there's actually other ways. So now, if you look further down in the notebook, how do you check if that's the next topic? So I'm hoping I'll finish this today, but nay. So, you can go through the notebook, you'll see it. There are other ways to estimate normality.

1135
01:59:04.380 --> 01:59:14.730
Abhishek Raghuvanshi .: Okay, okay, soâ€¦ and as a follow-up question, in the second graph, when we are seeing that there is a pattern in this, then we need to correct the model by, say, possibly indicating.

1136
01:59:14.730 --> 01:59:24.049
Faculty (Olympus): It is a suggestion for you to correct the model, but then again, notice that R squared is quite high. So you might be saying TK chat, you know, the linear model does a reasonable job, I'm okay with it, right?

1137
01:59:24.170 --> 01:59:35.609
Faculty (Olympus): But if you now throw in a second-order model, you'll have to change a lot of the code, right? I'll have to fitâ€¦ the coefficients will have to be two-dimensional, so I think I'll have to change the fitting function to use a

1138
01:59:36.360 --> 01:59:37.105
Faculty (Olympus): Amod

1139
01:59:54.890 --> 02:00:05.759
Faculty (Olympus): Sorry. So, okay. So, here I'll have to change the, fitting function. FitPredict. Notice predict is, sorry, fit is taking one, right? I can now fit the second order.

1140
02:00:06.080 --> 02:00:15.289
Faculty (Olympus): polynomial input, sorry, or rather, polynomial with order 2, and then you'll get a, you know, much better R-squared, and this residual also will become noisy.

1141
02:00:15.650 --> 02:00:20.319
Abhishek Raghuvanshi .: Or we, convert that variable into its square, like we did forâ€¦

1142
02:00:20.320 --> 02:00:25.350
Faculty (Olympus): Because there is a strong linear component, it's X squared plus X, or XB, hey, you can't throw that away.

1143
02:00:25.850 --> 02:00:32.710
Abhishek Raghuvanshi .: No, no, I'm saying the X square part, we make it a separate variable Z. That you can do, of course.

1144
02:00:32.710 --> 02:00:40.939
Faculty (Olympus): do that, absolutely. Then you make it multilinear modeling and do it, yes, absolutely. The only thing is, your plotting will become a mess, because now you'll only plot one versus the other, right?

1145
02:00:40.940 --> 02:00:41.990
Abhishek Raghuvanshi .: Yeah, yeah.

1146
02:00:41.990 --> 02:00:55.619
Faculty (Olympus): So you can'tâ€¦ that's the difficulty with multilinear plotting. You can't do, you know, 20 variables. Linear plot is, like, you'll have to plot one versus the other multiple times. Is that okay? Yeah, got it. And again, so a lot of these things, again, I think Professor,

1147
02:00:58.250 --> 02:01:02.840
Faculty (Olympus): Vinay will talk about some of these things, and you know, he will actually talk about

1148
02:01:03.170 --> 02:01:13.969
Faculty (Olympus): regression, I hope he will talkâ€¦ I'll talk to him about it. Maybe he can talk to you about general purpose regression, but the idea of giving you this code is for you to play with it, so that you can actually try this yourselves and see.

1149
02:01:15.990 --> 02:01:22.420
Faculty (Olympus): You can play with all of these various things. You can have polynomial fades, all of those, this code actually gives you a clean way to play with it.

1150
02:01:25.450 --> 02:01:26.420
Faculty (Olympus): Soumen?

1151
02:01:26.630 --> 02:01:29.390
Faculty (Olympus): Anne, are you done? You still have a question, or can I lower your hand?

1152
02:01:29.390 --> 02:01:31.719
Ann G. .: I didn't get a chance to ask, I don't know whyâ€¦

1153
02:01:31.720 --> 02:01:32.630
Faculty (Olympus): Please, please ask.

1154
02:01:32.990 --> 02:01:41.650
Ann G. .: Yeah, sir, SXY, that's the perpendicular distance of a data point from the line we've come up with, right?

1155
02:01:41.840 --> 02:01:49.049
Faculty (Olympus): No, SXY is simply X timesâ€¦ this is the correlation coefficient. You won't characterize it as the perpendicular distance.

1156
02:01:51.240 --> 02:01:52.750
Ann G. .: Characterize, okay.

1157
02:01:52.750 --> 02:01:56.199
Faculty (Olympus): It is the corâ€¦ you can think of it as the correlation between X and Y.

1158
02:01:57.530 --> 02:02:00.879
Faculty (Olympus): Right? This is how you compute a Pearson's correlation coefficient, right?

1159
02:02:01.310 --> 02:02:07.620
Ann G. .: So, which of these equations is the least, distance fromâ€¦ of the data point from the line?

1160
02:02:08.280 --> 02:02:20.900
Faculty (Olympus): So this is not by the least distance of the data point, it is the perpendicular dropped to the x-axis, that distance. So, for example, this would beâ€¦ SSR is that distance. In fact, it's the sum of the squares of those distances.

1161
02:02:22.010 --> 02:02:27.420
Ann G. .: Right. So SSR is the least distance of the data point from the perpendicular drop to the line.

1162
02:02:27.650 --> 02:02:34.109
Faculty (Olympus): No, no, no, it is the distance from theâ€¦ it is the distance between the line and the perpendicular drop from the point to the.

1163
02:02:36.190 --> 02:02:39.100
Ann G. .: Okay, I'm confused by perpendicular drop, I'llâ€¦ maybe I'llâ€¦

1164
02:02:39.100 --> 02:02:48.109
Faculty (Olympus): As in, you're dropping it vertically. So if you have aâ€¦ I'm gesticulating here, because my daughter is sitting on my lap, there is aâ€¦ it is theâ€¦

1165
02:02:48.370 --> 02:02:53.110
Faculty (Olympus): what is that called? You draw the Y axis, your point is on the YI is at theâ€¦

1166
02:02:53.340 --> 02:02:54.370
Faculty (Olympus): Is the point?

1167
02:02:54.540 --> 02:02:56.790
Faculty (Olympus): So, for a given XI, you have Yi, right?

1168
02:02:57.140 --> 02:02:57.510
Ann G. .: Right.

1169
02:02:57.510 --> 02:03:01.019
Faculty (Olympus): A plus BXI is the point on the straight line for a given XI.

1170
02:03:01.550 --> 02:03:05.839
Faculty (Olympus): You'd simply take that line vertically or horizontally, bring it up or down.

1171
02:03:06.430 --> 02:03:09.449
Faculty (Olympus): That is the distance you're calculating, Yi minus AXâ€¦

1172
02:03:09.450 --> 02:03:12.589
Ann G. .: I thought that was SXX and SY.

1173
02:03:12.590 --> 02:03:17.649
Faculty (Olympus): SXX is the distanceâ€¦ is basically the variation in X. It's like the variance of X.

1174
02:03:18.390 --> 02:03:18.770
Ann G. .: Okay.

1175
02:03:18.770 --> 02:03:19.980
Faculty (Olympus): the variance of Y.

1176
02:03:20.300 --> 02:03:26.729
Ann G. .: Okay, I'll think about it, sir. So my question was, I was assuming that SXY was.

1177
02:03:26.730 --> 02:03:28.100
Faculty (Olympus): The least distance of the point.

1178
02:03:28.100 --> 02:03:47.739
Ann G. .: from the plotted line. My question was, for polyfit of X raised to nth, equation, is the square of distance, the formula used for finding the least, discrepancy between data points and the, polynomâ€¦ the fit that the equation came up with?

1179
02:03:47.860 --> 02:03:49.790
Ann G. .: Or is it a different method?

1180
02:03:51.430 --> 02:03:56.619
Faculty (Olympus): Okay, I missed some of what you said, but yes, SXX is notâ€¦ it's not like a distanceâ€¦

1181
02:03:56.760 --> 02:04:03.169
Faculty (Olympus): It isâ€¦ it is like your variance in X. SYY is like variance in Y. This is like your correlation coefficient.

1182
02:04:05.360 --> 02:04:06.110
Ann G. .: Okay,

1183
02:04:06.110 --> 02:04:11.460
Faculty (Olympus): everyâ€¦ for every X point, so if you're doing a, you know, you've seen this in correlations, right?

1184
02:04:11.990 --> 02:04:14.270
Faculty (Olympus): This is, in fact, the numerical value.

1185
02:04:14.270 --> 02:04:14.700
Ann G. .: Yes, that'.

1186
02:04:14.700 --> 02:04:15.380
Faculty (Olympus): We're giving us something.

1187
02:04:15.730 --> 02:04:18.289
Ann G. .: how well X and Y are moving together.

1188
02:04:18.290 --> 02:04:18.700
Faculty (Olympus): Yes.

1189
02:04:18.700 --> 02:04:19.140
Ann G. .: recording.

1190
02:04:19.140 --> 02:04:23.480
Faculty (Olympus): That is what it is. Yeah, so it is not the perpendicular distance to the line or anything.

1191
02:04:24.330 --> 02:04:25.550
Ann G. .: Okay, maybe I.

1192
02:04:25.550 --> 02:04:31.360
Faculty (Olympus): Yes, so SSR is going to be the difference between your model

1193
02:04:31.550 --> 02:04:36.239
Faculty (Olympus): And your actual value. The model predicted value minus your actual value.

1194
02:04:37.370 --> 02:04:41.350
Faculty (Olympus): Because A plus BXI is your model predicted value, Yi is your actual value.

1195
02:04:42.230 --> 02:04:46.370
Ann G. .: Okay, I'll come back in the next class with a better well-thought question.

1196
02:04:46.370 --> 02:04:46.980
Faculty (Olympus): shut.

1197
02:04:48.680 --> 02:04:49.670
Faculty (Olympus): Soumen?

1198
02:04:50.240 --> 02:05:09.809
Soumen Deb .: Yeah, hi. So, I was just comparing the two functions, MakeData and MakeData1. So, in MakeData, you have done, MX plus C, which is a sort of 2X plus 0.25. And here, below, you have done X squared plus 1X plus, into 0.25, so it's just, like.

1199
02:05:10.780 --> 02:05:19.760
Soumen Deb .: So when we are generating this, it's just taking a line, and then making the second line as a cubic, or sorry, a squared, sort of a parabola, sort of.

1200
02:05:20.270 --> 02:05:20.810
Soumen Deb .: Amazing.

1201
02:05:20.810 --> 02:05:21.810
Faculty (Olympus): Quadratic, yes.

1202
02:05:21.810 --> 02:05:22.820
Soumen Deb .: Okay.

1203
02:05:22.820 --> 02:05:26.550
Faculty (Olympus): You can change anything, you can make this two also, nothing will happen. I mean, it's okay.

1204
02:05:26.550 --> 02:05:27.090
Soumen Deb .: Okay.

1205
02:05:27.200 --> 02:05:28.239
Soumen Deb .: Doesn't matter, so that's right.

1206
02:05:28.240 --> 02:05:41.440
Faculty (Olympus): I just cooked this up. You can put X squared, whatever you want, you can put in here and play with it. The X squared is a straightaway, you can see a pattern, and many of you may not be comfortable looking at this and saying, hey, this looks like X squared. So you need some experience to know that.

1207
02:05:42.080 --> 02:05:42.820
Soumen Deb .: Yeah.

1208
02:05:42.820 --> 02:05:51.410
Faculty (Olympus): I just wanted to show you that there is a pattern that will emerge, even though F squared is high, that you'll see a pattern in your residual. So it's always valuable to plot.

1209
02:05:52.550 --> 02:05:56.620
Soumen Deb .: Yeah, becauseâ€¦ because I'm justâ€¦ yeah, correct. Makes sense.

1210
02:05:57.060 --> 02:06:04.539
Soumen Deb .: Yeah, because the left-hand graph is actually the actual plot, and the right side is the square, right? So that's where you're getting.

1211
02:06:04.540 --> 02:06:07.259
Faculty (Olympus): The right side is the residual plot, it's not a square.

1212
02:06:07.860 --> 02:06:08.949
Soumen Deb .: Did I say no surprise?

1213
02:06:08.950 --> 02:06:17.239
Faculty (Olympus): below, I'll show you the show code. The show is basically, it's just saying Y minus Y P Rai sigma, and it just does plot X comma as standard results.

1214
02:06:17.970 --> 02:06:24.859
Soumen Deb .: Okay, so Y minus Y P divided byâ€¦ and the sigma is the square root ofâ€¦ okay, fine, okay, I need to see those two lines, though.

1215
02:06:24.860 --> 02:06:29.210
Faculty (Olympus): Yeah, this fellow is, like, so this sigma is really an estimator for your standâ€¦ for your knowledge.

1216
02:06:30.470 --> 02:06:40.010
Soumen Deb .: Okay, okay. Okay, that's why the curve is higher on the right side, which is because it's R-square, because of that square that you have done. Okay, maybe I could justâ€¦

1217
02:06:40.010 --> 02:06:53.490
Faculty (Olympus): Which is R squared, sorry. Oh, yeah, yeah, yeah, yeah, so this, when you look at this, yeah, so it's goingâ€¦ blowing up when larger, but notice my X values are notâ€¦ so, for example, I've carefully done the two changes here, huh? I made lint space from 0 to 3.

1218
02:06:53.630 --> 02:07:00.239
Faculty (Olympus): Correct. 0 to 1, you may not see a difference, because square of the quantity less than 1 will be actually small.

1219
02:07:01.280 --> 02:07:04.550
Faculty (Olympus): On the other hand, if I made this 5, for example, this would be even worse.

1220
02:07:06.230 --> 02:07:06.710
Soumen Deb .: Okay.

1221
02:07:06.710 --> 02:07:10.669
Faculty (Olympus): You'll see the pattern, like, really strongly emerging. See this?

1222
02:07:11.140 --> 02:07:15.159
Faculty (Olympus): Okay, because the noise is small in comparison to the square of the variation.

1223
02:07:15.820 --> 02:07:16.730
Soumen Deb .: Yeah.

1224
02:07:17.800 --> 02:07:24.580
Soumen Deb .: Okay, fine, fine, I understood. So I wasâ€¦ that was my second question, the Lin Space one, because you've done a Lin Space 3 here.

1225
02:07:24.580 --> 02:07:28.350
Faculty (Olympus): I've carefully done this so that you can see it, otherwise you won't see it at all.

1226
02:07:28.350 --> 02:07:29.490
Soumen Deb .: Need to make zero total.

1227
02:07:29.490 --> 02:07:38.109
Faculty (Olympus): you won't see this pattern. You'll be like, yeah, alright. So that's why, again, this is why the programming part is important, that you can play with it and understand and get some inside techniques.

1228
02:07:39.200 --> 02:07:42.509
Soumen Deb .: Okay, okay, okay, that was my question. Thank you very much, yeah.

1229
02:07:42.510 --> 02:07:43.040
Faculty (Olympus): open.

1230
02:07:43.360 --> 02:07:44.350
Faculty (Olympus): Rahul?

1231
02:07:45.070 --> 02:07:47.399
Rahul Shrikrishna Joshi .: But can Iâ€¦ can I show something, sir? I'm a littleâ€¦

1232
02:07:47.770 --> 02:07:50.439
Rahul Shrikrishna Joshi .: Disturbingâ€¦ this thing is disturbing me. Can I show you?

1233
02:07:50.440 --> 02:07:56.850
Faculty (Olympus): What is this? Can you describe it? Because showing means I have to now stop sharing screen, and then you have to share your screen. Okay, share your screen.

1234
02:07:56.850 --> 02:07:57.600
Rahul Shrikrishna Joshi .: Yeah, yeah.

1235
02:07:59.000 --> 02:08:00.210
Rahul Shrikrishna Joshi .: Okay, can you see my screen?

1236
02:08:00.480 --> 02:08:01.120
Faculty (Olympus): Nope.

1237
02:08:01.650 --> 02:08:02.580
Faculty (Olympus): Not yet.

1238
02:08:04.910 --> 02:08:07.600
Rahul Shrikrishna Joshi .: Okay, so, let me know, like, once it is visible here.

1239
02:08:07.600 --> 02:08:08.180
Faculty (Olympus): Yeah.

1240
02:08:08.520 --> 02:08:08.880
Rahul Shrikrishna Joshi .: Yeah.

1241
02:08:08.880 --> 02:08:10.650
Faculty (Olympus): I can see your screen, but it's too small.

1242
02:08:10.890 --> 02:08:13.889
Rahul Shrikrishna Joshi .: Oh, okay. Maybe make it bigger, yeah. Is it better now?

1243
02:08:14.160 --> 02:08:15.070
Faculty (Olympus): Yeah.

1244
02:08:15.070 --> 02:08:22.740
Rahul Shrikrishna Joshi .: Yeah, yeah. So, so what I'm trying to say is that, let's say theâ€¦ this is experiment, okay, left-hand side is experiment, okay? Where I've done 3 measurements.

1245
02:08:23.060 --> 02:08:34.539
Rahul Shrikrishna Joshi .: of X, and this is actuallyâ€¦ this is Y. These are the measured values, okay? And then, let's presume that it's a fitâ€¦ fit, linear y equal to 2X, okay?

1246
02:08:34.540 --> 02:08:35.030
Faculty (Olympus): Yeah.

1247
02:08:35.030 --> 02:08:39.199
Rahul Shrikrishna Joshi .: And then, this is the mean of Y, this is a sum of Y, this is a mean of Y.

1248
02:08:39.340 --> 02:08:45.399
Rahul Shrikrishna Joshi .: And then, why SYY is every value you subtract from the mean and square of that. This is the SYY, right?

1249
02:08:45.660 --> 02:08:46.550
Faculty (Olympus): Okay.

1250
02:08:46.550 --> 02:08:54.510
Rahul Shrikrishna Joshi .: Okay? Now, I spoofed the model, and instead of saying Y equal to 2X, somehow I say Y equal to mean value itself. Sure.

1251
02:08:54.680 --> 02:08:57.459
Rahul Shrikrishna Joshi .: And then, then also it will match, actually, SRR.

1252
02:08:57.890 --> 02:08:58.720
Faculty (Olympus): Okay.

1253
02:08:59.640 --> 02:09:01.820
Rahul Shrikrishna Joshi .: So, what I'm trying to say is that, then.

1254
02:09:02.030 --> 02:09:10.889
Rahul Shrikrishna Joshi .: This isâ€¦ even though this is not a right model, because Y is not constant, but the coefficient of determination will be perfect, right, in this case.

1255
02:09:10.890 --> 02:09:20.089
Faculty (Olympus): Again, because, notice that your values are going to be swamped out by the large values, right? You need more data points to actually verify whether it's a good fit or not a good fit.

1256
02:09:23.130 --> 02:09:30.839
Rahul Shrikrishna Joshi .: No, actually, my point was, ideally, your Y should increase as X, right? More data points. Even though you put another 10 data points.

1257
02:09:30.840 --> 02:09:33.239
Faculty (Olympus): But if the mean is this one, and if you say.

1258
02:09:33.240 --> 02:09:34.329
Rahul Shrikrishna Joshi .: that my model is always.

1259
02:09:34.330 --> 02:09:36.160
Faculty (Olympus): Let's do the mean value.

1260
02:09:36.580 --> 02:09:40.269
Faculty (Olympus): I am unbelieve Savi, one sec.

1261
02:09:40.270 --> 02:09:41.160
Rahul Shrikrishna Joshi .: Yeah, no worries here.

1262
02:09:42.160 --> 02:09:42.770
Faculty (Olympus): Yeah.

1263
02:09:43.510 --> 02:09:47.679
Rahul Shrikrishna Joshi .: Yeah, so even though we have, let's say, 100 data points, and if you calculate the mean of that and just.

1264
02:09:47.680 --> 02:09:55.549
Faculty (Olympus): See, what you're telling me is that the mean is the bestâ€¦ is a good predictor for your Y. Absolutely it is. In fact, it is the Bay Square's best predictor of Y.

1265
02:09:57.390 --> 02:10:07.590
Faculty (Olympus): Because your model is, again, just a single value here in this case. You're saying that there is one constant that I'm going to replace everything by, so your model is essentially some B0. You found the best constant for that. Sure.

1266
02:10:08.580 --> 02:10:10.390
Rahul Shrikrishna Joshi .: But this is not right, right, sir, because why should.

1267
02:10:10.390 --> 02:10:16.819
Faculty (Olympus): Why is it not linear? You're giving me a model that's linear. Sorry, you're giving me a model that's a constant. This is the best constant that's going to model your data.

1268
02:10:17.260 --> 02:10:21.890
Rahul Shrikrishna Joshi .: Now, but then this, this, this will hold good for every linear model, right? Two variable linear model.

1269
02:10:22.100 --> 02:10:27.209
Soumen Deb .: No, no, just make it 3X also, right? So itâ€¦ so you'll have to change the mean on this side, then.

1270
02:10:27.830 --> 02:10:28.530
Soumen Deb .: It's linear.

1271
02:10:28.530 --> 02:10:34.159
Rahul Shrikrishna Joshi .: No, no, no, I understand that. I got that, but what I meant to say is that if youâ€¦ means you canâ€¦ you canâ€¦

1272
02:10:34.570 --> 02:10:39.480
Rahul Shrikrishna Joshi .: cue the false interpretation by having this type of a model. That is what I'm trying to ask, actually.

1273
02:10:41.070 --> 02:10:49.570
Faculty (Olympus): I still don't understand what they're saying. You're telling me that if I give you a proper linear model, you will actually beat my linear model by giving me just a constant value?

1274
02:10:49.570 --> 02:10:52.939
Rahul Shrikrishna Joshi .: Correct, correct, correct, correct.

1275
02:10:52.940 --> 02:10:56.279
Faculty (Olympus): I'll give you a linear model that gives you the exact answer for this.

1276
02:10:56.440 --> 02:10:58.170
Faculty (Olympus): You're missing the whole point here.

1277
02:10:59.310 --> 02:11:01.720
Faculty (Olympus): I'll give you zero, you've not given me zero.

1278
02:11:03.170 --> 02:11:04.350
Faculty (Olympus): It's not the same.

1279
02:11:10.170 --> 02:11:11.659
Rahul Shrikrishna Joshi .: I'm missing something here, actually.

1280
02:11:11.920 --> 02:11:18.239
Faculty (Olympus): See, if you look at Y bar, see, you're telling me that if I give you a random variable, which is the weight of the students in the class.

1281
02:11:18.370 --> 02:11:20.590
Faculty (Olympus): My model is, everybody is 65 kgs.

1282
02:11:20.710 --> 02:11:28.239
Faculty (Olympus): And you're telling me that the, you know, it's going to give me excellent prediction? Yeah, to some extent, it's a bestâ€¦ it's a one number if you want to describe this model, great.

1283
02:11:29.490 --> 02:11:32.000
Rahul Shrikrishna Joshi .: Yeah, so, see, what I'm saying is that the modelâ€¦

1284
02:11:32.000 --> 02:11:32.570
Faculty (Olympus): It'sâ€¦

1285
02:11:32.990 --> 02:11:38.259
Rahul Shrikrishna Joshi .: Your model is not good, but the coefficient of determination will be very precise, actually, in this case.

1286
02:11:39.490 --> 02:11:40.240
Faculty (Olympus): Sorry?

1287
02:11:40.930 --> 02:11:44.620
Rahul Shrikrishna Joshi .: In this case, obviously, the model is not good. Model is absolutely not varying as the.

1288
02:11:44.620 --> 02:11:47.630
Faculty (Olympus): No, but according to you, you're saying the model is great. It's not great.

1289
02:11:47.630 --> 02:11:54.069
Rahul Shrikrishna Joshi .: from the coefficient of determination perspective, it isâ€¦ it isâ€¦ it isâ€¦ it is great, sir. That's what I'm trying to say. Not great, sir, sir.

1290
02:11:56.010 --> 02:11:56.809
Faculty (Olympus): So you tryâ€¦

1291
02:11:56.810 --> 02:11:57.960
Soumen Deb .: With a model, and then you look at.

1292
02:11:57.960 --> 02:11:59.449
Faculty (Olympus): What's a difference between those two?

1293
02:11:59.620 --> 02:12:01.039
Soumen Deb .: Yeah, looking at only one.

1294
02:12:01.040 --> 02:12:07.650
Faculty (Olympus): You're looking at one quantity and saying, yeah, I'm the best mark, I'm one student in class, I got 2 marks out of 100, I'm the best student, sure.

1295
02:12:08.610 --> 02:12:17.960
Soumen Deb .: So, so if it's a correlation between a height and a weight, right, you're ignoring the height and you're just looking at the weight, and then you're saying the weight is 65. That's what you're doing right now.

1296
02:12:18.080 --> 02:12:20.370
Soumen Deb .: And throughout the rest of the weight is 65.

1297
02:12:20.370 --> 02:12:22.760
Faculty (Olympus): No, that's exactly what you're doing, Rahul, you're completely.

1298
02:12:22.760 --> 02:12:23.130
Soumen Deb .: Yes.

1299
02:12:23.130 --> 02:12:29.060
Faculty (Olympus): understanding what you're saying. You're saying there's a single constant number, and you're giving me 3 values, and you're trying to prove your case.

1300
02:12:30.570 --> 02:12:35.389
Faculty (Olympus): I'm telling you, if I give you a linear model, I'll give you 0. My R-squared will be in 1.0.

1301
02:12:35.600 --> 02:12:37.600
Faculty (Olympus): I didn't shown that in my code.

1302
02:12:41.420 --> 02:12:43.160
Rahul Shrikrishna Joshi .: Okay, let me think over it, sir, I think.

1303
02:12:43.160 --> 02:12:44.130
Faculty (Olympus): No, you need to fiddle.

1304
02:12:44.130 --> 02:12:44.580
Siddhesh Dinesh Kadam .: God.

1305
02:12:44.580 --> 02:12:50.310
Faculty (Olympus): and you find the R-squared for that, you fit a linear model, and you fit a constant model, find the R-squared for that, and then you'll see the difference.

1306
02:12:50.310 --> 02:13:00.680
Siddhesh Dinesh Kadam .: Probably Raoâ€¦ Rau, you are assuming mean to be the true value, always. That is the main problem, because then you're fixing one point, and the second point is the only variable. Thatâ€¦ thatâ€¦ probably think about that.

1307
02:13:01.790 --> 02:13:05.570
Rahul Shrikrishna Joshi .: Okay, we'll think about it. I think I'm probably not phrasing my question properly.

1308
02:13:05.570 --> 02:13:23.030
Soumen Deb .: And even Excel also has linear regression-solving macros. So you can actually put those values, and it will give you, sort of a plot out there in it with numbers. If you check in the internet, there are Excel sheets which do linear regression based on the quantities that you put in it.

1309
02:13:23.030 --> 02:13:28.920
Faculty (Olympus): No, no, see, what he's saying is correct. See, if you want to represent something that has linear variation.

1310
02:13:29.050 --> 02:13:35.069
Faculty (Olympus): with a single number, the best number to use is the mean. In fact, there is no better number to be represented.

1311
02:13:35.070 --> 02:13:36.749
Rahul Shrikrishna Joshi .: Yeah, that is what I was trying to say.

1312
02:13:36.750 --> 02:13:38.460
Faculty (Olympus): No, you're not trying to say that.

1313
02:13:38.850 --> 02:13:42.540
Faculty (Olympus): You're misconstruing this statement with a linear model.

1314
02:13:46.270 --> 02:13:53.890
Faculty (Olympus): What is the linear model here? The linear model is 2x. You have not even given me a coefficient. You have not even treated this as a linear model. You're treating this as a constant model.

1315
02:13:55.390 --> 02:14:00.389
Faculty (Olympus): It is just like the example I showed you with the X squared. I'll give you a high R squared, but it's not a great model.

1316
02:14:01.050 --> 02:14:06.029
Rahul Shrikrishna Joshi .: That is what I was trying to say. So, R-square is not the onlyâ€¦ if the R-square is high, doesn't mean thatâ€¦

1317
02:14:06.030 --> 02:14:08.659
Faculty (Olympus): Yeah, you can lie with statistics, of course you can.

1318
02:14:09.080 --> 02:14:14.310
Faculty (Olympus): It's like saying, you know, Rahul Dwith, or whatever, Virat Kohli, whenever he bets, he's gonna score 43 runs.

1319
02:14:14.420 --> 02:14:15.370
Faculty (Olympus): Okay.

1320
02:14:16.140 --> 02:14:16.870
Rahul Shrikrishna Joshi .: But, yeah.

1321
02:14:17.900 --> 02:14:18.730
Faculty (Olympus): bugâ€¦

1322
02:14:19.060 --> 02:14:25.720
Faculty (Olympus): Right? It'sâ€¦ that's justâ€¦ that'sâ€¦ that's no use, because you've not given me a linear model. You've given meâ€¦ there are clearly a singleâ€¦

1323
02:14:26.540 --> 02:14:27.479
Rahul Shrikrishna Joshi .: Yeah, yeah. And I got it, sir.

1324
02:14:27.480 --> 02:14:29.650
Faculty (Olympus): He'll never score a century, according to you, basically.

1325
02:14:29.650 --> 02:14:31.700
Rahul Shrikrishna Joshi .: Yeah, yeah, I got it, yeah.

1326
02:14:32.870 --> 02:14:33.800
Rahul Shrikrishna Joshi .: Thank you, sir.

1327
02:14:34.420 --> 02:14:35.650
Soumen Deb .: Thank you. Thank you.

1328
02:14:35.650 --> 02:14:38.690
Faculty (Olympus): I have to go now. Bye-bye. See you tomorrow.

1329
02:14:39.520 --> 02:14:40.380
Kedar Digambar Gokhale .: Thank you.

