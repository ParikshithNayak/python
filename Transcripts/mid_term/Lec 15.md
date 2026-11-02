WEBVTT

1
00:04:13.730 --> 00:04:20.149
Abhineet Bansal: Hi guys, Abhinit here, just wanted to check, do we have an unofficial WhatsApp group?

2
00:04:20.570 --> 00:04:22.189
Abhineet Bansal: Among the students here.

3
00:04:30.260 --> 00:04:34.499
Abhineet Bansal: Swapnil, I don't know what that means. I mean, do we have one?

4
00:04:34.500 --> 00:04:35.480
Swapnil Sankla .: Yeah, we do have it.

5
00:04:36.190 --> 00:04:40.080
Abhineet Bansal: Can you add me to that group if I share my number here in the chat?

6
00:04:40.490 --> 00:04:41.910
Swapnil Sankla .: Yeah, please do that.

7
00:04:43.210 --> 00:04:44.660
Abhineet Bansal: I'm putting my number here.

8
00:05:03.170 --> 00:05:04.130
Abhineet Bansal: Thanks, Rotman.

9
00:05:54.100 --> 00:05:55.189
Faculty (Olympus): Morning, everyone.

10
00:05:59.370 --> 00:06:00.260
Abhishek Agrawal .: Good morning.

11
00:06:48.450 --> 00:06:49.890
Faculty (Olympus): Share my screen.

12
00:06:54.240 --> 00:06:55.140
Amlan Sarkar .: Yes, sir.

13
00:07:11.340 --> 00:07:15.549
Faculty (Olympus): Alright, so I still see very few participants today.

14
00:07:16.300 --> 00:07:20.450
Faculty (Olympus): This is going to be a very important class, soâ€¦ At least ifâ€¦

15
00:07:21.410 --> 00:07:28.670
Faculty (Olympus): People are not attending, I'm hoping they're watching the videos, because this content is very important for your quiz, for your mid-semester exam.

16
00:07:29.420 --> 00:07:34.880
Faculty (Olympus): So Whatever we have started now with regression is kind of.

17
00:07:35.460 --> 00:07:37.580
Faculty (Olympus): The first entry point into ML.

18
00:07:38.120 --> 00:07:43.319
Faculty (Olympus): And so, clearly, something that's important and that you need to pay attention to.

19
00:07:49.230 --> 00:07:52.289
Faculty (Olympus): It's asking you to start transcription.

20
00:08:06.890 --> 00:08:09.569
Faculty (Olympus): I'll join with my repaired outsourcer.

21
00:08:45.390 --> 00:08:50.869
Faculty (Olympus): Alright, can youâ€¦ Are you able to see my screen? Are you able to hear me?

22
00:08:52.950 --> 00:08:53.660
Anuj Kumar Gupta .: Yes, Professor.

23
00:08:54.230 --> 00:08:54.929
Varun Kumar .: Yeah, weâ€¦

24
00:08:55.590 --> 00:08:58.459
Faculty (Olympus): So class attendance today is very, very low.

25
00:08:59.690 --> 00:09:03.149
Varun Kumar .: Actually, this is marked as optional, so maybe this is the reason.

26
00:09:03.540 --> 00:09:04.490
Faculty (Olympus): Hopefully.

27
00:09:06.030 --> 00:09:12.909
Faculty (Olympus): No, this is optional. All right. This is where we get to the meat of things. All right. Is Rahul here?

28
00:09:14.450 --> 00:09:16.169
Soumen Deb .: Was in another call.

29
00:09:16.490 --> 00:09:18.980
Soumen Deb .: Let me see, please.

30
00:09:18.980 --> 00:09:19.480
Rahul Shrikrishna Joshi .: sir.

31
00:09:19.710 --> 00:09:28.270
Faculty (Olympus): Yeah, okay, great. Fine. So what I'll do is I'll quickly revise, and I will answer Rahul's question also from last time, since last time we did it at the end of the class.

32
00:09:28.520 --> 00:09:33.770
Faculty (Olympus): Very quickly, I'm not going to get to a lot of things. I want to quickly finish this,

33
00:09:34.030 --> 00:09:40.010
Faculty (Olympus): You know, just a quick revision of the basics. The idea, again, is we come up with a model.

34
00:09:40.010 --> 00:09:55.469
Faculty (Olympus): Okay, the idea is you have some dependent quantity, say in this case Y, which is a quantity you're interested in studying, and it depends as far as you are concerned on certain set of independent variables. So in that case, X1 dot dot dot to XR are your independent variables.

35
00:09:55.480 --> 00:10:00.639
Faculty (Olympus): And we're trying to find this relationship. So the first thing is we're creating a model.

36
00:10:00.860 --> 00:10:05.100
Faculty (Olympus): Where we propose that it is a linear model of this form.

37
00:10:05.200 --> 00:10:08.600
Faculty (Olympus): Once we do that, You end up with?

38
00:10:08.910 --> 00:10:18.290
Faculty (Olympus): a set of constants that are not yet determined. Okay, so B naught, beta naught, beta one, etc. are constants that define this relationship.

39
00:10:18.480 --> 00:10:24.000
Faculty (Olympus): And so linear regression is the process of finding these coefficients from some data that you measure.

40
00:10:24.800 --> 00:10:33.139
Faculty (Olympus): So formally we set this up by setting an error and this error has zero mean because if it didn't have zero mean it will be absorbed in your beta naught.

41
00:10:33.280 --> 00:10:40.599
Faculty (Olympus): And you end up with what's called the linear regression equation here, where beta I call the regression coefficients, okay?

42
00:10:41.450 --> 00:10:57.099
Faculty (Olympus): We quickly looked at estimators, and the idea was that if you are given some data, any parameters that you determine, like alpha and beta in this case, or beta naught, beta 1, so on and so forth in this case, are only estimates. And so the formula that you compute using some strategy.

43
00:10:57.330 --> 00:11:00.660
Faculty (Olympus): Is called an estimator for a specific parameter.

44
00:11:00.970 --> 00:11:11.139
Faculty (Olympus): And what we did was, we came up with a strategy called the least squares estimator of a parameter. And the approach here was, we found SSR. SSR is YI minus A minus BXI.

45
00:11:11.140 --> 00:11:22.600
Faculty (Olympus): In this case, which is essentially the difference between the measured value and the predicted value from my model. And please note, in this case, I considered a simple model, which is just having two parameters. It's a simple linear

46
00:11:22.600 --> 00:11:30.860
Faculty (Olympus): regression case with just alpha and beta, okay? And we replaced alpha and beta by A and B, just to make it absolutely clear to you that

47
00:11:30.860 --> 00:11:40.749
Faculty (Olympus): We are only finding estimates of alpha and beta. And as you do more and more and more and more experiments, that you will obtain, you will get towards your alpha and beta.

48
00:11:41.820 --> 00:11:54.029
Faculty (Olympus): So, the idea that we used to obtain formulae for A and B, the estimators, was to basically compute the sum of the squares of differences, which is the difference between the predicted value, which is A plus BXI, and YI.

49
00:11:54.400 --> 00:12:01.149
Faculty (Olympus): And this SSR is essentially sum of the squares of the residual. So the residual is basically YI minus A plus B itself, okay? That's what we looked at.

50
00:12:01.150 --> 00:12:14.770
Faculty (Olympus): Then we differentiate this with respect to the parameters A and B and got two normal equations which are linear in the parameters A and B. You can solve this with a linear system of equations. We got the solution in explicit form because it's two equations, it can just solve it straight away.

51
00:12:15.030 --> 00:12:33.020
Faculty (Olympus): And then we wrote out this coefficient of determination, okay? So where SYY is the variation in the set of values, SXX was the variation in your X value, which doesn't show up here, and SSR is, again, your sum of the squares of the residuals, okay? So, SYY minus SSR

52
00:12:33.150 --> 00:12:48.479
Faculty (Olympus): becomes the variation in the responses that is fully explained by the inputs, which means anything that is not accounted for by this is essentially noise. So it's the variation in the response explained by the inputs.

53
00:12:48.750 --> 00:12:51.989
Faculty (Olympus): Essentially SSR plus the noise becomes your SY.

54
00:12:52.080 --> 00:13:09.170
Faculty (Olympus): And so, the coefficient of determination, R squared, is defined as the variation in response explained by the inputs by the total variation, which turns out to 1 minus SSR by S5, and SSR is the sum of the squares. So one intuitive way of thinking about this is, SSR is nothing but

55
00:13:10.770 --> 00:13:19.279
Faculty (Olympus): the residual for every point. So if I take a given point, I find the difference between this and, you know, the predicted value versus the true value.

56
00:13:19.460 --> 00:13:29.660
Faculty (Olympus): take the sum of the squares, right? If that is very small, that suggests that my model has actually predicted very well. It's done a very good job. And so, as this goes to zero, this fellow is going to go towards one.

57
00:13:29.980 --> 00:13:38.800
Faculty (Olympus): Now, the problem with Rahul's example last class was he was confusing this notion of this formula here.

58
00:13:38.960 --> 00:13:39.880
Faculty (Olympus): And.

59
00:13:41.110 --> 00:13:46.460
Faculty (Olympus): The example he cited was, he has a model which simply predicts y bar, ok.

60
00:13:46.640 --> 00:13:54.430
Faculty (Olympus): Which is, what is Y bar? Y bar is sigma YI by N. If you do that, then your SSR actually becomes the same as SYY.

61
00:13:55.080 --> 00:13:56.869
Faculty (Olympus): Right? And the problem wasâ€¦

62
00:13:57.890 --> 00:14:02.900
Faculty (Olympus): If you look at this formula, what this means is R squared is 0. R squared is not 1.

63
00:14:03.460 --> 00:14:08.380
Faculty (Olympus): And so what I was saying was correct, that it is a really bad model if you just predict a single value.

64
00:14:08.530 --> 00:14:11.480
Faculty (Olympus): So R squared is actually zero in this case, it's not one.

65
00:14:11.940 --> 00:14:12.610
Rahul Shrikrishna Joshi .: Got it, yeah.

66
00:14:12.610 --> 00:14:17.310
Faculty (Olympus): Because SSR will be equal to SYY, so this becomes 1 minus 1, so it becomes close to 0.

67
00:14:17.550 --> 00:14:28.410
Faculty (Olympus): Right? So you really need to have a better model, you can't just predict the constant and get a variable. Having said that, what I was trying to explain was, in the specific example he picked, he said Y is equal to 2X.

68
00:14:29.200 --> 00:14:33.339
Faculty (Olympus): Right? When you look at Y is equal to 2X, what happens isâ€¦

69
00:14:33.720 --> 00:14:53.349
Faculty (Olympus): If you take Y itself, the best predictor of Y, Y is just a random variable in this case, the best predictor of Y, if you want a single number, will be the mean. So if you want to pick one constant, the best constant to pick is Y bar. Having said that, your SSR will still be pathetic, because you will still get YI minus Y bar, the whole squared, which is essentially the variance in the data.

70
00:14:53.520 --> 00:14:59.120
Faculty (Olympus): Okay, so unless your real result is all single value, every experiment you get the same number.

71
00:14:59.370 --> 00:15:01.440
Faculty (Olympus): Then you really don't have much of a model.

72
00:15:01.690 --> 00:15:10.470
Faculty (Olympus): It should be a single value. It should be a constant. In which case the best constant will be y bar, which is fine. But the instant you have a linear variation that does not hold. Okay.

73
00:15:10.620 --> 00:15:13.059
Faculty (Olympus): All right, Soumen, quick question.

74
00:15:14.660 --> 00:15:17.319
Soumen Deb .: Yeah, and on the same point, I think so.

75
00:15:17.660 --> 00:15:20.220
Soumen Deb .: The problem statement is that

76
00:15:20.450 --> 00:15:24.210
Soumen Deb .: We are given points, and then we have to plot a line in it.

77
00:15:24.490 --> 00:15:31.159
Soumen Deb .: The example which was shown yesterday, the line was already plot, and the points were already on the line. Hence.

78
00:15:31.160 --> 00:15:36.640
Faculty (Olympus): No, no, no, no, I never got the line. I had originally only had the points. So even when.

79
00:15:36.640 --> 00:15:40.350
Soumen Deb .: But it was Y is equal to 2X, that's the line, right?

80
00:15:41.060 --> 00:15:41.790
Faculty (Olympus): Even so.

81
00:15:41.790 --> 00:15:42.220
Soumen Deb .: energy.

82
00:15:42.220 --> 00:15:45.810
Faculty (Olympus): Even so, even if you look at y is equal to 2x and you take the values.

83
00:15:46.060 --> 00:16:02.400
Faculty (Olympus): Your SSR that he would have computed was actually the same as SYY. He was saying that oh, it's 1800 something, this is also 1800, so they're the same. So, yes, SSR was equal to SYY. That was the mistake. The mistake was you subtract the two, then it gets to zero, and that was the big problem.

84
00:16:02.690 --> 00:16:03.200
Rahul Shrikrishna Joshi .: Correct, correct.

85
00:16:03.620 --> 00:16:08.120
Faculty (Olympus): Right? So, all right. So, Prachi, very quick question. Prachi, go ahead.

86
00:16:08.120 --> 00:16:12.939
Lad Prachikumari Vijaykumar .: Sir, why we are not dividing by N in SSR and SSY?

87
00:16:13.520 --> 00:16:16.189
Faculty (Olympus): In SSR and SSY, whatever.

88
00:16:16.190 --> 00:16:17.190
Lad Prachikumari Vijaykumar .: In yeah.

89
00:16:17.610 --> 00:16:21.679
Lad Prachikumari Vijaykumar .: No, we are not dividing here, yeah, but actually.

90
00:16:22.310 --> 00:16:23.050
Lad Prachikumari Vijaykumar .: But.

91
00:16:23.050 --> 00:16:27.769
Faculty (Olympus): It's not the same as the variance. It is related to the variance by a constant M.

92
00:16:28.150 --> 00:16:37.750
Faculty (Olympus): I'm not saying it is similar to the variance. So yes, you'll have to divide by either n or n minus one. Correct. If you want to say this is the variance. I'm not saying it's the variance. I'm saying it is similar to the variance. That's all.

93
00:16:37.750 --> 00:16:40.080
Lad Prachikumari Vijaykumar .: And S S are also same

94
00:16:40.080 --> 00:16:56.000
Faculty (Olympus): SSR is not really, again, something like that. SSR, you can estimate as the variance of the noise. So you look atâ€¦ remember this, we have E here. So, in fact, the SSR divided by N minus 2 is actually an estimator for the variance in the noise.

95
00:16:56.500 --> 00:16:57.250
Lad Prachikumari Vijaykumar .: Okay.

96
00:16:57.250 --> 00:17:07.069
Faculty (Olympus): All right, which is why when we did theâ€¦ when we looked at, theâ€¦ assessing the model, we computed YI minus A plus BXI divided by SSR by M minus 2 square.

97
00:17:07.599 --> 00:17:11.199
Lad Prachikumari Vijaykumar .: So SSR is not equal to mean square error.

98
00:17:11.579 --> 00:17:14.599
Faculty (Olympus): It is the mean squared error. But it turns out that

99
00:17:15.299 --> 00:17:18.009
Faculty (Olympus): When you have normally distributed noise.

100
00:17:18.380 --> 00:17:18.750
Lad Prachikumari Vijaykumar .: the.

101
00:17:18.750 --> 00:17:24.699
Faculty (Olympus): This fellow will actually be a represent, will be a estimator for the variance in your noise.

102
00:17:25.510 --> 00:17:26.210
Lad Prachikumari Vijaykumar .: Okay.

103
00:17:26.470 --> 00:17:27.599
Lad Prachikumari Vijaykumar .: Okay, fine, sir.

104
00:17:27.609 --> 00:17:34.479
Faculty (Olympus): So I think you will do this in great detail when you do your statistics course. This is usually part of it. It's very straightforward to show this.

105
00:17:34.480 --> 00:17:35.200
Lad Prachikumari Vijaykumar .: Hmm, okay.

106
00:17:35.200 --> 00:17:39.860
Faculty (Olympus): Right, but straightforward money, it's tedious, but it's there's nothing very profound about it.

107
00:17:40.280 --> 00:17:41.050
Lad Prachikumari Vijaykumar .: Okay.

108
00:17:41.050 --> 00:17:56.439
Faculty (Olympus): This becomes an estimator for your, so notice we had this noise, right? And when I plotted my, this fellow, see there's noise in this data. So if I fit the straight line, right, I get a straight line here and there's noise about, so it's almost like there's this line and there's noise about that line.

109
00:17:56.470 --> 00:18:06.499
Faculty (Olympus): Right? So that noise, if you want to estimate the amount of noise, the variance of that noise, this SSR is actually a very useful quantity to use.

110
00:18:06.840 --> 00:18:08.440
Lad Prachikumari Vijaykumar .: Hmm, yes, exactly, yeah.

111
00:18:08.440 --> 00:18:11.669
Faculty (Olympus): So in fact, SSR by N minus two becomes your,

112
00:18:13.900 --> 00:18:15.890
Faculty (Olympus): You know, your variants of your,

113
00:18:15.890 --> 00:18:16.350
Lad Prachikumari Vijaykumar .: Huh.

114
00:18:16.350 --> 00:18:17.969
Faculty (Olympus): of the E. Okay.

115
00:18:17.970 --> 00:18:18.370
Lad Prachikumari Vijaykumar .: Hmm.

116
00:18:18.370 --> 00:18:19.120
Faculty (Olympus): Thanks.

117
00:18:19.120 --> 00:18:19.660
Lad Prachikumari Vijaykumar .: useful.

118
00:18:19.660 --> 00:18:20.290
Faculty (Olympus): All right.

119
00:18:20.650 --> 00:18:31.350
Faculty (Olympus): Okay, so again, we looked at this, and we said that, look, it's not some trivial thing here. You can use linear regression, even if it's not a linear model, so long as you know the functional form.

120
00:18:31.490 --> 00:18:44.709
Faculty (Olympus): and your coefficients are linear, you can actually use this for various other things, including polynomial regression. And then I very quickly showed you, I didn't prove this, but I just showed you the outline of how you would actually consider a multilinear regression case.

121
00:18:44.710 --> 00:18:55.629
Faculty (Olympus): Where you have Y1 is a measurement, Y2 is another measurement, so on and so forth. So I have N measurements, and I have, say, K variables, independent variables. And so now you assemble this X matrix as a constant column.

122
00:18:55.630 --> 00:19:05.340
Faculty (Olympus): Then this is your first variable, second variable, so there are N rows here, okay? And then you end up with a equation that becomes Y is equal to XB, where B is a

123
00:19:05.440 --> 00:19:10.000
Faculty (Olympus): K plus 1 column matrix. And so this is

124
00:19:10.250 --> 00:19:28.309
Faculty (Olympus): n cross k plus 1, and this fellow is k plus 1 cross 1. So you'll essentially get an n cross 1 matrix if you multiply these two, x and b, and therefore this is a consistent system of equations for n of these measurements. And to solve this, you do what's called the least squares form of the solution, because this is a non-square system.

125
00:19:28.460 --> 00:19:40.409
Faculty (Olympus): And this is exactly what is used when we did our old fellow. When we did this, pendulum example that we did, that's exactly what we did. We used least squares, Adinaz.least squares, which essentially solves this problem.

126
00:19:40.550 --> 00:19:49.380
Faculty (Olympus): Okay? And under the covers, whenever someone's doing linear regression or polynomial regression, this is essentially the equation they're solving. So it's an extremely powerful technique.

127
00:19:49.530 --> 00:19:55.470
Faculty (Olympus): for your first, you know, model that we are presenting. Okay, Rahul, you had raised your hand. Is there a question?

128
00:19:56.200 --> 00:19:58.190
Rahul Shrikrishna Joshi .: No, sorry, I'll come at the end, actually.

129
00:19:58.190 --> 00:20:17.530
Faculty (Olympus): Okay, great. Fine. So then all we did was, I took the same expressions that we had derived. I didn't really derive, I showed you how to derive, right? I didn't formally do it on the screen. And then I wrote out Python code for this and showed you, hey, these are the coefficients. Then I showed you with polyfit that you get the exact same coefficients.

130
00:20:17.540 --> 00:20:22.189
Faculty (Olympus): And then we computed the coefficient of determination, and I showed you these values.

131
00:20:22.240 --> 00:20:32.819
Faculty (Olympus): Then I started playing with the data. As in, I created a model where I said, look, I know the model is 2 times X plus 0.25, I'm going to add noise, and I'm going to see how this approach works.

132
00:20:32.880 --> 00:20:39.440
Faculty (Olympus): So using this, I can now, you know, get a feel for how this regression works.

133
00:20:39.600 --> 00:20:57.410
Faculty (Olympus): So I wrote a bunch of functions, which are all simple things. You know, one is just doing a polyfit with a single degree, so which means it's a linear fit. But if you wanted to make this 2 or 3, you can easily change this. It's just a small change here. And only thing is, when you do the predict also, you'll have to have, if it's

134
00:20:57.550 --> 00:21:16.229
Faculty (Olympus): it's a second-order polynomial, then you'll have coefficient 0 star x star x, plus coefficient of 0 star x, plus coefficient of, you know, 1, and then coefficient of 2. So you'll have to change this fellow, but the rest of it remains exactly the same, right? And then we wrote this fit and predict together in one shot.

135
00:21:16.230 --> 00:21:22.909
Faculty (Olympus): And then I wrote this little plot function, which does all the plotting. It shows you the original values, shows the best fit.

136
00:21:22.970 --> 00:21:26.879
Faculty (Olympus): And then, on a separate plot, it shows you the standardized

137
00:21:26.950 --> 00:21:33.589
Faculty (Olympus): Residuals, which is Y minus YP, which is the Y actual values by the Y predicted values, divided by this.

138
00:21:33.940 --> 00:21:37.439
Faculty (Olympus): Sigma, which is nothing but SSR by N minus square root.

139
00:21:37.800 --> 00:21:48.020
Faculty (Olympus): And then that is plotted. Okay. And that's what we showed. And I showed you this simple example. And I showed you the same thing with a, you know, a notebook. I think I'm going to have to rerun all of this.

140
00:21:48.910 --> 00:21:50.210
Faculty (Olympus): Quickly do that.

141
00:21:51.230 --> 00:21:53.939
Faculty (Olympus): I don't think I even ran the first cell, soâ€¦

142
00:21:57.740 --> 00:22:00.940
Faculty (Olympus): Thenâ€¦ Source.

143
00:22:04.350 --> 00:22:05.080
Faculty (Olympus): Cool.

144
00:22:08.710 --> 00:22:09.810
Faculty (Olympus): Thisâ€¦

145
00:22:10.180 --> 00:22:16.009
Faculty (Olympus): This, and then weâ€¦ so I showed you that, you know, you canâ€¦ you can get a sense of the R-squared and things like that.

146
00:22:16.280 --> 00:22:21.400
Faculty (Olympus): You know? So if I increase the amount of noise, for example, the R squared will keep dropping.

147
00:22:23.270 --> 00:22:40.260
Faculty (Olympus): Okay, so R squared here is 0.559, but you can see very clearly that even though, yes, there's a linear trend, a lot of the actual variation in the data is not explained purely by the straight line. And unfortunately, there's no pattern that I can discern here to make anything. It's just that this data is extremely noisy.

148
00:22:40.450 --> 00:22:48.850
Faculty (Olympus): Then I showed the same thing. I just changed one thing. I made this, the original data, I made it a parabolic model, but I still retained the fitting to be a straight line fit.

149
00:22:48.960 --> 00:23:02.659
Faculty (Olympus): And when you did this, you'll see that as I increase, say, N to, say, okay, 34 points or whatever, so, say, 55 points, you can see that, you know, there is a parabolic variation in this, but the R-squared is still quite high, which means it's a reasonable model.

150
00:23:02.740 --> 00:23:17.999
Faculty (Olympus): But when you start looking at the residuals, standardized residuals, you see that, okay, it looks like the noise is normally distributed, which is true, because that's what we did. But then you see the fact that, you know, there's a pattern that you can clearly see. And that pattern tells you that

151
00:23:18.350 --> 00:23:28.190
Faculty (Olympus): there is some modeling that has been missed, okay? So if you clearly see a pattern in your noise, in your, what is supposed to be noise, then perhaps you need to do a little more modeling.

152
00:23:28.780 --> 00:23:34.360
Faculty (Olympus): In one dimension, this is easy to do. In other dimensions, it may not be so easy to do. It may not be so easy to disarm.

153
00:23:34.550 --> 00:23:38.319
Faculty (Olympus): Okay, so again, the best quantity that you have on hand is your ask.

154
00:23:39.210 --> 00:23:51.270
Faculty (Olympus): All right. Now, one of the things that you will find that you will need to do at different points is to check your assumptions whether, you know, your errors are truly normal or are they not normal. There are several statistics, you know, quantities

155
00:23:51.270 --> 00:24:06.240
Faculty (Olympus): That will give you this answer. But if you want to also get a sense of it visually and through a plot, there is something called a QQ plot. And the QQ plot basically takes the quantiles of some given distribution with that of a known distribution and plots them against each other.

156
00:24:06.350 --> 00:24:10.309
Faculty (Olympus): So let me explain once again. What is a quantile? Quantile is like a percentile.

157
00:24:10.980 --> 00:24:14.710
Faculty (Olympus): Okay, so if I give you 2 distributions that should look the same.

158
00:24:14.970 --> 00:24:30.170
Faculty (Olympus): As in, I give you a normal distribution, I give you another normal distribution. Even if these parameters are different, if I were to look at it in terms of quantiles, which is percentiles, percentiles always go from 0 to 100. So, in a sense, the notion of percentiles, you know, standardizes

159
00:24:30.170 --> 00:24:40.640
Faculty (Olympus): your, your distribution, okay? So what is done is, you take your distributions, whatever distribution you have, say, of the errors or residuals.

160
00:24:40.640 --> 00:24:59.439
Faculty (Olympus): And you say, you know, look at the quantiles of this. And then you take a standard distribution, say a standard normal distribution, or a log-normal distribution, or a Poisson distribution, depending on what you know, or what you expect of that, then you can compare these two in a very nice way, okay? So I'll show you some examples which will make this very clear.

161
00:24:59.600 --> 00:25:13.610
Faculty (Olympus): So the way to do this is, from scipy.stats, there is this functionality called propplot, okay, which does exactly this, okay? So what we'll do is, we'll start with a simple np.random.normal. So this we know to be normally distributed noise, 1000 points.

162
00:25:13.810 --> 00:25:22.650
Faculty (Olympus): Okay, so now what I will do is, if I run prop plot, you see that it has several arguments. It says X, which is the actual array data.

163
00:25:22.650 --> 00:25:37.629
Faculty (Olympus): And then S params is the distribution-specific shape parameter. Shape parameters is like, you know, mu and sigma and all kinds of other things, okay? And this can be supplied as a tuple, okay? And by default, the distribution it is supposed to compare itself against is

164
00:25:37.790 --> 00:25:42.120
Faculty (Olympus): the normal distribution. So if you notice, this is default argument is norm.

165
00:25:42.130 --> 00:25:56.659
Faculty (Olympus): Now, you can supply, so if you see this, the dist has, is an argument, which can either be a string, which can be a name of one of the stats. So if you remember scipy.stats, there's norm, there is Poisson, there is Bernoulli, binomial, all kinds of things are there, right?

166
00:25:56.660 --> 00:26:04.140
Faculty (Olympus): So the name of that can be used, or you can actually take stats.distribution instance, which is, you can say scipy.stats.normal.

167
00:26:04.140 --> 00:26:05.669
Faculty (Olympus): Or not now, okay?

168
00:26:06.350 --> 00:26:10.990
Faculty (Olympus): So you can use any one of either of those options.

169
00:26:12.570 --> 00:26:29.349
Faculty (Olympus): And thenâ€¦ and then the other argument that we're going to look at is the plot, okay? So if you don't supply this plot object, which could be matplotlib's PLT, for example, if you don't supply it, it will not make a plot. It'll just, you know, return some values back to you, okay? So it'll return some tuple of NPI arrays.

170
00:26:29.350 --> 00:26:37.139
Faculty (Olympus): With some theoretical quantiles and the slope and the intercept, you know, of your best fit line and things like that, okay? Butâ€¦ so let's ignore that for now.

171
00:26:37.140 --> 00:26:54.050
Faculty (Olympus): I'll just show you a simple example. So what we're going to look at is, I'm going to simply do prop plot for this data. So imagine this data is not from our nice, normal, you know, standard, normal fellow. It could be some generic data. So if I do prop plot of X, and then say plot is equal to PET, notice this.

172
00:26:54.050 --> 00:26:57.190
Faculty (Olympus): If you do not supply plot as BLT, it won't make a plot.

173
00:26:57.360 --> 00:27:01.670
Faculty (Olympus): So when I do plot as PLT, it will actually make this nice probability problem.

174
00:27:02.190 --> 00:27:14.409
Faculty (Olympus): And the expectation that we have is that when the two distributions are similar, that is, the normal distribution, in this case, because the default is dist is norm.

175
00:27:14.560 --> 00:27:18.800
Faculty (Olympus): If your X is truly normally distribution, normally distributed.

176
00:27:19.450 --> 00:27:24.170
Faculty (Olympus): This dots that you have will fall along this.

177
00:27:26.080 --> 00:27:27.000
Faculty (Olympus): Language.

178
00:27:27.310 --> 00:27:29.929
Faculty (Olympus): Okay, and this line here is yourâ€¦

179
00:27:30.290 --> 00:27:31.870
Faculty (Olympus): X is equal to Y line.

180
00:27:32.850 --> 00:27:34.150
Faculty (Olympus): Does it make sense?

181
00:27:35.720 --> 00:27:37.410
Faculty (Olympus): Okay. So now I'll show you an example.

182
00:27:37.410 --> 00:27:40.969
Abhineet Bansal: So what is the second data that we are plotting? One is X, second is?

183
00:27:40.970 --> 00:27:44.729
Faculty (Olympus): This fellow here is basically telling you what is the ideal way it should look.

184
00:27:45.640 --> 00:27:56.010
Faculty (Olympus): It should look along this line. So I'll show you another example. So I'll now not use np.normal.sorry, random.normal. I will use random.random. What is this distribution?

185
00:27:57.070 --> 00:27:59.050
Faculty (Olympus): Can you remember what distribution this is?

186
00:28:00.340 --> 00:28:01.130
Gaurav Singh .: Beautiful.

187
00:28:01.130 --> 00:28:01.930
Samar Jain .: uniform?

188
00:28:01.930 --> 00:28:08.960
Faculty (Olympus): Uniform. So it's not normally district. So let's create this and let me do a probability plot of this. Notice it looks very different.

189
00:28:10.680 --> 00:28:15.620
Faculty (Olympus): So what this is telling you is this is not at all normally distributed.

190
00:28:16.230 --> 00:28:20.619
Faculty (Olympus): Okay, so this fellow, this noise is normally, is not normally distributed.

191
00:28:20.860 --> 00:28:23.939
Faculty (Olympus): Okay, so ideally, it should have been like this, okay?

192
00:28:24.070 --> 00:28:28.050
Faculty (Olympus): On the other hand, so maybe let me show you another fellow here.

193
00:28:29.890 --> 00:28:31.200
Faculty (Olympus): No plot.

194
00:28:31.500 --> 00:28:32.530
Faculty (Olympus): Why?

195
00:28:32.660 --> 00:28:36.340
Faculty (Olympus): And say, dist equal toâ€¦ uniform.

196
00:28:37.750 --> 00:28:39.730
Faculty (Olympus): Got it, okay.

197
00:28:42.530 --> 00:28:43.459
Faculty (Olympus): Look at that.

198
00:28:44.640 --> 00:28:51.269
Faculty (Olympus): Do you see that? Now, this fellow looks exactly the same as a normal. Yes, naturally, because this isâ€¦ it was a uniform testimony.

199
00:28:51.520 --> 00:29:00.109
Faculty (Olympus): Does this make sense? So this is an extremely powerful way with which if you know that something looks like normal, and you want to be able to assert that it is normal.

200
00:29:00.240 --> 00:29:10.920
Faculty (Olympus): You know, you actually show a QQ plot, and this gives you a good idea. Now, let's come back to the first one, which is, we considered NP.random.normal, size of 1000, right?

201
00:29:11.160 --> 00:29:20.159
Faculty (Olympus): Now, notice here, even though, yeah, this part is all okay, there is some deviation here. Do I have to worry about this? Okay, so this is an important question you should ask.

202
00:29:20.280 --> 00:29:27.810
Faculty (Olympus): It's not really matching here. So is this a problem? So always look at the data. Okay. Notice that we have only thousand points.

203
00:29:28.360 --> 00:29:29.190
Faculty (Olympus): Okay.

204
00:29:29.710 --> 00:29:34.380
Faculty (Olympus): And where is this location? This is near 3rdâ€¦ Standard deviation.

205
00:29:35.140 --> 00:29:40.350
Faculty (Olympus): So it's near the third standard deviation. Once you have hit the third standard deviation.

206
00:29:40.650 --> 00:29:47.480
Faculty (Olympus): The number of fellows who should be there in that is extremely small, which means you'll have one or two people in that bin.

207
00:29:48.090 --> 00:29:53.189
Faculty (Olympus): Right? It's like less than 1%. Very few numbers you'll find in that region, maybe 10.

208
00:29:54.050 --> 00:29:56.340
Faculty (Olympus): Is that okay? And soâ€¦

209
00:29:56.490 --> 00:30:10.100
Faculty (Olympus): here, you can't really make too many conclusions. So you need to look at at least the minus 2 to plus 2, you know, where if you have, say, 100 points, you have a reasonable number of representative points, then this will make better and better sense. So, for example, if I reduce this to 100.

210
00:30:10.240 --> 00:30:15.879
Faculty (Olympus): and plotted this. See, you'll again start deviate. You'll see deviations even at this, at the rate of minus 2.

211
00:30:16.460 --> 00:30:22.669
Faculty (Olympus): Right? Because it's only 100 points. You don't really have enough points here to be able to sample the entire distribution.

212
00:30:22.900 --> 00:30:27.480
Faculty (Olympus): On the other hand, if I keep increasing this to, say, 10,000.

213
00:30:28.010 --> 00:30:34.590
Faculty (Olympus): And then look at the QQ plot. Notice now it's gone to four where the differences start showing up. Am I making sense?

214
00:30:34.630 --> 00:30:48.190
Faculty (Olympus): So, basically, if you look at the probability density function for the normal distribution, you'll notice that as you go towards the tails, the number of points you expect there are very small. And you cannot draw statistical conclusions based on those points, okay? Soâ€¦

215
00:30:48.190 --> 00:30:56.689
Faculty (Olympus): these final trailing points, you may not be able to match, right? Because you have so few points there that statistically it may not make any difference.

216
00:30:57.990 --> 00:31:14.579
Faculty (Olympus): Alright, so I hope this is clear, so please don't use many of these plots blindly. Make sure you have some understanding of what is going on, okay, before you start, you know, drawing conclusions, okay? And one thing to be aware of is, these trailing points, you need to be very careful.

217
00:31:16.290 --> 00:31:17.449
Faculty (Olympus): All right.

218
00:31:17.680 --> 00:31:32.160
Faculty (Olympus): So let me stop here for some questions. All right, before I finish that, I'll hang on, let me finish this. So here again, I'm going to make data, I'm going to do fit predict, I'm going to find sigma, and I'm going to find the standard residuals, and I'm going to do a probabilistic plot of this.

219
00:31:33.120 --> 00:31:36.860
Faculty (Olympus): Can you see that this is not bad? It is actually fairly.

220
00:31:37.030 --> 00:31:39.249
Faculty (Olympus): Reasonably excuse me around the.

221
00:31:39.800 --> 00:31:43.680
Faculty (Olympus): Standard normal, okay? Same thing here.

222
00:31:44.180 --> 00:31:48.909
Faculty (Olympus): Okay, so if I take and make it 100, it's reasonable. It's not terrible in this case.

223
00:31:49.900 --> 00:31:52.060
Faculty (Olympus): Alright, so,

224
00:31:52.250 --> 00:32:01.630
Faculty (Olympus): Alright, here's a small exercise for you. Modify the interactive example to add the QQ plot to assess the errors. So the same two plots, so you make three, one of which shows you the QQ plot.

225
00:32:02.340 --> 00:32:08.059
Faculty (Olympus): All right, so now before you move on to stats model, I will stop for some questions, Gaurav.

226
00:32:08.940 --> 00:32:16.409
Gaurav Singh .: Professor Lick, probably this section, I could not understand what we are trying to achieve from the QQ plot.

227
00:32:16.410 --> 00:32:23.520
Faculty (Olympus): You're trying to show whether the errors are normally distributed or not. And this doesn't necessarily mean for errors. It could be for anything. If I give you a data set.

228
00:32:23.780 --> 00:32:29.529
Faculty (Olympus): And you want to get a sense of, is this really normally distributed or not? A QQ plot is a good way to check. That's it.

229
00:32:30.400 --> 00:32:47.359
Gaurav Singh .: But when we see a distribution, we see on x-axis usually the occurrence of x's and their, you know, probability distribution density, right? But here, I'm seeing a straight line, like linear graph.

230
00:32:47.360 --> 00:33:00.029
Faculty (Olympus): That's what I'm trying to say. You interpret this as, if every fellow falls on the straight line, it means it's a pretty good match for your probability distribution. Sometimes it won't work, because you didn't guess the right probability distribution.

231
00:33:00.180 --> 00:33:07.979
Faculty (Olympus): But I give you some random data. How do you tell whether it's normal or not normal? How do you prove to someone else quantitatively whether this is the case? You use a QQ plot.

232
00:33:09.540 --> 00:33:10.340
Gaurav Singh .: Okay.

233
00:33:12.680 --> 00:33:15.389
Gaurav Singh .: Okay, I'll work on it. Sure.

234
00:33:15.720 --> 00:33:32.930
Faculty (Olympus): No, I don't understand this. I mean, it's a tool for you to figure out whether somethingâ€¦ otherwise you're going to just look at it and say, this looks like Gaussian, that also looks like Gaussian. You're actually not really sure of it, because you're just eyeballing the art. And this gives you a much more concrete way to establish whether two things are actually normally distributed or not.

235
00:33:33.080 --> 00:33:33.680
Gaurav Singh .: Okay.

236
00:33:34.240 --> 00:33:46.949
Faculty (Olympus): Right? Or log normal. And any one of these standard, well-known distributions, there are, like, you know, 50-plus distributions that are available in SciPy. So if you have statistical evidence that, oh, this thing should be distributed like this, you can apply that.

237
00:33:48.970 --> 00:33:49.620
Gaurav Singh .: Got it.

238
00:33:50.000 --> 00:33:50.570
Faculty (Olympus): Yeah.

239
00:33:50.800 --> 00:33:51.750
Faculty (Olympus): Rahul.

240
00:33:51.940 --> 00:33:53.940
Faculty (Olympus): Oh, you were asked at the end, no?

241
00:33:53.940 --> 00:34:03.369
Rahul Shrikrishna Joshi .: Yeah, no, no, that is a separate question, this is another one. So the noise which you mentioned here, is it the noise of that regression, the last E, or it is a general data you are referring?

242
00:34:03.610 --> 00:34:13.099
Faculty (Olympus): It is E. In this case, it's E, because basically, the other fellows are all explainingâ€¦ all of these fellows are explainingâ€¦ are explained with the parameters that we identified.

243
00:34:13.370 --> 00:34:15.780
Faculty (Olympus): The one that's left is left to noise at this point.

244
00:34:16.179 --> 00:34:21.410
Faculty (Olympus): Now, it may turn out that, as I showed you in this parabolic example, sorry, here.

245
00:34:22.210 --> 00:34:29.599
Faculty (Olympus): That noise is not just noise, there's some parameter you missed, right? So maybe there's a, you know, square term sitting somewhere there. Maybe so.

246
00:34:30.670 --> 00:34:34.030
Rahul Shrikrishna Joshi .: And then how the noise is calculated for each data point, actually?

247
00:34:34.030 --> 00:34:39.830
Faculty (Olympus): There is no noise calculated. It's just the difference between your prediction from your model and your actual value.

248
00:34:40.639 --> 00:34:41.169
Rahul Shrikrishna Joshi .: Okay.

249
00:34:41.170 --> 00:34:43.720
Faculty (Olympus): Predicting the noise. We're not predicting any noise in this case.

250
00:34:43.949 --> 00:34:47.669
Rahul Shrikrishna Joshi .: Okay, so that's the difference between the actual value and the value which is coming.

251
00:34:47.670 --> 00:34:51.280
Faculty (Olympus): So all we have is we have data, raw data, and now we have a model.

252
00:34:51.400 --> 00:35:08.860
Faculty (Olympus): You know, that can explain this data. How well can it explain the data is answered by your R squared. And now the next question is, okay, how is that noise distributed? Is there a does it have a distribution? Is it normal? Is it not normal? So you can assess that by looking at the you know QQ plot and making this use the prob plot to actually assess this.

253
00:35:10.740 --> 00:35:26.789
Rahul Shrikrishna Joshi .: And then, sorry, one more question. Can we use this, let's say, if we design some model, can we use this technique to, let's say, we get another data to validate our model? Can we use the same technique to check how the new data which has arrived is fitting well with the model we have designed?

254
00:35:27.810 --> 00:35:30.420
Faculty (Olympus): Can you repeat the question? I don't understand.

255
00:35:30.420 --> 00:35:33.630
Rahul Shrikrishna Joshi .: Sorry, let's say if you have designed some model based on the data which we have got.

256
00:35:33.630 --> 00:35:33.960
Faculty (Olympus): Mmm.

257
00:35:33.960 --> 00:35:41.540
Rahul Shrikrishna Joshi .: Whatever is a recreation. And then we get another set of the data to validate whether that model is correct or not. Sure.

258
00:35:41.540 --> 00:35:41.990
Faculty (Olympus): You can.

259
00:35:41.990 --> 00:35:42.460
Rahul Shrikrishna Joshi .: do that?

260
00:35:42.460 --> 00:35:46.000
Faculty (Olympus): You should. Yeah, in fact, that's called the test and train split.

261
00:35:46.150 --> 00:35:54.810
Faculty (Olympus): So what we've done so far is we've kind of we've not done it in the formal ML way, which we will look at in the very next set of slides.

262
00:35:54.810 --> 00:36:06.580
Faculty (Olympus): Right? So theâ€¦ now we just treat it as, okay, there is data, we'll come up with a model. But very often, what you actually have to do is, you are given some set of measurements, you will take a subset of those measurements, form your model.

263
00:36:06.580 --> 00:36:12.180
Faculty (Olympus): And then you use this model to explain the unseen data. This is called testing your model or validating your model.

264
00:36:13.140 --> 00:36:20.079
Faculty (Olympus): Okay? And then you have to assess how good is the error, how does this behave with respect to your test and train data.

265
00:36:21.250 --> 00:36:22.140
Faculty (Olympus): Okay?

266
00:36:23.910 --> 00:36:24.700
Faculty (Olympus): So then, yesâ€¦

267
00:36:24.700 --> 00:36:25.180
Rahul Shrikrishna Joshi .: What?

268
00:36:25.180 --> 00:36:25.900
Faculty (Olympus): Yeah.

269
00:36:25.900 --> 00:36:35.159
Rahul Shrikrishna Joshi .: Yeah, and the difference between predicted value and the actual value, how you got hold of all such values, the code, above?

270
00:36:35.640 --> 00:36:36.609
Faculty (Olympus): I didn't understand.

271
00:36:36.840 --> 00:36:46.170
Rahul Shrikrishna Joshi .: So this graph is the noise, right? So for each data point, there is a difference between the predicted value and actual value, right? Correct. Where you got that in the code?

272
00:36:46.170 --> 00:36:47.410
Faculty (Olympus): So this is predictive.

273
00:36:47.410 --> 00:36:48.000
Rahul Shrikrishna Joshi .: connect.

274
00:36:48.170 --> 00:36:52.410
Faculty (Olympus): This is simply predicted values minus get R squared does the difference.

275
00:36:54.040 --> 00:36:55.169
Faculty (Olympus): Wait, hang on.

276
00:36:55.350 --> 00:37:01.070
Faculty (Olympus): This is Where did I show that it is?

277
00:37:01.470 --> 00:37:03.910
Faculty (Olympus): Okay, that is in the last cell over here.

278
00:37:04.390 --> 00:37:05.130
Faculty (Olympus): Yeah.

279
00:37:07.170 --> 00:37:10.829
Faculty (Olympus): Fit predict will give me Y predict R squared and the coefficient.

280
00:37:10.970 --> 00:37:12.919
Faculty (Olympus): YN is your original data.

281
00:37:13.470 --> 00:37:16.330
Faculty (Olympus): So it's simply yn minus yp divided by sigma.

282
00:37:16.550 --> 00:37:18.660
Faculty (Olympus): That's the standardized disciplines.

283
00:37:18.860 --> 00:37:20.200
Rahul Shrikrishna Joshi .: Right, got it. Thank you, sir.

284
00:37:27.070 --> 00:37:28.220
Faculty (Olympus): Varun?

285
00:37:29.170 --> 00:37:41.219
Varun Kumar .: Professor, so can we get some questions to practice on these things? Because this need, you know, conceptualizing and visualizing things will make more sense when we actually do something.

286
00:37:41.370 --> 00:37:44.230
Varun Kumar .: Here, I'm getting some idea, but, you know, there might be.

287
00:37:44.230 --> 00:37:51.299
Faculty (Olympus): So you should pick any one of the data. You can pick any data that you have been given already. For example, look at the pendulum data and do this.

288
00:37:52.600 --> 00:37:55.810
Faculty (Olympus): Make a linear fit. So I'll be there'll be an exercise that we'll give it to you.

289
00:37:57.470 --> 00:37:58.120
Varun Kumar .: Okay.

290
00:37:59.010 --> 00:37:59.430
Faculty (Olympus): Any.

291
00:37:59.430 --> 00:38:00.410
Varun Kumar .: You already given?

292
00:38:00.860 --> 00:38:02.580
Faculty (Olympus): No, no, it'll be given to you.

293
00:38:02.910 --> 00:38:03.450
Varun Kumar .: Okay.

294
00:38:03.450 --> 00:38:11.660
Faculty (Olympus): We've not even finished the class, right? Let me finish the class and we'll give you an exercise. We will be giving you exercises. And also, please note, you can make this up by yourself.

295
00:38:12.270 --> 00:38:15.720
Faculty (Olympus): That's why I've given you all the code. If not, I'd have just given you PDF slides.

296
00:38:16.640 --> 00:38:21.270
Faculty (Olympus): In fact, the next class, the next part of this class is going to be PDF slides. There is no code.

297
00:38:21.950 --> 00:38:26.630
Faculty (Olympus): The reason I'm giving you all this code is that you should now be in a position where you can generate.

298
00:38:26.910 --> 00:38:31.780
Faculty (Olympus): Play with this, modify it. It's very important you learn to do this, and in fact.

299
00:38:32.070 --> 00:38:37.289
Faculty (Olympus): I am going to give you an exercise with which I'm going to expect you to learn on your own.

300
00:38:37.560 --> 00:38:40.000
Faculty (Olympus): And if you want.

301
00:38:40.240 --> 00:38:44.550
Faculty (Olympus): I am happy to have a session which is just doubt clearance session.

302
00:38:44.730 --> 00:38:48.420
Faculty (Olympus): Because the idea now is you should be in a position to learn stuff by yourself.

303
00:38:48.820 --> 00:38:55.080
Faculty (Olympus): When given the theory, as in the programming should not be a roadblock for you anymore. You have enough knowledge about how to do the programming.

304
00:38:55.740 --> 00:39:04.819
Faculty (Olympus): Okay, so I will just wrap this session up, and then we'll switch to some theory. And then I'll give you an actual exercise, which I'll walk through the exercise, what you're expected to do.

305
00:39:05.080 --> 00:39:20.919
Faculty (Olympus): I strongly urge you to finish this exercise, and then during this week, we willâ€¦ I can answer questions about that. Because going forward, Professor Vinay is going to basically take that approach. He's going to say, here's the theory, this is what this is, and then he'll say, here's a prompt that will generate something for you.

306
00:39:21.060 --> 00:39:23.160
Faculty (Olympus): And then you have to make sense of that prompt.

307
00:39:23.850 --> 00:39:27.119
Faculty (Olympus): He's not going to walk you through the prompt, or the result of the prompt.

308
00:39:27.470 --> 00:39:38.370
Faculty (Olympus): So now you have to transition from being okay, I know programming, I know the integrity, to actually starting, you need to know this. You need to remember your basic programming since you've not done very advanced programming, you know, very basic programming.

309
00:39:38.810 --> 00:39:49.030
Faculty (Olympus): Now you need to be able to say, I generated code, I need to be able to understand this code, because that is what Professor Vinay is going to expect. He's going to expect that any code you generate with the AI, you can explain line by line.

310
00:39:50.000 --> 00:40:00.360
Faculty (Olympus): Line by line. It's not just, vaguely, I give this prompt, and you explain that the prompt is not enough. You're not going to get, you know, marks for that. And even your end semester is going to be required like this.

311
00:40:00.670 --> 00:40:01.670
Faculty (Olympus): So.

312
00:40:02.140 --> 00:40:08.889
Faculty (Olympus): Right? So now I'm trying to get you to a point where you're comfortable doing this, and it's not really very difficult.

313
00:40:09.480 --> 00:40:11.230
Faculty (Olympus): We'll walk you through a lot of this.

314
00:40:12.650 --> 00:40:14.010
Faculty (Olympus): Alex Shraddha.

315
00:40:15.060 --> 00:40:20.260
Shraddha Aniruddha Mitragotri .: Sir, can you please quickly explain prop plot? Okay.

316
00:40:20.700 --> 00:40:31.730
Faculty (Olympus): So Kraw plot you can think of as a tool. You can go read up a little bit more about it because the statistics of this will require you to have reasonable statistics comfort.

317
00:40:32.520 --> 00:40:43.710
Faculty (Olympus): What it does is, it looks at the quantiles of a given distribution of data. So, for example, over here, I have X, right? Thisâ€¦ I can find the quantiles of X. What is a quantile?

318
00:40:44.640 --> 00:40:48.260
Shraddha Aniruddha Mitragotri .: Yeah, first 25%, and then 25, soâ€¦

319
00:40:48.650 --> 00:40:50.300
Faculty (Olympus): No, that is the Quark type.

320
00:40:50.300 --> 00:40:51.250
Shraddha Aniruddha Mitragotri .: Quartile, okay.

321
00:40:51.370 --> 00:40:52.450
Faculty (Olympus): Okay.

322
00:40:52.450 --> 00:40:52.930
Shraddha Aniruddha Mitragotri .: I.

323
00:40:52.930 --> 00:40:55.240
Faculty (Olympus): Right? So it's like, think of it like.

324
00:40:55.670 --> 00:40:56.810
Faculty (Olympus): percentiles.

325
00:40:56.920 --> 00:40:58.139
Faculty (Olympus): Okay, I give you.

326
00:40:59.430 --> 00:41:08.970
Faculty (Olympus): 1%, 2%, 3%, 4%, Right? 25 percentile isâ€¦ happens to be yourâ€¦ Quarterly.

327
00:41:09.280 --> 00:41:16.759
Faculty (Olympus): So any one of these quantiles essentially says what fraction of the population is to the left of this particular value that you have, right?

328
00:41:17.890 --> 00:41:25.630
Faculty (Olympus): So if I were to take your random whatever data that you have supplied, in this case, I've generated it from this, right, normal distribution.

329
00:41:26.180 --> 00:41:39.249
Faculty (Olympus): Now, I know the normal distribution, and I know the quantiles that there should be there, so if I give you the perfect normal distribution, and say, you know, what fraction of the population should be left of zero, standard normal? It's 50%.

330
00:41:40.050 --> 00:41:58.310
Faculty (Olympus): Right? With your data, it may not be 50%, maybe 49, 51, because, you know, it's a sample. It's not the full data. So what is done here is, it takes whatever distribution you have proposed. In this case, by default, it is a normal distribution. It plots that as the theoretical quantiles.

331
00:41:58.700 --> 00:42:03.279
Faculty (Olympus): And then here it plots the ordered values from your actual data.

332
00:42:05.410 --> 00:42:09.579
Faculty (Olympus): And therefore you can compare these 2 fellows nicely.

333
00:42:10.500 --> 00:42:14.620
Faculty (Olympus): And they should actually lie on this vertical, on this line.

334
00:42:15.440 --> 00:42:21.259
Faculty (Olympus): On this, sorry, X is equal to Y line, if they are the same distribution.

335
00:42:24.890 --> 00:42:25.939
Shraddha Aniruddha Mitragotri .: Okay, got it.

336
00:42:25.990 --> 00:42:28.099
Faculty (Olympus): So, for example, if I give you

337
00:42:28.810 --> 00:42:38.699
Faculty (Olympus): If I tell you that elephant's weight is normally distributed, human beings' weight is normally distributed. Obviously, they're not exactly the same distribution, but they're both normal distributions, let's assume.

338
00:42:39.880 --> 00:42:55.810
Faculty (Olympus): the actual values are different. The elephant average weight might be, you know, 2 tons. Human average weight might be 60 kilos. I don't know, okay? They're very different quantities. But if I were to take these two and try to compare them, it's very hard for you to compare them, right? If you do a QQ plot.

339
00:42:55.900 --> 00:43:03.679
Faculty (Olympus): Right? You can assert that, hey, the elephant is also like a standard normal, this fellow is also like a standard normal. When you rescale it and plot it in terms of percentiles.

340
00:43:03.800 --> 00:43:07.020
Faculty (Olympus): The distribution of how this varies is going to look exactly the same.

341
00:43:07.250 --> 00:43:11.110
Faculty (Olympus): Because percentile is just between 1 and 100 or 0 and 100.

342
00:43:11.620 --> 00:43:12.890
Faculty (Olympus): Am I making sense?

343
00:43:13.040 --> 00:43:24.830
Faculty (Olympus): So you've kind of thrown away all the variation in the actual data. You're only looking at how the shape behaves. And what this allows you to do is to compare these two shapes, and if they fall on the X is equal to Y line, it tells you that they are

344
00:43:25.080 --> 00:43:26.900
Faculty (Olympus): Very likely the same distribution.

345
00:43:27.050 --> 00:43:30.880
Faculty (Olympus): as in the nature. The functional form of that distribution is normal.

346
00:43:34.980 --> 00:43:36.529
Faculty (Olympus): Does that answer your question? Okay.

347
00:43:36.530 --> 00:43:37.289
Shraddha Aniruddha Mitragotri .: Yes, thank you.

348
00:43:38.500 --> 00:43:49.690
Gaurav Singh .: Yeah, Professor, it's very clear that QQ plot, what it does. Just wondering, like, what was the negative values in theâ€¦ because quantile, can it be negative?

349
00:43:49.690 --> 00:43:54.020
Faculty (Olympus): No, no, no, no. So here again, it's trying toâ€¦

350
00:43:54.320 --> 00:43:58.759
Faculty (Olympus): So it is trying to relate this to the, you know, to your normal distribution.

351
00:43:58.980 --> 00:44:06.519
Faculty (Olympus): If you want to order it that way, then you're just shifting the origin, basically. So that you have a sense ofâ€¦ see, if I didn't give you this information.

352
00:44:06.970 --> 00:44:12.959
Faculty (Olympus): If I didn't give you minus 4, minus 3, I cannot tell you that, look, this is actually 4 standard deviations away from your mean.

353
00:44:13.840 --> 00:44:14.590
Gaurav Singh .: Okay.

354
00:44:14.590 --> 00:44:25.390
Faculty (Olympus): Right? So this actually gives you some insight as to where this fellow is. Otherwise, you'll be like, you know, it doesn't make sense, right? So if I give you 10,000 values, and they're actually, you know, different at the third quantile, then you have a problem.

355
00:44:26.240 --> 00:44:27.640
Gaurav Singh .: Soâ€¦

356
00:44:27.640 --> 00:44:32.930
Faculty (Olympus): It sort of gives you a sense of where to look. So it recasts that data in terms of your original.

357
00:44:33.080 --> 00:44:34.679
Faculty (Olympus): In terms of the standard now.

358
00:44:35.580 --> 00:44:45.660
Gaurav Singh .: And basically QQ plot is comparing similar kind of distribution and data and the data which we think that it follows the similar kind of distribution we are comparing.

359
00:44:45.660 --> 00:44:54.880
Faculty (Olympus): Right. So for example, look here, you know, the ordered values here are all at zero. This is actually telling you the ordered values in this case. They're all at zero and they go till about one. In fact, they stop off at one.

360
00:44:55.000 --> 00:45:02.559
Faculty (Olympus): Correct. Right? So this is telling you thatâ€¦ so this ordered values is going to be the right set of values. Here, this is always going to tell you in terms of the standard norm.

361
00:45:02.770 --> 00:45:04.110
Gaurav Singh .: Standard.

362
00:45:04.350 --> 00:45:09.470
Faculty (Olympus): Right? As in standard normals appropriately translated to 0.5 in this case.

363
00:45:10.080 --> 00:45:10.650
Gaurav Singh .: Good.

364
00:45:11.550 --> 00:45:13.150
Gaurav Singh .: Yeah. Okay.

365
00:45:13.470 --> 00:45:14.900
Faculty (Olympus): Yeah, sure.

366
00:45:16.820 --> 00:45:19.069
Faculty (Olympus): Rahul, very quickly, huh? Becauseâ€¦

367
00:45:19.070 --> 00:45:25.750
Rahul Shrikrishna Joshi .: Yes, yeah, here only, sir. Why we are, sorry, subtracting 2 from here in calculation of sigma?

368
00:45:26.930 --> 00:45:30.760
Faculty (Olympus): Yeah. You do this in your stats course. You lose 2 degrees of freedom, basically.

369
00:45:34.340 --> 00:45:36.490
Rahul Shrikrishna Joshi .: Is it the first and the last point, actually?

370
00:45:36.900 --> 00:45:44.100
Faculty (Olympus): No, no, no, not first and last. It's just like, how do you subâ€¦ why did you remove, N-1 for sample variance?

371
00:45:44.390 --> 00:45:45.620
Faculty (Olympus): Why did you do that?

372
00:45:48.230 --> 00:45:50.800
Rahul Shrikrishna Joshi .: Something to do with the degree of freedom, but don't.

373
00:45:50.800 --> 00:45:57.840
Faculty (Olympus): Yeah. Exactly. So the degree of freedom was you estimated the sample mean using the same data. So you lost one degree of freedom.

374
00:45:59.280 --> 00:46:03.899
Faculty (Olympus): So here you're estimating two parameters. They're explained alpha and beta, A and B.

375
00:46:05.450 --> 00:46:06.650
Faculty (Olympus): That's one way to think about it.

376
00:46:06.650 --> 00:46:07.960
Rahul Shrikrishna Joshi .: Okay, okay, got it, yeah.

377
00:46:08.510 --> 00:46:15.270
Faculty (Olympus): Okay. And then you're estimating sigma with whatever is left with the same data. And so you lose one more degree of freedom. You lose two degrees of freedom.

378
00:46:15.270 --> 00:46:19.460
Rahul Shrikrishna Joshi .: You're making the Sigma worst, in other words, like just to, I would say.

379
00:46:19.460 --> 00:46:25.839
Faculty (Olympus): No. You used n points. You've already determined two constants, so you've lost two points.

380
00:46:27.150 --> 00:46:28.410
Rahul Shrikrishna Joshi .: Got it, got it, Surya.

381
00:46:28.410 --> 00:46:33.830
Faculty (Olympus): Right? So you don't really have endpoints anymore. You have only n minus one from which you're estimating sigma. Right?

382
00:46:33.960 --> 00:46:40.000
Faculty (Olympus): So, this, again, actually is a good thing you asked me this question. Now, supposing I had a multilinear model.

383
00:46:41.790 --> 00:46:42.660
Faculty (Olympus): Right?

384
00:46:43.140 --> 00:46:50.630
Faculty (Olympus): You have a multilinear model, then you have to be very careful, because you're no longer estimating two parameters, you're estimating multiple parameters.

385
00:46:51.490 --> 00:46:59.170
Faculty (Olympus): So you will have to probably, you know, subtract out the R quantities that you have, or K plus 1 quantities that you have.

386
00:47:00.570 --> 00:47:06.279
Faculty (Olympus): Okay, so this is where you get into what's called the adjusted R-squared, okay, which I urge you to take a look at.

387
00:47:07.370 --> 00:47:08.250
Faculty (Olympus): Later on.

388
00:47:08.970 --> 00:47:10.020
Faculty (Olympus): Alright, soâ€¦

389
00:47:10.020 --> 00:47:15.049
Abhineet Bansal: For the exam, are we expected to remember these formula the way you calculated Sigma and everything else?

390
00:47:15.050 --> 00:47:17.320
Faculty (Olympus): Oh.

391
00:47:18.960 --> 00:47:36.939
Faculty (Olympus): No, the way we calculatedâ€¦ no, no, no, no, no, sorry. No, this is not a stat score, so no, I'm not going to expect you to remember all that. What I will expect you to be able to do is solve this, which is why the next part is very important, I want to finish this. I give you a linearâ€¦ I give you, say, some data, and I say fit a linear model to it.

392
00:47:37.990 --> 00:47:47.819
Faculty (Olympus): So, which is why using stats models is useful. I will give you exercises on how to learn how to do this also, and sorry, I will, you know, I'll show you how to do this here.

393
00:47:48.000 --> 00:47:52.420
Faculty (Olympus): And I will also show you how to use Scikit-learn.

394
00:47:55.050 --> 00:47:58.899
Faculty (Olympus): Rahul, I'm not going to answer your question now. We'll come back to your question, okay?

395
00:47:58.900 --> 00:47:59.709
Rahul Shrikrishna Joshi .: Yeah, that's fine, yeah.

396
00:48:00.410 --> 00:48:19.329
Faculty (Olympus): So, the next step is, how do you solve the same thing with stats models? So here, if you notice, I set up all of this, you know, all of this code based on basic theory, right? Stats models is a very powerful package that allows you to do a lot of these things very easily, but it also gives you a whole bunch of additional statistics here.

397
00:48:20.460 --> 00:48:29.849
Faculty (Olympus): And it lets you do lots of other things, including modeling parameters that are not numerical. As in, for example, let's say you have categorical variables.

398
00:48:30.230 --> 00:48:42.470
Faculty (Olympus): Those also can be modeled, using stats models. But we're not going to look at that at this stage. I will show you that. You canâ€¦ I'll give you an exercise where you self-learn this. I'll provide that for you later.

399
00:48:42.510 --> 00:48:50.469
Faculty (Olympus): But let's first start with stats models for our existing data, right? And our data was this pendulum data. I'm just going to use that as a toy example here.

400
00:48:50.510 --> 00:48:55.239
Faculty (Olympus): So I create this data frame, Pandas data frame, where I have L list.

401
00:48:55.360 --> 00:49:04.840
Faculty (Olympus): the EL, which is the length. I have time, T, and I have T squared, which also is simply T times T. Okay, we've calculated this. So now I create this data frame.

402
00:49:05.910 --> 00:49:07.900
Faculty (Olympus): Oh, I did not run this.

403
00:49:09.060 --> 00:49:09.980
Faculty (Olympus): So let's see.

404
00:49:13.240 --> 00:49:15.479
Faculty (Olympus): The problem with notebooks.

405
00:49:18.230 --> 00:49:19.060
Faculty (Olympus): Cheers.

406
00:49:20.490 --> 00:49:24.219
Faculty (Olympus): Okayâ€¦ sorry, I'm gonna scroll, scroll, scroll, okay.

407
00:49:24.360 --> 00:49:26.379
Faculty (Olympus): So let's create this data frame.

408
00:49:26.670 --> 00:49:38.379
Faculty (Olympus): That's good. Now, in stats models, there are many ways to do this, and once again, going forward, it is very likely that you will not be generating, barring the mid-semester, you're not going to be generating this code.

409
00:49:38.380 --> 00:49:57.900
Faculty (Olympus): you know, AI will probably spit out this code, but that's okay. So, import statsmodel.api as SM. Again, this is a standard way of doing the imports. And then there's statsmodels.formula as SMF, okay? Now, these are just imports. They are useful because they allow you to specify the model in a very structured fashion.

410
00:49:58.090 --> 00:50:05.440
Faculty (Olympus): So, the first thing we have here is we construct a model where we are saying.

411
00:50:05.640 --> 00:50:09.189
Faculty (Olympus): T squared is linearly proportional to L.

412
00:50:09.270 --> 00:50:27.629
Faculty (Olympus): And implicitly, there is also a constant involved, okay? So it is not said here, whenever you write this notation, this notation actually comes from R's notation. So stats models basically allows you to write in R kind of syntax. I hope all of you know about the R programming language, which is really very strong in statistics.

413
00:50:27.630 --> 00:50:35.249
Faculty (Olympus): And they have this formula, this notion of writing a formula, which encapsulates a relationship between multiple quantities.

414
00:50:35.580 --> 00:50:48.119
Faculty (Olympus): So what this proportionality sign says is these are related, so T squared is related to L, okay? And the data for this is in this data frame, and notice that these variables that you have here

415
00:50:48.440 --> 00:50:53.349
Faculty (Olympus): L and T squared are variables from the columns of this data frame.

416
00:50:54.820 --> 00:51:05.280
Faculty (Olympus): So now, to do this ordinary least squares, what they call ordinary least squares, you simply say SMF.OLS, apply the formula, give it the data, and then you simply say model.fit.

417
00:51:05.350 --> 00:51:15.220
Faculty (Olympus): And boom, you're finished your linear regression. Now, obviously, this is the most simple linear regression. You can also do, you know, encode variables that are

418
00:51:15.450 --> 00:51:16.439
Faculty (Olympus): As I said.

419
00:51:16.580 --> 00:51:31.780
Faculty (Olympus): you know, binary variables, all kinds of things can be encoded with, you know, stats models, but I'm notâ€¦ the idea for me is to just expose you to this simple API that you can use. I will show you a more fancy API, you know, during the exercises, which I will share with you by end of the day.

420
00:51:32.120 --> 00:51:34.980
Abhineet Bansal: But what kind of relationship you're not defining, sir?

421
00:51:34.980 --> 00:51:35.700
Faculty (Olympus): Nina.

422
00:51:35.970 --> 00:51:39.249
Faculty (Olympus): There's this T squared is proportional to L, that's all.

423
00:51:39.250 --> 00:51:41.989
Abhineet Bansal: Inversely proportional or proportional or something like that.

424
00:51:41.990 --> 00:51:44.160
Faculty (Olympus): No, no, this is not inversely, this is directly from.

425
00:51:44.160 --> 00:51:45.260
Abhineet Bansal: Directly proportional.

426
00:51:45.260 --> 00:51:45.630
Faculty (Olympus): Yes.

427
00:51:45.630 --> 00:51:46.150
Abhineet Bansal: Okay.

428
00:51:46.620 --> 00:51:50.009
Faculty (Olympus): Right, okay, so this is, so good question because

429
00:51:50.450 --> 00:51:53.889
Faculty (Olympus): This is telling you that there's a proportionality relationship.

430
00:51:54.350 --> 00:52:07.910
Faculty (Olympus): Okay? And it is distinctly not 1 by L. So if you want to introduce 1 by L, then you have to construct another variable here, say, you know, 1 by L or something like that, and then stick it in and say 1 by L, or whatever, that name of that variable.

431
00:52:08.380 --> 00:52:11.410
Faculty (Olympus): Okay? So it's just saying, it's a linear relationship between these quantities.

432
00:52:12.260 --> 00:52:31.250
Faculty (Olympus): Okay, now the nice thing is, when you do results.summary, it will give you a lot of these results. And these are all statistical results. They will tell you the dependent variable is this, how was it modeled? This is done with least squares. Okay, number of observations was 90, number of residuals was 88, the degrees of freedom.

433
00:52:31.250 --> 00:52:37.340
Faculty (Olympus): Okay, then what is the R squared? What is the adjusted R squared? Okay, so the adjusted R squared is very important.

434
00:52:37.340 --> 00:52:55.730
Faculty (Olympus): this is the F statistic, then the probability related to that F statistic, log likelihood, AIC, blah blah blah, okay? And also, it'll tell you the same thing with respect to the intercepts and the slope, okay? So the coefficient for the intercept that you get, it also tells you what's called a p-value. Have you done p-values in your stats course?

435
00:52:57.460 --> 00:52:58.609
Abhineet Bansal: Not yet, sir.

436
00:52:58.610 --> 00:53:02.410
Faculty (Olympus): Okay, you will do this. So the point is, this fellow will tell you

437
00:53:02.410 --> 00:53:06.470
Faculty (Olympus): The p-value of these quantities. So this will make more sense when you finish more of your stats.

438
00:53:06.470 --> 00:53:23.659
Faculty (Olympus): But the important thing is it gives you a lot of these statistical information. Some of it is too much. You know, you may be like, why do I need all of this? That's okay, don't worry about it. So what I've done is I've sort of shown you, quickly listed out some of the most common ones that you will find useful.

439
00:53:23.810 --> 00:53:27.559
Faculty (Olympus): Okay, so it tells you the p-values and tells you the confidence intervals.

440
00:53:30.500 --> 00:53:37.420
Faculty (Olympus): Okay? And then the F statistic, for example, is indicative if the independent variables are an effect or not, which means

441
00:53:37.640 --> 00:53:43.320
Faculty (Olympus): Supposing you have something which has no contribution to the actual final value.

442
00:53:43.470 --> 00:54:00.100
Faculty (Olympus): you know, then the p-value for that will be actually not so small. It'll be a larger value, okay? And also, this is the confidence interval for the parameter. So, this intercept, you know, there's a 95% confidence interval is between 0.032 and 0.115, and the slope

443
00:54:00.440 --> 00:54:17.469
Faculty (Olympus): the confidence interval is between 4.073 and 4.2. I hope you remember what these confidence intervals are. So you can thinkâ€¦ you can actually numerically obtain these by doing bootstrapping. You take the same data, you resample, make another plot, you'll get a new set of coefficient and intercept.

444
00:54:17.470 --> 00:54:30.320
Faculty (Olympus): You repeat this CIA 10,000 times, and then read off your 25 percentile and 97, you know, 97.5 percentile, sorry, read off your 2.5 percentile and 97.5 percentile, that gives you the confidence interval.

445
00:54:30.570 --> 00:54:50.359
Faculty (Olympus): Okay, so it tells you where yourâ€¦ all ofâ€¦ remember, all of these parameters that you're determining, this A and B, the estimators, are all statistical quantities, which means they will themselves have probability density functions, as in they will also have a distribution associated with them. And therefore, I can read off, you know, confidence intervals, saying, you know, 80% of the data, or 95% of the data lies in the center.

446
00:54:50.810 --> 00:54:57.470
Faculty (Olympus): Okay, so that is what this is trying to tell you, this confidence interval for these parameters.

447
00:54:58.490 --> 00:55:07.289
Faculty (Olympus): And so here again, if the probability for your F statistic for one of these parameters, is basicallyâ€¦ so these are, you know, if it's.

448
00:55:07.560 --> 00:55:13.320
Faculty (Olympus): If it isâ€¦ probability is not less than 0.005, then it's not, you know, not a very good effect.

449
00:55:13.500 --> 00:55:17.020
Faculty (Olympus): And then there are several what are called omnibus statistics, which

450
00:55:17.280 --> 00:55:27.259
Faculty (Olympus): tell you about the normality of the residuals, okay? So if they are close to zero, it means they are perfectly normal, but almost never will they be, you know, perfectly zero.

451
00:55:27.670 --> 00:55:33.569
Faculty (Olympus): So, similarly, there's this Durbin-Watson, which tells you between, you know, the residuals, if you have multilinear regression.

452
00:55:33.770 --> 00:55:36.839
Faculty (Olympus): You know, it'll tell you whether they're correlated and things like that.

453
00:55:36.950 --> 00:55:45.579
Faculty (Olympus): Okay, so for now, you can maybe ignore this, you can come back to this. When you do your ML, you know, your ML course, maybe they'll cover this, but in your statistics, they'll probably cover this.

454
00:55:47.810 --> 00:55:52.259
Charu Sidana .: So, sorry for interrupting, Professor, so this will not be part of midterm exam.

455
00:55:53.120 --> 00:55:55.719
Faculty (Olympus): Regression will absolutely be part of the midterm exam.

456
00:55:56.100 --> 00:56:02.609
Faculty (Olympus): But all these crazy statistics that we have here that you do not understand, I'm not going to expect that you'll be able to.

457
00:56:02.760 --> 00:56:12.280
Faculty (Olympus): But the bare minimum you should be able to understand. For example, what is the intercept? What does this, you know, confidence interval of this mean? You should have at least an intuitive understanding from the numerical pointer.

458
00:56:12.400 --> 00:56:20.720
Faculty (Olympus): I'm not going to ask you to take pen and paper and prove something and do some integrals and something, or, you know, look at distributions. That is your stats course, that's not this course.

459
00:56:21.060 --> 00:56:28.839
Faculty (Olympus): I may ask you to do something by doing, say, numerical evaluation of some things using probabilistic programming, because we spent one and a half classes on that.

460
00:56:28.990 --> 00:56:29.320
Charu Sidana .: Yeah.

461
00:56:29.320 --> 00:56:38.669
Faculty (Olympus): And you've done many exercises. So that's my expectation, that you understand the basics. You know how to create QQ plots. That is absolutely necessary.

462
00:56:38.840 --> 00:56:47.590
Faculty (Olympus): Right? But I'm definitely not going to quiz you on AIC, BIC, you know, tell me what is this value, what is the interpretation of this value, I'm not going to ask you about that.

463
00:56:48.790 --> 00:56:53.169
Faculty (Olympus): But I will certain there will definitely be one problem which is going to be regression.

464
00:56:53.850 --> 00:56:55.040
Faculty (Olympus): Okay, so.

465
00:56:55.230 --> 00:56:57.030
Faculty (Olympus): You should know your regression method.

466
00:56:57.380 --> 00:57:05.830
Faculty (Olympus): Which is why, you know, next, even though I've done 3 extra classes, I'm happy to, you know, have a doubt-clearing session before your Mitsavasarita next week sometime.

467
00:57:06.540 --> 00:57:11.920
Faculty (Olympus): All right, so Soumen Gaurav very quickly because I have

468
00:57:12.570 --> 00:57:14.500
Faculty (Olympus): A lot of material to finish.

469
00:57:14.500 --> 00:57:22.580
Soumen Deb .: Yeah, sorry. So, just wanted to understand the formula that you punched in, CSQ tilde L, that's like.

470
00:57:22.580 --> 00:57:40.569
Faculty (Olympus): Yeah, so to learn this again, you can read the stats model documentation. I am not going to expect you to do this. I'm not going to expect you to know our formulas, right? Because there are lots of nuances here. For example, if you have categorical variables, you have to encode them. You have to basically say C of something.

471
00:57:40.590 --> 00:57:46.449
Faculty (Olympus): Right? There areâ€¦ it's not very difficult, but since I have not spent too much time, I'm not going to expect her to do it, butâ€¦

472
00:57:46.930 --> 00:57:54.540
Faculty (Olympus): Supposing you're given an exercise, like a homework exercise, I would expect that you'll be able to read the stats model documentation and construct your own formula.

473
00:57:56.590 --> 00:57:57.460
Faculty (Olympus): Okay.

474
00:57:57.990 --> 00:58:00.710
Soumen Deb .: And you've done only simple regression yet.

475
00:58:00.710 --> 00:58:02.200
Faculty (Olympus): I want it on simple encryption.

476
00:58:02.500 --> 00:58:04.280
Soumen Deb .: Tipal is not done yet, so fine.

477
00:58:04.280 --> 00:58:10.039
Faculty (Olympus): Multiple is justâ€¦ is the same thing, right? There's nothing much to be done, but it's, again, very easy.

478
00:58:10.550 --> 00:58:13.479
Faculty (Olympus): We'll come to this. I'll give you an exercise where you do all of this.

479
00:58:14.820 --> 00:58:15.659
Soumen Deb .: Fine, thank you.

480
00:58:15.660 --> 00:58:30.819
Faculty (Olympus): is not going to give you too much insight that is different from this, but it's very easy to do. And that's why I want to quickly get to scikit-learn, where it's like, you can do the same thing. And you can do the same thing here also. You have multiple variables. So let's say you have something else. You have L andâ€¦

481
00:58:32.000 --> 00:58:33.679
Faculty (Olympus): See, you can actually do this.

482
00:58:34.140 --> 00:58:37.930
Soumen Deb .: Correct. So what's the difference between the two libraries that we have always beenâ€¦ so you have.

483
00:58:37.930 --> 00:58:38.590
Faculty (Olympus): So the staff.

484
00:58:38.590 --> 00:58:38.990
Soumen Deb .: Much more.

485
00:58:38.990 --> 00:58:44.030
Faculty (Olympus): will give you a lot of statistical information by default. It'll give you all of this stuff.

486
00:58:44.310 --> 00:58:51.670
Faculty (Olympus): Okay? Scikit-learn will not give you those kind of statistics. It'll just do the fitting and tell you, okay, here are your coefficients.

487
00:58:53.020 --> 00:58:59.260
Faculty (Olympus): It's not going to give you all of the statistical information, because it's not aâ€¦ it's not really focused on statistics, psychically.

488
00:58:59.810 --> 00:59:00.530
Faculty (Olympus): It's an ML book.

489
00:59:00.530 --> 00:59:01.070
Soumen Deb .: Okay.

490
00:59:01.670 --> 00:59:02.480
Soumen Deb .: Okay.

491
00:59:02.480 --> 00:59:10.130
Faculty (Olympus): Rest of the stuff that we've done before in this class is to show you that the building blocks of regression are already there in SciPy and NumPy.

492
00:59:10.430 --> 00:59:11.330
Faculty (Olympus): That's all.

493
00:59:12.820 --> 00:59:27.850
Faculty (Olympus): And that gives you an easier understanding. If I just say, okay, this is Scikit-learn, here is the model, it's very straightforward. You just run it, you'll get something. But you won't understand anything about how it is actually constructed. That's why I spent a lot of time on the understanding part of regression, because this is your first entry point into regression.

494
00:59:28.190 --> 00:59:32.899
Faculty (Olympus): Even before your stats course does it, then your stats course is going to do it in a more theoretical fashion.

495
00:59:33.060 --> 00:59:44.699
Faculty (Olympus): Right? And then next, when you start, when Professor Vinay starts doing it, he'll just say, regression, and that's it. So then, if you just treat it as a black box, you'll have to have any understanding. My goal here was to take simple regression.

496
00:59:44.900 --> 00:59:47.039
Faculty (Olympus): And get you to understand the basics.

497
00:59:48.700 --> 00:59:49.390
Soumen Deb .: Okay.

498
00:59:51.340 --> 00:59:52.690
Faculty (Olympus): Okay, Gaurav?

499
00:59:53.900 --> 00:59:57.289
Gaurav Singh .: Yeah, I think most of the questions answered from.

500
00:59:57.290 --> 01:00:05.539
Faculty (Olympus): Okay, great, fine. So I'll, let's hold off questions. I'm now going to show you Scikit-Learn, okay? And the Scikit-Learn is an extremely popular library.

501
01:00:05.610 --> 01:00:21.980
Faculty (Olympus): And it provides a ton of MML methods to use, many of which I'm not going to discuss, but Professor Vinay will be discussing a lot of these. And the expectation is that you will use AI to generate, but you really need to understand how Scikit-Learn is constructed. So I'm going to set this up in the context of

502
01:00:22.560 --> 01:00:28.989
Faculty (Olympus): Regression. And please remember, regression is ML, right? It's your baby version of ML, if you will.

503
01:00:36.920 --> 01:00:41.709
Faculty (Olympus): So, when we did regression, I'll just quickly, sort of, point out something here.

504
01:00:42.530 --> 01:00:44.669
Faculty (Olympus): When we did this fit and predict.

505
01:00:44.910 --> 01:00:47.500
Faculty (Olympus): This fitting is like training your.

506
01:00:48.150 --> 01:00:58.020
Faculty (Olympus): your ML, okay? You give it data, you train it, and that fellow spits out some constants. That constants allow you to predict, because now I have a model, okay?

507
01:00:58.190 --> 01:01:03.819
Faculty (Olympus): So ML is basically a more generalized version. It's the same thing, right? But

508
01:01:04.200 --> 01:01:10.149
Faculty (Olympus): The underlying model may not be a straight line, might be an extremely complicated model. It could be a neural network. Okay.

509
01:01:11.070 --> 01:01:19.510
Faculty (Olympus): But the underlying idea is the same. You're essentially learning to find some constants for a specific model using the data.

510
01:01:19.860 --> 01:01:22.199
Faculty (Olympus): Okay, that's really what you're doing.

511
01:01:22.710 --> 01:01:33.110
Faculty (Olympus): And as a result, the Scikit learns API, as in how you call it to set up a model, is pretty much the same regardless of what the underlying model is.

512
01:01:33.320 --> 01:01:40.730
Faculty (Olympus): So I'm going to show this with linear regression, and I'm going to spend a little bit of time, say 10 minutes on this, so that you understand how this API works.

513
01:01:41.630 --> 01:01:50.369
Faculty (Olympus): So, once again, Scikit-learn, first thing, is requires data in the form of a particular shape of your data, okay?

514
01:01:50.850 --> 01:01:58.279
Faculty (Olympus): And there are two main functions that you will use. You will first create a model, okay, let's call it model, the object model.

515
01:01:58.550 --> 01:02:05.350
Faculty (Olympus): You will call it with fit X and Y, where X is your independent variables and Y is your dependent variables, okay?

516
01:02:05.720 --> 01:02:09.810
Faculty (Olympus): Once you have done this, you have essentially trained your model with the data.

517
01:02:10.460 --> 01:02:14.800
Faculty (Olympus): Then given any other set of x values, independent variables.

518
01:02:14.990 --> 01:02:22.249
Faculty (Olympus): You can say model.predict, which is exactly why I use the same kind of aâ€¦ Same kind of functions earlier, okay?

519
01:02:23.480 --> 01:02:36.979
Faculty (Olympus): Now, here what we have is our X-rays in the form of a 2D array. So theâ€¦ when Scikit-learn works, it is going to expect that this X has the form of a two-dimensional array of the following shape. Number of samples.

520
01:02:37.250 --> 01:02:38.850
Faculty (Olympus): And the number of variables.

521
01:02:39.260 --> 01:02:42.560
Faculty (Olympus): Which means I have N rows and N columns.

522
01:02:44.430 --> 01:02:47.749
Faculty (Olympus): Okay, and so the n columns will be

523
01:02:49.430 --> 01:02:54.750
Faculty (Olympus): So each row corresponds to one measurement, and each of those is going to be some set of values.

524
01:02:55.740 --> 01:03:04.550
Faculty (Olympus): Now, in our linear model, We had T squared versus L. I have only one Very good.

525
01:03:04.960 --> 01:03:08.520
Faculty (Olympus): Okay. And so we had just 90 values of L. Okay.

526
01:03:08.730 --> 01:03:11.810
Faculty (Olympus): And the y values was the t squared. You remember this?

527
01:03:12.300 --> 01:03:18.559
Faculty (Olympus): A prediction we had lengths of the pendulum, and I have the time period of oscillation of the pendulum. Okay, time period of oscillation is

528
01:03:18.770 --> 01:03:28.590
Faculty (Olympus): the dependent variable. The length of the problem is the independent variable. So my X quantity, which is the independent variable, is just one column of L values, 90 values, right?

529
01:03:28.970 --> 01:03:33.039
Faculty (Olympus): So we have the shape to be 90 comma, but it should be 90 comma 1.

530
01:03:33.470 --> 01:03:37.169
Faculty (Olympus): Because that is how scikit-learn expects the data to be.

531
01:03:37.840 --> 01:03:48.220
Faculty (Olympus): So, what we'll do is I'll now walk you through the code of how to set up linear regression with Sanket. So, first thing is, we'll instantiate the model, which is linear regression. So I just say, create the model.

532
01:03:48.580 --> 01:03:55.379
Faculty (Olympus): And then I'm going to say L reshape minus 1, 1. This minus 1 is useful because it says.

533
01:03:55.580 --> 01:03:57.220
Faculty (Olympus): Everything before this.

534
01:03:57.520 --> 01:04:03.200
Faculty (Olympus): Okay? I don't need to say 90 or whatever. When you say minus 1, it says, okay, it's the full data. It's everything that there is.

535
01:04:03.480 --> 01:04:06.290
Faculty (Olympus): And then you say 1 here, it is basicallyâ€¦

536
01:04:06.440 --> 01:04:15.260
Faculty (Olympus): Going to reshape. Okay, so when we do this, I will run this. Notice that L shape is 90 km. I could have also done this as 90.

537
01:04:16.070 --> 01:04:17.729
Faculty (Olympus): But instead, you can do minus 7.

538
01:04:18.750 --> 01:04:19.660
Faculty (Olympus): Okay?

539
01:04:19.870 --> 01:04:27.510
Faculty (Olympus): Now my data is in the required shape. T squared is going to be just a one-dimensional array. X is in this shape of 90,1.

540
01:04:28.180 --> 01:04:31.079
Faculty (Olympus): And now I can call modern topic. Yes, yes, Varun.

541
01:04:33.070 --> 01:04:42.240
Varun Kumar .: Yeah, Professor, so this one I did not understand why we are doing minus 1 to 1, because you just said that we can do by 90 comma. Are we doing some NumPy things here?

542
01:04:42.240 --> 01:04:47.790
Faculty (Olympus): Yes. When you give me reshape of minus one, it basically will assume the existing length.

543
01:04:50.180 --> 01:04:52.340
Varun Kumar .: Okay, so it is the same thing what weâ€¦

544
01:04:52.340 --> 01:04:58.369
Faculty (Olympus): Because otherwise, then I have to say len of L and all of this, right? So you just say minus one, it's the same thing.

545
01:04:58.920 --> 01:04:59.650
Varun Kumar .: Okay.

546
01:04:59.650 --> 01:05:01.210
Faculty (Olympus): Okay, otherwise I'm gonna put 90.

547
01:05:03.100 --> 01:05:05.060
Faculty (Olympus): There's nothing, this is just standard NumPy.

548
01:05:07.780 --> 01:05:08.680
Faculty (Olympus): Okay?

549
01:05:09.170 --> 01:05:11.830
Rahul Shrikrishna Joshi .: Sir, can we do transpose also in this case to getâ€¦ to achieve that?

550
01:05:12.200 --> 01:05:15.219
Faculty (Olympus): No, no, please, Rahul, you try this yourself, okay?

551
01:05:15.460 --> 01:05:16.070
Rahul Shrikrishna Joshi .: Okay.

552
01:05:17.390 --> 01:05:24.950
Faculty (Olympus): I think the answer was already answered in the NumPy notebook, but okay, look at this. So now, model.fit L, T squared.

553
01:05:26.380 --> 01:05:35.629
Faculty (Olympus): There's another way to do this also that I discussed in Non-Numpy, right? You can add a new axis. It's fine. Anyway, so now I do model.fit L and T squared.

554
01:05:36.810 --> 01:05:38.369
Faculty (Olympus): L and T squared.

555
01:05:39.270 --> 01:05:45.110
Faculty (Olympus): Now it has basically finished fitting this, and it'll also spit out the parameters. It says, okay, it fits the intercept.

556
01:05:45.220 --> 01:05:59.639
Faculty (Olympus): And it, you know, some information about the parameters of the linear regression model. And now, if I want to predict some values, I can just give it some set of values. In this case, I want the L values themselves, and say, predict these values. So I say, okay, fine, like that, give me the predictions.

557
01:06:00.250 --> 01:06:06.180
Faculty (Olympus): And now I do PLT.scatter LT squared, and then plot the predicted values in red.

558
01:06:06.830 --> 01:06:08.769
Faculty (Olympus): We get our same old fellow.

559
01:06:09.200 --> 01:06:16.200
Faculty (Olympus): Okay? If you want to look at the coefficients, you can say print model.cof and model.intercept. Cof is going to be the linear.

560
01:06:16.960 --> 01:06:20.739
Faculty (Olympus): And this intercept is going to be that constant. And notice it's the same value.

561
01:06:21.430 --> 01:06:24.030
Faculty (Olympus): Okay? But the key thing here isâ€¦

562
01:06:24.410 --> 01:06:28.190
Faculty (Olympus): Scikit-learn has many, many models. Okay.

563
01:06:29.000 --> 01:06:36.010
Faculty (Olympus): All of them will have the same structure. You shape your data so that it is of this form, n sample, n variables.

564
01:06:36.130 --> 01:06:39.050
Faculty (Olympus): And then you call fit, you call predict, and you're done.

565
01:06:39.860 --> 01:06:58.670
Faculty (Olympus): Is that okay? So using Scikit-learn is actually very easy. All you need to know is which model to choose, how to interpret these models, you know, and how to choose between these models, right? For linear regression, we have seen that if I give you two models, and I give you one has a larger R-squared than the other, the larger R-squared model is a better model, okay?

566
01:06:59.140 --> 01:07:16.190
Faculty (Olympus): Right? So, in similar fashion, if I give you two different models, right, you need mechanisms by which you can test them, okay? But the thing is, Scikit-learn makes it super easy for you to try this, try different models, right? And so if you ask AI to say, okay, give me a linear model for this, use this, use this, use this, use that.

567
01:07:16.190 --> 01:07:25.289
Faculty (Olympus): It'll actually do all the work for you, and then your job now becomes assessing these models, which is why you need to understand things like R-squared and, you know, how do you assess these models.

568
01:07:26.120 --> 01:07:28.510
Faculty (Olympus): Alright, so is the API simple?

569
01:07:28.510 --> 01:07:33.259
Abhineet Bansal: Last time you've written model is equal to linear regression, is thatâ€¦ Why is that necessary, sir?

570
01:07:33.930 --> 01:07:36.630
Faculty (Olympus): I mean, how else are you going to create a modem?

571
01:07:37.110 --> 01:07:40.800
Abhineet Bansal: Okay, so you're telling the system that this is a linear regression we're initiating.

572
01:07:41.300 --> 01:07:41.940
Faculty (Olympus): Yes.

573
01:07:42.080 --> 01:07:48.369
Faculty (Olympus): Okay. Just like, how do you create, say, a normal distribution? Scipoi.stats, you'll import something, and then you'll instantiate it, right?

574
01:07:49.310 --> 01:07:54.599
Abhineet Bansal: And this same term model that you've used, this variable is then used for fit and predict.

575
01:07:54.600 --> 01:08:00.000
Faculty (Olympus): Yes. So I've created, so this is an object, which is an instance of this linear regression model.

576
01:08:00.450 --> 01:08:01.250
Faculty (Olympus): Right?

577
01:08:01.490 --> 01:08:04.150
Faculty (Olympus): Now you can just call fit on it, and then predict.

578
01:08:04.680 --> 01:08:09.840
Faculty (Olympus): And you can keep calling predict. We have some more data, you predict, because your model is now set. It stored the values of the model.

579
01:08:10.320 --> 01:08:11.490
Faculty (Olympus): Does it make sense?

580
01:08:11.670 --> 01:08:16.289
Abhineet Bansal: And we need to store that predict value into some variable, or we could have directly used that on the plot.

581
01:08:16.290 --> 01:08:17.190
Faculty (Olympus): Yeah, you can.

582
01:08:17.290 --> 01:08:18.839
Faculty (Olympus): Not directly. That's fine.

583
01:08:19.149 --> 01:08:19.689
Abhineet Bansal: Sure.

584
01:08:20.390 --> 01:08:21.060
Akondi Vyasa Sai Ashish Kumar .: Professor Smith.

585
01:08:21.060 --> 01:08:29.569
Faculty (Olympus): So the rest of this is just Python. There is nothing, no fancy business here. The only thing is this is somebody, someone has carefully written this model for you, which does all this work.

586
01:08:29.970 --> 01:08:36.109
Faculty (Olympus): Right? The only thing you need to remember is that this is the API that you must use. To train your model, you just do model.fit.

587
01:08:36.220 --> 01:08:47.299
Faculty (Olympus): To predict from the model, you just do model.predict, right? Create the model, fit, predict, fit, predict. And when you fit, the data has to have this structure, which is n sample, n variables. That's how your X has to be.

588
01:08:47.420 --> 01:08:53.820
Faculty (Olympus): This is the only thing you have to do. Then, of course, there are refinements. Now, you want to do, you know, you know, you want to create features.

589
01:08:54.120 --> 01:09:09.549
Faculty (Olympus): Then there's something, there's a scikit-learn API called Pipeline API, and what I'm going to do now is, I'm going to talk about some theory, and then we'll walk through an example, which I'm going to give you as an exercise, that I want toâ€¦ I'm expecting you to self-learn this.

590
01:09:09.550 --> 01:09:18.339
Faculty (Olympus): And this is important for two reasons. One is, you will get the confidence that, hey, I can read documentation now and actually figure this out, or read a book and figure this out.

591
01:09:18.490 --> 01:09:21.990
Faculty (Olympus): Right, which is now a confidence builder for you. Second thing is.

592
01:09:22.100 --> 01:09:27.189
Faculty (Olympus): This is how it is going to be henceforth, right? No one is going to handhold you with every single piece.

593
01:09:27.290 --> 01:09:33.110
Faculty (Olympus): Now it is going to beâ€¦ you need to read the code, you need to understand it, because now that should not be a problem at this stage.

594
01:09:33.560 --> 01:09:35.090
Faculty (Olympus): Okay, Soumen?

595
01:09:35.210 --> 01:09:39.060
Faculty (Olympus): Very quickly, because I'm done with this notebook, I'm gonna set up.

596
01:09:39.060 --> 01:09:39.380
Soumen Deb .: gonna.

597
01:09:39.380 --> 01:09:40.180
Faculty (Olympus): Yes.

598
01:09:40.189 --> 01:09:57.049
Soumen Deb .: No, no, so the shape that you had, created, if you go up there on the matrix multiplications, can you just explain on how the variables are set? So if you go to reâ€¦ go a little bit up, where you had created.

599
01:09:57.479 --> 01:10:00.889
Soumen Deb .: this, snell, butâ€¦

600
01:10:01.340 --> 01:10:04.329
Faculty (Olympus): Oh no, so this was different. Here we had L and a constant.

601
01:10:05.100 --> 01:10:05.900
Soumen Deb .: Okay.

602
01:10:06.640 --> 01:10:09.060
Soumen Deb .: So it is notâ€¦ it's not related to that, soâ€¦ okay.

603
01:10:09.060 --> 01:10:14.629
Faculty (Olympus): Well, it is in a sense related, but you didn't need to encode this constant because in our linear regression model.

604
01:10:14.780 --> 01:10:17.940
Faculty (Olympus): There is an additional parameter called intercept.

605
01:10:18.610 --> 01:10:21.169
Faculty (Olympus): Okay, fit intercept. By default, it is true.

606
01:10:21.300 --> 01:10:25.499
Faculty (Olympus): Which means it'll internally create that one array for you. You don't have to worry about it.

607
01:10:26.590 --> 01:10:27.250
Soumen Deb .: Okay.

608
01:10:27.410 --> 01:10:43.200
Faculty (Olympus): All you're giving it is, here are my variables, right? My length. So if you have a multilinear model, nothing will change. You'll just say your n sample, n variables. So let's say you have x, y, z, you know, a, b, c. You have three variables. You'll get a you'll get a NumPy array of that shape.

609
01:10:44.150 --> 01:10:47.050
Faculty (Olympus): In fact, in principle, this could even be a data frame.

610
01:10:48.280 --> 01:10:48.740
Soumen Deb .: Yeah.

611
01:10:48.740 --> 01:10:53.859
Faculty (Olympus): Okay, you can also make it with a data frame. So I'll show you the example, we'll walk you through this, right?

612
01:10:53.860 --> 01:10:54.540
Soumen Deb .: Okay, fine.

613
01:10:54.540 --> 01:10:57.939
Faculty (Olympus): Okay, and what this will do is, it'll tell you,

614
01:10:59.070 --> 01:11:07.700
Faculty (Olympus): Make sure that your X is going to be of this shape. N sample and variance. That's it. And this N can be truly anything. You can have 90 variables.

615
01:11:08.350 --> 01:11:09.289
Faculty (Olympus): It's okay.

616
01:11:09.530 --> 01:11:14.410
Faculty (Olympus): This is a bad model, but it's fine, right? You can construct something. Is this clear?

617
01:11:14.600 --> 01:11:18.450
Faculty (Olympus): But the API is just this create model, fit, predict.

618
01:11:19.560 --> 01:11:26.340
Akondi Vyasa Sai Ashish Kumar .: Professor, can you just explain the significance of that reshape, the minus one used in the reshape, function call?

619
01:11:26.340 --> 01:11:28.969
Faculty (Olympus): Okay, if you don't like it, just put 90 here.

620
01:11:29.710 --> 01:11:30.670
Faculty (Olympus): Same thing.

621
01:11:30.960 --> 01:11:37.309
Akondi Vyasa Sai Ashish Kumar .: OK, so you mean to like all the all the variables, like the entire array you want to include, that's why you.

622
01:11:37.310 --> 01:11:41.530
Faculty (Olympus): Yeah. And if you don't like that either, I can also say L is equal to EL.

623
01:11:41.830 --> 01:11:42.830
Faculty (Olympus): Poland.

624
01:11:47.070 --> 01:11:48.010
Faculty (Olympus): Same thing.

625
01:11:48.340 --> 01:11:50.170
Akondi Vyasa Sai Ashish Kumar .: Okay, okay, okay, thank you.

626
01:11:51.090 --> 01:11:52.799
Faculty (Olympus): So this is just NumPy magic.

627
01:11:54.830 --> 01:12:02.050
Akondi Vyasa Sai Ashish Kumar .: So, it just takes the, like, last element, and then we reshape it, like, we, interchange rows and columns, that's what.

628
01:12:02.230 --> 01:12:06.120
Faculty (Olympus): No. It's just it's basically reshaping it to 90,1 instead of just 90,1.

629
01:12:06.120 --> 01:12:07.039
Akondi Vyasa Sai Ashish Kumar .: Oh, okay, okay.

630
01:12:07.920 --> 01:12:08.840
Abhineet Bansal: Yeah.

631
01:12:08.840 --> 01:12:14.789
Faculty (Olympus): Think of it as row and column, but Iâ€¦ again, as I said, NumPy is not row-column. NumPy is an array library.

632
01:12:15.290 --> 01:12:17.649
Faculty (Olympus): For us, convenience, yeah, 90 comma 1.

633
01:12:21.740 --> 01:12:25.369
Abhineet Bansal: Or we can just use none also here in the second line.

634
01:12:25.830 --> 01:12:26.380
Faculty (Olympus): Yeah.

635
01:12:26.930 --> 01:12:28.760
Abhineet Bansal: No, no, instead of new access.

636
01:12:28.760 --> 01:12:29.420
Faculty (Olympus): Yes.

637
01:12:30.330 --> 01:12:32.779
Faculty (Olympus): Yeah, there are hundreds of ways we can do this.

638
01:12:33.330 --> 01:12:39.680
Faculty (Olympus): Right? And somebody else said you can do transpose, you can't quite do transpose. I already showed you that you can't do transpose.

639
01:12:39.680 --> 01:12:42.459
Abhineet Bansal: It doesn't work with a linear single line.

640
01:12:42.460 --> 01:12:49.630
Faculty (Olympus): Yes, I showed you this as a specific example in the past. I know it's a lot of material, but I did spend some time on this. Ashish.

641
01:12:50.130 --> 01:13:05.089
Ashish Kumar .: Yes, sir, I just have a doubt, since, thisâ€¦ we use this linear regression model because we knew that the relationship between L and T squared is proportional. If the data was, something else, then we would have chosen another, model.

642
01:13:06.310 --> 01:13:08.949
Faculty (Olympus): So, one second, let me just,

643
01:13:21.660 --> 01:13:23.470
Faculty (Olympus): Yeah. Can you repeat your question, please?

644
01:13:23.470 --> 01:13:30.599
Ashish Kumar .: Yes, sir. The question was, we created the model linear regression because we knew that the relation between L and T squared is proportional.

645
01:13:30.780 --> 01:13:31.840
Ashish Kumar .: That's why.

646
01:13:32.030 --> 01:13:32.810
Faculty (Olympus): Yep.

647
01:13:33.240 --> 01:13:36.550
Faculty (Olympus): If food isâ€¦ Okay. That is correct.

648
01:13:36.870 --> 01:13:40.699
Ashish Kumar .: So if the relationship was something else, we have to choose another model.

649
01:13:40.700 --> 01:13:41.350
Faculty (Olympus): Yes.

650
01:13:42.130 --> 01:13:42.900
Ashish Kumar .: Okay, sir.

651
01:13:48.870 --> 01:13:54.050
Faculty (Olympus): The Zoom window goes off somewhere, so if I change somethingâ€¦ Weâ€¦

652
01:13:59.130 --> 01:14:05.239
Faculty (Olympus): Back toâ€¦ Okay, everyone is here, so nothing shared.

653
01:14:08.680 --> 01:14:17.089
Faculty (Olympus): Yeah, so, as you said, the modeling depends on the modeler, right? So you need to have some knowledge. This is why it's not saying black box model, okay?

654
01:14:20.070 --> 01:14:21.720
Faculty (Olympus): All right, so.

655
01:14:23.790 --> 01:14:27.249
Faculty (Olympus): I don't know how much how far I will get along in this, you know.

656
01:14:27.390 --> 01:14:32.319
Faculty (Olympus): Set of slides, butâ€¦ I'll try to make some progress here.

657
01:14:32.920 --> 01:14:35.560
Abhineet Bansal: Very frankly, sir, all this is scaring us right now.

658
01:14:35.700 --> 01:14:36.070
Faculty (Olympus): assuming.

659
01:14:36.070 --> 01:14:38.239
Abhineet Bansal: This will be part of the midterm also.

660
01:14:40.140 --> 01:14:41.850
Faculty (Olympus): Yeah, we shouldn't get worried about this.

661
01:14:45.010 --> 01:14:50.830
Varun Kumar .: The way we started the class initially for small things, we spent a lot of time, but this is one is.

662
01:14:51.340 --> 01:14:52.950
Varun Kumar .: It's going little fast.

663
01:14:53.330 --> 01:15:03.800
Faculty (Olympus): Yes, it will go fast. When it goes to Professor Dinay, it'll go even faster. There will be no coding examples. No one will show you anything about code. You'll be expected to be, like, experts in coding.

664
01:15:04.690 --> 01:15:06.640
Faculty (Olympus): So anyway.

665
01:15:07.350 --> 01:15:13.109
Faculty (Olympus): Alright, so the idea here is, again, you need to understand how to use these programming models.

666
01:15:13.250 --> 01:15:18.070
Faculty (Olympus): So, one of the key things here isâ€¦ I will give you an exercise, so don't worry.

667
01:15:18.480 --> 01:15:29.879
Faculty (Olympus): If you're good in your basics, there will be some programming questions. If you spoke to the exam, don't worry too much. There will be certain programming questions. There will also be some regression-related material. There will be some scikit-learn.

668
01:15:29.880 --> 01:15:40.979
Faculty (Olympus): Right? And I will give you a workbook where you're supposed to go and systematically work it out, and there will be a TA session slash I can also come and answer any doubts before your mid-semester. So don't worry so much about it.

669
01:15:41.360 --> 01:15:59.280
Faculty (Olympus): It's important that you learn to shift away from this, you know, thing that everything is given to you, you're given lots and lots of examples, because when you're actually working on realistic problems, you're not going to get 100 problems, right? When you're doing your ML course, main ML course, you will not have 100 problems. You'll be havingâ€¦ this is the theory, this is it.

670
01:15:59.720 --> 01:16:07.789
Faculty (Olympus): Here is maybe one problem, two problems, and here's some exercise, and that's it. That's how it's going to go, which is exactly how we are doing it. In fact, I have spent a lot of time

671
01:16:07.930 --> 01:16:12.589
Faculty (Olympus): Working through the programming aspects to sort of tell you, hey, this is the connections to basic programming.

672
01:16:12.780 --> 01:16:22.769
Faculty (Olympus): But now, we leave that behind. Now we're saying, okay, there is thisâ€¦ you understand, basically, what regression does, and now here's an API with which you give this thing, it'll set it up.

673
01:16:22.930 --> 01:16:29.160
Faculty (Olympus): And now I'll give you some exercises for this, so thatâ€¦ so don't panic, don't worry about it. It's actually very simple.

674
01:16:37.440 --> 01:16:38.910
Faculty (Olympus): All right, so,

675
01:16:39.720 --> 01:16:42.929
Faculty (Olympus): This is against Han theory, I'm going to skip some of this stuff.

676
01:16:43.140 --> 01:16:48.350
Faculty (Olympus): So today our main focus will be regression and classification because they're very related to each other.

677
01:16:48.540 --> 01:16:53.010
Faculty (Olympus): But before we move ahead, you know, there's this very nice definition of what we mean by machine learning.

678
01:16:53.740 --> 01:16:59.560
Faculty (Olympus): Soâ€¦ It says a computer program is set to learn from experience E.

679
01:17:00.200 --> 01:17:02.279
Faculty (Olympus): With respect to some set of tasks.

680
01:17:02.550 --> 01:17:18.210
Faculty (Olympus): T and performance measure P. If its performance in tasks in T as measured by P improves with experience, okay? So it's maybe a little pithy, but the idea is you give it experience, which means you give it data for some set of tasks. You have a specific performance metric.

681
01:17:18.360 --> 01:17:23.050
Faculty (Olympus): Which means you measure, like, say, R squared, okay? And I give you more data, right?

682
01:17:23.180 --> 01:17:24.000
Faculty (Olympus): Ifâ€¦

683
01:17:24.240 --> 01:17:42.100
Faculty (Olympus): your performance, which is your R-squared, is improving as I supply more data for it, you know, then it is learning. So that's what the definition of machine learning is inâ€¦ according to something. So it's a nice way to think about this, which connects the math and connects the idea of what machine learning is.

684
01:17:43.270 --> 01:17:44.180
Faculty (Olympus): Now.

685
01:17:44.600 --> 01:17:50.030
Faculty (Olympus): Before we get into, you know, the content of this, have you looked at these

686
01:17:50.230 --> 01:17:53.629
Faculty (Olympus): You know, scales of measurements, have they covered this in your stats course?

687
01:17:54.030 --> 01:17:54.510
Mayank Johri .: Noted.

688
01:17:55.910 --> 01:17:57.750
Soumen Deb .: We have an idea.

689
01:17:57.750 --> 01:18:05.279
Faculty (Olympus): Some idea already. So nominal basically means it's only a name, right? Tamil Nadu, Maharashtra, Karnataka.

690
01:18:05.590 --> 01:18:22.850
Faculty (Olympus): Right? Uttar Pradesh, Mathe Pradesh. They're names. There's no sense of an order with respect to the name itself, right? You may then say, no, population-wise, there's an order. Literary rate might, there's an order. No. I'm just saying the name itself does not mean anything in terms of a measurement. It's just a name, okay?

691
01:18:23.160 --> 01:18:26.340
Faculty (Olympus): So there is, there are variables which are like name.

692
01:18:26.480 --> 01:18:27.430
Faculty (Olympus): Yeah, like.

693
01:18:27.540 --> 01:18:30.300
Faculty (Olympus): Car brand, right? It could be, like, Toyota.

694
01:18:31.090 --> 01:18:32.820
Faculty (Olympus): BMW, right?

695
01:18:33.920 --> 01:18:38.369
Faculty (Olympus): My Indra, whatever it is. So each of these is just a name.

696
01:18:39.070 --> 01:18:43.019
Faculty (Olympus): So these are so I may have a column of data which just has these names.

697
01:18:43.230 --> 01:18:44.220
Faculty (Olympus): I like.

698
01:18:45.040 --> 01:18:47.199
Faculty (Olympus): Tendulkar Kohli and stuff like that.

699
01:18:47.500 --> 01:18:52.989
Faculty (Olympus): Then you have what are called ordinal, you know, where there is some idea of a ranking.

700
01:18:53.110 --> 01:18:58.040
Faculty (Olympus): You can say poor, you know, Prabhu's class was poor, was okay.

701
01:18:58.540 --> 01:19:03.409
Faculty (Olympus): Good. Excellent. Right? So you have some four or five different rankings that you can apply.

702
01:19:03.560 --> 01:19:21.200
Faculty (Olympus): These are called ordinal, but the numbers there are not necessary. The difference between two numbers doesn't really mean much, okay? It just tells you there is an ordering, but, you know, you may not be able to assign, like, a value to one of these numbers, and that number is kind of notional, okay?

703
01:19:21.450 --> 01:19:36.649
Faculty (Olympus): And even the difference, like, the difference between poor and good may not be the same as the difference between good and excellent, right? That number may not be different. So, okay, so those are other kinds of variables, they're called ordinal. There is an implicit ranking and order, but the number doesn't mean nothing.

704
01:19:36.970 --> 01:19:42.350
Faculty (Olympus): Then there comes these quantities called interval quantities. So, for example, if you look at.

705
01:19:43.410 --> 01:19:46.950
Faculty (Olympus): The measurement of temperature in terms of a centigrade.

706
01:19:47.420 --> 01:19:50.189
Faculty (Olympus): A centigrade is not like an absolute measurement.

707
01:19:50.900 --> 01:19:52.890
Faculty (Olympus): It's not like absolute temperature.

708
01:19:53.370 --> 01:19:59.569
Faculty (Olympus): Okay? So, for example, 40 degrees centigrade is not twice as hot as 20 degrees centigrade.

709
01:20:00.300 --> 01:20:15.329
Faculty (Olympus): Right? Colloquially, you may say, it's twice as hot, but actually, if you look at the thermodynamics, it's not twice, right? Because it's actually 273 Kelvin is zero. That is absolute zero. So the absolute zero temperature Kelvin, for example, will be what's called a ratio quantity.

710
01:20:15.500 --> 01:20:23.749
Faculty (Olympus): Right? Where you can take ratios of quantities, and it makes sense to take ratios of quantities. That is, right? So, for example, in ratio quantities.

711
01:20:24.090 --> 01:20:33.329
Faculty (Olympus): there is a notion of an absolute zero. In absolute zero, there is no temperature, basically, right? Whereas at zero degrees centigrade or zero degrees Fahrenheit.

712
01:20:33.780 --> 01:20:47.429
Faculty (Olympus): That zero does not mean there is no temperature. Temperature does not exist in here. It is some value of temperature, you have arbitrarily set some zero quantity, okay? So these are four different kinds of measurement quantities that you will encounter in your data. Okay.

713
01:20:49.660 --> 01:20:56.479
Faculty (Olympus): So we need to keep this in mind when we are going to look at regression vis-a-vis classification.

714
01:20:56.900 --> 01:21:14.530
Faculty (Olympus): So, when we talk about machine learning, there are typically four kinds of, or three kinds of broad classes of things that you look at. Supervised learning, unsupervised, and reinforcement learning, okay? And so, in this course, we'll probably be touching on drip-supervised learning in the form of classification and regression, and we will also touch upon unsupervised learning.

715
01:21:14.580 --> 01:21:17.400
Faculty (Olympus): Pravinay will touch upon. I won't do that, so don't worry.

716
01:21:17.460 --> 01:21:21.170
Faculty (Olympus): This is not there for mid-semester, right? I'm just telling you broadly, this is what works.

717
01:21:21.500 --> 01:21:26.799
Faculty (Olympus): Now, when you're learning, when you're doing machine learning, not you learning, machines learning.

718
01:21:26.950 --> 01:21:43.070
Faculty (Olympus): The idea is you want to use a model to make predictions, okay? So, for example, in our case of regression, what we had was we had Y is some F of X, okay? And in our specific example, we had F of X was equal to alpha plus beta X, right? And we had estimators for alpha and beta.

719
01:21:43.560 --> 01:21:44.410
Faculty (Olympus): Okay.

720
01:21:44.660 --> 01:21:54.289
Faculty (Olympus): Now, this model, for example, when you see, this is an interpretable model. Why? Because I know it is a straight line, I have a consâ€¦ you know, I have a constant plus a slope, right? So you can actually interpret this model.

721
01:21:54.490 --> 01:22:03.610
Faculty (Olympus): But you may also have models that are black box, right? So, for example, your LLM models are some, you know, some 40 billion parameters, or 1 trillion parameter model.

722
01:22:03.690 --> 01:22:16.110
Faculty (Olympus): It's not an interpretable model in that sense. You and I cannot understand what the hell it means because there are so many parameters and there's no intuitive way to understand what one parameter will do with respect to the other parameters. Okay, there are just too many of them.

723
01:22:16.290 --> 01:22:26.000
Faculty (Olympus): Okay? And most of these models, the idea is you're trying to learn some sort of a mapping, okay, which isâ€¦ which takes values for X and spits out some value of Y.

724
01:22:26.000 --> 01:22:40.379
Faculty (Olympus): And you're trying to learn what F is. That is really all what machine learning is really trying to do. And to do this under the covers, probability theory is used very often to understand or to make sense of how this happens. That's why you're learning probability theory in, you know, the other course.

725
01:22:40.490 --> 01:22:49.289
Faculty (Olympus): So when we look at supervised learning specifically, what you're learning is some function f, which is given some inputs x, and which spits out some outputs y.

726
01:22:49.420 --> 01:22:59.319
Faculty (Olympus): Okay? The inputs are either called features, covariates, predictors, independent variables, and the outputs are called either labels or target or responses. Yes?

727
01:22:59.950 --> 01:23:07.740
Faculty (Olympus): So when you train a model using a given data, you end up with something that looks like this. And remember, this looks exactly like what we had for scikit-learn's fit.

728
01:23:07.840 --> 01:23:13.660
Faculty (Olympus): That X fellow was, you had this X is a set of you

729
01:23:14.200 --> 01:23:20.939
Faculty (Olympus): Input variables and y is your output variables, okay, so now you have n of these for every measurement.

730
01:23:21.050 --> 01:23:26.800
Faculty (Olympus): For every data point, we have some set of values, X, and some potential outputs, Y, okay?

731
01:23:27.350 --> 01:23:32.679
Faculty (Olympus): When you do training, In the machine learning model, we are also doing fitting, okay?

732
01:23:32.750 --> 01:23:52.290
Faculty (Olympus): And there are many ways to do this, and there are many different kinds of models. So, some people pejoratively call machine learning just glorified curve fitting, right? It's just like your best fit line, but instead of having some, you know, linear or parabolic model, you have some ridiculously complicated or not so complicated, okay? But at the end of the day, that's really what you're doing, okay? Well, of course.

733
01:23:52.370 --> 01:23:57.210
Faculty (Olympus): How do you assess these models? That is really what you'll be learning in the second half of this course.

734
01:23:57.440 --> 01:24:11.199
Faculty (Olympus): So in the context of something very specific that we learned today is in the context of linear regression. When we found those parameters A and B for the linear model, that is called training. That formula that you derived and you got.

735
01:24:11.430 --> 01:24:21.130
Faculty (Olympus): When you plug in the values of Xi and Yi into that formula, you calculated, you know, SXX, XY, SYY, all of that stuff. Then you did this, you got this formula.

736
01:24:21.260 --> 01:24:36.560
Faculty (Olympus): That process is called training. It just turns out that in our case, we had an explicit way of calculating that because we solved that system of linear equations. So it's the easiest way to do ML is a linear regression or this sort of a regression process is an easy way to do it.

737
01:24:37.160 --> 01:24:48.069
Faculty (Olympus): With neural networks, it's just a lot more complicated, because what you have is, you have some objective function, you have an optimizer, and that fellow is optimizing using some algorithm called backpropagation, you know? So.

738
01:24:48.150 --> 01:25:01.829
Faculty (Olympus): At the high level, they're doing the same thing. It's just that for linear regression, I can solve this in one shot. In one instant, I can solve it. So, doing the training process for all of these complicated models is taking a lot of time, but for a linear regression, it's like that.

739
01:25:03.080 --> 01:25:03.900
Faculty (Olympus): No.

740
01:25:04.040 --> 01:25:12.840
Faculty (Olympus): Given new input to compute a new response is what is called inference in ML Tanagarjan.

741
01:25:13.000 --> 01:25:19.690
Faculty (Olympus): Okay, so when someone say, I'm running inference, it means they've trained, they've gotten all their parameter values, so they have this function.

742
01:25:19.910 --> 01:25:22.310
Faculty (Olympus): which is given an input, it will spit out a value of it.

743
01:25:22.670 --> 01:25:33.589
Faculty (Olympus): So that is all you're really doing at the highest level. So this is very important that you understand this is really ML from 40,000 foot. So if you want to say, explain ML in, like, two lines, this is what you're doing.

744
01:25:35.290 --> 01:25:38.389
Faculty (Olympus): All right, now let's get to specifics.

745
01:25:38.540 --> 01:25:41.129
Faculty (Olympus): When we look at supervised learning and regression.

746
01:25:41.710 --> 01:25:45.890
Faculty (Olympus): Y that you have the output variable is either an interval or ratio quantity.

747
01:25:46.190 --> 01:25:56.970
Faculty (Olympus): Which means it's some numerical value. It is not a label. It is not a name. It is not something like, you know, good, bad, ugly, whatever, right? It's not any of those things. It is.

748
01:25:57.260 --> 01:26:01.549
Faculty (Olympus): A number which is either an interval or a ratio, those kind of outputs.

749
01:26:02.020 --> 01:26:05.230
Faculty (Olympus): Are suitable for regression problems, okay.

750
01:26:05.940 --> 01:26:23.740
Faculty (Olympus): the input F, whatever is X, whatever goes into X, can be any one of these quantities, and I've not yet told you how to do that. I will show you in the very few slides, I will show you how you can actually encode quantities that are not numerical in your linear regression or non-linear regression models, okay?

751
01:26:24.500 --> 01:26:31.790
Faculty (Olympus): Now, to actually model this F, there are very many ways, okay? The simplest thing that we looked at was a linear model.

752
01:26:32.000 --> 01:26:35.269
Faculty (Olympus): And we also looked at a polynomial model, right, for f.

753
01:26:35.770 --> 01:26:48.089
Faculty (Olympus): And then there are things called support vector machines, which, again, you will probably encounter in Professor Vinay's course, as well as tree-based methods. All of these are just methods of constructing an F.

754
01:26:48.760 --> 01:27:03.509
Faculty (Olympus): Okay? And then, finally, you will have deep neural networks, where this F is just a deep neural network, which is just a stack of matrix, vector, multiply, nonlinear operator, one more operating on this, so it's composition of functions. So it's F of G of H of X, kind of like that.

755
01:27:03.540 --> 01:27:23.149
Faculty (Olympus): That's what a DNN is. So, at the end of the day, all regression is just doing this. Y is equal to F of X. The models differ in what this F of X is. For us, it was alpha X plus B, or beta naught plus beta 1X1 plus beta 2X2, dot dot dot, to beta RXR. That is a linear model. Polynomial will be just X plus, you know, constant X squared, so on and so forth.

756
01:27:23.340 --> 01:27:31.049
Faculty (Olympus): Right? And then you can compose more complicated fellows with just these two, right? Then you have support vector machines, then you have tree-based methods and DNS.

757
01:27:32.350 --> 01:27:41.360
Faculty (Olympus): When it comes to classification, your output is a set of labels or classes, and that's the major differentiation between regression and classification.

758
01:27:41.650 --> 01:27:48.679
Faculty (Olympus): So instead of having an interval or ratio quantity, you have something which is like, you know, good, bad.

759
01:27:48.790 --> 01:28:00.379
Faculty (Olympus): Okay? Or you have something which is just a label, right? This is a cat, this is a dog. These are all called classification problems, okay? So, which means Y is essentially what's called a categorical nominal slash ordinal variable.

760
01:28:00.380 --> 01:28:12.099
Faculty (Olympus): This is also called pattern resolution, and if the category is only two, you know, you want to find whether the fellow is going to get out or not get out, okay, success or failure, then it becomes a binary classification, okay?

761
01:28:12.130 --> 01:28:25.059
Faculty (Olympus): So, given an image of an English letter, identify it, right? This becomes a multi-level classification problem, not just binary, okay? Given an image, identify it, okay? Similarly, identify the boundary between two classes of parameters, you know, based on the parameters.

762
01:28:25.210 --> 01:28:26.710
Faculty (Olympus): Also, a classification.

763
01:28:28.830 --> 01:28:29.660
Faculty (Olympus): All good.

764
01:28:30.150 --> 01:28:37.460
Faculty (Olympus): So, for classification, again, there are many methods. There is logistic regression, which I will quickly touch upon.

765
01:28:37.570 --> 01:28:51.780
Faculty (Olympus): Then there are tree-based methods, classification and regression trees, random forest, gradient boosted methods, support vector classification, neural networks. All of these can be used. So just like you have regression having several different methods.

766
01:28:51.780 --> 01:29:00.520
Faculty (Olympus): Classification will also have several different. Okay, and once again, the basic form is just the same. Y is equal to f of x. In the classification case, y is labels.

767
01:29:00.520 --> 01:29:04.100
Faculty (Olympus): In the non-classification case, Y is, you know, numbers.

768
01:29:04.130 --> 01:29:05.599
Faculty (Olympus): Basically, that's what we have.

769
01:29:07.410 --> 01:29:13.269
Faculty (Olympus): Okay Gaurav I will I have only about five minutes so I'll have to finish here anyway

770
01:29:13.520 --> 01:29:20.319
Faculty (Olympus): And then I do have a couple of videos that I will share with you that you can see at your leisure. Again, just

771
01:29:21.790 --> 01:29:23.240
Faculty (Olympus): You can see this for your.

772
01:29:23.460 --> 01:29:29.879
Faculty (Olympus): learning, and I think Professor Vinay will also recover some of this material. But anyway, I will give you that also.

773
01:29:30.290 --> 01:29:36.179
Faculty (Olympus): Alright. So, when you look at an AI that is being trained.

774
01:29:36.390 --> 01:29:46.850
Faculty (Olympus): How does this work? So what you first do is you identify some sort of a loss function. And if you say F is some mapping that you're trying to learn, it could be linear regression, for example.

775
01:29:47.100 --> 01:29:59.359
Faculty (Olympus): So you have the input variables, and you have these thetas, which are the parameters. So for in our example, it was A and B, or alpha beta, or beta naught beta 1, beta 2. So these are all the quantities you're trying to learn in some functional form.

776
01:29:59.590 --> 01:30:11.220
Faculty (Olympus): So what you do is you set up the total loss of your system. This was our SSR, which is 1 by n, i equal to 1 to n, sum, loss function for each fellow, this is the true value, this is your predicted value.

777
01:30:12.420 --> 01:30:18.570
Faculty (Olympus): Okay? This is exactly what we had. So we had capital YI minus A plus BXI. That was our loss function squared.

778
01:30:18.780 --> 01:30:21.220
Faculty (Olympus): So that is the mean squared error.

779
01:30:21.490 --> 01:30:32.850
Faculty (Olympus): Okay. And then when you train it, you find the best parameters theta. And this is denoted mathematically as the arg min theta for this loss function L.

780
01:30:33.650 --> 01:30:47.810
Faculty (Olympus): Okay, so you basically find the model parameters that produce the least loss. And now, depending on what kind of loss function you use, you know, and, you know, what kind of parameters you use, and what kind of model you use, you get all these different ones.

781
01:30:49.640 --> 01:30:51.200
Faculty (Olympus): Okay, am I making sense?

782
01:30:52.100 --> 01:31:00.590
Faculty (Olympus): So again, with respect to our linear regression, this loss function was mean squared error, which means predicted value minus true value.

783
01:31:00.730 --> 01:31:01.670
Faculty (Olympus): Square.

784
01:31:01.990 --> 01:31:15.400
Faculty (Olympus): And then you put all of those fellows, sum them, find the minimum of these, and it turned out we can solve it with a linear equation. So I can just solve a simple matrix method, and one shot, I'll get the solution. Okay, that's why these are nice, because they're fast, quick, easy to understand.

785
01:31:15.590 --> 01:31:17.439
Faculty (Olympus): But the basic principle is the same.

786
01:31:19.230 --> 01:31:22.850
Faculty (Olympus): All right, same thing what I'm saying, you know, MSC, this is what we get.

787
01:31:23.270 --> 01:31:26.029
Faculty (Olympus): I'm going to ignore this, you'll do this in your stats course.

788
01:31:27.720 --> 01:31:30.050
Faculty (Olympus): Alright, so.

789
01:31:30.320 --> 01:31:36.080
Faculty (Olympus): This is very important, and since I'm going to give you an exercise on this, I thought I'll quickly, you know, walk you through this.

790
01:31:37.330 --> 01:31:57.140
Faculty (Olympus): How do you deal with categories? So, let's say you want to do linear modeling. I want to do, just a simple linear model, or even say, you know, some linear model plus, say, some X squared term, like our model was T squared is proportional to L, right? So, you can come up with some model, folks. Now, let us say some of those quantities were

791
01:31:57.620 --> 01:31:59.599
Faculty (Olympus): Adult, not adult.

792
01:31:59.930 --> 01:32:06.710
Faculty (Olympus): Right? So you could have a categorization like this. Or, you know, knows programming, does not know program. Simple binary variable.

793
01:32:06.710 --> 01:32:21.080
Faculty (Olympus): Or you can have something, you know, good student, excellent student, not so good student. You know, you can have some categories based on your grade or something like that. Right? So you can imagine many, many situations in your own personal datasets where you have data that is actually categorical.

794
01:32:21.620 --> 01:32:25.499
Faculty (Olympus): How do you deal with categorical variables in your inputs?

795
01:32:25.740 --> 01:32:28.240
Faculty (Olympus): When you're predicting a when you're doing a regression problem.

796
01:32:28.820 --> 01:32:38.199
Faculty (Olympus): So what you need to do is you need to encode these variables suitably, which means you need to convert this into some sort of a number or something else. Okay, and we'll see exactly what we do here.

797
01:32:38.590 --> 01:32:43.079
Faculty (Olympus): So, if it is what's called a binary explanatory variable.

798
01:32:43.710 --> 01:32:52.190
Faculty (Olympus): You use what's called an indicator variable, which is a dummy variable, which says it is 1 when this variable is this value, it is 0 when this value is

799
01:32:52.440 --> 01:32:53.360
Faculty (Olympus): Not this.

800
01:32:53.570 --> 01:32:54.330
Faculty (Olympus): Okay.

801
01:32:55.590 --> 01:33:03.280
Faculty (Olympus): Alright, so if it's a binary explanatory variable, you use what's called an indicator, okay? And again, this indicator variable you would have seen in your stats course, okay?

802
01:33:03.850 --> 01:33:10.840
Faculty (Olympus): I don't know what form they used, or what symbol they used, but it'll say it is 1 when it is of this class, it is 0 when it is not of that class.

803
01:33:11.640 --> 01:33:27.370
Faculty (Olympus): Similarly, nominal and ordinal quantities, in general, there are these three different ways by which you can encode them. And when you say encode, what it means is, I give you something which is adult, not adult, okay? Or I tell you, you know, movie rating, R-rated, this rated, G-rated, whatever, child rated, whatever.

804
01:33:27.440 --> 01:33:36.999
Faculty (Olympus): How do I now encode this into some mechanism that I can pass it into regression, where it becomes a set of numbers, and I solve a linear system of equations and give you some parameters, right? So to do that.

805
01:33:37.000 --> 01:33:49.270
Faculty (Olympus): you have encoding mechanisms, which will convert these into numbers in some sensible fashion. So one of them is called one-hot encoding, which we'll talk about soon. The other is label encoding, which means you just sort of arbitrary

806
01:33:49.410 --> 01:33:58.989
Faculty (Olympus): numbers that you put. Third is target encoding, and the one that we would recommend the most for this course at this point is one hot encoding, okay? We'll come to this and quickly explain this.

807
01:33:59.740 --> 01:34:09.530
Faculty (Olympus): So if you have a binary variable, the simplest thing to do is you encode it as a dummy variable, which is either 0 or 1, okay? So, one way of thinking of this is.

808
01:34:09.840 --> 01:34:15.820
Faculty (Olympus): You have what's called a null or a control variable. So let's say you say the baseline is everybody is an average student.

809
01:34:16.800 --> 01:34:22.770
Faculty (Olympus): And then, you know, or you say, if you have cars, right, you have some basic model of the car, that can be the zero value.

810
01:34:22.830 --> 01:34:40.210
Faculty (Olympus): Then you say, oh, this fellow has some additional feature, fancy features. It has, you know, anti-breaking, it has some AC, it has, you know, fancy stereo and all of that. That becomes one. Then next fellow becomes two, okay? So what you do is, what this basically implies is when the binary variable is zero.

811
01:34:40.720 --> 01:34:43.160
Faculty (Olympus): It will add a constant called beta naught.

812
01:34:43.560 --> 01:34:44.330
Faculty (Olympus): Good?

813
01:34:44.950 --> 01:34:49.939
Faculty (Olympus): When the binary variable is 1, you will essentially get beta naught plus beta 1.

814
01:34:52.170 --> 01:34:56.339
Faculty (Olympus): So, essentially, what this does is it allows you to turn on and off a constant.

815
01:34:56.380 --> 01:35:13.659
Faculty (Olympus): Based on this binary variable's existence or non-existence. So it essentially allows you to shift the curve up and down. So if you're looking at linear modeling with a single variable, you know, a single linear quantity, this additional binary encoding allows you to shift the intercept by doing this, okay?

816
01:35:14.420 --> 01:35:17.980
Faculty (Olympus): So this is what this is one way of encoding a binary value.

817
01:35:18.620 --> 01:35:22.949
Faculty (Olympus): But supposing you don't have just binary variables, right? Let's say you have multiple categories.

818
01:35:23.180 --> 01:35:26.220
Faculty (Olympus): So what you do is, instead of taking,

819
01:35:26.870 --> 01:35:35.319
Faculty (Olympus): It's similar to binary, but when you take k values, you take k minus 1 dummy values, okay? So when k minus 1 are 0, you get the reference.

820
01:35:35.780 --> 01:35:36.550
Faculty (Olympus): Good.

821
01:35:36.940 --> 01:35:55.450
Faculty (Olympus): And again, it's a good idea to choose the reference fellow carefully, so that the zero value corresponds to some basic thing, and that everything else is some additional feature or something that you're looking at, right? For example, in cars, basic model can be your null model, okay? And the next fellow, and the value takes 1, 2, 3, 4, whatever, you know.

822
01:35:55.450 --> 01:36:00.850
Faculty (Olympus): It shows up as, Additional values.

823
01:36:01.150 --> 01:36:11.640
Faculty (Olympus): So, the way to encode this is, so, as I said, if I have k values, you take k minus 1 dummies. What this means is, I actually introduce k minus 1 variables, which are either 0 or 1.

824
01:36:12.240 --> 01:36:14.379
Faculty (Olympus): Okay, this is called one hot encoding.

825
01:36:14.610 --> 01:36:17.460
Faculty (Olympus): Basically, the idea isâ€¦

826
01:36:18.480 --> 01:36:23.989
Faculty (Olympus): So, let's say, Vivian, Can I take a couple of minutes? You want to finish just this part?

827
01:36:24.550 --> 01:36:25.629
Mayank Johri .: Go ahead, sir.

828
01:36:25.630 --> 01:36:31.190
Faculty (Olympus): Yeah, so let me just, let me encode.

829
01:36:33.910 --> 01:36:35.020
Faculty (Olympus): Okay.

830
01:36:40.300 --> 01:36:46.570
Faculty (Olympus): Okay, so, let's say I have, Three values.

831
01:36:46.720 --> 01:36:49.260
Faculty (Olympus): So let me send it up. Moroti.

832
01:36:50.460 --> 01:36:56.129
Faculty (Olympus): I don't know if 800 is available now. Then I can sayâ€¦ what's that?

833
01:36:56.570 --> 01:36:57.700
Faculty (Olympus): Laganar.

834
01:37:01.630 --> 01:37:04.130
Faculty (Olympus): And let's say I have,

835
01:37:04.340 --> 01:37:11.769
Faculty (Olympus): Balino, okay? I know there are many models, so let's imagine we have 3 such cars, okay? I will call this as my reference fellow.

836
01:37:12.160 --> 01:37:17.320
Faculty (Olympus): Okay? And then I'll have oneâ€¦ so I'll basically introduce 3 new variables.

837
01:37:17.760 --> 01:37:21.110
Faculty (Olympus): Okay, so I may have had just one column which has

838
01:37:21.210 --> 01:37:29.250
Faculty (Olympus): you know, this car is my 800 Wagon R, my Amarithi 800, so on and so forth. So what I'll do is I'll actually introduce 3 variables.

839
01:37:32.660 --> 01:37:43.570
Faculty (Olympus): Or, if you will, I will introduce two new variables, which are, either 0 or 1. Okay, so if, for example, it is 00, this fellow will correspond to Marithi.

840
01:37:43.940 --> 01:37:50.259
Faculty (Olympus): If it is 1, 0, it will correspond to Wagoner. If it is Balino, it will be 0.

841
01:37:50.640 --> 01:37:53.869
Faculty (Olympus): So, only one of these quantities willâ€¦ okay.

842
01:37:55.550 --> 01:37:59.100
Faculty (Olympus): There is all this. Let me draw it again. So I have.

843
01:38:00.910 --> 01:38:05.170
Faculty (Olympus): Okay, 800. What is that? What's the second one I said?

844
01:38:05.660 --> 01:38:06.700
Soumen Deb .: Back in August.

845
01:38:06.700 --> 01:38:07.400
Gaurav Singh .: Emma.

846
01:38:07.760 --> 01:38:08.140
Faculty (Olympus): Shall.

847
01:38:08.140 --> 01:38:08.700
Soumen Deb .: Monday.

848
01:38:08.900 --> 01:38:12.650
Faculty (Olympus): And I said, what's the third one? It was Balinova.

849
01:38:12.900 --> 01:38:14.990
Faculty (Olympus): Oh, but I hope that is aboutâ€¦

850
01:38:15.280 --> 01:38:19.229
Faculty (Olympus): Okay, and so I will say this fellow corresponds to 00.

851
01:38:20.380 --> 01:38:22.249
Faculty (Olympus): This fellow corresponds to.

852
01:38:22.410 --> 01:38:23.810
Faculty (Olympus): 1, 0.

853
01:38:24.040 --> 01:38:26.260
Faculty (Olympus): This value corresponds to 0.

854
01:38:29.640 --> 01:38:43.799
Faculty (Olympus): Does it make sense? So if the data is encoded as 001001, each of these will correspond to adding a new constant into your data set. So whenever I see a Balino, that fellow's variable will be one. Everything else will be zero.

855
01:38:44.200 --> 01:38:45.400
Faculty (Olympus): Does it make sense?

856
01:38:47.850 --> 01:39:07.100
Faculty (Olympus): So your base model will be just the Marithi 800. When this fellow isâ€¦ when the second fellow is 1, this quantity is 1, this fellow will be Baganar, this fellow is 1, this fellow will be Bali. So this is a way by which you can encode these categories as different values. So this is called one-hot encode.

857
01:39:07.230 --> 01:39:11.379
Faculty (Olympus): So what you can do is, when you use pandas.

858
01:39:11.720 --> 01:39:13.530
Faculty (Olympus): If you give it a data frame.

859
01:39:14.510 --> 01:39:30.760
Faculty (Olympus): Given all your data sets, your data values, right, all your columns, it will look at them, decide which one of them is, categorical, so it'll look at the object, right? So any of them is object or string, it'll convert that into a done.

860
01:39:31.260 --> 01:39:40.519
Faculty (Olympus): Right? And it'll drop the first fellow to give you K minus 1 dummies. So it'll construct a new data frame which has this structure.

861
01:39:41.520 --> 01:39:58.739
Faculty (Olympus): Okay, another way to do this encoding is to do sklearn.preprocessing with another module and has a one-hot encoder. Okay, so you just use one hot encoder, pass it whatever data, it'll convert this into a you know one hot encoded data set, which you just pass to fit.

862
01:39:59.400 --> 01:40:05.099
Faculty (Olympus): So once you do the encoding, you just say model.fit, give it this, and it'll do the same linear regression.

863
01:40:05.890 --> 01:40:06.770
Faculty (Olympus): Okay.

864
01:40:07.900 --> 01:40:12.890
Faculty (Olympus): Label encoding is something which I do not recommend, simply because

865
01:40:13.360 --> 01:40:20.629
Faculty (Olympus): You know, it'sâ€¦ you need to use it very carefulâ€¦ carefully, so what you do is you simply encode these labels as some integers.

866
01:40:22.780 --> 01:40:39.850
Faculty (Olympus): for things like, you know, poor, fair, good, excellent, right? And the thing is, these numbers, the gaps should also make sense, right? So if you have data like that, then it makes sense. But if you really are forced to use something like this, use SKLearn preprocessing, ordinal encoder will do this automatically for you.

867
01:40:39.850 --> 01:40:50.249
Faculty (Olympus): So again, given a categorical column, it'll convert this into numbers appropriately, okay? But please avoid this for linear models, okay? So only when you know enough about the model, and if they say.

868
01:40:50.270 --> 01:40:52.490
Faculty (Olympus): Use label encoding for such a data.

869
01:40:52.630 --> 01:40:57.839
Faculty (Olympus): Use it for linear models, so in our course, for my mid-semester, please don't use ordinary number.

870
01:40:59.640 --> 01:41:18.700
Faculty (Olympus): Then there is what's called other kinds of encoding. There's target encoding where you replace each category by the average value for all of those target values. So again, right? So this label encoder is better used for decision trees. So if you have a decision tree model, which Professor Vinayak will cover, you know, you can use label encoder.

871
01:41:20.590 --> 01:41:29.839
Faculty (Olympus): Okay, This is unfortunate, soâ€¦ Alright, so I can't finish any of this because we're out of time.

872
01:41:31.970 --> 01:41:38.110
Faculty (Olympus): All right, so I will stop here. I will request Professor Vinay to finish a lot of this material.

873
01:41:38.290 --> 01:41:43.670
Faculty (Olympus): I will give you an exercise up to and including this part, you know, which isâ€¦

874
01:41:44.380 --> 01:41:49.359
Faculty (Olympus): How do you do categorical data? So I will give you an exercise so you understand how to do this.

875
01:41:49.460 --> 01:41:57.200
Faculty (Olympus): And then we'll have maybe a doubt-clearing session sometime in this week, at your convenience. Maybe during the TA session, I can come for a short one.

876
01:41:57.320 --> 01:42:03.540
Faculty (Olympus): And answer any questions. So I will stop here, because I think I've already taken too much time.

877
01:42:03.680 --> 01:42:07.620
Faculty (Olympus): But don't worry too much about this, Professor Vinay will be covering.

878
01:42:10.130 --> 01:42:14.030
Faculty (Olympus): We'll cover this in some detail. I will tell him I've only covered so much.

879
01:42:15.980 --> 01:42:17.380
Faculty (Olympus): So we'll stop here.

880
01:42:18.980 --> 01:42:29.079
Faculty (Olympus): I'm ready to answer any questions. I have already uploaded this slide, so you have the whole set of slides, you can use it how you will, but as far as the MIDSEM is concerned.

881
01:42:29.190 --> 01:42:35.489
Faculty (Olympus): Linear models, along with categorical datasets, will be included in the syllabus.

882
01:42:36.280 --> 01:42:37.650
Faculty (Olympus): Nothing much else.

883
01:42:38.830 --> 01:42:40.120
Faculty (Olympus): Alright, Gaurav.

884
01:42:41.000 --> 01:42:46.199
Gaurav Singh .: Professor, like, in multiple categories scenario, or even in case of, I think.

885
01:42:46.400 --> 01:42:59.819
Gaurav Singh .: you said binary beta 0 and beta 1. Why, I mean, but K values take K minus 1 dummies. Why are we saying K minus 1 dummies? Because one of the value anyways will be 0.

886
01:42:59.930 --> 01:43:02.630
Faculty (Olympus): No, no, no. So what happens is, you're basically saying.

887
01:43:03.620 --> 01:43:10.969
Faculty (Olympus): When that fellowâ€¦ so it's like this. What this allows you to do is it allows you to add a constant for different categories.

888
01:43:11.120 --> 01:43:13.469
Faculty (Olympus): Okay, like an intercept for different categories.

889
01:43:13.750 --> 01:43:16.339
Faculty (Olympus): Say, for example, let's say I'm saying

890
01:43:20.500 --> 01:43:22.650
Faculty (Olympus): Elephants and human beings. Okay? Again.

891
01:43:22.860 --> 01:43:36.469
Faculty (Olympus): let us say the constant, you know, whenâ€¦ when yourâ€¦ the radius forâ€¦ noâ€¦ no human being's, you know, circumference is ever going to be zero, okay? So it's going to be some value between some, you know, say, 20 centimeters to, say.

892
01:43:37.320 --> 01:43:40.490
Faculty (Olympus): 400 centimeters for some gigantic film, okay?

893
01:43:40.710 --> 01:43:43.829
Faculty (Olympus): Same way for an elephant, it probably will be for a baby elephant.

894
01:43:44.560 --> 01:43:48.190
Faculty (Olympus): Maybe 400 centimeters to, you know,

895
01:43:48.470 --> 01:43:55.009
Faculty (Olympus): 5,000 centimeters or something, right? And now let's say we construct some sort of a model, polynomial or linear or whatever.

896
01:43:55.820 --> 01:44:00.930
Faculty (Olympus): There's gonna be some basic constant that is involved for a human being, which is very different for the elephant.

897
01:44:01.550 --> 01:44:10.140
Faculty (Olympus): However, the scaling laws with respect to your tissue, organic tissue, is going to be the same. So, you may have something that says the weight is proportional to the volume of the creature.

898
01:44:10.330 --> 01:44:21.219
Faculty (Olympus): Okay, and of course, the constitution of that creature. So, for example, maybe carnivores have a different slope because they are mostly muscle, whereas herbivores may be, you know, different because of whatever other reason.

899
01:44:21.350 --> 01:44:32.719
Faculty (Olympus): Or even, for example, you look at, say, rhinoceros versus elephant. Rhinoceros has very thick skin, even elephants do. But rhinoceros has horn, elephant has tusk, so there's some constant value that may be sitting there, that affects.

900
01:44:32.920 --> 01:44:42.309
Faculty (Olympus): Okay, and there are other quantities that are physical quantities. So what this allows you to do is, it allows you to say, supposing I encode, say, elephant.

901
01:44:42.420 --> 01:44:47.459
Faculty (Olympus): And human being is an elephant. It's not elephant, it's human being. It's a binary classification.

902
01:44:47.590 --> 01:44:52.549
Faculty (Olympus): What you're saying is, when not elephant, that fellow is a human being. Am I making sense?

903
01:44:53.180 --> 01:44:58.250
Faculty (Olympus): So I don't need that extra variable. That's why you end up with k minus one dummies.

904
01:44:58.920 --> 01:44:59.680
Gaurav Singh .: Okay.

905
01:45:00.000 --> 01:45:02.540
Faculty (Olympus): Okay. But when I have the elephant, what happens is this.

906
01:45:02.730 --> 01:45:06.959
Faculty (Olympus): This will be the baseline model plus an additional constant which represents the effect.

907
01:45:08.070 --> 01:45:08.520
Gaurav Singh .: Hmm.

908
01:45:08.520 --> 01:45:13.550
Faculty (Olympus): And since the variable in question can either be zero or one, the only thing it can do is be a constant.

909
01:45:15.200 --> 01:45:29.519
Faculty (Olympus): Okay? But this is when it concerns linear models. So you may now say, no, no, no, no, I want to have a model where I multiply this fellow with something else. You can create a model like this. Right? But that becomes a model where you have a multiplier effect.

910
01:45:30.450 --> 01:45:35.310
Faculty (Olympus): Yeah. So, you can create, you know, what are called features.

911
01:45:35.500 --> 01:45:42.300
Faculty (Olympus): which encode this behavior. You can say, no, no, no, I want to have a feature where these two are essentially a product.

912
01:45:42.950 --> 01:45:47.389
Faculty (Olympus): So you can have product features. And have this feature into that feature.

913
01:45:49.250 --> 01:45:59.440
Faculty (Olympus): And they will have appropriate coefficients. Now, this is aâ€¦ this is where modeling enters. So now you need to use your knowledge, and you need to be able to justify this. You can't arbitrarily put whatever product you want.

914
01:46:00.770 --> 01:46:06.200
Faculty (Olympus): Right? So you say, no, no, no, I expect this to behave like this, and therefore I allow this kind of relationship.

915
01:46:06.770 --> 01:46:13.030
Faculty (Olympus): But you are perfectly fine doing those kind of things. Once again, you'll get a coefficient multiplying this product.

916
01:46:14.690 --> 01:46:20.969
Faculty (Olympus): So you can again plug it into a linear regression and obtain those coefficients. Am I making sense?

917
01:46:21.680 --> 01:46:39.369
Faculty (Olympus): So this is the art of feature engineering, where you're basically saying, okay, simplest brain-dead thing to do is constant plus this fellow constant, you know, beta naught into X1, beta 2 into X2, so on and so forth. Now, you may have some knowledge which says, no, no, no, there should be another feature, which is some beta K plus 1,

918
01:46:39.610 --> 01:46:41.119
Faculty (Olympus): X1 times X2.

919
01:46:41.670 --> 01:46:43.390
Faculty (Olympus): It's fine, no problem.

920
01:46:44.720 --> 01:46:45.959
Faculty (Olympus): Does it make sense?

921
01:46:46.580 --> 01:46:52.290
Gaurav Singh .: Yeah, it makes sense, Professor Link. It's too much, but it aligns us to the right direction.

922
01:46:52.290 --> 01:47:10.939
Faculty (Olympus): Yeah. So but that's all you need to understand at this stage because now if you know this, all you need to do is set up a feature. So I'm gonna give you a workout exercise where you can see how you can set these kind of problems up very easily with psychetry. So it'll be very simple, two lines, two lines of code, and it is supported by that book, data science, handbook.

923
01:47:10.940 --> 01:47:14.800
Faculty (Olympus): So I'm basically gonna ask you to read a section and say, okay. Now write the code from there.

924
01:47:14.940 --> 01:47:21.709
Faculty (Olympus): Go read this, write the code from there. So once you do that, you know, you'll have an understanding of how to use this, so please do that.

925
01:47:21.840 --> 01:47:23.930
Faculty (Olympus): And then we can answer any questions.

926
01:47:24.310 --> 01:47:25.470
Gaurav Singh .: Got it. Thank you.

927
01:47:25.470 --> 01:47:35.010
Faculty (Olympus): Don't panic. Don't worry. You're all ready now to do this kind of work. So you're actually ready for Pravinay. Wish I had done a little more, but that's okay. Thank you.

928
01:47:35.010 --> 01:47:40.809
Gaurav Singh .: Actually, Professor, we are not getting much time for practicing. I mean, the sessions are going very good, but yeah, likeâ€¦

929
01:47:40.810 --> 01:47:43.549
Faculty (Olympus): Yeah, yeah, that's the hard part, but going forward, it's going to be.

930
01:47:43.550 --> 01:47:45.940
Gaurav Singh .: Job, it is difficult, a little bit.

931
01:47:46.430 --> 01:47:50.880
Faculty (Olympus): Yeah, so problems that I have not yet put up, I have to put it up, so I'll try and set it up.

932
01:47:51.000 --> 01:47:59.410
Faculty (Olympus): As soon as possible, and set up this, you know, worked out exercise. I have it ready, but Iâ€¦ maybe I'll add some small things here and there, and share that.

933
01:48:01.470 --> 01:48:02.120
Gaurav Singh .: Sure.

934
01:48:02.190 --> 01:48:03.180
Faculty (Olympus): Abhishek.

935
01:48:09.030 --> 01:48:10.800
Faculty (Olympus): Abhishek, did I answer your question already?

936
01:48:10.860 --> 01:48:19.189
Abhishek Raghuvanshi .: Oh, Professor, I just wanted to check for the examination. There's mentioned that for the part, the second part of the exam, which is.

937
01:48:19.330 --> 01:48:22.770
Abhishek Raghuvanshi .: Plotting and all, we can carry, we can use the notes.

938
01:48:22.920 --> 01:48:26.980
Abhishek Raghuvanshi .: But I think that mentioned that we need to carry printouts.

939
01:48:27.190 --> 01:48:30.700
Abhishek Raghuvanshi .: Rather than referring online, soâ€¦ so I don't know.

940
01:48:31.410 --> 01:48:33.719
Abhishek Raghuvanshi .: Weird because there are so many sheets.

941
01:48:33.720 --> 01:48:39.159
Faculty (Olympus): No, no, no, no, I don't want you to print out and all that, no, no, so I'llâ€¦ I will talk to them and update the instructions by tomorrow.

942
01:48:39.500 --> 01:48:48.439
Faculty (Olympus): Tomorrow, I'llâ€¦ I'll meet the TAs, and we'llâ€¦ we'll give you theâ€¦ we'll give you instructions. So I don'tâ€¦ I'm not going to be unreasonable. Anyway, we areâ€¦ there's going to be some proctoring.

943
01:48:48.550 --> 01:48:51.470
Faculty (Olympus): So maybeâ€¦

944
01:48:51.670 --> 01:48:55.349
Faculty (Olympus): Maybe we can allow you to see the notebooks on your computer.

945
01:48:56.540 --> 01:48:58.200
Faculty (Olympus): Download all the content.

946
01:48:58.560 --> 01:49:12.669
Faculty (Olympus): Right? Just don't use an AI or chat with somebody and get the answer. That's really what I want. For the second part. First part will be anyway on that SCB, which is a pain in the neck, so you can't do anything else. Hopefully, you don't use another device. That is going to cheat, butâ€¦

947
01:49:13.810 --> 01:49:17.680
Faculty (Olympus): But you're not supposed to use another device, so there will be, I think, some proctoring for that.

948
01:49:18.180 --> 01:49:24.390
Faculty (Olympus): And this time, we won't give you a big, big window, huh? There'll be only a small window. Hopefully, we will do another.

949
01:49:24.770 --> 01:49:27.270
Faculty (Olympus): I was asking the TAs to do another.

950
01:49:27.380 --> 01:49:32.389
Faculty (Olympus): Mock test so that everybody, again, has the interface fully set up with cut, paste, copy, all of that sorted out.

951
01:49:33.300 --> 01:49:43.920
Abhishek Raghuvanshi .: Yeah, so that's already there. I tried it, but I think it's better than last time. But copy still, sometimes there is an issue. So I don't know what the issue is, but then drag it.

952
01:49:43.920 --> 01:49:58.470
Faculty (Olympus): So, but anyway, the first part, the programming part will be more straightforward. It'll be just normal programming things. The second part is where you'll be expected to answer a notebook and upload the notebook on GL interface. So, you know, that's where it'll get a little more complicated, right?

953
01:49:59.350 --> 01:50:01.340
Faculty (Olympus): Yes sir.

954
01:50:01.340 --> 01:50:07.920
Abhishek Raghuvanshi .: It's already fairly complicated for us, because some of us are new in programming, so it takes a lot of bandwidth there.

955
01:50:08.700 --> 01:50:14.750
Faculty (Olympus): Yeah, but there's only so much we can do, right? Yeah. That's why we set up that initial course and all that, so you could haveâ€¦

956
01:50:14.900 --> 01:50:18.910
Faculty (Olympus): You know, finish that before you came in. Anyway, that's okay, but, you knowâ€¦

957
01:50:21.450 --> 01:50:22.380
Abhishek Raghuvanshi .: Oh, thanks, bro.

958
01:50:24.330 --> 01:50:25.280
Faculty (Olympus): Rati.

959
01:50:26.010 --> 01:50:35.859
Lad Prachikumari Vijaykumar .: Sir, same question on this. Like, second part is, we have to perform on Jupyter, right? So, we have to perform this on SCB browser, then how we will download.

960
01:50:35.860 --> 01:50:40.160
Faculty (Olympus): No, no, no. I don't think the second part is on SEB. Second part is not on SEB. Second part you have.

961
01:50:40.160 --> 01:50:40.920
Lad Prachikumari Vijaykumar .: Okay.

962
01:50:41.300 --> 01:50:42.380
Lad Prachikumari Vijaykumar .: He just put it.

963
01:50:42.380 --> 01:50:47.409
Faculty (Olympus): There will be some proctoring to make sure that people don't cheat. That's all. So don't use AI.

964
01:50:47.580 --> 01:50:57.549
Faculty (Olympus): You can use all the notebooks, all the class material, you can use tab completion onâ€¦ without, you know, don't use WhatsApp for it, Copilot or something to tab complete all the answers.

965
01:50:57.910 --> 01:50:58.490
Faculty (Olympus): But.

966
01:50:58.490 --> 01:50:59.140
Lad Prachikumari Vijaykumar .: Okay.

967
01:50:59.140 --> 01:51:02.999
Faculty (Olympus): Yeah, but use a Jupyter Notebook, set up the answer, answer it, and upload it.

968
01:51:03.580 --> 01:51:06.330
Lad Prachikumari Vijaykumar .: And same as assignment, we have to upload,

969
01:51:06.330 --> 01:51:15.929
Faculty (Olympus): Yes, yes, but you'll have some finite window, as in, I think, within 15 minutes of the end time, there'll be a time that they'll give you. By then, it has to be uploaded. After that, uploads will be closed.

970
01:51:17.080 --> 01:51:22.619
Lad Prachikumari Vijaykumar .: Okay, can we have a once a demo or some instruction steps? So at least.

971
01:51:22.960 --> 01:51:25.330
Lad Prachikumari Vijaykumar .: We can aware about, likeâ€¦

972
01:51:25.730 --> 01:51:27.710
Faculty (Olympus): Same as assignments, right? You upload on GL.

973
01:51:27.710 --> 01:51:28.260
Lad Prachikumari Vijaykumar .: Okay.

974
01:51:28.260 --> 01:51:35.120
Faculty (Olympus): And then you'll have the SEB like your quiz. No, nothing different. So one hour will be for the thing, you finish the quiz, jump to the next problem set.

975
01:51:35.530 --> 01:51:43.999
Faculty (Olympus): So we'll give you two systems. So Yakshka, whatever comes on SAB thing will be automatic. You don't have to see that. For the other one, there'll be a question paper which will be on the GL interface. You download it.

976
01:51:44.210 --> 01:51:45.230
Faculty (Olympus): When's start?

977
01:51:46.200 --> 01:52:10.180
Lad Prachikumari Vijaykumar .: Hmm, okay. And, sir, one another question, like, in York's portal, we've written the code and the, you know, whatever marks we are getting based on the test cases, whatever we have passed. So, supposeâ€¦ So, suppose 80% test cases we have passed, right? But in York's portal, that is not showingâ€¦ it is only showing errors, right? So, how we will get to know, like, weâ€¦

978
01:52:10.180 --> 01:52:19.019
Faculty (Olympus): Final score, I think if you get your final score, you'll see that it's it's based on the number of tests you pass. So if you pass most of them, you'll get at least some fractional marks you should have gotten.

979
01:52:20.210 --> 01:52:27.280
Lad Prachikumari Vijaykumar .: Oh, okay, okay. And, sir, last one. This one hot encoder and this multi-category is also part of MEDEXM?

980
01:52:27.280 --> 01:52:27.920
Faculty (Olympus): Yes.

981
01:52:28.200 --> 01:52:33.830
Faculty (Olympus): I'll give you a workbook. It's very straightforward. There's nothing much. You just do this mostly automatic.

982
01:52:33.830 --> 01:52:34.290
Lad Prachikumari Vijaykumar .: only.

983
01:52:34.290 --> 01:52:35.770
Faculty (Olympus): So, I'll give you a worked out thing.

984
01:52:35.770 --> 01:52:36.560
Lad Prachikumari Vijaykumar .: Yeah, you canâ€¦

985
01:52:36.620 --> 01:52:38.530
Faculty (Olympus): Work it out and see how to do it.

986
01:52:39.270 --> 01:52:40.340
Lad Prachikumari Vijaykumar .: And apart.

987
01:52:40.970 --> 01:52:46.140
Lad Prachikumari Vijaykumar .: And apart from logistic regression, other models we have to prepare,

988
01:52:46.140 --> 01:52:58.119
Faculty (Olympus): Since I've not really covered logistic, I think, you know, I can't ask you formally the questions about logistic either, so we'll maybe skip that part. Even though I have some questions, I'm going to give you a workbook.

989
01:52:58.450 --> 01:52:59.600
Faculty (Olympus): you can feel free to.

990
01:52:59.600 --> 01:53:00.840
Lad Prachikumari Vijaykumar .: Yes, yes.

991
01:53:00.840 --> 01:53:05.160
Faculty (Olympus): There are going to be questions there that are also involving regression. Sorry.

992
01:53:05.530 --> 01:53:14.539
Faculty (Olympus): Classification with logistic, but it'll walk you through that. I won't ask you questions about it in the midterm, but I strongly encourage you to do it because

993
01:53:14.660 --> 01:53:18.370
Faculty (Olympus): When Prosavinay starts, he will assume you know Sai Kirtan.

994
01:53:18.770 --> 01:53:25.229
Faculty (Olympus): So I strongly suggest you finish this, but I'm not going to ask you a question on classification in the midterm.

995
01:53:26.400 --> 01:53:27.910
Lad Prachikumari Vijaykumar .: Okay, sir, thank you.

996
01:53:27.910 --> 01:53:28.389
Faculty (Olympus): Okay, sure.

997
01:53:28.390 --> 01:53:28.890
Lad Prachikumari Vijaykumar .: you.

998
01:53:29.110 --> 01:53:32.080
Faculty (Olympus): Rahul, you have waited patiently till the end.

999
01:53:32.080 --> 01:53:50.210
Rahul Shrikrishna Joshi .: Thank you, sir. Question. So in order to calculate the effectiveness of the at least linear regression model, whatever. So SRR, which is like a calculate the value of predicted value minus actual value and square it. Is this the only parameter or?

1000
01:53:50.210 --> 01:53:52.019
Faculty (Olympus): R, you mean R squared, right?

1001
01:53:52.020 --> 01:53:53.239
Rahul Shrikrishna Joshi .: Yeah, yeah, yeah, square, yeah, yeah.

1002
01:53:53.240 --> 01:54:04.220
Faculty (Olympus): So in multilinear model, you should actually use the quantity called adjusted R squared. You can read up about it. Adjusted R squared is better because it basically penalizes you for more.

1003
01:54:04.380 --> 01:54:06.089
Faculty (Olympus): Adding more and more variables.

1004
01:54:08.170 --> 01:54:09.539
Rahul Shrikrishna Joshi .: Email is okay, okay?

1005
01:54:09.540 --> 01:54:18.650
Faculty (Olympus): Basically, if you have too many variables, if I give you 1 billion linear model, it's like not so great a model. So adjusted R squared adjusts for that.

1006
01:54:19.710 --> 01:54:21.200
Faculty (Olympus): You can go read up about it.

1007
01:54:21.360 --> 01:54:32.410
Rahul Shrikrishna Joshi .: Yeah, that's fine, sir, thank you. Second question is, in that, yesterday's topic about, so SRR is understood, there is a coefficient of determination where SRR divided by SYY.

1008
01:54:32.590 --> 01:54:36.179
Faculty (Olympus): No, it is, yeah, 1 minus SRR by SSR by SY.

1009
01:54:36.180 --> 01:54:46.560
Rahul Shrikrishna Joshi .: Yeah, 1 minus SRR byâ€¦ but sir, SYY, is it really making sense, actually? Because if the Y is, scattered, then SYY will be very high value, right?

1010
01:54:47.300 --> 01:54:48.030
Faculty (Olympus): Yeah.

1011
01:54:48.030 --> 01:54:48.949
Rahul Shrikrishna Joshi .: But SRR may not.

1012
01:54:48.950 --> 01:54:49.550
Faculty (Olympus): the.

1013
01:54:49.550 --> 01:54:50.130
Rahul Shrikrishna Joshi .: Sarawak City.

1014
01:54:50.130 --> 01:54:54.800
Faculty (Olympus): It gives you a sense of proportion. Say, supposing I tell you the Y quantity is in tons.

1015
01:54:54.990 --> 01:54:58.839
Faculty (Olympus): Okay. Or the Y quantity is some, you know, some insect ant.

1016
01:54:59.060 --> 01:55:02.699
Faculty (Olympus): SYMA will be very small. So now if I look at the SSR,

1017
01:55:02.900 --> 01:55:07.409
Faculty (Olympus): The quantities will be vastly different, so think of it as a relative error, for example.

1018
01:55:07.930 --> 01:55:10.929
Rahul Shrikrishna Joshi .: But Sir, SRR completely makes sense to me. That is the.

1019
01:55:10.930 --> 01:55:16.899
Faculty (Olympus): SSR is the difference between predicted and okay. So let me put it this way. I'm predicting the weight of an elephant.

1020
01:55:17.080 --> 01:55:18.000
Faculty (Olympus): Okay.

1021
01:55:18.380 --> 01:55:20.049
Faculty (Olympus): My prediction is.

1022
01:55:20.220 --> 01:55:22.060
Faculty (Olympus): Accurate to about a kilogram.

1023
01:55:22.850 --> 01:55:24.880
Faculty (Olympus): I would consider that a great model.

1024
01:55:25.440 --> 01:55:26.120
Faculty (Olympus): Right?

1025
01:55:26.280 --> 01:55:27.010
Rahul Shrikrishna Joshi .: Yep.

1026
01:55:27.010 --> 01:55:28.600
Faculty (Olympus): I'm now predicting ants.

1027
01:55:29.570 --> 01:55:37.559
Faculty (Olympus): But Ant model is also 1 kg. You think it's a great model? It's a lousy model, right? Because Ant's weight is, like, micrograms.

1028
01:55:38.520 --> 01:55:50.609
Faculty (Olympus): Am I making sense? So by dividing by SS by SYY, you are able to get it into a proportion, and you're guaranteed R squared is between 0 and 1. If you do not divide by SYY, it is not guaranteed to be between 0 and 1.

1029
01:55:52.260 --> 01:55:53.020
Rahul Shrikrishna Joshi .: Oh, okay.

1030
01:55:54.260 --> 01:55:56.569
Faculty (Olympus): R squared is always between zero and one.

1031
01:55:58.410 --> 01:56:01.619
Faculty (Olympus): And you can prove it. Your stat scores may prove it for you.

1032
01:56:02.730 --> 01:56:03.450
Rahul Shrikrishna Joshi .: Okay.

1033
01:56:03.700 --> 01:56:04.700
Faculty (Olympus): Am I making sense?

1034
01:56:04.800 --> 01:56:11.219
Faculty (Olympus): Because essentially it's a proportion of how much you are able to explain with your model divided by how much variation there is actually in the data.

1035
01:56:13.330 --> 01:56:13.890
Faculty (Olympus): Yeah, because.

1036
01:56:13.890 --> 01:56:28.130
Rahul Shrikrishna Joshi .: So my question was the variation in the data. Let's say if you are considering the sales numbers, which can vary a lot actually. So the variation in the data will be far too high. But SRR is not expected to be far too high, right? Because you are predicting.

1037
01:56:28.130 --> 01:56:30.780
Faculty (Olympus): It is, it is, because again, look at the example.

1038
01:56:31.330 --> 01:56:37.569
Faculty (Olympus): Elephant weights, you're doing a model to predict. You'll be fine with a 1 kg error with each fellow. That's peanuts.

1039
01:56:42.370 --> 01:56:45.340
Faculty (Olympus): Elephant has a sip of water, it'll probably be a few kilos.

1040
01:56:48.700 --> 01:56:49.520
Faculty (Olympus): Right?

1041
01:56:54.020 --> 01:56:59.589
Rahul Shrikrishna Joshi .: Natural, I'm convinced about SRR, I'm a little confused about SRR divided by SYY.

1042
01:57:00.720 --> 01:57:02.449
Faculty (Olympus): What is the confusion? I don't understand.

1043
01:57:03.390 --> 01:57:04.040
Rahul Shrikrishna Joshi .: My.

1044
01:57:04.040 --> 01:57:07.649
Faculty (Olympus): What is SSR? SSR is the sum of the squares of the differences, right?

1045
01:57:07.650 --> 01:57:08.270
Rahul Shrikrishna Joshi .: Correct, correct.

1046
01:57:08.270 --> 01:57:09.479
Faculty (Olympus): Predicted value minus.

1047
01:57:09.610 --> 01:57:10.340
Rahul Shrikrishna Joshi .: Good morning.

1048
01:57:10.340 --> 01:57:10.870
Faculty (Olympus): value.

1049
01:57:10.870 --> 01:57:16.409
Rahul Shrikrishna Joshi .: that directly helps us to understand how well we are predicting. So SRR is fine.

1050
01:57:16.410 --> 01:57:18.679
Faculty (Olympus): But it is relative to what you are predicting, right?

1051
01:57:21.000 --> 01:57:23.069
Faculty (Olympus): How is this not easy to understand?

1052
01:57:26.690 --> 01:57:31.620
Faculty (Olympus): How do you determine what is large? You are telling me error is large. Tell me what you do. How do you define error is large?

1053
01:57:35.720 --> 01:57:49.819
Rahul Shrikrishna Joshi .: Okay, so let me, let me, can I take 2 minutes, sir, to explain the example? Sure. Okay, so let's say, we are, we are predicting, we have a linear aggregation regression model, this thing, let's say, spendulum model, where the length and the T square, okay?

1054
01:57:49.820 --> 01:58:03.929
Rahul Shrikrishna Joshi .: So length is independent. T square is a, you're predicting T square. You write some linear regression model and then you predict T square. And then you are for that particular value of L, you have the actual value of T, T square, and you have got your difference is S.

1055
01:58:03.930 --> 01:58:06.819
Faculty (Olympus): Just one second, one second, just one second, I'll be right back, sir.

1056
01:58:10.060 --> 01:58:13.090
Faculty (Olympus): you Yeah, but big play.

1057
01:58:17.220 --> 01:58:18.790
Faculty (Olympus): Yes, sorry.

1058
01:58:19.290 --> 01:58:33.620
Rahul Shrikrishna Joshi .: Yeah, yeah. So what I was saying is that in the pendulum example, you predict the value of T square based on L, using our model, and then you have the actual value of T square for that given length, and difference between the two will help me to understand SRR.

1059
01:58:33.620 --> 01:58:35.880
Faculty (Olympus): So that SRA is understood. SSR, yeah.

1060
01:58:35.880 --> 01:58:36.630
Rahul Shrikrishna Joshi .: is.

1061
01:58:36.630 --> 01:58:39.439
Faculty (Olympus): Sum of the squares of those quantities, correct.

1062
01:58:39.440 --> 01:58:45.260
Rahul Shrikrishna Joshi .: Correct. SSR. Now SYY is the actual variation in the T square, right?

1063
01:58:45.340 --> 01:58:47.079
Faculty (Olympus): All the values of T square, right?

1064
01:58:47.680 --> 01:58:54.510
Faculty (Olympus): Yeah, so it's TI squared minus the mean of those T squared lines. Yeah, so my action.

1065
01:58:54.840 --> 01:59:01.520
Rahul Shrikrishna Joshi .: Correct. So my T's can be, let's say, can be a bigger range as compared to my individual value I'm predicting.

1066
01:59:02.070 --> 01:59:04.220
Faculty (Olympus): Okay, so what? Okay, fine.

1067
01:59:05.660 --> 01:59:08.880
Rahul Shrikrishna Joshi .: So, are these two comparable? That is what my question was, actually.

1068
01:59:09.140 --> 01:59:11.870
Rahul Shrikrishna Joshi .: Because here I'm compâ€¦ here I'm,

1069
01:59:11.870 --> 01:59:12.220
Faculty (Olympus): the.

1070
01:59:12.220 --> 01:59:13.110
Rahul Shrikrishna Joshi .: single value.

1071
01:59:13.110 --> 01:59:16.320
Faculty (Olympus): You divide one by the other, you'll understand this little better.

1072
01:59:19.100 --> 01:59:21.869
Rahul Shrikrishna Joshi .: So probably T square there will not be much variation but.

1073
01:59:21.870 --> 01:59:29.729
Faculty (Olympus): No, I think you're I don't understand your your your point is I don't understand your question. I'm telling you that Vike has some units, for example.

1074
01:59:30.560 --> 01:59:40.169
Faculty (Olympus): I have to be consistent with that units if I want to give you a parameter that's varying between 0 and 1, right? Guaranteeing R squared is between 0 and 1. You're giving me no such guarantee with SSR.

1075
01:59:40.170 --> 01:59:41.580
Soumen Deb .: Like the pendulum can.

1076
01:59:41.580 --> 01:59:42.289
Faculty (Olympus): Same thing.

1077
01:59:42.630 --> 01:59:44.769
Soumen Deb .: Yeah, it cannot predict ours, right?

1078
01:59:44.920 --> 01:59:47.670
Soumen Deb .: So there is a ratio with X to Y.

1079
01:59:47.980 --> 01:59:59.210
Soumen Deb .: That's what it is said. So you can predict an elephant's weight, but you can't predict an ant's weight with that same model. So pendulum will only predict with seconds. So there is a ratio between the X quantity and the Y quantity.

1080
01:59:59.500 --> 02:00:06.950
Soumen Deb .: That ratio, if it is skewed, then your model is incorrect. That's what he's trying to say. If I'm not wrong, that's what the point is.

1081
02:00:09.320 --> 02:00:13.090
Faculty (Olympus): Yes. And also mathematically, you can prove that r squared is between zero and one.

1082
02:00:14.450 --> 02:00:15.499
Faculty (Olympus): Keep working with it.

1083
02:00:17.020 --> 02:00:19.279
Rahul Shrikrishna Joshi .: Yeah, thank you, sir. I think I got it now.

1084
02:00:19.280 --> 02:00:24.360
Faculty (Olympus): Yeah, but the thing is, see, also note that the mathematics will predict that R squared is between 0 and 1.

1085
02:00:25.500 --> 02:00:26.160
Rahul Shrikrishna Joshi .: Yep.

1086
02:00:26.930 --> 02:00:32.469
Faculty (Olympus): So whereas with SSR, you don't have any such guarantee. SSR can be any number depending on the kind of the data.

1087
02:00:36.640 --> 02:00:40.639
Rahul Shrikrishna Joshi .: Yeah, so R squared is SSR divided by SYY, right? One minus, I think, right?

1088
02:00:40.640 --> 02:00:43.879
Faculty (Olympus): Yeah, one minus that. Come on. One minus. Yeah.

1089
02:00:44.510 --> 02:00:50.390
Faculty (Olympus): Thank you. Which is why yesterday, you know, you missed the one minus part. So it will be one is what you're saying.

1090
02:00:50.390 --> 02:00:51.030
Rahul Shrikrishna Joshi .: one.

1091
02:00:51.030 --> 02:01:03.089
Faculty (Olympus): So it becomes zero. So it's actually very bad R squared. So R squared is still a very good measure of how well your model is predicting because in fact, if R squared is high, it means the SSR is very small.

1092
02:01:03.790 --> 02:01:04.460
Rahul Shrikrishna Joshi .: Correct.

1093
02:01:05.090 --> 02:01:05.760
Faculty (Olympus): Yep.

1094
02:01:06.190 --> 02:01:07.670
Rahul Shrikrishna Joshi .: Thank you, sir. Thank you. Got it now.

1095
02:01:08.440 --> 02:01:09.220
Faculty (Olympus): Ravi.

1096
02:01:12.400 --> 02:01:28.319
Ravi Kumar Pathak .: Sir, my question is related to, the help, if we can take, W3 school sort of thing, in exam, will it be allowed, or it will be, like, only the documentation, within the Jupyter Notebook we can?

1097
02:01:30.250 --> 02:01:32.830
Faculty (Olympus): Yeah, so you're going to say for the second part, right?

1098
02:01:33.970 --> 02:01:38.199
Ravi Kumar Pathak .: For, for quiz, for exam, basically. Can weâ€¦

1099
02:01:38.200 --> 02:01:41.659
Faculty (Olympus): There are two parts to the exam. One is going to be on SEB where nothing is allowed.

1100
02:01:42.170 --> 02:01:45.569
Faculty (Olympus): Okay, the second part is where it is like a homework assignment.

1101
02:01:46.100 --> 02:01:55.960
Faculty (Olympus): Right? I am hoping that you can basically even do Google search, but it cannot be you search, here is the cut-paste question, you please give me answer, and you cut-paste the answer. That is notâ€¦

1102
02:01:57.980 --> 02:02:02.559
Ravi Kumar Pathak .: Okay, okay. Yeah, I mean, just like documentation or some sort of,

1103
02:02:02.560 --> 02:02:11.449
Faculty (Olympus): Yeah, yeah, documentation, Python documentation, W3Schools, TK, but you shouldn't be cut-pasting the example on the Google and asking, you know, that's all.

1104
02:02:11.760 --> 02:02:14.480
Ravi Kumar Pathak .: Sure, sure. Got it, got it, sir. Thank you.

1105
02:02:19.740 --> 02:02:22.029
Faculty (Olympus): Ravi, have I answered? Okay.

1106
02:02:22.840 --> 02:02:23.770
Faculty (Olympus): All day.

1107
02:02:24.590 --> 02:02:27.199
Faculty (Olympus): Soumen, I think you had a question, but you have put it down.

1108
02:02:27.200 --> 02:02:38.480
Soumen Deb .: No, no, no. I have a question. Sorry, somehow. So the reference text which you gave in your introduction slides, there are four books, right? So which book we should refer for Scikit-learn, Python, Data Science?

1109
02:02:38.480 --> 02:02:55.540
Faculty (Olympus): Oh, Scikit-learn, I think you can, the Python data science. In fact, so my assignment will specifically mention that book and ask you to read specific sections to solve some problems. So that, you know, that is a huge book. I can't give you the whole book and say, read this from its end. So I'm going to walk you through Scikit-learn usage.

1110
02:02:55.650 --> 02:02:58.319
Faculty (Olympus): For classification and regression using that.

1111
02:02:58.760 --> 02:03:04.089
Faculty (Olympus): So, I'll need some time to, you know, edit this, and then give it, because I didn't know how much I will cover today.

1112
02:03:04.240 --> 02:03:06.440
Faculty (Olympus): And I will try and share it by this evening.

1113
02:03:07.130 --> 02:03:18.830
Soumen Deb .: Okay, and in today's course, which you have mentioned, so there areâ€¦ there is, there are 3 types of training, right? So, one is.

1114
02:03:19.300 --> 02:03:24.340
Soumen Deb .: Supervised, then is unsupervised, and the third one is regression, though. So what, whatâ€¦

1115
02:03:24.340 --> 02:03:24.720
Faculty (Olympus): Mohammed.

1116
02:03:24.720 --> 02:03:25.220
Soumen Deb .: anything.

1117
02:03:25.220 --> 02:03:26.020
Faculty (Olympus): was correct.

1118
02:03:26.020 --> 02:03:29.559
Soumen Deb .: Yeah. So reinforcement, what type of learning is that? Just to understand that.

1119
02:03:29.560 --> 02:03:31.939
Faculty (Olympus): So reinforcement is like, you know, you play games.

1120
02:03:33.040 --> 02:03:39.510
Faculty (Olympus): Right? So you give it aâ€¦ you give it someâ€¦ youâ€¦ you give it aâ€¦ you basically guide the actions of the ML agent.

1121
02:03:39.960 --> 02:03:45.489
Faculty (Olympus): In order to, you know, win a game, so it's a very different class of,

1122
02:03:45.750 --> 02:03:46.570
Faculty (Olympus): Training.

1123
02:03:47.670 --> 02:03:48.170
Soumen Deb .: Okay.

1124
02:03:48.600 --> 02:03:53.319
Soumen Deb .: Okay, so which means there is some training which I can.

1125
02:03:53.320 --> 02:03:53.680
Faculty (Olympus): Yeah.

1126
02:03:53.680 --> 02:03:54.510
Soumen Deb .: Goes on.

1127
02:03:54.510 --> 02:04:05.979
Faculty (Olympus): And not only that, you don't know the result at the end, right? You have toâ€¦ how do you make a decision? You're playing chess, for example, right? You're making a decision now. How does this decision very change your final outcome? It's, like, very.

1128
02:04:06.410 --> 02:04:08.010
Faculty (Olympus): You know, it's not like supervised learning.

1129
02:04:08.650 --> 02:04:09.310
Faculty (Olympus): Soâ€¦

1130
02:04:09.310 --> 02:04:09.960
Soumen Deb .: the.

1131
02:04:09.960 --> 02:04:14.370
Faculty (Olympus): other things. So, you know, the approaches that you take for things like that is slightly different.

1132
02:04:15.070 --> 02:04:19.029
Soumen Deb .: Supervised learning is like you show pictures of dog and then.

1133
02:04:19.030 --> 02:04:22.860
Faculty (Olympus): Yes, we train it so that it learns how to pick a dog from a cat.

1134
02:04:23.270 --> 02:04:24.070
Faculty (Olympus): That's all.

1135
02:04:24.070 --> 02:04:25.250
Soumen Deb .: Reinforcement is.

1136
02:04:25.250 --> 02:04:37.830
Faculty (Olympus): Labeled examples and you check. Unsupervised, you don't have labeled examples. And then there's in between these like semi-supervised is like you have in some cases you generate the data where you can train something and say, awesome.

1137
02:04:38.130 --> 02:04:39.119
Faculty (Olympus): A lot of common.

1138
02:04:39.120 --> 02:04:41.910
Soumen Deb .: Of course, we'll not cover reinforcement learning, right?

1139
02:04:41.910 --> 02:04:59.010
Faculty (Olympus): No. In fact, this course, you will basically look at traditional ML algorithms. You may use DNNs as, like, a matter of course, saying, okay, here's a classification, because Scikit-learn makes it very easy to do that. You can say, okay, use this DNN with these parameters. It'll do it.

1140
02:04:59.890 --> 02:05:10.440
Faculty (Olympus): You don't need to know the nitty-gritty of what the DNN is, but you need to know how to evaluate. You look at the R-squared for this, R-squared for that. Or if you're doing classification, there are other parameters, you know, your accuracy, recall.

1141
02:05:12.100 --> 02:05:15.829
Faculty (Olympus): You know, precision, those quantities you can look at and then determine.

1142
02:05:15.960 --> 02:05:21.809
Faculty (Olympus): Or your F1 score, which is there in this site set, but I have not had the time to discuss it because of when I will talk.

1143
02:05:21.930 --> 02:05:29.230
Soumen Deb .: Okay, but what I'm trying to ask is, not in this, next time also, the reinforcement learning.

1144
02:05:29.630 --> 02:05:37.470
Faculty (Olympus): Yes. Yeah, that I don't know. To be honest, I don't know. I don't think they will cover reinforcement one. Because that's a fairly.

1145
02:05:39.310 --> 02:05:42.120
Faculty (Olympus): It's a bit niche. I mean, not everyone does RN.

1146
02:05:42.380 --> 02:05:45.529
Faculty (Olympus): Of course, everyone who's training LLMs now does RL, but.

1147
02:05:47.850 --> 02:05:48.580
Soumen Deb .: Okay.

1148
02:05:48.920 --> 02:05:49.530
Faculty (Olympus): Okay.

1149
02:05:49.890 --> 02:05:50.899
Soumen Deb .: OK, we'll wait.

1150
02:05:50.900 --> 02:05:56.639
Faculty (Olympus): I really don't know. You'll have to check the syllabus of the courses. And it may change also depending on the instructor.

1151
02:05:59.260 --> 02:06:00.380
Soumen Deb .: Yeah, thank you, thank you.

1152
02:06:01.060 --> 02:06:02.419
Faculty (Olympus): Okay, good luck.

1153
02:06:03.160 --> 02:06:05.819
Faculty (Olympus): Wish you all the best, I don't see any more questions, soâ€¦

1154
02:06:06.080 --> 02:06:09.979
Faculty (Olympus): Have a good Sunday. Don't worry too much. Okay, you'll do fine.

1155
02:06:10.330 --> 02:06:11.730
Dinesh Devnath Yadav .: Thank you. Thank you. Thank you.

1156
02:06:11.730 --> 02:06:13.380
Faculty (Olympus): Okay, bye.

1157
02:06:13.380 --> 02:06:13.840
Anand Kumar: the.

1158
02:06:15.150 --> 02:06:16.170
Vidya Gavel .: Thank you, bye-bye.

1159
02:06:16.170 --> 02:06:17.309
Soumen Deb .: Thank you, thank you.

