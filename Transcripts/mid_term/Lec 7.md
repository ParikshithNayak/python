WEBVTT

1
00:10:59.680 --> 00:11:01.030
Faculty (Olympus): Morning, everyone.

2
00:11:02.740 --> 00:11:04.029
Dinesh Devnath Yadav .: Good morning, Professor.

3
00:11:04.030 --> 00:11:05.269
Roshan Mathane .: We're running the process.

4
00:11:09.190 --> 00:11:10.919
Faculty (Olympus): Sorry, I'm a bit late today.

5
00:11:10.920 --> 00:11:11.490
Srikanta Kumar Parida .: Funny.

6
00:11:12.130 --> 00:11:13.020
Dinesh Devnath Yadav .: No problem.

7
00:11:46.880 --> 00:11:50.590
Faculty (Olympus): Dude, let me share my screen.

8
00:11:52.030 --> 00:11:53.750
Dinesh Devnath Yadav .: How's your health, professor?

9
00:11:58.100 --> 00:11:59.999
Faculty (Olympus): I hope no screen is visible.

10
00:12:01.030 --> 00:12:01.770
Dinesh Devnath Yadav .: Yes.

11
00:12:02.070 --> 00:12:02.990
Jasmine Samant .: Yes, Professor.

12
00:12:03.030 --> 00:12:03.580
Amlan Sarkar .: Yes.

13
00:12:04.750 --> 00:12:05.429
Ankit Singh: Happy Teas.

14
00:12:05.430 --> 00:12:12.130
Faculty (Olympus): Let me set up myâ€¦ so, if there are questions, I can answer them for a few minutes now, butâ€¦

15
00:12:14.610 --> 00:12:17.140
Faculty (Olympus): While I do that, let me set up my headphones.

16
00:12:19.320 --> 00:12:20.500
Faculty (Olympus): Hello, thank you.

17
00:12:20.970 --> 00:12:25.599
Faculty (Olympus): For theâ€¦ Kind wishes. Happy Teacher's Day, too.

18
00:12:26.050 --> 00:12:34.089
Faculty (Olympus): all the teachersâ€¦ Classâ€¦ Yeah, soâ€¦

19
00:12:35.000 --> 00:12:38.279
Faculty (Olympus): I don't see any hand raises so far.

20
00:12:39.370 --> 00:12:43.560
Faculty (Olympus): If you have a question, just raise your hand, otherwise I'll just start the class in a moment, we'll wait.

21
00:12:50.900 --> 00:12:55.490
Faculty (Olympus): All right, okay, so it looks like there are no major questions at this point.

22
00:12:55.830 --> 00:12:58.049
Faculty (Olympus): Happy Teacher's Day, thank you very much.

23
00:12:59.290 --> 00:12:59.970
Amlan Sarkar .: Dang.

24
00:13:02.860 --> 00:13:03.750
Amlan Sarkar .: Fair.

25
00:13:04.080 --> 00:13:04.840
Faculty (Olympus): Yes?

26
00:13:05.020 --> 00:13:11.699
Amlan Sarkar .: Yesterday, during the last class, na, we haveâ€¦ we are facing some issues with that slider part.

27
00:13:11.840 --> 00:13:17.059
Amlan Sarkar .: Actually, we have been able to resolve that. That was because of the caching.

28
00:13:17.980 --> 00:13:20.210
Amlan Sarkar .: Hmm, okay. That was usual.

29
00:13:20.620 --> 00:13:24.139
Faculty (Olympus): So you basically had to, delete your cache, orâ€¦

30
00:13:24.140 --> 00:13:25.570
Amlan Sarkar .: Yeah, yeah, yes, yes.

31
00:13:28.190 --> 00:13:29.949
Faculty (Olympus): Thank you for letting me know.

32
00:13:32.170 --> 00:13:37.439
Faculty (Olympus): Alright, so let's start, since,

33
00:13:37.760 --> 00:13:40.409
Faculty (Olympus): Questions? We'll stop for questions later.

34
00:13:43.200 --> 00:13:51.180
Faculty (Olympus): So I'll just quickly go back to what we were discussing in the last class, so go through this once again, in case you have questions, and then we'llâ€¦

35
00:13:51.770 --> 00:13:52.780
Faculty (Olympus): Go ahead.

36
00:13:53.230 --> 00:13:58.109
Faculty (Olympus): So the idea here is we're trying to see what this probabilistic programming is all about.

37
00:13:58.280 --> 00:14:04.299
Faculty (Olympus): And we are looking atâ€¦ Initially, we're just looking at how these random number generators

38
00:14:05.320 --> 00:14:08.809
Faculty (Olympus): are available in NumPy, and how we can use them.

39
00:14:09.240 --> 00:14:20.139
Faculty (Olympus): Okay, so the first example I cited was the np.random.rand function, where we have two important arguments, this is the low and the high.

40
00:14:20.290 --> 00:14:22.410
Faculty (Olympus): And the high value is not used.

41
00:14:22.530 --> 00:14:30.370
Faculty (Olympus): So it's just like the range or slicing. So it includes 0 and 1 here, and you get 50 numbers, and these are all number arrays.

42
00:14:30.700 --> 00:14:45.740
Faculty (Olympus): So, the very next set of material is on NumPy, so, you know, we'll look at NumPy in greater detail, but for now, we just understand that an array is a very efficient data structure that houses these, typically floating-point numbers or integers.

43
00:14:46.780 --> 00:14:58.609
Faculty (Olympus): Then we looked at an example to simulate a four-sided die. It was a trivial thing, where we have values between 1 and 4, so 1, 2, 3, 4. So you can imagine that we have a, you know.

44
00:14:58.620 --> 00:15:07.070
Faculty (Olympus): 10-sided die or 6-sided die, you can easily implement this. And you don't technically require this function, it's just that this function sometimes makes it easier to read.

45
00:15:08.590 --> 00:15:12.060
Faculty (Olympus): Then we looked at, uniformly distributed random numbers.

46
00:15:12.340 --> 00:15:24.820
Faculty (Olympus): Where we had np.random.random, and if you remember, the idea is that here the numbers are uniformly distributed between 0 and 1, which means if I take any segment in 0 to 1, so let's say I take aâ€¦

47
00:15:25.150 --> 00:15:36.340
Faculty (Olympus): 0.1 sized dabba. If I move this dBA anywhere in 01, the probability is equal, and it's the same for allâ€¦ wherever it is. So that's what it means by uniformly distributed random number.

48
00:15:36.400 --> 00:15:53.800
Faculty (Olympus): And I showed you that you can have any shape, so you can generate a random matrix, with elements drawn from such a random distribution, from such a random variable. You can create it like this. I also showed you that you can really create huge number of,

49
00:15:54.030 --> 00:15:55.030
Faculty (Olympus): Values.

50
00:15:56.280 --> 00:16:03.689
Faculty (Olympus): Someone was saying we didn't cover in this class. Yes, we did. We actually went quite a distance on this. We went about halfway down.

51
00:16:04.100 --> 00:16:05.590
Faculty (Olympus): this, notebook.

52
00:16:05.930 --> 00:16:13.149
Faculty (Olympus): So, the nice thing about having this random number generator support is the fact that

53
00:16:13.560 --> 00:16:20.949
Faculty (Olympus): I can generate very large number of such random numbers very quickly, right? So this is a million numbers, and then I plotted this.

54
00:16:21.460 --> 00:16:30.240
Faculty (Olympus): with a histogram, a density plot, and you can see that, essentially, it's close to 1 within experimental L. And as the numbers keep increasing, it'll go towards a uniform.

55
00:16:30.480 --> 00:16:36.769
Faculty (Olympus): And this is exactly what I meant when I just explained this to you earlier. So here, notice we have some bins.

56
00:16:36.970 --> 00:16:51.689
Faculty (Olympus): And if you notice, the area under each of the bins, which means the height times the width, the width is the same. So the height is roughly the same, and therefore theâ€¦ allâ€¦ no matter where I place this box, the probability is almost the same, essentially close to 1.

57
00:16:51.830 --> 00:16:56.639
Faculty (Olympus): That's what meanâ€¦ that's what we mean by saying it's a uniformly distributed window.

58
00:16:57.590 --> 00:17:14.389
Faculty (Olympus): On the other hand, so then I showed you very quickly that random numbersâ€¦ so the idea behind this exercise was to say, okay, we have random numbers between 0 and 1, and I want to now generate, again, random variants in the region minus 1 to 1 using, again, with uniform distribution. It's important that they need to be uniform.

59
00:17:15.390 --> 00:17:19.330
Faculty (Olympus): And to do this, it's just as simple as multiplying by 2 and subtracting 1.

60
00:17:19.670 --> 00:17:34.549
Faculty (Olympus): And so, the key thing to remember here is, if you think of a set of random numbers that you're generating, don't think of it as some magic. They're just numbers, okay? So, it's like, we have the example I cited in the last class is if you have weights of students in class.

61
00:17:36.700 --> 00:17:52.230
Faculty (Olympus): Right? If you have them in kilograms, you can convert them to pounds, or you have temperatures and centigrade, you can convert them. So you can do any kind of transformation to these random variables, in the sense that for every value, you can transform it to something else, okay? And this is something you'll probably

62
00:17:52.430 --> 00:17:57.790
Faculty (Olympus): I've already done what you're going to be doing, in your, stats course.

63
00:17:58.080 --> 00:18:02.039
Faculty (Olympus): You'll have to excuse me, there's someone at the door, I'll just be right back.

64
00:18:02.210 --> 00:18:03.919
Faculty (Olympus): Just 30 seconds.

65
00:18:31.160 --> 00:18:33.219
Faculty (Olympus): Sorry for the interruption, I'm back.

66
00:18:33.910 --> 00:18:50.100
Faculty (Olympus): All right, so, the point I was trying to make is that random variables, they're a set of numbers, so you can think of them like a column in, say, a spreadsheet or something like that. And so you can doâ€¦ you can transform these quantities to something else. So I'm just saying that they're just like other numbers in this case.

67
00:18:50.360 --> 00:19:02.970
Faculty (Olympus): Now, once you do a transformation, if it's a linear transformation, it's easy to figure out what it is going to become, but if it's not linear, then the distribution of the eventual thing is going to change, okay? So we'll keep thisâ€¦ just keep that in mind.

68
00:19:05.240 --> 00:19:10.579
Faculty (Olympus): And when I mean distribution, I mean this. The density function will change if I do a different transformation.

69
00:19:11.160 --> 00:19:22.410
Faculty (Olympus): But the really nice thing about the tools that we have built so far is you can actually find out how this is supposed to look by simply plotting a histogram as a densities.

70
00:19:24.800 --> 00:19:30.530
Faculty (Olympus): We have other kinds of random numbers as well, and when I say other random numbers, it means they haveâ€¦

71
00:19:30.720 --> 00:19:47.070
Faculty (Olympus): known distributions. For example, if you want a normally distributed random variable, you can just use np.random.normal, okay? So here's the example, which we ran last class, and you can see that this looks like a familiar Gaussian.

72
00:19:48.140 --> 00:19:51.600
Faculty (Olympus): I think we stopped here. Soâ€¦

73
00:19:52.840 --> 00:19:59.819
Faculty (Olympus): maybe, let me elaborate what I was trying to say here. So, if we take this set of X values, right?

74
00:20:00.610 --> 00:20:04.549
Faculty (Olympus): I thinkâ€¦ okay, I've not run it yet, so run it, I get this.

75
00:20:04.980 --> 00:20:08.219
Faculty (Olympus): Now, let me have a couple of cellsâ€¦

76
00:20:16.600 --> 00:20:22.370
Faculty (Olympus): Okay, so now let me say I do some non-trivival transformation to X. So let's say I take,

77
00:20:22.580 --> 00:20:27.050
Faculty (Olympus): sine of x, okay? So if I did pl.histe.

78
00:20:27.960 --> 00:20:30.360
Faculty (Olympus): X, you know, this is what you get.

79
00:20:30.800 --> 00:20:35.080
Faculty (Olympus): But here, I'm going to say PLT of, say, sine of X, VINs is equal to auto.

80
00:20:38.160 --> 00:20:44.040
Faculty (Olympus): Let me not do sine of X, let me start with something elementary, right? So X star X PX squared.

81
00:20:44.410 --> 00:20:46.389
Faculty (Olympus): I'm gonna say density is 2.

82
00:20:50.760 --> 00:20:53.010
Faculty (Olympus): Notice that the distribution has changed.

83
00:20:54.130 --> 00:20:59.719
Faculty (Olympus): Alright, so I originally had something that's uniformly distributed, but now I have something that looks like this.

84
00:21:00.780 --> 00:21:07.290
Faculty (Olympus): So, the nice thing is, of course, we don't know the functional form of this. If you want the functionalâ€¦ oops, signâ€¦

85
00:21:08.770 --> 00:21:22.579
Faculty (Olympus): This also has changed. So now, since, if you want a functional form, you have to do this formula, as in you have to know the distribution, you have to perform an integral, you have to find the cumulative distribution function, differentiate it, and then you'll get a symbolic thing.

86
00:21:22.580 --> 00:21:28.939
Faculty (Olympus): But if you just want to get a sense of how this thing looks like, all you're doing is plt.hist, which is going to give you

87
00:21:29.100 --> 00:21:33.530
Faculty (Olympus): The transformed random variables, probability density function, or cumulative distribution function.

88
00:21:33.760 --> 00:21:36.450
Faculty (Olympus): Okay, so if we want a cumulative distribution function.

89
00:21:40.410 --> 00:21:41.639
Faculty (Olympus): Can you get this.

90
00:21:41.920 --> 00:21:47.080
Faculty (Olympus): Okay? So, just keep this in mind, that, you know.

91
00:21:47.300 --> 00:21:55.929
Faculty (Olympus): This is an extremely powerful, even though you think it's just, okay, histograms, it's, you know, really powerful. It's an easy way for you to understand random variables, univariate random variables.

92
00:21:57.620 --> 00:22:04.790
Faculty (Olympus): All right, so now, let us move on. Any questions at this point?

93
00:22:05.140 --> 00:22:08.729
Faculty (Olympus): Yeah, I'd stop here for a few minutes of questions.

94
00:22:12.130 --> 00:22:15.380
Niraj Kumar Mishra .: Sir, I have one question, this is Niraj.

95
00:22:15.680 --> 00:22:21.450
Faculty (Olympus): Yes, one second, let me justâ€¦ my chat window has become veryâ€¦ one second.

96
00:22:22.460 --> 00:22:23.170
Faculty (Olympus): Summ.

97
00:22:23.290 --> 00:22:25.629
Faculty (Olympus): I can't keep track of the chat, just a second.

98
00:22:28.230 --> 00:22:29.570
Faculty (Olympus): Huh. All right.

99
00:22:29.720 --> 00:22:31.540
Faculty (Olympus): Niraj, please ask a question.

100
00:22:31.790 --> 00:22:43.090
Niraj Kumar Mishra .: Sir, what is the difference between random.random and random.normal? I didn't get it quite well, and in which case, we have to use these two functions.

101
00:22:43.960 --> 00:22:47.310
Faculty (Olympus): Soâ€¦ this plot should answer your question.

102
00:22:47.740 --> 00:22:52.390
Faculty (Olympus): If I do X is NP random random, the distribution of points I get is this.

103
00:22:53.150 --> 00:22:55.910
Faculty (Olympus): So it's uniformly distributed between 0 and 1.

104
00:22:56.230 --> 00:23:03.800
Faculty (Olympus): If I do np.normal, np.random.normal, I get a distribution that looks like this. This is a Gaussian distance.

105
00:23:05.590 --> 00:23:17.150
Faculty (Olympus): So the probability density function of a normally distributed random variable is normally distributed. The probability density function of a uniformly distributed random variable is uniformly distributed, between 0.

106
00:23:17.890 --> 00:23:25.080
Faculty (Olympus): When would you use each of these? It depends on the actual random variable that you're trying to simulate.

107
00:23:29.080 --> 00:23:29.990
Niraj Kumar Mishra .: Okay.

108
00:23:30.470 --> 00:23:31.240
Faculty (Olympus): Okay?

109
00:23:31.560 --> 00:23:32.130
Niraj Kumar Mishra .: Nope.

110
00:23:33.240 --> 00:23:34.550
Faculty (Olympus): Alright, Abhineet?

111
00:23:35.780 --> 00:23:40.920
Abhineet Bansal: two dogs here. In the first one, we found it to be great functions there.

112
00:23:40.920 --> 00:23:44.590
Faculty (Olympus): Sorry, your voice is not very clear.

113
00:23:45.400 --> 00:23:47.380
Abhineet Bansal: Am I audible now, sir? Trying to speak louder?

114
00:23:47.380 --> 00:23:48.370
Faculty (Olympus): Yeah, yeah.

115
00:23:49.210 --> 00:23:57.139
Abhineet Bansal: In the first function that you've drawn, the first graph, can the area under the graph be more than one? Some of the spikesâ€¦ No.

116
00:23:57.140 --> 00:23:59.199
Faculty (Olympus): Area under the graph will not be more than one.

117
00:24:00.710 --> 00:24:03.029
Faculty (Olympus): By definition, it cannot be more than one.

118
00:24:03.440 --> 00:24:04.270
Faculty (Olympus): Right?

119
00:24:04.700 --> 00:24:05.320
Faculty (Olympus): Butâ€¦

120
00:24:05.340 --> 00:24:06.200
Abhineet Bansal: Added.

121
00:24:06.200 --> 00:24:10.600
Faculty (Olympus): So, please remember, for a density function, a density function cannot be negative.

122
00:24:11.400 --> 00:24:13.410
Faculty (Olympus): But it does not have to be less than 1.

123
00:24:13.540 --> 00:24:17.780
Faculty (Olympus): It's only the integral of the density function that has to be equal to 1.

124
00:24:19.990 --> 00:24:20.650
Abhineet Bansal: Okay.

125
00:24:22.810 --> 00:24:30.670
Abhineet Bansal: Thanks, and in the second question, sir, where you've drawn the normal distribution, can you explain what is this N of C is equal to 0.01 scale.

126
00:24:30.670 --> 00:24:34.160
Faculty (Olympus): Sorry, what was the word you said? Can I explain what? The word was not clear.

127
00:24:34.160 --> 00:24:40.479
Abhineet Bansal: The normal distribution graph that we brought, sir, can you explain what is this LOC equal to 0.0 and.

128
00:24:40.480 --> 00:24:45.369
Faculty (Olympus): Okay, so LOC, so if you look at the doc string, it'll tell you LOC is basically

129
00:24:45.520 --> 00:25:00.439
Faculty (Olympus): the mean of the distribution, and scale is the standard deviation. So, a normal distribution, so onceâ€¦ I don't know if you've covered this in your stats course, a normal distribution is governed by two parameters. One is the mean, the other is the standard deviation. Only two parameters are necessary.

130
00:25:00.450 --> 00:25:07.820
Faculty (Olympus): So this is the reason why random variables are useful. So Iâ€¦ I don't know how much you have covered in your random variable score, you know, stat scores.

131
00:25:11.330 --> 00:25:12.720
Abhineet Bansal: I'll send an introduction.

132
00:25:12.720 --> 00:25:14.400
Soumen Deb .: Not covered today. Not covered.

133
00:25:14.400 --> 00:25:15.360
Abhineet Bansal: This is not similar.

134
00:25:15.360 --> 00:25:18.370
Faculty (Olympus): So, you will be covering it very soon.

135
00:25:19.240 --> 00:25:20.999
Faculty (Olympus): He will be covering it very soon.

136
00:25:23.950 --> 00:25:27.500
Abhineet Bansal: Okay, so we are giving here the mean and the standard deviation.

137
00:25:27.500 --> 00:25:34.669
Faculty (Olympus): Yes, so the pointâ€¦ so, okay, let meâ€¦ maybe before we get to it in stats, let me just quickly explain to you why this is useful.

138
00:25:34.880 --> 00:25:36.319
Faculty (Olympus): See,

139
00:25:36.700 --> 00:25:46.670
Faculty (Olympus): In many cases, you kind of can guess, or can have a good sense of what kind of a random variable you can expect.

140
00:25:46.930 --> 00:25:48.720
Faculty (Olympus): Okay?

141
00:25:50.050 --> 00:25:55.779
Faculty (Olympus): So, for example, I'll give you a very simple example. If you have any quantity that is true or false.

142
00:25:56.280 --> 00:25:59.169
Faculty (Olympus): Okay, like a coin plus. True, false.

143
00:25:59.890 --> 00:26:02.929
Faculty (Olympus): That random variable is Bernoulli runs.

144
00:26:03.170 --> 00:26:05.339
Faculty (Olympus): If you have a quantity that is

145
00:26:06.910 --> 00:26:09.930
Faculty (Olympus): N of these, so I haveâ€¦ No.

146
00:26:10.770 --> 00:26:22.069
Faculty (Olympus): For example, I have something where you know programming, you don't know programming, okay? In class. And I have N students. Now, if I want to say, you know, what is the count

147
00:26:22.200 --> 00:26:37.659
Faculty (Olympus): of theâ€¦ if I take a sample of students, what is the number of students who is going to know Python and the number who is not going to know Python, okay? So this is also a random variable, but this will beâ€¦ this will be distributed like a binomial distribution, okay?

148
00:26:37.790 --> 00:26:46.349
Faculty (Olympus): So, like this, there are many such well-known examples, well-known cases, where If you know

149
00:26:46.760 --> 00:26:51.770
Faculty (Olympus): something about the random variable, you actually know the distribution. And once you know that.

150
00:26:51.950 --> 00:27:11.190
Faculty (Olympus): All you need isâ€¦ the nice thing about these known distributions, like normal distribution, uniform distribution, things like that, is that they are governed by one or two parameters, and you can estimate those parameters. Once you estimate those parameters, you know everything there is to know about that random variable, because you know the probability density function. Am I making sense?

151
00:27:11.720 --> 00:27:28.309
Faculty (Olympus): So, if you remember Sachin's scores, you could answer a lot of very interesting questions, right? You could say, what's the probability that Sachin or Poli can basically score, you know, what's the probability that they're going to cross 100, given that they've crossed something, or given that they've reached their 90s, or whatever? You can ask a whole host of questions.

152
00:27:28.930 --> 00:27:35.640
Faculty (Olympus): The reason is, you haveâ€¦ The probability density function, or at least the empirical probability density function, right?

153
00:27:35.830 --> 00:27:47.489
Faculty (Olympus): So now, supposing I tell you there's some physical process, or, you know, for example, you know, number of accidents in a road, okay? You can model it using a specific random variable, like a Poisson distribution.

154
00:27:47.880 --> 00:28:02.909
Faculty (Olympus): Which is governed by a single parameter. And there's an easy way to estimate that parameter from the data. So now, if I know that, I can actually model that whole thing. Okay, so this is why these sort of random variables that are well-known and well-established are so important.

155
00:28:03.780 --> 00:28:05.080
Faculty (Olympus): Does it make sense?

156
00:28:06.640 --> 00:28:23.760
Faculty (Olympus): And whatâ€¦ and what Python does now is it allows you to simulate this, so I don't have to go and do a physical experiment. If I say, yeah, I'm going to expect this, what are myâ€¦ what are theâ€¦ can I give you some confidence interval? Can I give you some numbers from this? We will actually do a small exercise towards the end of this notebook.

157
00:28:23.760 --> 00:28:29.039
Faculty (Olympus): Right? So you can do those kind of simulations very easily with something. That's the idea.

158
00:28:29.780 --> 00:28:33.259
Abhineet Bansal: So, sir, can random numbers not have any kind of distribution?

159
00:28:33.810 --> 00:28:37.069
Faculty (Olympus): No, by definition, a random variable will always have a distribution.

160
00:28:37.790 --> 00:28:40.320
Faculty (Olympus): That's the definition. A random variable is something

161
00:28:40.560 --> 00:28:46.469
Faculty (Olympus): Right, what is the random variable? It has a set of values, it's a mapping from the space of events to the real life.

162
00:28:46.950 --> 00:28:50.859
Faculty (Olympus): Which means it's some number associated with an experiment.

163
00:28:50.960 --> 00:28:56.179
Faculty (Olympus): The experiment has some random, or stochasticity, or, you know, has some randomness associated.

164
00:28:57.450 --> 00:29:11.760
Faculty (Olympus): By definition, a random variable is therefore something that hasâ€¦ acquires some set of values, and for each of those values, there is either a probability mass, or there's a probability density, depending on whether it's discrete or continuous. That's it, that's the definition of a random variable.

165
00:29:14.130 --> 00:29:14.800
Faculty (Olympus): Yeah.

166
00:29:15.490 --> 00:29:16.430
Faculty (Olympus): Shirley?

167
00:29:18.440 --> 00:29:32.669
Shirley Menezes .: Sir, I actually had a question regarding the help text. So, if you go to the, random.random or random.choice, any help text, there's a note there which says that for future code, you need to use, random.generator.

168
00:29:32.670 --> 00:29:33.930
Faculty (Olympus): Yeah, true.

169
00:29:34.170 --> 00:29:35.890
Shirley Menezes .: Why is that, like.

170
00:29:35.890 --> 00:29:41.659
Faculty (Olympus): So, a lot of, you know, a lot of libraries will have APIs that are pulled, like.

171
00:29:41.920 --> 00:29:56.819
Faculty (Olympus): You know, because they aired some 15, 20 years ago, and then they're kind of stuck with those, and there are certain useful things that you can do. So in a lot of these things that I've shown you, I've shown you the most simple and easy way to use them, okay?

172
00:29:56.820 --> 00:29:57.240
Shirley Menezes .: end of the.

173
00:29:57.240 --> 00:29:58.420
Faculty (Olympus): Conditional way of doing it.

174
00:29:58.810 --> 00:30:16.330
Faculty (Olympus): The issue with some of this isâ€¦ so, in a lot of these random number generators that we have here, that I've used, there's implicitly a state, which means the seed that you started with, for example. That seed is some global constant, which is usually a very bad idea, because if someone changes that constant, everybody else is affected.

175
00:30:16.440 --> 00:30:25.150
Faculty (Olympus): So the newer API is basically, say, create a generator, and then that fellow is independent of everybody else. So you can have 5 different generators with 5 different seats.

176
00:30:26.240 --> 00:30:27.639
Faculty (Olympus): Am I making sense?

177
00:30:27.800 --> 00:30:35.189
Faculty (Olympus): there's no common global state that everybody's mucking around with, so therefore it's a useful, you know, it's an API change that will come.

178
00:30:35.890 --> 00:30:51.649
Shirley Menezes .: Okay, so, like, now, let's say, in future, Rah, or now for the later codes or later modelings, more preferable, or I would say mostly generators would be used, random dot generators versusâ€¦

179
00:30:51.650 --> 00:30:56.829
Faculty (Olympus): Sure, yeah, you can useâ€¦ it'sâ€¦ I don't know if thereâ€¦ there's not an explicit deprecation at this point.

180
00:30:56.830 --> 00:30:57.790
Shirley Menezes .: Okay, okay.

181
00:30:57.790 --> 00:31:06.880
Faculty (Olympus): Right, so I don't think they're gonna kill this. It's like, there are some things which have a bad API, like, you know, BINS is 10. It should have been auto all the time, but, well, it's 10.

182
00:31:07.210 --> 00:31:26.180
Faculty (Olympus): They're not going to change it, because there's going to be a lot of code out there that probably relies on it, we don't know. Okay, so making a change like this, until it becomes a deprecation, I wouldn't worry too much about it. And here, I've made this, you know, this particular interface simply because it's much easier to access immediately. Otherwise, I have to tell you, generator KI, and then after that.

183
00:31:26.570 --> 00:31:29.079
Shirley Menezes .: Okay, makes sense.

184
00:31:29.080 --> 00:31:35.010
Faculty (Olympus): even if we look at my Matplotlibâ€¦ if you look at examples on Matplotlib's site, they will not use the API that I've used.

185
00:31:35.130 --> 00:31:42.750
Faculty (Olympus): They will use an axis, and then you will have a method for the access, and all of that. I find that for beginners, that's a bit too complicated.

186
00:31:42.880 --> 00:31:52.419
Faculty (Olympus): But you can feel free to use it. The goal now is to quickly ramp you up, to teach you the basics, and then, of course, you can learn these things and modify your code.

187
00:31:52.420 --> 00:31:53.030
Shirley Menezes .: Okay.

188
00:31:53.030 --> 00:31:59.849
Faculty (Olympus): Nothing sacrosanct. But here, please note, I'm trying to, you know, straddle two territories. I'm trying to look at programming, basic programming.

189
00:32:00.090 --> 00:32:09.690
Faculty (Olympus): programming for data science, and connected to statistics. So I'm, you know, I want to keep things as simple as I possibly can, because for me, the connections are the most important. You can always pick up these things.

190
00:32:09.690 --> 00:32:10.819
Shirley Menezes .: Okay, thank you.

191
00:32:12.260 --> 00:32:13.030
Faculty (Olympus): Soumen?

192
00:32:14.080 --> 00:32:28.960
Soumen Deb .: Yeah. So, just wanted to, understand the point that you have raised. So, using the PMF and the mean, are we saying we will be able to predict what the upcoming data will be? Is thatâ€¦ thatâ€¦

193
00:32:29.330 --> 00:32:32.279
Soumen Deb .: the criteria, sorry, weekend stacks.

194
00:32:32.280 --> 00:32:43.270
Faculty (Olympus): can never predict, with anything that is statistical, you cannot predict. You can'tâ€¦ well, you can predict, but you have to be careful when you say predict, right? Prediction does not mean certain outcome.

195
00:32:43.540 --> 00:32:56.939
Faculty (Olympus): What you're saying is, I can associate a probability with something. So you can basically say, okay, what is the likelihood of something? And still a likelihood, right? What is the chance that Sachin is going to score a century today? You can answer that question based on his past data.

196
00:32:57.730 --> 00:33:10.960
Faculty (Olympus): Is that clear? So now you have a mechanism with which you can give an answer, which everybody can agree on. It's not like, I'm a Sachin fan, you're a Poly fan, and you know, we have very different opinions. It's not based on opinion, it's based on the data, and everybody

197
00:33:11.140 --> 00:33:13.290
Faculty (Olympus): Can get the same result.

198
00:33:14.150 --> 00:33:15.589
Faculty (Olympus): Am I making sense?

199
00:33:15.960 --> 00:33:33.619
Faculty (Olympus): predictions will be probabilistic predictions, which means you will haveâ€¦ you can do lots of interesting things with this. You can also giveâ€¦ you can say, I have an 80% chance, right? Or you can say, you know, the score is going to be between this and this, with so much confidence, right? So you canâ€¦ you can define these sort of

200
00:33:35.730 --> 00:33:42.910
Faculty (Olympus): quantities based on these sort of simulations, right? So, in that sense, you can make a prediction.

201
00:33:44.550 --> 00:33:44.990
Soumen Deb .: Okay.

202
00:33:45.020 --> 00:33:53.200
Faculty (Olympus): Right? It's not like where we conventionally think, can you predict when it's going to rain today? Well, I can't, right? I can only tell you there's a 90% chance of rain today.

203
00:33:54.600 --> 00:34:06.539
Soumen Deb .: So if you take a very bird's-eye view of the system, so it will take the PMF and the mean, determine what the next probable values are, and then maybe, you know what.

204
00:34:06.980 --> 00:34:13.880
Soumen Deb .: Those next models, they do is they actually, you know, give possible outcomes, what they are doing.

205
00:34:13.880 --> 00:34:18.289
Faculty (Olympus): I'm not clear, what are you trying to explain? Are you talking about reality, or are you talking about models?

206
00:34:18.290 --> 00:34:23.479
Soumen Deb .: No, yeah, models only. I mean, like, the Gen AI models, because they always are mentioned, they are probabilistic, so I never.

207
00:34:23.480 --> 00:34:34.220
Faculty (Olympus): Look at even GenAI, even if you look at a small, basic thing, even if you look at a simple neural network and you're trying to optimize it, your optimizer is essentially a stochastic gradient set, which means it's actually using random numbers inside.

208
00:34:35.190 --> 00:34:38.600
Soumen Deb .: So every outcome will beâ€¦ Possibly different.

209
00:34:38.600 --> 00:34:47.290
Faculty (Olympus): Yes. In fact, it should be different, and you're supposed to run multiple runs and find an ensemble, and then, you know, when you see plots, they'll always give you some sort of a bar around it.

210
00:34:47.540 --> 00:34:51.309
Faculty (Olympus): Okay. Basically telling you there's some scattering, you know, how your loss goes.

211
00:34:51.909 --> 00:34:56.209
Soumen Deb .: Okay, makes sense. Okay, understood. Okay, I'm sorry, trying to connect the dots, that's it.

212
00:34:56.210 --> 00:35:16.099
Faculty (Olympus): No, no, no, it's fine. The point is, this is the connection. From next class, again, it'll become more Python, Python stuff. I want this because many courses don't talk about this part, and I think it's an extremely powerful way to understand statistics, and if you don't understand statistics, you're kind of missing some very useful things. So that's the reason I'm spending some time and making sure you understand it.

213
00:35:16.390 --> 00:35:16.950
Faculty (Olympus): Anand?

214
00:35:16.950 --> 00:35:17.570
Soumen Deb .: Thank you.

215
00:35:17.960 --> 00:35:24.279
Anand Kumar: Yeah, so good morning. Sir, my question is about which random function type should we use in which scenarios?

216
00:35:24.780 --> 00:35:26.530
Faculty (Olympus): In which scenarios?

217
00:35:26.700 --> 00:35:31.279
Anand Kumar: So, given a problem, how do I figure out which random function is more preferred in this scenario? Like.

218
00:35:31.400 --> 00:35:31.950
Anand Kumar: Say normal.

219
00:35:31.950 --> 00:35:41.910
Faculty (Olympus): You need the knowledge. You need knowledge about what you expect, right? So, as I said, if I have a coin toss, if I have something that basically has two possible outcomes.

220
00:35:41.910 --> 00:35:42.520
Anand Kumar: Near.

221
00:35:43.110 --> 00:35:50.080
Faculty (Olympus): It's a Bernoulli randomly. If I have something which is a set of n of these, it is a binomial distribution.

222
00:35:50.460 --> 00:35:54.470
Faculty (Olympus): Right? If you haveâ€¦ and there's a whole bunch of these which you'll cover in your stats course.

223
00:35:54.470 --> 00:35:55.330
Anand Kumar: Okay, okay, sure.

224
00:35:55.330 --> 00:36:00.039
Faculty (Olympus): Okay, so the idea is, for example, you'llâ€¦ have you done central limit theorem yet?

225
00:36:00.040 --> 00:36:01.140
Anand Kumar: No, not, not later.

226
00:36:01.140 --> 00:36:05.490
Faculty (Olympus): Not yet. So when you do that, you'll basically find that if you have any random variables.

227
00:36:05.680 --> 00:36:07.970
Faculty (Olympus): Which have finite mean and variance.

228
00:36:08.850 --> 00:36:16.159
Faculty (Olympus): Okay, and there are random numbers, random, variables that do not have finite, variance.

229
00:36:16.620 --> 00:36:19.599
Faculty (Olympus): But if they have finite variants, if you add them.

230
00:36:19.710 --> 00:36:22.139
Faculty (Olympus): So, add the random variable, okay?

231
00:36:22.940 --> 00:36:29.259
Faculty (Olympus): Thenâ€¦ the distribution of the added fellows goes towards a Gaussian.

232
00:36:30.890 --> 00:36:34.079
Faculty (Olympus): Extremely powerful theorem, okay?

233
00:36:34.390 --> 00:36:43.720
Faculty (Olympus): And so, a lot of things where, you know, there are lots of small errors that accumulate to make a largerâ€¦ lots of random variables that add together, right?

234
00:36:44.170 --> 00:36:44.830
Faculty (Olympus): Cool.

235
00:36:45.510 --> 00:36:48.260
Faculty (Olympus): Their distribution tends to be normally distributed.

236
00:36:48.500 --> 00:37:00.459
Faculty (Olympus): So, for example, you have a multi-component system, maybe not a cell phone anymore, but, you know, something which has multiple components, and each of them is a random variable. You add all of them, you get another random variable. This fellow is going to be going towards a normal description.

237
00:37:01.420 --> 00:37:08.220
Faculty (Olympus): Okay, as N becomes large, the number of components become larger and larger, it's going to go towards the normal distribution. That's what the central limit theorem is.

238
00:37:09.950 --> 00:37:21.610
Faculty (Olympus): Right? So, you need to know theâ€¦ that's the reason you learned statistics, because you understand, you know, there are existingâ€¦ there's an existing body of knowledge that sort of has categorized a lot of these things.

239
00:37:21.740 --> 00:37:25.749
Faculty (Olympus): And the part about the programming part is that

240
00:37:26.110 --> 00:37:36.640
Faculty (Olympus): The traditional statistics approach is pen and paper, which means everything is known distributions which have nice mathematical form, so that you can manipulate them in pen and paper.

241
00:37:37.140 --> 00:37:45.190
Faculty (Olympus): But here, what we did with Sachin' scores, for example, is completely unlike that, right? What we did was, we basically said.

242
00:37:45.880 --> 00:37:48.990
Faculty (Olympus): We're gonna use certain scores and treat this as a random variable.

243
00:37:49.810 --> 00:38:03.759
Faculty (Olympus): And so that gives youâ€¦ and then you can do computations using probabilistic programming, which we're going to come to in a little while, and then you'll see the power of this. Basically, you don't need to have known distribution in the sense that it's a mathematically, you know, known distribution.

244
00:38:03.790 --> 00:38:20.610
Faculty (Olympus): But you can do these probabilistic programming things with it, and still get similar statistical results, right? You can estimate quantity, you can estimateâ€¦ you can find the distribution of that quantity, you can find confidence intervals, all of those can be performed with probabilistic programming.

245
00:38:21.040 --> 00:38:23.529
Faculty (Olympus): And it sort of generalizes theâ€¦

246
00:38:23.680 --> 00:38:27.320
Faculty (Olympus): Theoretical way that you would probably study it in a statistics course.

247
00:38:27.870 --> 00:38:29.359
Faculty (Olympus): This reasons is important.

248
00:38:30.560 --> 00:38:33.269
Faculty (Olympus): Alright, so let's move on.

249
00:38:35.170 --> 00:38:46.490
Faculty (Olympus): So, how does the computer generate a random number? So, many of you may know this. Are they really random? How do you tell? Okay, so the first question you ask is, supposing I tell you, hey, I have something that's true.

250
00:38:46.720 --> 00:38:47.619
Faculty (Olympus): If they are random numbers.

251
00:38:47.620 --> 00:38:48.550
Nilesh Mahadik .: I could see it.

252
00:38:48.780 --> 00:38:49.520
Nilesh Mahadik .: I'm sorry.

253
00:38:49.520 --> 00:38:55.060
Faculty (Olympus): Please mute yourselves. Okay. So if you have something that's a random variable.

254
00:38:55.290 --> 00:38:57.709
Faculty (Olympus): How will you tell that it's actually random?

255
00:38:58.600 --> 00:39:07.040
Faculty (Olympus): So you need to think about this. For example, if I were to take this, you know, XS NP random random, and plot a histogram, it looks like this.

256
00:39:07.300 --> 00:39:12.980
Faculty (Olympus): On the other hand, if I did X1 is lean space, that also looks uniformly distributed.

257
00:39:13.040 --> 00:39:29.160
Faculty (Olympus): But one of them is a random variable, the other one is absolutely not a random variable, okay? In the sense that it's perfectly deterministic. So if I look at the sequence of values in X1, the sequence of values are essentially going to be 0, whatever.001, or whatever, right? It's going to keep increasing.

258
00:39:29.160 --> 00:39:33.859
Faculty (Olympus): Here, on the other hand, every number that's gonna come out is going to be a different number.

259
00:39:33.920 --> 00:39:40.690
Faculty (Olympus): Right? It's going to be something in 01, but it's going to be, you know, all over the place. So, the idea is, if I give you a sequence of random numbers.

260
00:39:41.290 --> 00:39:43.249
Faculty (Olympus): As far as you're concerned.

261
00:39:43.480 --> 00:39:50.260
Faculty (Olympus): The random number generator, or the pseudo-random number generator on the computer, generates it in a way that is indistinguishable from

262
00:39:50.640 --> 00:39:55.780
Faculty (Olympus): an actual random number. That is the power of a random number generator, okay? Soâ€¦

263
00:39:59.250 --> 00:40:01.540
Faculty (Olympus): Someone's saying, can you hear me, everyone?

264
00:40:02.520 --> 00:40:03.619
Jasmine Samant .: Yes, we can hear you.

265
00:40:04.100 --> 00:40:04.500
Ashish Kumar .: Supreme.

266
00:40:04.500 --> 00:40:05.260
varun kumar .: Ravijan.

267
00:40:05.260 --> 00:40:07.760
Faculty (Olympus): Alright, okay, sorry. Someone saidâ€¦

268
00:40:07.760 --> 00:40:12.350
Abhineet Bansal: Sorry to intervene here, sir, but the graph shows area more than one in some of the boxes.

269
00:40:12.640 --> 00:40:13.240
Faculty (Olympus): No.

270
00:40:13.880 --> 00:40:15.989
Abhineet Bansal: It's clearly evident, sir, in the graph.

271
00:40:16.190 --> 00:40:16.820
Faculty (Olympus): Nope.

272
00:40:16.940 --> 00:40:18.830
Faculty (Olympus): Which box is greater than one area?

273
00:40:18.830 --> 00:40:20.769
Abhineet Bansal: It looks like the third one, sir.

274
00:40:21.430 --> 00:40:21.920
Faculty (Olympus): Oh.

275
00:40:21.920 --> 00:40:23.199
Abhineet Bansal: It's more than one.

276
00:40:23.200 --> 00:40:24.730
Faculty (Olympus): How do you compute the area?

277
00:40:24.990 --> 00:40:27.459
Faculty (Olympus): It is height times width. What is the width?

278
00:40:28.320 --> 00:40:31.329
Faculty (Olympus): So the area of the total graph should be 1.

279
00:40:33.250 --> 00:40:38.219
Saurav kumar: axis looks like, above 1, if it's the Y axis, right?

280
00:40:38.560 --> 00:40:40.180
varun kumar .: Density is true.

281
00:40:42.680 --> 00:40:50.029
Faculty (Olympus): So, you have a fundamental misunderstanding. If you have a density function, density function does not have to be less than 1.

282
00:40:50.940 --> 00:40:57.390
Faculty (Olympus): For example, if I had these values, let me just now plot theâ€¦ same thing, I'm just multiplying this by 0.1.

283
00:40:59.760 --> 00:41:01.110
Faculty (Olympus): Look at the values.

284
00:41:02.490 --> 00:41:03.340
Faculty (Olympus): Ten.

285
00:41:05.020 --> 00:41:08.480
Faculty (Olympus): Doesn't mean anything, because the width of this willow has now become 0.1.

286
00:41:10.540 --> 00:41:15.160
Faculty (Olympus): Okay, and if you're still not convinced, oh, there's something looking woofy, look at cumulative.

287
00:41:18.330 --> 00:41:20.740
Faculty (Olympus): Yes, fellows, what did I disclore?

288
00:41:21.600 --> 00:41:22.760
Tushar Sachdev .: Salazo.

289
00:41:22.760 --> 00:41:24.120
Faculty (Olympus): Kunal.

290
00:41:24.680 --> 00:41:26.339
Faculty (Olympus): You're motivating this.

291
00:41:26.650 --> 00:41:28.050
Faculty (Olympus): This fellow goes to him.

292
00:41:30.230 --> 00:41:35.660
Faculty (Olympus): Okay, so the definition of the random variable, how it is computed, is you take the total count.

293
00:41:36.680 --> 00:41:38.479
Faculty (Olympus): Divide by total n.

294
00:41:38.980 --> 00:41:43.840
Faculty (Olympus): And then, by the bandwidth. And so, by construction, your area is always going to be 1.

295
00:41:44.520 --> 00:41:47.849
Faculty (Olympus): Okay? It's just that in this vin there's, okay.

296
00:41:47.990 --> 00:41:54.849
Faculty (Olympus): equal higher density, higher density here, slightly lower density for this random variable, right? If I rerun this, I'll get a different distribution.

297
00:41:55.480 --> 00:41:59.969
Faculty (Olympus): Okay? But it's essentially a ROMA, because, again, this is notâ€¦

298
00:42:00.690 --> 00:42:08.890
Faculty (Olympus): This is not the true quantity, this is a sample of 10,000 values from a uniform random variable, okay?

299
00:42:09.370 --> 00:42:17.929
Faculty (Olympus): So, once again, please remember that any sample, any measurement, is only a sample. It is not the true random variable, okay? It's only an instance of that random variable.

300
00:42:19.480 --> 00:42:21.000
Faculty (Olympus): Alright, is that clear?

301
00:42:21.690 --> 00:42:31.099
Faculty (Olympus): Okay, so the basic point is, you can't really tell the difference with very good quality random numbers. Okay, so just looking at a histogram is not enough.

302
00:42:31.240 --> 00:42:49.570
Faculty (Olympus): The main thing you're looking for is there should be no correlation, you know, multiple-level correlation between one value and the next value, which means if I give you a value, there's no way you can predict what the next value in that sequence is going to be. And random number generators are designed to be like that, which means you will get any number anywhere here, and the distribution will be like what you expect it to.

303
00:42:49.570 --> 00:42:51.669
Faculty (Olympus): Okay, so these are called pseudoranglements.

304
00:42:52.200 --> 00:43:11.480
Faculty (Olympus): Now, one of the problems with pseudo-random numbers is thatâ€¦ or with random numbers in general, is you also wantâ€¦ the nice thing about computer science and computers in general is that it's repeatable, right? I run a code, you run a code, in principle, we have built standards and build lots of things so that I get the same results that you get, even if you're using a different architecture of computer, right?

305
00:43:11.600 --> 00:43:14.640
Faculty (Olympus): You're running a Mac, I'm running Linux, nobody's running Windows.

306
00:43:14.780 --> 00:43:19.049
Faculty (Olympus): you'll get the same results, okay? So we want repeatability.

307
00:43:19.220 --> 00:43:30.390
Faculty (Olympus): So this is where you have the seed, and so I didn't cover this earlier, but many of you are already familiar with this. So what the seed is, is basically, it allows you to control the sequence starting point.

308
00:43:31.530 --> 00:43:35.049
Faculty (Olympus): Okay, and so, once you control the starting point, the sequence is fixed.

309
00:43:35.170 --> 00:43:44.289
Faculty (Olympus): But if I were to just give you the sequence, you cannot, given a single value of the sequence, I can't tell you the next number, or the previous number, or the nth number that follows this, okay?

310
00:43:44.680 --> 00:43:50.789
Faculty (Olympus): So, if I look at this, right, notice there's really no pattern between these set of numbers. It's something, can be anything.

311
00:43:51.080 --> 00:43:59.490
Faculty (Olympus): Okay, but if I run this again, notice I get different numbers every time. So if I were to do a computation, you're going to do a computation, we'll get very different numbers if I were to calculate the mean for each of them.

312
00:44:00.070 --> 00:44:03.370
Faculty (Olympus): So, on the other hand, you can set this seed, you can say NPRandomSeed.

313
00:44:03.930 --> 00:44:05.959
Faculty (Olympus): And any seed value is fine.

314
00:44:06.210 --> 00:44:14.129
Faculty (Olympus): If I were to do this, every single time, I will get exactly the same sequence. Okay, so this is a useful way by which you can control

315
00:44:15.080 --> 00:44:23.890
Faculty (Olympus): Your random number generator, and still get some repeatability for statistical measures or statistical quantities that you're computing using these generator kind of models.

316
00:44:24.590 --> 00:44:26.510
Faculty (Olympus): Alright, so just keep this in mind.

317
00:44:27.350 --> 00:44:28.220
Faculty (Olympus): Okay.

318
00:44:28.710 --> 00:44:34.250
Faculty (Olympus): I think this concept, I think everybodyâ€¦ yeah, okay, very quickly, Rahul.

319
00:44:36.720 --> 00:44:41.709
Rahul Joshi .: Professor, just one question. Can you explain the seed part again? Is it, like, a starting point you mentioned, right?

320
00:44:41.710 --> 00:44:46.090
Faculty (Olympus): It's a starting point of the algorithm, okay? So what, basically.

321
00:44:46.270 --> 00:44:49.359
Faculty (Olympus): You can think of it as, you set this number to, say, 123,

322
00:44:49.680 --> 00:44:58.219
Faculty (Olympus): the seed is set, and you get this sequence becomes a set sequence. Okay, so if I change this number to, say, 13, I'll get a different sequence.

323
00:44:59.420 --> 00:45:00.280
Faculty (Olympus): Right?

324
00:45:00.640 --> 00:45:09.420
Faculty (Olympus): But if I set the seed to 13, you set the seat to 13, and both of us run code even at different times, we will get exactly the same set of counts.

325
00:45:10.760 --> 00:45:12.420
Faculty (Olympus): That isâ€¦ that's all it is.

326
00:45:13.920 --> 00:45:21.039
Rahul Joshi .: And sorry, just one more follow-up question. In this, numpy random.random, is it always, returns the values between 0 and 1?

327
00:45:21.040 --> 00:45:24.159
Faculty (Olympus): Yes. NP.random.random is uniformly distributed.

328
00:45:24.850 --> 00:45:29.659
Faculty (Olympus): But the seed will apply to whatever you call, if it's, like, you know, Naura.

329
00:45:30.320 --> 00:45:34.960
Rahul Joshi .: And what if we want the values which are greater than, let's say, between 5 to 10?

330
00:45:37.390 --> 00:45:39.059
Faculty (Olympus): I already answered that question.

331
00:45:39.680 --> 00:45:43.090
Faculty (Olympus): Do you want it uniformly distributed? How do you want it distributed?

332
00:45:48.290 --> 00:46:00.850
Rahul Joshi .: No, sorry, my question was, I thought the random, randomly generating the values between 0 and 1, but uniformly distributed. If I need values, still uniformly distributed, but let's say between 10 and 20.

333
00:46:01.200 --> 00:46:02.339
Rahul Joshi .: Or some other reason.

334
00:46:03.030 --> 00:46:06.090
Faculty (Olympus): Yeah, I explained this with this exercise already.

335
00:46:06.270 --> 00:46:08.150
Faculty (Olympus): Spent quite a bit of time on this.

336
00:46:13.400 --> 00:46:15.759
Faculty (Olympus): So we want 0 to 5, multiply by 5.

337
00:46:15.760 --> 00:46:16.149
Rahul Joshi .: Oh, beautiful.

338
00:46:16.150 --> 00:46:16.960
Faculty (Olympus): And try it.

339
00:46:18.870 --> 00:46:19.310
Rahul Joshi .: Okay, God.

340
00:46:19.310 --> 00:46:23.050
Faculty (Olympus): You'll probably learn the theory for this in your stats course.

341
00:46:24.500 --> 00:46:26.490
Faculty (Olympus): Sidishâ€¦ Soâ€¦

342
00:46:27.870 --> 00:46:31.720
Siddhesh Dinesh Kadam .: Soâ€¦ Sorry, can you hear me, probably?

343
00:46:31.720 --> 00:46:32.680
Faculty (Olympus): Yes, yes.

344
00:46:32.680 --> 00:46:44.630
Siddhesh Dinesh Kadam .: Yeah, okay, soâ€¦ in a large code, right, so once you've entered anandom.seed 13, it thenâ€¦ I'm trying to get my head around, so once this code is entered.

345
00:46:44.800 --> 00:46:49.529
Siddhesh Dinesh Kadam .: The randomness is actually taken away from the entire code.

346
00:46:50.200 --> 00:46:52.660
Faculty (Olympus): So, my question is, what do you mean by randomness?

347
00:46:53.470 --> 00:46:56.800
Siddhesh Dinesh Kadam .: So right now, any timeâ€¦ every time you run, random.run himselfâ€¦

348
00:46:56.800 --> 00:46:58.380
Faculty (Olympus): Your definition of randomness.

349
00:46:58.830 --> 00:47:01.989
Faculty (Olympus): As someone who's studying stats, what is a random variable?

350
00:47:05.400 --> 00:47:11.580
Siddhesh Dinesh Kadam .: Unpredictable is what you would want, but ifâ€¦ that's what you've done, the unpredictability you've taken away.

351
00:47:12.160 --> 00:47:14.790
Faculty (Olympus): Where is it or not? Whereâ€¦ what do you mean is unpredictable?

352
00:47:16.510 --> 00:47:21.660
Faculty (Olympus): So, if you're saying, the world is random, if I jump out of this window, will I fall or not?

353
00:47:22.560 --> 00:47:24.160
Faculty (Olympus): How should I fly upwards?

354
00:47:25.400 --> 00:47:26.200
Siddhesh Dinesh Kadam .: Yeah.

355
00:47:26.800 --> 00:47:34.529
Faculty (Olympus): So, just because there is randomness in certain things, it doesn't mean that the outcome is necessarily, you know.

356
00:47:34.690 --> 00:47:38.300
Faculty (Olympus): There is randomness, yes, but there are certain larger

357
00:47:38.460 --> 00:47:41.730
Faculty (Olympus): Statistical quantities that are going to hold.

358
00:47:42.490 --> 00:47:43.300
Faculty (Olympus): Pradeep?

359
00:47:43.560 --> 00:47:46.419
Faculty (Olympus): If I throw some rock from here, it is going to fall.

360
00:47:46.730 --> 00:47:51.870
Faculty (Olympus): But, if 5 of us took measurements of that rock, there would be slight differences in those measurements.

361
00:47:53.750 --> 00:47:54.420
Siddhesh Dinesh Kadam .: Right.

362
00:47:55.690 --> 00:47:58.770
Faculty (Olympus): So, you are assuming, somehow, thatâ€¦

363
00:47:58.960 --> 00:48:04.940
Faculty (Olympus): If it's random, output should be something. Every time some nonsense should happen. No, that's not what we are saying here.

364
00:48:06.040 --> 00:48:08.599
Faculty (Olympus): So you have an implicit assumption that

365
00:48:09.090 --> 00:48:12.570
Faculty (Olympus): outcome should always be different. Correct. When it's random.

366
00:48:12.700 --> 00:48:15.929
Faculty (Olympus): That's an assumption you're making. That is technically not required.

367
00:48:16.370 --> 00:48:16.760
Siddhesh Dinesh Kadam .: I agree.

368
00:48:16.760 --> 00:48:20.279
Soumen Deb .: The outcome is same, but the measurements might be different.

369
00:48:20.280 --> 00:48:23.329
Faculty (Olympus): Yes, and what I'm saying is, I'm fixing those set of measurements.

370
00:48:23.980 --> 00:48:36.569
Faculty (Olympus): And there is absolutely no correlation between the one measurement and the next measurement. So every random variable that you are so-called sampling is going to be a distribution of values, where there is no correlation between any one of those.

371
00:48:38.480 --> 00:48:40.689
Faculty (Olympus): It's just like, you have a fixed sample.

372
00:48:41.560 --> 00:48:44.280
Faculty (Olympus): Supposing I say you have 1,000 people, you've done a measurement.

373
00:48:45.420 --> 00:48:48.659
Faculty (Olympus): That 1,000 people data is no longer random.

374
00:48:49.280 --> 00:48:51.259
Faculty (Olympus): But it is a sample of a random variable.

375
00:48:51.620 --> 00:48:55.800
Faculty (Olympus): I'm just saying you're fixing your sample now. When you sit the seed, you're essentially fixing your sample.

376
00:48:56.650 --> 00:49:11.670
Siddhesh Dinesh Kadam .: Yeah, so, just to draw that, actually, so if I'm fixing my sample using random.seed13 now, and if I enter this line of code anywhere in my program, does it mean my sample size is always going toâ€¦ it means my sample is always going to come the same?

377
00:49:12.110 --> 00:49:12.800
Faculty (Olympus): Yes.

378
00:49:13.170 --> 00:49:13.630
Siddhesh Dinesh Kadam .: Yes.

379
00:49:13.630 --> 00:49:14.720
Faculty (Olympus): That's why it's repeatable.

380
00:49:15.060 --> 00:49:20.500
Siddhesh Dinesh Kadam .: So, can we then, undo that. Is there a countercode to this?

381
00:49:22.780 --> 00:49:23.920
Faculty (Olympus): That's how you undo it.

382
00:49:24.550 --> 00:49:37.729
Siddhesh Dinesh Kadam .: No, no, what I mean is thatâ€¦ in a sequential manner, right? So let's say as a part of programming, I'm taking 10 samples from 1000 dataset, right? I've taken those samples, and I have to take another 10 samples.

383
00:49:37.900 --> 00:49:47.659
Siddhesh Dinesh Kadam .: what I'm trying to get to is, once this line of code is entered, does it mean that the program is always going to, because the program is always going to select those 10 samples only, but now if I wantâ€¦

384
00:49:47.660 --> 00:49:51.099
Faculty (Olympus): Not only, not only those things, sorry, sorry, sorry, you're missing the point.

385
00:49:51.520 --> 00:49:59.179
Faculty (Olympus): If I had 20 random numbers, it's not like these 20 random numbers is all you're going to get. If I ask for 20 more random numbers, you'll get 20 more random numbers.

386
00:50:01.070 --> 00:50:03.469
Faculty (Olympus): And those will not be the same as what you had.

387
00:50:04.060 --> 00:50:08.439
Faculty (Olympus): It's just that the sequence of these 40 random numbers that you had is fixed.

388
00:50:09.990 --> 00:50:12.289
Faculty (Olympus): So I think you're misunderstanding what this is doing.

389
00:50:14.840 --> 00:50:16.650
Siddhesh Dinesh Kadam .: Okay, I think I'llâ€¦

390
00:50:16.650 --> 00:50:22.699
Faculty (Olympus): So, let's say you have an experiment where you're calling, you need 40 million random numbers, okay?

391
00:50:23.250 --> 00:50:25.320
Faculty (Olympus): First, 20 million random numbers.

392
00:50:25.530 --> 00:50:29.200
Faculty (Olympus): Something. And then you decided, okay, I need 40 more.

393
00:50:30.190 --> 00:50:30.660
Siddhesh Dinesh Kadam .: Hmm.

394
00:50:30.660 --> 00:50:39.400
Faculty (Olympus): You just generate those random numbers, it's just that because you set that seed, the next 40 is also a fixed sequence, but it's perfectly a random distribution of those values.

395
00:50:42.900 --> 00:50:43.490
Siddhesh Dinesh Kadam .: Okay.

396
00:50:44.310 --> 00:50:50.969
Rahul Joshi .: Just one question. Whenever you say sequence is fixed, is it a distribution is fixed, or the actual numbers generated will be fixed?

397
00:50:50.970 --> 00:50:58.620
Faculty (Olympus): look, the distribution has to be fixed anyway, regardless of what specific values you get. I'm saying the specific values are going to be fixed.

398
00:50:59.420 --> 00:51:02.660
Faculty (Olympus): And those values will be distributed according to the original distribution.

399
00:51:03.030 --> 00:51:08.360
Faculty (Olympus): Again, the analogy is with the sample. So, we have a fixed sample, Right?

400
00:51:08.950 --> 00:51:13.479
Faculty (Olympus): You have a fixed population, let's say, and I say, I freeze all of your weight somehow, okay?

401
00:51:14.140 --> 00:51:18.809
Faculty (Olympus): I now say, okay, population of the class is 200, I will now, or whatever, 200 odd.

402
00:51:19.160 --> 00:51:26.010
Faculty (Olympus): Now, whatever numbers I'm going to get, I'm going to get only in thatâ€¦ let's say I have an experiment where I've measured some n number of students.

403
00:51:26.200 --> 00:51:28.959
Faculty (Olympus): It's always going to be the same. Why? Because the same set of students.

404
00:51:37.190 --> 00:51:39.220
Faculty (Olympus): You need to think about this a little more.

405
00:51:40.070 --> 00:51:45.179
Faculty (Olympus): I think you're still struggling with this random variable randomness in this sequence around.

406
00:51:51.390 --> 00:51:53.840
Faculty (Olympus): Sitesh, have I answered your question, orâ€¦ Yes, no.

407
00:51:53.840 --> 00:51:55.100
Siddhesh Dinesh Kadam .: Yes, yes, yes, you should do.

408
00:51:55.100 --> 00:51:56.680
Faculty (Olympus): Okay, fine. Some of?

409
00:51:57.860 --> 00:52:09.209
Samar .: Yes, sir. So, just thinking about this seed only, so are we also saying that everyone who will use the seed 13 and random, they will get the same?

410
00:52:09.210 --> 00:52:09.900
Faculty (Olympus): Yes.

411
00:52:10.380 --> 00:52:11.140
Samar .: Okay.

412
00:52:12.360 --> 00:52:15.450
Samar .: So this is aâ€¦

413
00:52:15.910 --> 00:52:25.759
Faculty (Olympus): It's an algorithm. See, it's a computer program. The computer program is generating these numbers, and it hasâ€¦ allows you this sort of simplistic interface. You can say, okay, I'll tell you where to start.

414
00:52:25.950 --> 00:52:27.619
Faculty (Olympus): You generate the random numbers.

415
00:52:28.270 --> 00:52:29.419
Samar .: I see. Okay.

416
00:52:29.930 --> 00:52:30.870
Samar .: Thanks, Jim.

417
00:52:31.100 --> 00:52:32.380
Faculty (Olympus): Yep. Good luck!

418
00:52:36.930 --> 00:52:54.270
PALAK GOEL .: I understood what you're trying to say, that we have the same sample space and everything. Will the algorithm automatically understand that it has to generate the next 5? In this case, when I again give the same sentence, or do I need to put in some other parameter?

419
00:52:55.140 --> 00:52:56.449
Faculty (Olympus): Hmm, I didn't understand.

420
00:52:56.790 --> 00:52:57.460
PALAK GOEL .: Like,

421
00:52:57.460 --> 00:53:01.989
Faculty (Olympus): So, for example, let me just do this. I'll run this, and then I will run this fellow.

422
00:53:02.560 --> 00:53:03.959
Faculty (Olympus): I'll learn this again.

423
00:53:04.180 --> 00:53:07.650
Faculty (Olympus): I will run this again. You will get exactly the same set of numbers.

424
00:53:08.350 --> 00:53:19.939
Faculty (Olympus): So you can now call one more time, I can say 50 fellows here. It'll give you, but it'll give you in that sequence. So you can think of it as, given a seed, there's a huge infinite sequence of numbers. Not infinite, very, very, very, very large sequence.

425
00:53:20.570 --> 00:53:23.339
Faculty (Olympus): You would basically start taking values from that sequence.

426
00:53:23.960 --> 00:53:29.150
Faculty (Olympus): And if I didn't tell you the seed, there's no way for you to find out what the seed was.

427
00:53:29.500 --> 00:53:34.499
Faculty (Olympus): So, as far as you're concerned, Right? You don't know.

428
00:53:34.960 --> 00:53:36.519
Faculty (Olympus): Still a random number.

429
00:53:37.170 --> 00:53:40.199
PALAK GOEL .: And, this works with random.normal as well.

430
00:53:40.200 --> 00:53:41.020
Faculty (Olympus): Yes.

431
00:53:41.390 --> 00:53:42.730
PALAK GOEL .: Okay, thank you.

432
00:53:42.730 --> 00:53:43.360
Faculty (Olympus): Yes.

433
00:53:44.250 --> 00:53:45.260
Faculty (Olympus): Kedar?

434
00:53:45.690 --> 00:54:00.929
Kedar Digambar Gokhale .: Good morning, sir. I'm just wondering, is there anything really random? Because probably we may not be aware of the event, we may not be aware of the factors which are resulting to particular event, and that might be the reason we are concerned.

435
00:54:00.930 --> 00:54:03.090
Faculty (Olympus): Okay, this is a philosophical question, we can discuss.

436
00:54:03.550 --> 00:54:04.360
Faculty (Olympus): at the end.

437
00:54:04.740 --> 00:54:25.240
Kedar Digambar Gokhale .: No, no, but one small thing, like, if I count the number of flowers bloomed on the tree every morning, it's going to be random, but if I build a probabilistic model of that event, and try to figure out what will be the next day, number of flowers bloomed.

438
00:54:25.240 --> 00:54:33.410
Kedar Digambar Gokhale .: would it help me to study the factors behind it? Like, I can assign some factors and study this event.

439
00:54:35.150 --> 00:54:38.400
Faculty (Olympus): Once again, so the thing is, again, you'll get a probabilistic outcome.

440
00:54:39.100 --> 00:54:43.820
Kedar Digambar Gokhale .: Yes, and if I correlate that with the real life tomorrow morningâ€¦

441
00:54:43.820 --> 00:54:47.710
Faculty (Olympus): That is how all experiments, you know, real-world experiments are performed, right?

442
00:54:47.710 --> 00:54:49.190
Kedar Digambar Gokhale .: Okay.

443
00:54:49.190 --> 00:54:57.149
Faculty (Olympus): You do a measurement, you have no guarantee of anything, right? So you basically do lots of measurements, and then you plot error bars, you say, okay, this is how it is distributed, so on and so forth.

444
00:54:57.150 --> 00:54:58.520
Kedar Digambar Gokhale .: Yeah, okay.

445
00:54:58.520 --> 00:55:00.169
Faculty (Olympus): Okay, got it. Abhishek?

446
00:55:02.750 --> 00:55:08.020
Abhishek Raghuvanshi .: Yeah, there is a statement, that, you know, mentioned in your slide, regarding

447
00:55:08.220 --> 00:55:11.830
Abhishek Raghuvanshi .: the generator not be non-revered. What does it mean?

448
00:55:12.640 --> 00:55:14.689
Faculty (Olympus): Yeah, don't write your own, is what I mean.

449
00:55:15.040 --> 00:55:19.490
Faculty (Olympus): Don't think, oh, there's some linear congruential generator.

450
00:55:19.600 --> 00:55:22.389
Faculty (Olympus): Okay, don't write your ownâ€¦ It's not easy to write.

451
00:55:23.000 --> 00:55:23.960
Abhishek Raghuvanshi .: Okay, okay.

452
00:55:24.020 --> 00:55:30.900
Faculty (Olympus): Random number generator is an art. Doing it correctly is not trivial, in the sense that it's very difficult.

453
00:55:31.810 --> 00:55:39.739
Abhishek Raghuvanshi .: So basically, the random number is simulating the randomness, that's all. And if it purely talk in terms of probability.

454
00:55:39.900 --> 00:55:46.529
Abhishek Raghuvanshi .: All the chance of picking any particular number, which is,

455
00:55:46.830 --> 00:55:50.889
Abhishek Raghuvanshi .: Which is equal in case of when we are doing assembling.

456
00:55:51.130 --> 00:55:57.470
Abhishek Raghuvanshi .: That is not true, because there is a pattern that it follows, although the numbers are not correlated to each other, but still that

457
00:55:57.650 --> 00:56:01.999
Abhishek Raghuvanshi .: That is not very similar in the same sense as we have read in probability.

458
00:56:02.810 --> 00:56:04.579
Faculty (Olympus): I didn't understand, I'm sorry.

459
00:56:05.950 --> 00:56:15.779
Abhishek Raghuvanshi .: No, so I'm saying that, usually we say that if I have to pick randomly, it means that all the chances of picking any particular item from a set

460
00:56:16.120 --> 00:56:18.829
Abhishek Raghuvanshi .: Isâ€¦ is the same. The probability is the same.

461
00:56:18.830 --> 00:56:21.690
Faculty (Olympus): That is if it's uniformly distributed. So you're sampling uniformly.

462
00:56:21.850 --> 00:56:22.410
Abhishek Raghuvanshi .: Yeah.

463
00:56:22.620 --> 00:56:23.290
Faculty (Olympus): Okay.

464
00:56:25.110 --> 00:56:30.920
Abhishek Raghuvanshi .: So that's not true, because it is simulating those random numbers in an aggregate basis, we'll get the same distribution.

465
00:56:30.920 --> 00:56:37.590
Faculty (Olympus): But in an aggregate basis, even ifâ€¦ okay, that you're telling me that if I coin toss this, aggregate basis, something is going to change? No.

466
00:56:38.100 --> 00:56:41.500
Faculty (Olympus): This is where I think you'reâ€¦ a lot of you are getting really confused about this.

467
00:56:42.890 --> 00:56:47.600
Faculty (Olympus): The aggregate basis is a statistical quantity you're calculating with a bunch of values.

468
00:56:47.790 --> 00:56:54.510
Faculty (Olympus): That our reality seems real because, you know, there is consistency in those measurements.

469
00:56:55.800 --> 00:57:00.200
Faculty (Olympus): It's not like G today is 1, tomorrow is minus 1, we'll be flying around, no.

470
00:57:00.410 --> 00:57:05.870
Faculty (Olympus): is roughly 9.81, right? But if I did a measurement, you did a measurement, slight differences are going to show up.

471
00:57:06.430 --> 00:57:12.870
Faculty (Olympus): all this is, is a computer program, right? So it's an algorithm that's generating it. So it's going to generate random numbers.

472
00:57:13.360 --> 00:57:17.599
Faculty (Olympus): which are identical as far as yourâ€¦ see, if I gave you a set of numbers.

473
00:57:17.810 --> 00:57:20.089
Faculty (Olympus): You will not be able to tell what the seed is.

474
00:57:20.580 --> 00:57:27.479
Faculty (Olympus): Unless you've seen exactly that seed. If I give you some crazy seed, and give you a set of numbers, I could pick, say, these four numbers.

475
00:57:28.690 --> 00:57:30.979
Faculty (Olympus): You will not be able to tell what it is.

476
00:57:31.710 --> 00:57:42.599
Faculty (Olympus): The only way you'll be able to tell it is statistical measures. So you'll have to say, okay, get a lot of these numbers, and then plot them, say, yeah, it looksâ€¦ because there is no way you can correlate any of this. The algorithm is designed that way.

477
00:57:45.130 --> 00:57:45.740
Abhishek Raghuvanshi .: Okay.

478
00:57:46.160 --> 00:57:47.559
Faculty (Olympus): Right? Soâ€¦

479
00:57:49.070 --> 00:58:06.179
Faculty (Olympus): In the aggregate sense, absolutely. That's how you get a mean, right? If I have a random variable, it has a mean. In the aggregate sense, that's the mean. But if I were to pick a specific value, so like Sachin, his average may be 40 or whatever, right? Doesn't mean every match he walks out, he's going to score 40. In fact, the largest probability is going to be near 0.

480
00:58:06.450 --> 00:58:07.749
Faculty (Olympus): You saw the data.

481
00:58:08.600 --> 00:58:09.860
Faculty (Olympus): Low scores?

482
00:58:10.160 --> 00:58:14.040
Faculty (Olympus): are the highest probability for it. Okay, the histogram is like this, right?

483
00:58:15.330 --> 00:58:15.890
Abhishek Raghuvanshi .: Yeah.

484
00:58:16.540 --> 00:58:21.510
Abhishek Raghuvanshi .: Yeah, I was not able to explain the question well, but I think that's what exactly.

485
00:58:21.510 --> 00:58:27.320
Faculty (Olympus): Do you understand it now? Do you understand the basic principles? This allows you to do a computer experiment.

486
00:58:27.320 --> 00:58:28.150
Abhishek Raghuvanshi .: Which isâ€¦ Right.

487
00:58:28.150 --> 00:58:33.980
Faculty (Olympus): Indistinguishable from doing an actual experiment out there, so long as your modeling is reasonable.

488
00:58:35.700 --> 00:58:45.160
Faculty (Olympus): This is normal distribution. Reality is some other distribution. Obviously, the statistics are going to be wrong, right? So, your programming is wrong means that is outside the scope of this discussion.

489
00:58:45.450 --> 00:58:45.940
Faculty (Olympus): Right?

490
00:58:45.940 --> 00:58:53.889
Abhishek Raghuvanshi .: So I'm saying that it is not simulating at a trial level, but it isâ€¦ at an aggregate level, it will give that distribution, so that's howâ€¦ for each experiment.

491
00:58:54.020 --> 00:58:58.640
Abhishek Raghuvanshi .: So, if I'm doing, say, 100 experiments, soâ€¦ because it follows a particular pattern once I get.

492
00:58:58.640 --> 00:59:01.540
Faculty (Olympus): Yes, that is by the definition of the fact that it's a random variable.

493
00:59:01.540 --> 00:59:02.060
Abhishek Raghuvanshi .: Right.

494
00:59:02.060 --> 00:59:04.670
Faculty (Olympus): I'm telling you that this is a computer analog of a random variable.

495
00:59:04.880 --> 00:59:07.899
Abhishek Raghuvanshi .: Got it, got it. That's what I was trying to check. Okay, thanks.

496
00:59:07.900 --> 00:59:17.460
Faculty (Olympus): Right? So that's why it's a very powerful thing. I can create a random variable on the computer, get samples, all of that stuff I can do with this. So it's like aâ€¦

497
00:59:18.620 --> 00:59:21.980
Faculty (Olympus): Very convenient system. That's why it's a very powerful idea.

498
00:59:22.230 --> 00:59:23.230
Faculty (Olympus): Gaurav.

499
00:59:24.570 --> 00:59:34.509
Gaurav Singh .: Yeah, Professor, so, wanted to ask that, like, generally we talk about the sample space and, you know, so in that we consider

500
00:59:34.880 --> 00:59:48.530
Gaurav Singh .: the events will follow a pattern, right? Like, for example, binomial distribution or poison distribution. We know that what would be the pattern of our sample, right? So, what is theâ€¦ So, I think you should use the.

501
00:59:48.530 --> 00:59:50.329
Faculty (Olympus): right words. I mean, I would sayâ€¦

502
00:59:50.460 --> 00:59:55.140
Faculty (Olympus): The right technical way of saying this is, you know the distribution of your Sumple.

503
00:59:55.140 --> 00:59:56.620
Gaurav Singh .: Exactly. Yeah.

504
00:59:56.620 --> 00:59:56.970
Faculty (Olympus): Nope.

505
00:59:56.970 --> 01:00:13.600
Gaurav Singh .: One way, we know the distribution, and generally we discuss or, you know, calculate the mean, medians, and all those analysis we do on top of that kind of data, which we know the sequence or distribution of our random variable. But then.

506
01:00:13.600 --> 01:00:21.730
Gaurav Singh .: What's the purpose of generating such kind of random variable that that doesn't have any distribution pattern? What is theâ€¦

507
01:00:21.820 --> 01:00:23.419
Gaurav Singh .: What is the goal behind it?

508
01:00:23.580 --> 01:00:26.799
Faculty (Olympus): Made some statements here which are scaring me, becauseâ€¦

509
01:00:27.070 --> 01:00:29.739
Faculty (Olympus): Where did I say there is no distribution known here?

510
01:00:30.570 --> 01:00:35.420
Faculty (Olympus): The random.random is going to give you a uniform distribution of random numbers.

511
01:00:35.570 --> 01:00:37.390
Faculty (Olympus): It is uniformly distributed.

512
01:00:39.890 --> 01:00:48.839
Gaurav Singh .: Andâ€¦ What's the meaning of uniform distribution? Sorry, Akshayâ€¦ I could not get that, but, youâ€¦

513
01:00:48.840 --> 01:00:51.259
Faculty (Olympus): Okay, what is the meaning of distribution of numbers?

514
01:00:53.280 --> 01:00:55.689
Faculty (Olympus): You made the statement, I didn't make the statement. What is the meaning?

515
01:00:55.690 --> 01:01:00.950
Gaurav Singh .: of numbers means, it, it follow a functional pattern, probably.

516
01:01:00.950 --> 01:01:02.370
Faculty (Olympus): Why should it have a function?

517
01:01:03.580 --> 01:01:04.490
Gaurav Singh .: Mmmâ€¦

518
01:01:04.490 --> 01:01:10.489
Faculty (Olympus): You mean, say, I should be able to write down, so if Sachin Tindulkar, I should have some mathematical formula for how he's going to generate it?

519
01:01:11.380 --> 01:01:12.200
Gaurav Singh .: No.

520
01:01:12.620 --> 01:01:14.950
Faculty (Olympus): Then what is this data? Is it random?

521
01:01:16.670 --> 01:01:18.940
Gaurav Singh .: Yeah, in that case, it is not random, but.

522
01:01:18.940 --> 01:01:22.359
Faculty (Olympus): Why that case? How is that case different from any other case?

523
01:01:23.030 --> 01:01:27.930
Gaurav Singh .: No, what I was saying is, like, for example, traffic scenario, we were talking about that.

524
01:01:28.060 --> 01:01:37.040
Gaurav Singh .: this kind of distribution of data will be happening, right? So it's not purely random in that sense, but yeah, in this scenario.

525
01:01:37.040 --> 01:01:40.139
Faculty (Olympus): No, no, no, no, no, no, no, no, you have a fundamental misunderstanding here.

526
01:01:40.140 --> 01:01:40.650
Gaurav Singh .: Okay.

527
01:01:40.650 --> 01:01:42.090
Faculty (Olympus): Fundamental misunderstanding.

528
01:01:42.330 --> 01:01:45.369
Faculty (Olympus): Again, you are assuming random is Poojihog.

529
01:01:45.920 --> 01:01:46.600
Gaurav Singh .: Hmm.

530
01:01:47.330 --> 01:01:54.850
Faculty (Olympus): Please throw that notion out of the window. That is wrong. That's a very layman way of thinking of randomness.

531
01:01:55.390 --> 01:02:01.369
Faculty (Olympus): And the whole point of random variables is, I pick a random variable, that random variable has a distribution.

532
01:02:01.550 --> 01:02:03.549
Faculty (Olympus): Which means I have now locked it

533
01:02:03.830 --> 01:02:09.419
Faculty (Olympus): This is now a quantity that has a distribution. And in fact, anything you consider.

534
01:02:09.600 --> 01:02:13.659
Faculty (Olympus): has a distribution. It's just that you may not know the distribution.

535
01:02:13.880 --> 01:02:23.100
Faculty (Olympus): You may not have a mathematical formula to talk about that distribution, but it has a distribution. Just like such in scores, you cannot write as some formula, sine of x na A.

536
01:02:23.460 --> 01:02:23.910
Gaurav Singh .: Hmm.

537
01:02:23.910 --> 01:02:25.300
Faculty (Olympus): But it has a distribution.

538
01:02:26.360 --> 01:02:33.250
Faculty (Olympus): So, which means it's a universal way of describing how a quantity which has, you know, which is not predictable

539
01:02:33.420 --> 01:02:34.340
Faculty (Olympus): As in?

540
01:02:34.570 --> 01:02:38.809
Faculty (Olympus): When I say predictable, I mean which is not precisely predictable like a computer program.

541
01:02:39.660 --> 01:02:44.140
Faculty (Olympus): How does it behave? And the random variable perfectly characterizes it.

542
01:02:45.040 --> 01:02:56.650
Faculty (Olympus): And what we have here is a mechanism by which, if I tell you, hey, this is uniformly distributed, I can generate numbers which are indistinguishable from uniformly distributed anomaly. So if you want a Poisson distribution.

543
01:02:56.770 --> 01:03:00.600
Faculty (Olympus): If you want a binomial distribution, all of those can be generated.

544
01:03:01.150 --> 01:03:14.599
Faculty (Olympus): So if you want to do a coin toss with 100 coin tosses and do 1 million experiments of 100 coin tosses, it's trivial to do it with this, because I have a computer program which will produce numbers that you cannot distinguish from actually doing an experiment.

545
01:03:15.080 --> 01:03:17.330
Faculty (Olympus): Because, statistically, they are the same.

546
01:03:18.950 --> 01:03:19.780
Gaurav Singh .: Okay.

547
01:03:20.160 --> 01:03:29.530
Gaurav Singh .: So, does it mean that a specific instance of that random variable has the randomness? But if I see the overall distribution has some pattern.

548
01:03:30.220 --> 01:03:30.590
Faculty (Olympus): Yes.

549
01:03:30.590 --> 01:03:31.450
Gaurav Singh .: That'sâ€¦

550
01:03:31.450 --> 01:03:32.749
Faculty (Olympus): Definition of Haranda miracle.

551
01:03:32.750 --> 01:03:41.590
Gaurav Singh .: Yes. So, basically, even in poison distribution, if I want to get theâ€¦

552
01:03:41.590 --> 01:03:47.249
Faculty (Olympus): Yeah, basically saying that if I do an experiment, I randomly pick a student here. Will I find the way to be 65? No.

553
01:03:47.250 --> 01:03:47.600
Gaurav Singh .: No.

554
01:03:47.600 --> 01:03:48.050
Faculty (Olympus): something.

555
01:03:48.050 --> 01:03:49.000
Gaurav Singh .: Okay, understood.

556
01:03:49.000 --> 01:04:07.309
Faculty (Olympus): If I did lots of experiments, I can tell you the statistics of this, and that will give me an approximate distribution of this population. But this, again, is a sample of the true population of the students, right? So it's only one thing, so it's an approximation to the reality that you think there is. So this is the modeling. It's an Râ€¦ it'sâ€¦ you're modeling the population of all possible students.

557
01:04:07.450 --> 01:04:10.810
Faculty (Olympus): And every such measurement is only a finite sample of those.

558
01:04:11.490 --> 01:04:14.230
Gaurav Singh .: Got it. That's very clear. Yeah, thanks.

559
01:04:14.990 --> 01:04:15.870
Faculty (Olympus): Ravi?

560
01:04:17.390 --> 01:04:26.850
Ravi Kumar Pathak .: Sir, my question is related to, you mentioned the state of it, so random variable or random number has a defined state, though we don't know.

561
01:04:26.850 --> 01:04:29.360
Faculty (Olympus): You know, random variable doesn't have state. This isâ€¦

562
01:04:29.900 --> 01:04:33.819
Faculty (Olympus): The random number generator has a state. The random variable has no state.

563
01:04:33.990 --> 01:04:39.230
Faculty (Olympus): Random variable, in fact, if we knew the state is no longer, you know, a very nice random variable, right? I can predict everything there.

564
01:04:40.980 --> 01:04:47.360
Faculty (Olympus): Right? So the random variable doesn't have. This is our model ofâ€¦ this is a way by which I can generate numbers that look

565
01:04:47.780 --> 01:04:48.730
Faculty (Olympus): Random.

566
01:04:49.860 --> 01:04:57.279
Faculty (Olympus): And the seed is a way by which I can control that, so that if I were to do an experiment, you're doing an identical experiment, our results will be the same.

567
01:04:58.820 --> 01:05:00.550
Ravi Kumar Pathak .: Okay, got it. Thank you, Sonu.

568
01:05:00.550 --> 01:05:12.870
Faculty (Olympus): Right? But the sequence of numbers that are generated are indistinguishable from an actual random experiment. It's just that my sample and your sample are the same, right? If I take 5 students in the class, I weigh them, we have the same weighing machine, right, with the same code.

569
01:05:13.050 --> 01:05:18.010
Faculty (Olympus): I weigh them, find the mean, I find the same mean, you'll find exactly the same mean, the same language.

570
01:05:18.890 --> 01:05:21.069
Faculty (Olympus): Right? And of course, at the same instant of time.

571
01:05:21.230 --> 01:05:25.740
Faculty (Olympus): Right? They can't have lunch and dinner and go to the toilet and come back, the weights will change, right?

572
01:05:26.050 --> 01:05:26.500
Ravi Kumar Pathak .: Hmm.

573
01:05:26.500 --> 01:05:30.499
Faculty (Olympus): So I measure them all at the same time, you measure them all at the same time? Yeah, then we haveâ€¦

574
01:05:30.870 --> 01:05:33.559
Faculty (Olympus): You know, we're gonna get the same statistics.

575
01:05:34.000 --> 01:05:37.139
Faculty (Olympus): But are the weights of these 5 fellows going to be the same? No, they're not.

576
01:05:40.320 --> 01:05:44.379
Ravi Kumar Pathak .: The purpose of random variable is mainly for the experimentation.

577
01:05:44.380 --> 01:05:48.559
Faculty (Olympus): No, random variable is different. Random variable is a generalâ€¦ is an abstraction.

578
01:05:48.930 --> 01:05:50.700
Faculty (Olympus): You mean the random number generator?

579
01:05:53.160 --> 01:05:55.410
Ravi Kumar Pathak .: Yes, the valueâ€¦

580
01:05:55.410 --> 01:06:03.130
Faculty (Olympus): Lots of purposes, lots of purposes. When you're sending packets on the network, your network, if there's a collision, it's gonna wait for a random amount of time. So it's used all over the place.

581
01:06:04.120 --> 01:06:06.320
Ravi Kumar Pathak .: Okay, okay, sure. Thank you soâ€¦

582
01:06:06.560 --> 01:06:07.340
Faculty (Olympus): Yep.

583
01:06:07.750 --> 01:06:08.969
Faculty (Olympus): Varun.

584
01:06:10.690 --> 01:06:26.089
varun kumar .: Yeah, Professor, my question is regarding the seed. So, can I understand the seed as, let's say, there is a college and there are many hostâ€¦ hostel rooms? So, one room will be numbered with 13, you know, you used a word, or let's say 5.

585
01:06:26.410 --> 01:06:33.209
varun kumar .: And, whenever I'm going, everybodyâ€¦ I mean, let's say I'm, putting seed is equals to 5,

586
01:06:33.550 --> 01:06:36.799
varun kumar .: There is a set of people living in that room will come out.

587
01:06:36.800 --> 01:06:41.300
Faculty (Olympus): No, so let's not do that analogy, because then I have to start underâ€¦ very simple.

588
01:06:41.780 --> 01:06:44.239
Faculty (Olympus): I want a set of random numbers, right?

589
01:06:44.470 --> 01:06:48.700
Faculty (Olympus): And I want that set of random numbers to be repeatable across multiple computer codes.

590
01:06:49.920 --> 01:06:54.729
Faculty (Olympus): If I just give you theâ€¦ hang on, hang on, if I give you the random numbers.

591
01:06:54.990 --> 01:06:57.159
Faculty (Olympus): They will be distributed according to a pattern.

592
01:06:58.060 --> 01:06:58.380
varun kumar .: Yes.

593
01:06:58.380 --> 01:07:04.890
Faculty (Olympus): So I will guarantee you that. And I will guarantee to you that every number, the next number is unpredictable. I don't know what the next number is going to be.

594
01:07:05.680 --> 01:07:11.129
Faculty (Olympus): In the sense that there's no correlation, if I give you this Bhaihota Nay, nothing, nothing like that, okay?

595
01:07:12.060 --> 01:07:12.770
Faculty (Olympus): Time?

596
01:07:13.350 --> 01:07:14.579
varun kumar .: No, so, let's sayâ€¦

597
01:07:14.580 --> 01:07:20.029
Faculty (Olympus): No, I give you multiple such sequences, so I can control which sequence I pick by setting the C. That's all it is.

598
01:07:21.270 --> 01:07:29.939
varun kumar .: Yeah, so last thing, if you are using that number 5, and I am using the number 5 on my computer, will it be same or different?

599
01:07:31.660 --> 01:07:32.939
Faculty (Olympus): It'll be exactly the same.

600
01:07:33.320 --> 01:07:36.289
Faculty (Olympus): I've answered this both in my lecture as well as to other people.

601
01:07:36.290 --> 01:07:36.700
varun kumar .: No, no.

602
01:07:36.700 --> 01:07:37.230
Faculty (Olympus): the same question.

603
01:07:37.230 --> 01:07:38.160
varun kumar .: I just told me.

604
01:07:38.300 --> 01:07:39.010
varun kumar .: I amâ€¦

605
01:07:39.010 --> 01:07:45.880
Faculty (Olympus): I'm sorry, but I really have to move on, right? I have only 12 classes, I have a lot of material to do, right? Soâ€¦

606
01:07:46.250 --> 01:07:55.849
Faculty (Olympus): If you really are struggling with this, go back to the videos. I try to be very careful with the words that I choose to use, okay? Please, you need to think about this a little longer.

607
01:07:56.060 --> 01:08:00.940
Faculty (Olympus): I don't think having this discussion is going to help everybody else, right? Because there are 200 people waiting.

608
01:08:03.880 --> 01:08:13.399
Faculty (Olympus): Right? Because it's been, like, half an hour of questions on just seed, right? Or 20 minutes of questions, right? So let'sâ€¦ can we pause? If there are more questions on seed, I'm not going to answer them now.

609
01:08:15.080 --> 01:08:20.099
Faculty (Olympus): And you also need to try, you need to experiment, you need toâ€¦ then you'll get a sense of what is going on, okay?

610
01:08:20.100 --> 01:08:29.759
Soumen Deb .: So, so I agree with you, Professor. So, if you copy-paste those two lines which you are highlighting right now, do it two, three times, the same numbers are generated. Maybe that will answer a lot of questions.

611
01:08:29.760 --> 01:08:36.660
Faculty (Olympus): Yes, that's why I did it. I wrote it like this for exactly that reason, okay? And if I change the seed, I will get different sets of numbers.

612
01:08:36.660 --> 01:08:42.499
Soumen Deb .: Yeah. No, no, so what I'm trying to say is, if you copy-paste those two lines, the sequence starts from the same number.

613
01:08:42.500 --> 01:08:42.850
Faculty (Olympus): Yes.

614
01:08:42.850 --> 01:08:43.790
Soumen Deb .: That's what you're trying to say.

615
01:08:43.790 --> 01:08:44.220
Faculty (Olympus): Yes.

616
01:08:44.220 --> 01:08:45.179
Soumen Deb .: Exactly, yeah, thanks.

617
01:08:45.189 --> 01:08:45.749
Faculty (Olympus): Cheops.

618
01:08:47.739 --> 01:08:50.619
Faculty (Olympus): Okay, Ravi, is this something not related to seeds?

619
01:08:52.620 --> 01:08:55.869
Ravi Kumar Pathak .: Sorry, sir, my question is answered. I'll lower myâ€¦

620
01:08:55.870 --> 01:09:03.350
Faculty (Olympus): Okay. Someone is saying that if you just say npandom.se it, it'll set it to unknown. No, it will not set it to unknown, it'll set it to the current time.

621
01:09:03.750 --> 01:09:12.559
Faculty (Olympus): Which, everybody is gonna probably call it at different times, so you'll get some variability in what the exact seed is. That's all. It's just that you've hidden the seed.

622
01:09:12.700 --> 01:09:24.850
Faculty (Olympus): You don't know what that seed value is. That's all, right? And because the sequence is indistinguishable, you can't tell the difference. That's the point I'm trying to make. If I hid out this seed, and give you a sequence of numbers, you cannot find out what it is, right?

623
01:09:25.450 --> 01:09:26.380
Faculty (Olympus): Manu?

624
01:09:29.000 --> 01:09:30.069
Manu Gupta .: Good morning, sir.

625
01:09:30.460 --> 01:09:31.109
Faculty (Olympus): running.

626
01:09:31.529 --> 01:09:35.600
Manu Gupta .: So my point is regarding a pseudo-random number generated.

627
01:09:36.890 --> 01:09:46.409
Manu Gupta .: So, as far as I understood, that pseudo-random numbers are generated by a fixed algorithm, or I would say a deterministic algorithm.

628
01:09:46.600 --> 01:09:53.679
Manu Gupta .: So how we can say whatâ€¦ are these statistically similar to random numbers?

629
01:09:54.870 --> 01:09:56.759
Faculty (Olympus): So, statistically, they are.

630
01:09:56.900 --> 01:09:59.089
Faculty (Olympus): But they are not truly random numbers.

631
01:10:00.920 --> 01:10:06.779
Manu Gupta .: So, if theâ€¦ is the algorithm so that there are not obvious patterns?

632
01:10:06.780 --> 01:10:21.399
Faculty (Olympus): That's why it is absolutely non-trivial, so don't write your own without doing lots of research. Even if you come up with a new algorithm tomorrow, it will not be adopted by the community. You'll have to wait for a long time, ensure that, you know, it's okay, and then only you'll be adopted.

633
01:10:24.010 --> 01:10:25.210
Manu Gupta .: Yep.

634
01:10:26.580 --> 01:10:27.480
Faculty (Olympus): Sajith?

635
01:10:28.880 --> 01:10:32.839
Sajith K N .: Yeah, Saljan, yeah, and generic question. So, weâ€¦

636
01:10:32.840 --> 01:10:34.009
Faculty (Olympus): Okay, general question can be posted.

637
01:10:34.010 --> 01:10:36.340
Sajith K N .: Yeah, Northendrik,

638
01:10:36.510 --> 01:10:50.730
Sajith K N .: about the such statistics, right? Okay. So, we know there is a randomness. So, how do you see if it is a uniform distribution, or some type of distribution? By protein this way, histoâ€¦ histogram, orâ€¦

639
01:10:51.040 --> 01:10:52.150
Sajith K N .: Sorry.

640
01:10:52.150 --> 01:10:53.779
Faculty (Olympus): Can you repeat the question, please?

641
01:10:53.780 --> 01:11:04.900
Sajith K N .: Yeah, the searching data, right? Yeah. So, like, we have a randomness, we use a random, numbers, and then we try to plot uniform distribution, right? Like, curves.

642
01:11:05.100 --> 01:11:09.160
Sajith K N .: So, if you're given practical, such in data.

643
01:11:09.300 --> 01:11:19.219
Sajith K N .: Now, how do weâ€¦ we know there is randomness, right? Like, we explained the randomness of the data. So, either the same technique we use to see what kind of data it is, like.

644
01:11:19.440 --> 01:11:20.490
Sajith K N .: Using theâ€¦

645
01:11:20.490 --> 01:11:23.150
Faculty (Olympus): Are you saying, do you want to fit something to it?

646
01:11:23.150 --> 01:11:29.179
Sajith K N .: Yeah, like that, yeah. I think it's too early, that model fit and all, because, yeah.

647
01:11:29.180 --> 01:11:31.779
Faculty (Olympus): Yeah, yeah, there are tools, that's the whole point of statistics.

648
01:11:31.780 --> 01:11:32.430
Sajith K N .: Oh.

649
01:11:32.670 --> 01:11:37.130
Faculty (Olympus): Lot of statistics is going towards that direction, as in, what you're going to learn, the course.

650
01:11:37.130 --> 01:11:37.540
Sajith K N .: Okay.

651
01:11:37.540 --> 01:11:39.300
Faculty (Olympus): Pretty well-established theories there.

652
01:11:39.300 --> 01:11:39.960
Sajith K N .: Yeah.

653
01:11:40.450 --> 01:11:49.450
Faculty (Olympus): Right? So, for example, I have aâ€¦ I know that a distribution is normally distributed. If I just estimate two parameters, I'm done. I can tell you I know everything about the random variable.

654
01:11:49.790 --> 01:11:57.659
Faculty (Olympus): Just because I know everything about the random variable doesn't mean I can predict, you know, the next thing that I'm gonna get, because it's random, inherently. I can tell you the distribution.

655
01:11:58.660 --> 01:12:01.310
Faculty (Olympus): And I can tell you statistical properties of that distribution.

656
01:12:01.470 --> 01:12:02.020
Faculty (Olympus): That's it.

657
01:12:02.050 --> 01:12:05.699
Sajith K N .: That's a first question. How do you know which distribution?

658
01:12:05.810 --> 01:12:08.339
Sajith K N .: It's just the numbers such as data and all, right?

659
01:12:08.340 --> 01:12:10.179
Faculty (Olympus): You may not. You have to fit it.

660
01:12:10.360 --> 01:12:11.260
Sajith K N .: Oh, correct.

661
01:12:11.530 --> 01:12:13.810
Faculty (Olympus): If I give you a curve, how do you find out what curve it is?

662
01:12:14.370 --> 01:12:15.410
Faculty (Olympus): Not easy.

663
01:12:16.490 --> 01:12:19.260
Faculty (Olympus): So you have to either fit it, you have algorithms to do this.

664
01:12:19.260 --> 01:12:19.949
Sajith K N .: Oh, well, damn.

665
01:12:19.950 --> 01:12:22.920
Faculty (Olympus): It's complicated. But yes, it can be done.

666
01:12:23.180 --> 01:12:23.700
Sajith K N .: Gill.

667
01:12:24.300 --> 01:12:32.640
Faculty (Olympus): Right? Andâ€¦ or if you have insight into the nature of the quantity, you will know, oh, this should be like this, right? And then you can make some assumptions. It's all about modeling. This is the whole art of modeling.

668
01:12:33.990 --> 01:12:38.650
Faculty (Olympus): Okay, Rahul, last question. No more questions for, like, half an hour. I need to finish material.

669
01:12:38.650 --> 01:12:51.679
Rahul Joshi .: Thank you, sir. Last question here. So, in this cell number 39, if you generate the random numbers, let's say 500 random numbers, and then in that array, if you take alternate numbers, do they still follow the same distribution?

670
01:12:53.030 --> 01:12:56.119
Faculty (Olympus): You can answer this question yourself. Exercise, homework.

671
01:12:58.840 --> 01:13:01.620
Faculty (Olympus): Try it out. That's the whole point of this course.

672
01:13:01.820 --> 01:13:08.780
Faculty (Olympus): Right? If you had to ask your statistics instructor, you'll have to do some complicated thing. You can write the code to answer this question yourself.

673
01:13:08.780 --> 01:13:10.489
Rahul Joshi .: I'll do it. That's right.

674
01:13:10.560 --> 01:13:27.419
Faculty (Olympus): Try it, right? A lot of these questions, that's the point, so one thing I want to, you know, make very clear. I'm giving you the tools to understand statistics better, and that is the goal of this, right? So I'm very happy there are so many questions, but, you know, Iâ€¦ otherwise I'll have to take extra class to finish the material.

675
01:13:27.540 --> 01:13:28.970
Faculty (Olympus): Right, so I'm alsoâ€¦

676
01:13:29.160 --> 01:13:35.590
Faculty (Olympus): They have limited time. There's so much more to cover. Not gotten even close to data science yet, okay?

677
01:13:36.030 --> 01:13:40.619
Faculty (Olympus): So bear with me, I'm sorry, I've been trying to make sure I'm controlling the time, but, you know.

678
01:13:40.920 --> 01:13:42.890
Faculty (Olympus): So, justâ€¦

679
01:13:43.160 --> 01:13:59.700
Faculty (Olympus): no offense, but I really need to move on, okay? But the point of giving you these notebooks and giving you an interface where you can try it is you can go nuts playing with this. You can do lots of cool things with this, right? So, by all means, interact with the data, play with these numbers, plot them, right? You've been given all the nice tools

680
01:13:59.790 --> 01:14:10.609
Faculty (Olympus): do that, and then you'll be able to answer these questions, okay? Alright, so the next thing that is very, very useful is something called np.random.choice. So let's say I have two possible events, 0 and 1.

681
01:14:10.780 --> 01:14:24.839
Faculty (Olympus): If I want to say, give me, randomly, with uniform probability, that is either 0 or 1, and give me 20 numbers, it'll do this for me, okay? But of course, I could also do, you know, 3, 5. That'll also work.

682
01:14:25.030 --> 01:14:27.930
Faculty (Olympus): So, given a set, it will randomly

683
01:14:28.210 --> 01:14:33.539
Faculty (Olympus): Choose from this, okay, such that each of those events is equally probable, okay?

684
01:14:40.830 --> 01:14:45.229
Faculty (Olympus): So, and this does not always have to be just, you know, a number.

685
01:14:46.140 --> 01:14:50.660
Faculty (Olympus): This, can also be heads and tails, for example, like this, okay?

686
01:14:54.190 --> 01:15:08.139
Faculty (Olympus): Alright? Now, if you want a biased coin, that also can be simulated. So, for example, you have these two events, heads and tails, but let's say I want the probability of the first guy, heads, to be 0.1, and I want the probability of the second guy to be 0.9, okay?

687
01:15:08.240 --> 01:15:18.089
Faculty (Olympus): If I were to run this, that's what I will get, which means I will get more true values and less false values, okay? And I can reverse this, and I will get similarly a distribution.

688
01:15:18.360 --> 01:15:23.719
Faculty (Olympus): And of course, you can plot a distribution for each of these, and plot a histogram, and see how is this distribution?

689
01:15:24.360 --> 01:15:25.140
Faculty (Olympus): Yeah.

690
01:15:26.350 --> 01:15:36.550
Faculty (Olympus): Now, this is also useful when you're sampling from some data. Let's say I have a dataset. I can resample that dataset, I can get more numbers from that data set by simply doing NP.random.choice.

691
01:15:37.160 --> 01:15:38.000
Faculty (Olympus): Okay?

692
01:15:39.330 --> 01:15:40.210
Faculty (Olympus): No.

693
01:15:40.420 --> 01:15:44.199
Faculty (Olympus): Here's an example. I have values from 900 to 1000.

694
01:15:44.430 --> 01:15:48.210
Faculty (Olympus): And I want to get 10 values from 900 to 1000. This is how you do it.

695
01:15:48.730 --> 01:15:56.070
Faculty (Olympus): And these are randomly chosen from 900 to 999, okay, in this case.

696
01:15:57.230 --> 01:16:13.340
Faculty (Olympus): Now, you can also do sampling without replacement. So, if I give you some data set, there's 100 values, and I say, you know, do not replace the values, that also can be done, right? But the only thing you have to be careful is, if the size of this is greater than the size of this data set.

697
01:16:13.340 --> 01:16:17.980
Faculty (Olympus): Obviously, it will not work. It's, for example, if I say, planter and bottom.

698
01:16:19.380 --> 01:16:36.869
Faculty (Olympus): cannot take a larger sample when replace is false, obviously, right? So just be aware of this. I hope you understand sampling withâ€¦ must beâ€¦ have done these problems, right? You have an urn, you pick out the ball, you replace that ball, right? That's sampling with replacement. Without replacement, you pull it out, that thing is gone. I have 10 people, you take out 1%, then it becomes 9 people.

699
01:16:37.420 --> 01:16:55.570
Faculty (Olympus): So you can do these sort of things also. There are other useful functions, like there's npandom permutation, there's npandom shuffle, so let's take a quick look at this. If I create, you know, 5 random numbers between 0 and 100, or 0 and 99, and I do np.random.shhuffle, so let me show you what this looks like.

700
01:16:56.390 --> 01:17:00.490
Faculty (Olympus): So it's 1, 9, 45, 21, 72. Now, if I do shuffle this data.

701
01:17:04.700 --> 01:17:06.340
Faculty (Olympus): Quick little details.

702
01:17:07.580 --> 01:17:10.109
Faculty (Olympus): Notice it shuffled. I'm shuffled this again.

703
01:17:10.350 --> 01:17:11.850
Faculty (Olympus): It's changed, okay?

704
01:17:12.030 --> 01:17:31.830
Faculty (Olympus): The other thing that you can do is you can do permutations. So I want just a random permutation of the first 10 numbers, or for a data set, right? You can either give a sequence or a permuted range, and it will give you back, you know, a permutation of either, if it's an integer, it'll just give you a permutation of up to that number. Or if you have a set data set, give it a set of values, it'll permute those.

705
01:17:33.090 --> 01:17:43.090
Faculty (Olympus): All right, so these are all useful tools for performing typical kind of experiments that, you know, you must have seen in your statistics or probability courses.

706
01:17:44.000 --> 01:17:53.020
Faculty (Olympus): Now, so far, we've only seen randint. What does randint do? It gives you integers that are uniformly distributed, from low to some high minus 1.

707
01:17:53.340 --> 01:18:04.350
Faculty (Olympus): I've also shown you random.random, which is uniformly distributed between 0 and 1, which is a continuous distribution of numbers, right? So it's a continuous random variable between 0 and 1.

708
01:18:04.500 --> 01:18:07.140
Faculty (Olympus): And then I showed you normals. I've only showed you these three.

709
01:18:07.960 --> 01:18:21.849
Faculty (Olympus): And of course, with random.choice, you can do some, you know, other crazy things, like with non-equal probabilities and things like that. Okay, that's fine, right? But there are actually many more distributions that NumPy provides, okay? For example.

710
01:18:21.850 --> 01:18:29.369
Faculty (Olympus): somebody was talking about binomial distribution, right? So you can do np.random.binomial, 10, 0.25. Okay, if you read the doc string for this.

711
01:18:29.400 --> 01:18:33.050
Faculty (Olympus): 10 will beâ€¦ The number of coin tosses.

712
01:18:33.270 --> 01:18:47.849
Faculty (Olympus): And 0.25 will be the probability of success in that coin toss. So if it's a fair coin, it'll be this. If it's a biased coin, it'll be something like this, okay? So I'll now get numbers, it's a discrete one available, right? So this is the number of successes

713
01:18:47.880 --> 01:19:00.090
Faculty (Olympus): when I do 10 coin tosses, with a coin which can get a success with probability 0.25. And you can see the numbers that you get here. Okay, so this, if I were to do a large number of this, right, so I'm going to do this.

714
01:19:02.260 --> 01:19:08.229
Faculty (Olympus): Thisâ€¦ I will get something that looksâ€¦ Approximately like theâ€¦

715
01:19:08.330 --> 01:19:13.230
Faculty (Olympus): true binomial distribution, and getâ€¦ will get better and better as I increase the number of binomials.

716
01:19:14.350 --> 01:19:25.690
Faculty (Olympus): Okay? So once again, you can use this as a means to do experiments, right? And it will behave just like somebody is doing this coin toss 10 times, with a value of P is 1 to 5.

717
01:19:27.640 --> 01:19:30.720
Faculty (Olympus): There are other distributions, like, you know, the beta distribution.

718
01:19:30.940 --> 01:19:36.739
Faculty (Olympus): Right? So, I'm not going to get into what this is, butâ€¦ No, that's,

719
01:19:37.070 --> 01:19:45.570
Faculty (Olympus): The point is, all of these distributions can easily be utilized, and you can generate them. Standard T distribution can also be distributed, oops.

720
01:19:45.960 --> 01:19:46.840
Faculty (Olympus): Who knows?

721
01:19:49.140 --> 01:20:03.949
Faculty (Olympus): Right? You can compare a T distribution and normal distribution, so all of these things you canâ€¦ I've just given these as examples. You can look at these, and when you're doing your stats course, when you encounter these distributions, you know, you can do, you canâ€¦

722
01:20:11.610 --> 01:20:15.849
Faculty (Olympus): Sorry, just give me a second. Don't sayâ€¦

723
01:20:32.490 --> 01:20:33.430
Faculty (Olympus): Okay.

724
01:20:38.870 --> 01:20:39.810
Faculty (Olympus): Sometime?

725
01:20:40.480 --> 01:20:41.670
Faculty (Olympus): 20 minutes.

726
01:20:45.870 --> 01:21:01.789
Faculty (Olympus): So the next thing isâ€¦ so, so far, we've looked at NumPy's np.random functionality, and this is kind of a limited functionality. It allows you to generate these random numbers, it allows you to do choice, which is you can choose all of these things that I've shown you so far.

727
01:21:02.270 --> 01:21:06.210
Faculty (Olympus): But there's another library called SciPy, a very powerful library.

728
01:21:06.480 --> 01:21:13.679
Faculty (Olympus): Which does all kinds of things, and one of them is it has a module or a package called stats. So, scipy.stats.

729
01:21:13.800 --> 01:21:24.560
Faculty (Olympus): Right? Which provides a lot more conveniences, especially when you're looking at this as a, you know, stats student, and you want to, like, understand some new thing, or, you know, some different distribution and things like that.

730
01:21:25.000 --> 01:21:44.939
Faculty (Olympus): So, if you click on this link, it will take you to the SciPy Stats reference documentation. It's very worth checking out. You can look at all the different things that are available. You can look at all the different methods that are available for these various kind of distributions, and you'll find them extremely useful if you're going to do some calculations with these idealized, you know, distributions.

731
01:21:45.920 --> 01:21:46.790
Faculty (Olympus): Soâ€¦

732
01:21:47.040 --> 01:22:03.360
Faculty (Olympus): The idea is the following. We've seen a few examples. We've looked at uniform distribution, we've looked at, say, normal distribution, binomial, poison, exponential, there are a whole host. These are just a small number. There must be hundreds of these kind of, distributions, okay?

733
01:22:04.180 --> 01:22:11.939
Faculty (Olympus): Now, so far, we've only generated random numbers. These are called random variants. So, let me explain.

734
01:22:12.080 --> 01:22:13.239
Faculty (Olympus): If I takeâ€¦

735
01:22:13.470 --> 01:22:27.729
Faculty (Olympus): a uniform distribution. Random variants will basically give me a set of random numbers sampled from that distribution. So if I have a Gaussian distribution, and I say, give me 20 numbers, you're sampling 20 numbers from this.

736
01:22:28.190 --> 01:22:29.050
Faculty (Olympus): Okay?

737
01:22:34.210 --> 01:22:34.990
Faculty (Olympus): Soâ€¦

738
01:22:49.100 --> 01:22:52.419
Faculty (Olympus): Sorry, what is it Singh?

739
01:22:52.580 --> 01:22:57.040
Faculty (Olympus): Yeah, sorry, somebody's trying desperately to reach me, soâ€¦ Not distracted.

740
01:22:57.150 --> 01:23:05.659
Faculty (Olympus): So, np.random gives you only the random variants, but what sciPy.stats

741
01:23:05.660 --> 01:23:25.560
Faculty (Olympus): these random variants, the random variables that you can create, or these distributions that you can create, will allow you to doâ€¦ will allow you to generate the exact probability density function, will allow you to find the cumulative distribution function, will allow you to find mean, median, you can find the inverse of the CDF, all of these quantities areâ€¦ all of these functions are available to you, okay?

742
01:23:25.560 --> 01:23:44.799
Faculty (Olympus): So I'm just going to walk through this with an example to sort of show you what I'm trying to talk about, okay? So I'm going to use our familiar IPyWidgets interact. If this doesn't work for you on the online interface, make sure you do pip install IPIW widgets. And now look at this code. I'm saying from scipy.stats, import by norm norm poison, which meansâ€¦

743
01:23:44.800 --> 01:23:47.350
Faculty (Olympus): Stats has a whole bunch of different

744
01:23:47.410 --> 01:23:51.250
Faculty (Olympus): distributions that are available. So, VIN norm.

745
01:23:51.370 --> 01:24:09.710
Faculty (Olympus): is the name of a class-like thing which you can instantiate. It's an object that you can instantiate, and then you can say, give me this, give me that, so on and so forth, okay? So here is an example where I'm going to plot the binomial distribution, okay? So let's read the code, so I'll just walk you through this so you understand what's happening, and then, you know, you can run this on your own.

746
01:24:10.160 --> 01:24:18.509
Faculty (Olympus): So I'm now creating a random variable, okay? So I'm saying this random variable is an instantiation of this binom, which is from stats, okay?

747
01:24:18.770 --> 01:24:25.609
Faculty (Olympus): And it takes two arguments. The first is N, which is the number of coin losses, and the second is P, which is the probability of success.

748
01:24:26.010 --> 01:24:26.820
Faculty (Olympus): Okay?

749
01:24:28.970 --> 01:24:34.589
Faculty (Olympus): The next thing is a straightforward line of code, which I will, talk to you about.

750
01:24:36.220 --> 01:24:55.669
Faculty (Olympus): in a very short, I mean, next class, when we'll be doing numpy arrays. So we have np.arange. A range is, like, the equivalent for range, but with NumPy arrays. And it also supports start and stop being non-integer ones. So it's a more generalized version of your standard Python range, okay? So here, what we will get is

751
01:24:55.670 --> 01:24:58.110
Faculty (Olympus): I'll get elements starting from 0,

752
01:24:58.860 --> 01:25:04.060
Faculty (Olympus): all the way to N. 0, 1, 2, 3, 4, 5, 6, all the way to N, because the default step size is 1.

753
01:25:04.770 --> 01:25:11.939
Faculty (Olympus): And now, notice, I'm saying plT.plot, X. What is X? X is this A range fellows, which is B0 all the way to N.

754
01:25:12.200 --> 01:25:15.029
Faculty (Olympus): And then I can say RV.pmf.

755
01:25:15.190 --> 01:25:32.650
Faculty (Olympus): Notice, I'm not taking a sample, then doing a histogram, nothing. I can simply say, now I know it's a binomial, tell me what the probability mass function is at this location, and it will actually give us. So this is where this SciPyStats functionality is extremely useful. So now you can plot this for all, and these are just vertical lines.

756
01:25:32.650 --> 01:25:39.139
Faculty (Olympus): For the same thing, so it basically shows a dot, so if you look at a textbook, they'd have these plots with a, you know, this discrete value, there's this file.

757
01:25:39.140 --> 01:25:39.900
Faculty (Olympus): Okay?

758
01:25:40.220 --> 01:25:58.060
Faculty (Olympus): And then what I do is I compare this binomial distribution with a normal distribution by computing the equivalentâ€¦ the same mean as for this distribution, and the same standard deviation. So this mean for a binomial is n times p, the standard deviation is going to be square root of np into 1 minus A.

759
01:25:58.060 --> 01:26:01.929
Faculty (Olympus): Okay, this isâ€¦ I think your stats course may have already covered this, right?

760
01:26:02.350 --> 01:26:08.710
Faculty (Olympus): And then I'm going to take a lint space, because this is a continuous distribution, and then do norm.pdf.

761
01:26:08.860 --> 01:26:25.560
Faculty (Olympus): Okay, which isâ€¦ so there's another way of calling the random variable. Instead of creating the instance like this random variable, you can simply say norm.pdf, pass it the X values, and then pass it these additional log, and, you know, this is the mean, and the standard additional blocks. So if I run thisâ€¦

762
01:26:28.410 --> 01:26:29.340
Faculty (Olympus): Small.

763
01:26:31.670 --> 01:26:32.749
Faculty (Olympus): I get this.

764
01:26:33.020 --> 01:26:33.860
Faculty (Olympus): Okay.

765
01:26:34.270 --> 01:26:36.619
Faculty (Olympus): So now you can see that as I move in.

766
01:26:37.640 --> 01:26:41.199
Faculty (Olympus): So the green curve, green dashed curve, is the Gaussian.

767
01:26:41.610 --> 01:26:50.619
Faculty (Olympus): And these vertical lines are the binomial distribution. So you can see, right, by just doing these small five lines of code, that when n is large.

768
01:26:50.790 --> 01:26:57.980
Faculty (Olympus): That the normal distribution is actually a reasonable approximation, right, for the binometer.

769
01:26:58.880 --> 01:27:00.829
Faculty (Olympus): Yeah, you can now reduce this.

770
01:27:01.740 --> 01:27:04.430
Faculty (Olympus): And just go higher and higher as you increase n.

771
01:27:04.690 --> 01:27:06.889
Faculty (Olympus): The binomial actually becomes like a positive.

772
01:27:07.120 --> 01:27:07.840
Faculty (Olympus): Good.

773
01:27:08.090 --> 01:27:13.130
Faculty (Olympus): So once again, we didn't do any theory, I didn't do any mathematics, I didn't write anything, do anything.

774
01:27:14.270 --> 01:27:15.070
Faculty (Olympus): Okay?

775
01:27:15.190 --> 01:27:29.480
Faculty (Olympus): All I did was use these nice functions and plotted this. And this is why I feel this is very useful for you in stats, because now you can actually plot these yourselves. You don't have to trust the instructor or do a complicated math. You can actually write some little Python code and generate this.

776
01:27:29.550 --> 01:27:36.120
Faculty (Olympus): Okay, so here's an example with a Poisson distribution, and you can see how the Poisson distribution looks, and it's again compared with a

777
01:27:36.650 --> 01:27:44.489
Faculty (Olympus): Gaussian distribution. So you can see as lambda increases, the parameter for a boson, it also tends to behave like a non-existion.

778
01:27:44.770 --> 01:27:56.749
Faculty (Olympus): Okay? So, again, this is one more example. You can try this on your own. I've just put it in there, so you can see t-distribution you're going to see in your stats course, and I want to show you, hey, you can actually make a nice plot of it using SciPy.stats.

779
01:27:56.970 --> 01:27:57.720
Faculty (Olympus): Good.

780
01:27:57.940 --> 01:28:00.770
Faculty (Olympus): So, why is this useful? So, as I said before.

781
01:28:01.030 --> 01:28:06.260
Faculty (Olympus): For your class, for your stats class, this is extremely useful because you can understand and study these distributions.

782
01:28:06.390 --> 01:28:23.220
Faculty (Olympus): The second thing, which is really where we use it in practice, is you can construct experiments with these random variables, which means if you say, hey, I want coin tosses, well, just say, okay, I want to end coin tosses. You can now just create this fellow and then ask all kinds of questions of it. You can generate some, you can do simulations, all of these things can be done.

783
01:28:24.300 --> 01:28:41.690
Faculty (Olympus): So you can numerically explore very interesting questions, and this is sort of the entry point to what are called Monte Carlo methods, which essentially do this. They essentially set up an experiment, and this experiment may not be like a coin toss. It may be a much more complicated setting. You know, there are a bunch of random variables that are interacting in some way, and now.

784
01:28:41.890 --> 01:28:52.359
Faculty (Olympus): You get a result as a result of, you know, a set of random variables performing something, and then you can basically ask statistical questions about the outcome.

785
01:28:52.540 --> 01:28:55.170
Faculty (Olympus): So, you know, sort ofâ€¦

786
01:28:56.720 --> 01:29:20.350
Faculty (Olympus): Fancy example is, supposing you have a nuclear reactor, and you want to find the amount of lead shielding you need to do, you can do an experiment like that. You say, hey, I know this, I know how much radiative material, radioactive material I have, I know the half-life of this, so I know this distribution of this. Now I'll start generating alpha particles at this thing. I know that certain properties of lead, and also I can now have saying, okay, given this length of lead, how many alpha particles am I going to see outside?

787
01:29:20.350 --> 01:29:28.579
Faculty (Olympus): So then you run lots and lots of experiments, say, okay, I expect, you know, this much radiation to be at the end. You'll actually be able to make a similar difference, okay?

788
01:29:28.580 --> 01:29:31.080
Faculty (Olympus): Things like this you can actually do as a computer solution.

789
01:29:32.350 --> 01:29:34.219
Faculty (Olympus): And so,

790
01:29:34.290 --> 01:29:40.499
Faculty (Olympus): The other thing is, Monte Carlo methods, or these kind of methods, sort of defeat the curse of dimensionality. So.

791
01:29:40.540 --> 01:29:58.010
Faculty (Olympus): You know, I'm basically going to skip this. This is kind of advanced, so those of you who are already fairly advanced and know this stuff may find this useful, but I'll just quickly tell you what I'm going to do. I'm not going to run the cells. I'm going to quickly calculate the area of a sphere in D dimensions, okay?

792
01:29:58.010 --> 01:30:06.800
Faculty (Olympus): And it turns out that, this is very easy to do with np.random.random and the tools that are available in NumPy.

793
01:30:06.940 --> 01:30:13.919
Faculty (Olympus): So what we'll do is we'll consider a single quadrant. So, in 2D, you multiply this quantity by 2 to the party. If I have

794
01:30:14.020 --> 01:30:16.189
Faculty (Olympus): two-dimensional.

795
01:30:16.620 --> 01:30:21.480
Faculty (Olympus): system, I have 4 quadrants. If I have 3 dimensional system, I have 2 to the bar 3, which is 8 quadrants.

796
01:30:21.760 --> 01:30:23.819
Faculty (Olympus): Not quarters. 8,

797
01:30:24.350 --> 01:30:29.649
Faculty (Olympus): 8 parts. If I take only the positive X, positive Y, no, I have 1, I have 8 such.

798
01:30:29.820 --> 01:30:41.340
Faculty (Olympus): So if I want to find the volume, I can estimate the volume in the firstâ€¦ in the first quadrant, and multiply by 4, okay? So, in ND, I can do 2 to the party. For D dimensions, it's 2 to the party.

799
01:30:41.750 --> 01:30:43.680
Faculty (Olympus): Then what I do is I throw dots.

800
01:30:44.580 --> 01:30:50.349
Faculty (Olympus): Uniformly distributed in this And then find the number of points that are inside the sphere.

801
01:30:50.540 --> 01:30:54.110
Faculty (Olympus): Divide these two, and I'll get an approximation to the area of that.

802
01:30:54.570 --> 01:30:56.680
Faculty (Olympus): And I can do this in any number of dimensions.

803
01:30:57.210 --> 01:30:59.340
Faculty (Olympus): Okay, so,

804
01:30:59.510 --> 01:31:09.310
Faculty (Olympus): This is what, you know, this thing walks you through, so I will notâ€¦ I'm gonna skip this. You can play with this yourselves, and see what it's doing.

805
01:31:09.970 --> 01:31:13.880
Faculty (Olympus): And maybe once you learn the NumPy a little better, you'll understand this sort ofâ€¦

806
01:31:14.010 --> 01:31:20.249
Faculty (Olympus): syntax that I have typed here, but this is the only line of code you need to actually answer this question. So you can take aâ€¦

807
01:31:24.940 --> 01:31:33.469
Faculty (Olympus): Yeah, you can solve these problems really nicely. So this is two-dimensional. You can change the number of dimensions that you want, right? Soâ€¦

808
01:31:33.580 --> 01:31:39.860
Faculty (Olympus): Maybe I should generalize this and say t is equal to 2, CSDâ€¦

809
01:31:43.300 --> 01:31:52.760
Faculty (Olympus): So if you run this for any number of dimensions, you can actually estimate the area, okay? So notice, in two dimensions, there's approximately pi. This is the area of a sphere in two dimensions.

810
01:31:53.340 --> 01:31:58.080
Faculty (Olympus): But if I change D to, say, 4th, Right? It changes.

811
01:31:58.240 --> 01:32:00.600
Faculty (Olympus): Aditya to 10.

812
01:32:00.800 --> 01:32:08.300
Faculty (Olympus): actually drops, and in principle, it should actually go towards zero. Okay, so it becomes so small at this point. Okay, so let's go to 20.

813
01:32:08.660 --> 01:32:10.639
Faculty (Olympus): They're really, really smart.

814
01:32:12.560 --> 01:32:13.720
Faculty (Olympus): To speed.

815
01:32:13.900 --> 01:32:20.039
Faculty (Olympus): Right? I need more numbers to actually do those. But the idea is, you can, you know, you can do kind ofâ€¦

816
01:32:20.350 --> 01:32:25.719
Faculty (Olympus): Simple, cute things like this with, you know, random number generators, and you can do it in any number of dimensions.

817
01:32:27.270 --> 01:32:43.650
Faculty (Olympus): Okay, so now we have the last 5 to 10 minutes. I will wrap it, wrap up this session, and then next class we'll start with NumPy. I think that's a good breakpoint. But now I'm going to show you a very useful thing that so far we have been taking, and probably some of you are like, what is all this talking? It's likeâ€¦

818
01:32:44.520 --> 01:32:50.269
Faculty (Olympus): It's like your other stats course, where maybe you're not seeing connections to the reality yet. Here is an actual problem.

819
01:32:50.410 --> 01:32:59.109
Faculty (Olympus): Okay, and I'll show you how thisâ€¦ all of these statistical computations are extremely useful in solving this very particular problem.

820
01:32:59.500 --> 01:33:05.540
Faculty (Olympus): So, given Sachin or Kohli's or any of the other batsmen scored in our data directory, let us say

821
01:33:05.730 --> 01:33:12.440
Faculty (Olympus): the player is going to play in an ODI series of 3 games, or 2 games, or 5 games, okay? So I've just picked 3 here.

822
01:33:13.710 --> 01:33:16.909
Faculty (Olympus): Now, what I want to answer isâ€¦

823
01:33:17.310 --> 01:33:24.240
Faculty (Olympus): Estimate what you think this person will score on an average, With an 80% confidence interval.

824
01:33:26.210 --> 01:33:29.879
Faculty (Olympus): Okay, so now this is a not-so-straightforward thing.

825
01:33:30.020 --> 01:33:37.559
Faculty (Olympus): But you must have seen language like this at some point, somewhere, in some paper, or someone talking some statistics, right?

826
01:33:37.680 --> 01:33:45.910
Faculty (Olympus): You want to know the score with an 80% confidence interval. So, which means I want to give you sort of an 80% probability interval

827
01:33:46.710 --> 01:33:47.550
Faculty (Olympus): Off?

828
01:33:47.770 --> 01:33:54.189
Faculty (Olympus): the average score in those three matches. Okay, so let me repeat the problem. So we have, say, Sachin or Virat, I don't know.

829
01:33:54.930 --> 01:33:56.940
Faculty (Olympus): Do you want me to pick? Let's pick Sachv.

830
01:33:58.290 --> 01:34:02.549
Faculty (Olympus): Sachin now is going to playâ€¦ let's assume this is not, you know, old, retired Sachin.

831
01:34:03.280 --> 01:34:07.010
Faculty (Olympus): Sachin in his prime, now going to play an ODI series of 3 games.

832
01:34:07.210 --> 01:34:07.970
Faculty (Olympus): Okay.

833
01:34:08.200 --> 01:34:09.559
Faculty (Olympus): I want to find out.

834
01:34:09.790 --> 01:34:13.189
Faculty (Olympus): On the average, what do you think Sachin is going to score?

835
01:34:14.550 --> 01:34:15.390
Faculty (Olympus): Okay?

836
01:34:15.940 --> 01:34:23.030
Faculty (Olympus): And now I want to do better than that. I just don't want to give you one single number. I want to say, okay, give me some sort of a range of numbers.

837
01:34:23.890 --> 01:34:30.850
Faculty (Olympus): where there's an 80% confidence that he is going to score that average score in the three matches. Am I clear?

838
01:34:32.710 --> 01:34:34.569
Faculty (Olympus): Is the problem clear to everyone?

839
01:34:35.430 --> 01:34:35.780
Rahul Joshi .: Yep.

840
01:34:35.780 --> 01:34:37.300
Faculty (Olympus): Tambres? Okay, great.

841
01:34:38.230 --> 01:34:39.919
Faculty (Olympus): So now, how do we solve this?

842
01:34:40.700 --> 01:34:43.250
Faculty (Olympus): So, first thing is, let us load the data.

843
01:34:43.550 --> 01:34:46.270
Faculty (Olympus): Np.load.pht.

844
01:34:48.960 --> 01:34:50.359
Faculty (Olympus): Well, such enough.

845
01:34:51.120 --> 01:34:52.030
Faculty (Olympus): Killer?

846
01:34:52.330 --> 01:34:53.700
Faculty (Olympus): So now I have the data.

847
01:34:55.680 --> 01:34:59.019
Faculty (Olympus): Okay, so let me create a few more empty cells.

848
01:35:01.470 --> 01:35:02.280
Faculty (Olympus): Okay.

849
01:35:02.690 --> 01:35:04.159
Faculty (Olympus): Now, what's our next step?

850
01:35:04.780 --> 01:35:12.300
Faculty (Olympus): So many of you at this stage will be like, okay, I can't see the connection. Well, so what I have now is, I have a set of scores.

851
01:35:12.710 --> 01:35:17.290
Faculty (Olympus): This isâ€¦ Kunal Sachin's career, okay? All of his career.

852
01:35:19.110 --> 01:35:24.649
Faculty (Olympus): So, in a sense, this is the set of all possible scores that Sachin has.

853
01:35:25.050 --> 01:35:27.529
Faculty (Olympus): Okay? And what I want to do isâ€¦

854
01:35:27.940 --> 01:35:35.199
Faculty (Olympus): I want to say, give me 3 numbers sampled from this data set.

855
01:35:35.980 --> 01:35:37.449
Faculty (Olympus): And spit it out for me.

856
01:35:37.970 --> 01:35:44.689
Faculty (Olympus): That'll be 1 ODI series of 3 games, I will get those 3 variables. So, how do we generate that? NP.

857
01:35:47.350 --> 01:35:48.490
Faculty (Olympus): Random dot?

858
01:35:51.370 --> 01:35:52.390
Faculty (Olympus): Nolan?

859
01:35:52.390 --> 01:35:53.520
Soumen Deb .: Choice, choice.

860
01:35:53.520 --> 01:35:54.040
Faculty (Olympus): annoying.

861
01:35:54.040 --> 01:35:54.589
Amit Srivastava .: Thank you, thank you.

862
01:35:54.590 --> 01:35:54.960
Soumen Deb .: Right.

863
01:35:54.960 --> 01:36:02.120
Faculty (Olympus): Thank you. And then I give it the data, and then ask for size is equal toâ€¦ 3.

864
01:36:02.120 --> 01:36:02.560
Shravan Kumar Ganpur: Agreed.

865
01:36:03.170 --> 01:36:03.560
Faculty (Olympus): Okay?

866
01:36:03.560 --> 01:36:04.839
Soumen Deb .: 3, yeah, three.

867
01:36:04.840 --> 01:36:06.060
Faculty (Olympus): I got 3 scores.

868
01:36:06.630 --> 01:36:07.590
Faculty (Olympus): Okay?

869
01:36:08.010 --> 01:36:10.010
Faculty (Olympus): Can I find the average of these cores?

870
01:36:10.900 --> 01:36:12.690
Soumen Deb .: Yes, yes. So how do I do that?

871
01:36:12.690 --> 01:36:16.049
Faculty (Olympus): I can just say, entity of, not mean of this fellow.

872
01:36:17.030 --> 01:36:18.800
Faculty (Olympus): Is this clear so far?

873
01:36:18.800 --> 01:36:19.630
Soumen Deb .: Yes.

874
01:36:19.630 --> 01:36:19.980
Faculty (Olympus): So I go.

875
01:36:19.980 --> 01:36:20.369
varun kumar .: That's cool.

876
01:36:20.370 --> 01:36:27.989
Faculty (Olympus): it's, like, close to 50, okay? If I run this again, will I get the same? No, I'll get different, right? So I'll getâ€¦ so now you can say that

877
01:36:28.600 --> 01:36:31.140
Faculty (Olympus): I can now do a statistical game.

878
01:36:31.450 --> 01:36:34.829
Faculty (Olympus): Where I imagine, because I have this data.

879
01:36:35.180 --> 01:36:39.279
Faculty (Olympus): that I will now create, scores.

880
01:36:40.150 --> 01:36:41.469
Faculty (Olympus): His course.

881
01:36:42.170 --> 01:36:43.609
Faculty (Olympus): Abhin sports.

882
01:36:44.960 --> 01:36:46.160
Faculty (Olympus): empty list.

883
01:36:46.770 --> 01:36:48.609
Faculty (Olympus): Now, let me run an experiment.

884
01:36:48.940 --> 01:36:50.710
Faculty (Olympus): Let me say NMIS.

885
01:36:51.600 --> 01:36:57.479
Faculty (Olympus): So, I'm going to run an experiment with 10,000, or let me keep it simple. For IN range N,

886
01:37:00.720 --> 01:37:07.150
Faculty (Olympus): ofâ€¦ So instead of average scores in a number, I will call it averages.

887
01:37:07.800 --> 01:37:09.759
Faculty (Olympus): Rosalin Shop of Time.

888
01:37:09.950 --> 01:37:11.600
Faculty (Olympus): averages.append.

889
01:37:12.170 --> 01:37:13.010
Faculty (Olympus): Oops.

890
01:37:16.320 --> 01:37:17.309
Faculty (Olympus): Are we good?

891
01:37:17.570 --> 01:37:19.119
Faculty (Olympus): So, what will we now have?

892
01:37:19.470 --> 01:37:20.650
Faculty (Olympus): I will haveâ€¦

893
01:37:20.650 --> 01:37:21.390
Soumen Deb .: Random average.

894
01:37:21.390 --> 01:37:23.420
Samar .: Then, demolished.

895
01:37:23.420 --> 01:37:31.870
Faculty (Olympus): 10,000 in number, okay? Yeah. And now I can say plt.lotâ€¦ sorry, plt.hist, averagesâ€¦

896
01:37:34.290 --> 01:37:36.419
Faculty (Olympus): VINs is equal to a parto.

897
01:37:37.850 --> 01:37:38.540
Faculty (Olympus): Bansal.

898
01:37:38.540 --> 01:37:40.350
Soumen Deb .: And Z is equal to true, yeah.

899
01:37:40.910 --> 01:37:42.040
Faculty (Olympus): Same problem.

900
01:37:42.920 --> 01:37:43.770
Faculty (Olympus): Boo!

901
01:37:43.930 --> 01:37:45.760
Faculty (Olympus): It's not normally distributed.

902
01:37:46.100 --> 01:37:48.139
Faculty (Olympus): These are the set of averages that we have.

903
01:37:48.250 --> 01:37:49.299
Faculty (Olympus): Make sense?

904
01:37:49.690 --> 01:37:52.230
Soumen Deb .: And his average is 40, that's correct.

905
01:37:52.480 --> 01:38:11.539
Faculty (Olympus): Yeah, it's around 40, which should be true to the original data. So now, please note, with these four lines of code, I've done something very profound. I've basically looked at Sachin's data, and I know that that's his PMF, essentially, or his probability, you know, hisâ€¦ all of the probability information is encoded in that SS. I'm just choosing from those scores.

906
01:38:12.170 --> 01:38:28.290
Faculty (Olympus): with equal probability, any of those values. So if there's some set of scores either he's doing more near zero, I will also get more near zero, because that's there and reflected in the data set, okay? So what I'm essentially doing is I'm sampling this many, many times. I'm doing 33333, finding the average, storing that average, okay?

907
01:38:28.290 --> 01:38:33.439
Faculty (Olympus): But now comes the beauty. I want an 80% confidence interval, right? So, which meansâ€¦

908
01:38:33.540 --> 01:38:36.129
Faculty (Olympus): what I'd like to know is, what is theâ€¦

909
01:38:36.410 --> 01:38:51.829
Faculty (Olympus): the probability where 80% of this data lies. This is also very easy to do, because I already have percentiles. I want to say 10% of the set of scores from these 10,000 left, 10% to the right means beach me, I have 80%. So I can simply say np.percentile.

910
01:38:51.830 --> 01:38:52.770
Soumen Deb .: What's anytime.

911
01:38:54.630 --> 01:38:57.100
Faculty (Olympus): and give it AVGS.

912
01:38:57.400 --> 01:39:01.429
Faculty (Olympus): And then say, give meâ€¦ 10 and 90.

913
01:39:03.840 --> 01:39:05.270
Faculty (Olympus): And I have the answer.

914
01:39:05.800 --> 01:39:14.930
Faculty (Olympus): So, I have 80% confidence that Sachin is going to score between 12.6 and 72, or 12 and 72.

915
01:39:15.970 --> 01:39:28.290
Faculty (Olympus): Now, this is an extremely profound thing that we have done, because this data is not normally distributed, God knows what theâ€¦ there is no known distribution for it, but I have just written 5-6 lines of code to show you that I can do something non-trivial like this.

916
01:39:28.290 --> 01:39:36.560
Faculty (Olympus): So I can't use some theorem saying, oh, central limit theorem applies nothing, because only three scores. In fact, I can even make it one match, or two matches, and tell you what's the, you knowâ€¦

917
01:39:36.560 --> 01:39:40.999
Faculty (Olympus): And ask interesting questions and give you actual numbers corresponding to us.

918
01:39:41.590 --> 01:39:47.880
Faculty (Olympus): Okay? So, you can answer, sort of, very practical questions. So, later on, for example,

919
01:39:48.340 --> 01:40:05.219
Faculty (Olympus): even if you're doing a regression, right? Sometimes they will show you error bars around that, right? Those sometimes are computed using such an approach. This approach is called what'sâ€¦ it's called bootstrapping, which means I have the same dataset, but I'm going to resample from that data set in order to generate,

920
01:40:05.570 --> 01:40:10.070
Faculty (Olympus): more data, and from that, I'm going to do a bunch of statistics.

921
01:40:10.070 --> 01:40:32.829
Faculty (Olympus): Okay? And this is really why probabilistic programming is extremely powerful. So you can not just do this, you can also do Bayesian analysis with the same. We are doing a very frequent, straightforward thing so far, but you can do Bayesian analysis. So you can basically start doing things like, you know, finding prior, posterior, and, you know, updating your assumptions based on data, all using probabilistic programming. In fact, so there's a

922
01:40:32.830 --> 01:40:39.280
Faculty (Olympus): Bunch of tools, which we're not going to discuss in this course, which, you know, make it very easy to do those kind of analysis as well.

923
01:40:39.280 --> 01:40:47.060
Faculty (Olympus): But the building block, fundamental building block, is probabilistic program, you know, okay? So it's now 11. I will stop here.

924
01:40:47.120 --> 01:40:49.250
Faculty (Olympus): And no?

925
01:40:50.090 --> 01:40:54.369
Faculty (Olympus): And answer questions. Just give me a second, I want to see if there's some emergency.

926
01:41:06.320 --> 01:41:08.550
Faculty (Olympus): Sorry, there was an emergency in the family.

927
01:41:19.900 --> 01:41:22.100
Faculty (Olympus): Just give me a second, please.

928
01:41:44.490 --> 01:41:46.450
Faculty (Olympus): Sorry, so my name, my nameâ€¦

929
01:41:46.610 --> 01:41:48.899
Faculty (Olympus): My family had a heart attack.

930
01:41:49.270 --> 01:41:56.739
Faculty (Olympus): Sorry, I'll take questions, sorry, given the emergency, I can take questions for 5 minutes. My apologies.

931
01:41:57.300 --> 01:42:00.570
Jasmine Samant .: Would you like to take our questions?

932
01:42:00.570 --> 01:42:12.100
Faculty (Olympus): They've been admitted, so it's okay. I'll take 5 minutes and then go, soâ€¦ I'm useless. I'm there in a different city, and that's why I got so many calls.

933
01:42:12.570 --> 01:42:14.210
Faculty (Olympus): Just check to make sure.

934
01:42:14.210 --> 01:42:15.680
Jasmine Samant .: They recover very soon.

935
01:42:15.680 --> 01:42:22.609
Faculty (Olympus): Yeah, thank you so much. I will pass the message on. But I'm useless, as in I can only call and SOARG people. I can do that in 5 minutes.

936
01:42:22.980 --> 01:42:26.649
Faculty (Olympus): So, very quickly, if you have questions, I'll try and answer whatever I can.

937
01:42:29.010 --> 01:42:39.290
Abhineet Bansal: Hi, sir, Abhineet here. In the last example that you've taken, sir, for confidence level 80, you started from 9 to 90, 10 to 90. I could have gone from 5 to 85 also, right?

938
01:42:39.980 --> 01:42:48.579
Faculty (Olympus): You could have, but then, remember, this is the 10 probability, so there's only 10% of the population to the left here, so why would you want to pick 0 toâ€¦

939
01:42:49.540 --> 01:42:50.110
Faculty (Olympus): thisâ€¦

940
01:42:51.440 --> 01:42:56.900
Abhineet Bansal: No, no, I could have taken from 5 to 85, or 15 to 95. I just need to ensure that theâ€¦

941
01:42:56.900 --> 01:43:02.199
Faculty (Olympus): Gap is ADC, right? So theâ€¦ no, that is true, but where you pick the gap is important, right?

942
01:43:02.550 --> 01:43:06.909
Faculty (Olympus): So notice, from this plot, the probability of all these guys is very low.

943
01:43:10.040 --> 01:43:10.710
Abhineet Bansal: Okay.

944
01:43:11.410 --> 01:43:14.160
Faculty (Olympus): Right? There's a low probability here as well.

945
01:43:14.460 --> 01:43:16.390
Faculty (Olympus): Sort of picks up somewhere in the middle.

946
01:43:17.550 --> 01:43:28.950
Faculty (Olympus): But yes, there is arbitrariness about this, okay? So in Bayesian analysis, you'll have a slight different way of doing this, but the idea is, you know, I'm chopping off 10% at the high end.

947
01:43:29.260 --> 01:43:32.840
Faculty (Olympus): I'm chopping off 10% at the low end, and I'm looking at the middle in this case.

948
01:43:33.390 --> 01:43:36.060
Faculty (Olympus): So that seems like a very reasonable thing to do, right?

949
01:43:36.510 --> 01:43:37.930
Faculty (Olympus): Why would I Same over the other.

950
01:43:38.550 --> 01:43:40.289
Abhineet Bansal: It's just subjective, right?

951
01:43:41.870 --> 01:43:42.460
Abhineet Bansal: I meanâ€¦

952
01:43:42.460 --> 01:43:45.819
Faculty (Olympus): What is your choice? Okay, if you're saying it's subjective, I'll ask you, what is your choice?

953
01:43:45.820 --> 01:43:48.890
Abhineet Bansal: I could have gone for 5 to 85, would have covered better.

954
01:43:48.890 --> 01:43:53.240
Faculty (Olympus): Why would you say 5 to 85? I don't understand why you picked that. Again, it's subjective, right?

955
01:43:53.420 --> 01:43:59.849
Faculty (Olympus): I am, in fact, doingâ€¦ I'm saying I'm going to chop the low probability, and I'm going to chop equally the high probability. That's all I'm saying.

956
01:44:00.360 --> 01:44:00.879
Abhineet Bansal: by looking at.

957
01:44:00.880 --> 01:44:05.609
Faculty (Olympus): Low scores, not probability, sorry, sorry, sorry, brain not worth it. Low scores and high scores.

958
01:44:06.820 --> 01:44:07.639
Abhineet Bansal: Okay, okay.

959
01:44:07.640 --> 01:44:17.639
Faculty (Olympus): Okay? Right, but there's something else called HDIE and all in Bayesian stats. My intention is not, you know, to go there. But to just tell you that, look, you can do these sort of things.

960
01:44:19.100 --> 01:44:28.529
Faculty (Olympus): But usually, when you're looking at two-sided intervals, when you do your stat scores, you'll see this again, right? You will pick 10% on this side, 10% to the area on this side, regardless of the symmetry of that.

961
01:44:31.080 --> 01:44:32.030
Abhineet Bansal: Got it, sir.

962
01:44:32.030 --> 01:44:34.789
Faculty (Olympus): And then you say there's 80% of the probability in between.

963
01:44:38.020 --> 01:44:41.740
Faculty (Olympus): Yes, gaurav?

964
01:44:42.990 --> 01:44:49.370
Gaurav Singh .: Yeah, Professor, like, in the previous line, the previous cell, basicallyâ€¦ Hmm.

965
01:44:49.510 --> 01:45:00.640
Gaurav Singh .: Can you just drop the graph where you haveâ€¦ yeah. So, here you have taken the NP random choice, size equals to 3, and you are appending to the averages, like.

966
01:45:01.060 --> 01:45:03.450
Gaurav Singh .: Y size equals to 3 has been chosen.

967
01:45:03.450 --> 01:45:07.080
Faculty (Olympus): Because he's playing an ODA series of three games. That is the problem, given to him.

968
01:45:07.080 --> 01:45:07.980
Gaurav Singh .: healthcare.

969
01:45:07.980 --> 01:45:09.770
Faculty (Olympus): And then change it to whatever else you want.

970
01:45:10.560 --> 01:45:12.179
Faculty (Olympus): Depending on the nature of the power.

971
01:45:12.960 --> 01:45:13.900
Gaurav Singh .: Understood, okay.

972
01:45:13.900 --> 01:45:17.509
Faculty (Olympus): Right? So this 3 is not magic number, it was given in the problem statement.

973
01:45:17.510 --> 01:45:18.500
Gaurav Singh .: Problems, technical.

974
01:45:19.550 --> 01:45:37.960
Faculty (Olympus): But it could be anything, right? It could be 20â€¦ but when it comes to 20, I can start making assumptions, center limit theorem, and all that I can do, but you learn upâ€¦ you learn about this. But the point is, you now have a computational engine with which you can do these things yourselves, and get estimates, and at least feel for a lot of these numbers, and you can actually use it in practical data sets.

975
01:45:38.820 --> 01:45:39.730
Gaurav Singh .: Got it.

976
01:45:40.190 --> 01:45:40.810
Faculty (Olympus): Okay.

977
01:45:40.810 --> 01:45:41.230
Gaurav Singh .: Thank you.

978
01:45:41.230 --> 01:45:41.900
Faculty (Olympus): Anand?

979
01:45:42.170 --> 01:45:49.499
Kunal Bijlani .: so, you told about the seed, where it takes the same number irrespective of the sequence and everything.

980
01:45:49.500 --> 01:46:03.969
Kunal Bijlani .: So, but regarding the choice, that is the, that isâ€¦ that we get it from the problem, that this has to be determined, that we need to give this, like, this, once you said, the size is equal to 3, because we areâ€¦ he's playing the ODI series of 3 games, soâ€¦

981
01:46:03.970 --> 01:46:04.360
Faculty (Olympus): Yeah.

982
01:46:04.360 --> 01:46:05.720
Kunal Bijlani .: Good to understand. Okay.

983
01:46:05.720 --> 01:46:06.110
Faculty (Olympus): Yes.

984
01:46:06.660 --> 01:46:07.720
Kunal Bijlani .: This isâ€¦

985
01:46:07.720 --> 01:46:21.420
Faculty (Olympus): because of that. Seed is nothing. So seed, you canâ€¦ you can set a seed here, then I and U will get the same set of averages. So this, again, this problem will also help you understand the seed. So what'll happen is if I set the seed at the first line here, say NP.seed, send me random seed.

986
01:46:21.730 --> 01:46:25.970
Faculty (Olympus): you and I will have the same averages. So you'll get the same histogram plot.

987
01:46:26.320 --> 01:46:29.010
Faculty (Olympus): But you'll still get aâ€¦ you'll still get a distribution.

988
01:46:30.540 --> 01:46:37.409
Faculty (Olympus): Right? And you change the seed, you'll get slightly different distribution, but the statistical quantities, like, you know, thisâ€¦ these fellows, will be roughly the same.

989
01:46:38.030 --> 01:46:38.700
Kunal Bijlani .: Okay.

990
01:46:39.710 --> 01:46:41.590
Kunal Bijlani .: So, thank you, thank you so much, son, thank you.

991
01:46:41.590 --> 01:46:42.120
Faculty (Olympus): Sure.

992
01:46:44.500 --> 01:46:47.709
Faculty (Olympus): Kunal, I think I answered your question just now, or no?

993
01:46:50.090 --> 01:46:51.510
Faculty (Olympus): Kunal, please ask.

994
01:46:51.700 --> 01:46:53.710
Kunal Bijlani .: So, for me, it is answered, like, I mean.

995
01:46:53.710 --> 01:46:55.810
Faculty (Olympus): Okay, great, okay, okay. Soumen?

996
01:46:58.650 --> 01:47:00.180
Soumen Deb .: scope,

997
01:47:00.660 --> 01:47:11.539
Soumen Deb .: So we have solved this problem with, what you said, bootstrapping and sampling. So is there a way to solve it with PMF also? I think so we must have shown it in last class, but just wanted to ask.

998
01:47:12.270 --> 01:47:22.460
Faculty (Olympus): No, no, so PMFâ€¦ so, okay, so, yeah, so PMF is slightly different. So the PMF now tells me about the distribution information. It doesn't actually give me the scores.

999
01:47:23.750 --> 01:47:35.390
Faculty (Olympus): So, in this approach, I'm actually spitting out new scores by sampling from the original distribution. From theâ€¦ from theâ€¦ so, when I do this random.choice, you know, you're essentially sampling from the original.

1000
01:47:37.470 --> 01:47:44.779
Faculty (Olympus): So, if there's a greater prevalence of Saturn to score low scores, which is kind of evident here, right? The tendency is to have lower scores.

1001
01:47:45.810 --> 01:47:49.990
Faculty (Olympus): You get out soon, right? And then you can stay for a long time.

1002
01:47:50.970 --> 01:47:53.690
Faculty (Olympus): That will reflect naturally when you do random choice.

1003
01:47:54.310 --> 01:48:00.610
Faculty (Olympus): For example, if I have 300 values of 0 and I have 3 values of 1, if I randomly choose from there, I'm going to get more zeros than 1.

1004
01:48:02.080 --> 01:48:08.480
Faculty (Olympus): So, in that sense, this random.choice does a fair job of picking from these numbers, and then gives you more numbers.

1005
01:48:11.050 --> 01:48:11.680
Soumen Deb .: Okay.

1006
01:48:11.680 --> 01:48:12.119
Faculty (Olympus): Makes sense.

1007
01:48:12.120 --> 01:48:12.820
Soumen Deb .: and stuff.

1008
01:48:13.210 --> 01:48:28.979
Faculty (Olympus): The idea isâ€¦ but the idea is, you have an existing data set, you're sort of resampling from that in an unbiased fashion. It's not like a human being sampling where you may have preferences. Like, computers are generating a random number, and those random numbers are statistically, you know, good properties.

1009
01:48:28.980 --> 01:48:34.610
Faculty (Olympus): Sorry, I didn't catch it off my video. Okay, so, so, and then you're generating these numbers.

1010
01:48:35.610 --> 01:48:38.980
Soumen Deb .: No, I'm asking this because in previous to previous class, we had that.

1011
01:48:39.200 --> 01:48:48.530
Faculty (Olympus): Correct, so there I'm asking a different question. So there I'm saying, you know, given all of this, can you tell me what's the probability that he's going to do this or that in a, you know, in a given score?

1012
01:48:48.810 --> 01:48:58.080
Faculty (Olympus): In which case, you know, the PMF gives me a much faster way to do this. If I wanted to do that here, then I'd have to again generateâ€¦ but there, I don't need to generate the data, because I already have the scores.

1013
01:48:58.390 --> 01:49:06.969
Faculty (Olympus): But yes, you can generate more data from that sample, generate one larger batch, and then use the same PMF idea there. You can do that too.

1014
01:49:08.400 --> 01:49:14.969
Soumen Deb .: So this one's more like, you know, what you have done is, like, you know, the random coin toss. So you're gonna toss a coin, that's whatâ€¦

1015
01:49:14.970 --> 01:49:29.759
Faculty (Olympus): I was trying to show you the connection, the intimate connection between these two quantities, you know, histograms and random variables. Here, I'm trying to show you how you can do probabilistic programming using these kind of tools to solve non-trivivial problems that you cannot solve by hand.

1016
01:49:30.470 --> 01:49:37.870
Soumen Deb .: Makes sense. Okay, okay, no, it answers, just clarifies both the approaches were. Okay, thank you, thank you very much.

1017
01:49:37.870 --> 01:49:39.600
Faculty (Olympus): Sure. Samrat?

1018
01:49:42.120 --> 01:49:46.500
Samrat Purkayastha .: Yes, sir. Sir, actually, I had a query regarding this, biased coin.

1019
01:49:46.970 --> 01:49:49.380
Samrat Purkayastha .: Regarding the bias, can you scroll over there, sir?

1020
01:49:50.110 --> 01:49:50.920
Faculty (Olympus): Okay?

1021
01:49:50.920 --> 01:49:53.500
Samrat Purkayastha .: Sir, in that, the P means the probability, correct?

1022
01:49:53.500 --> 01:49:54.140
Faculty (Olympus): Yes.

1023
01:49:54.490 --> 01:50:00.820
Samrat Purkayastha .: So, so, if I give a size 10 event, it should ideally give 5 heads and 5 tails?

1024
01:50:01.240 --> 01:50:02.850
Samrat Purkayastha .: But if I don't show you?

1025
01:50:03.120 --> 01:50:04.680
Faculty (Olympus): Come again, I'm sorry, Kamal again.

1026
01:50:04.680 --> 01:50:10.599
Samrat Purkayastha .: The probability is 5 for heads and 5, 50% for heads and 50% for tails.

1027
01:50:10.900 --> 01:50:11.320
Faculty (Olympus): Okay?

1028
01:50:11.320 --> 01:50:16.859
Samrat Purkayastha .: but when I give a size, for example, 5, 10, or 15, it usually doesn't give.

1029
01:50:17.660 --> 01:50:28.040
Faculty (Olympus): It won't. That's the point, because that is one sample of 5 coin tosses. If I give you 5 coin tosses, will you get exactlyâ€¦ well, 4 coin tosses? Not fair to ask for 5 and get same, right? Because I can only get 3 and 2.

1030
01:50:28.220 --> 01:50:29.659
Faculty (Olympus): One of them has to be more.

1031
01:50:29.960 --> 01:50:36.450
Faculty (Olympus): So let's say I do 10 divisible by 2, I should get 5 and 5, right? But you're not going to get 5 and 5.

1032
01:50:38.850 --> 01:50:39.730
Faculty (Olympus): Okay?

1033
01:50:41.260 --> 01:50:42.600
Samrat Purkayastha .: Okay, okay, thank you, sir.

1034
01:50:42.600 --> 01:50:49.160
Faculty (Olympus): Right? So what you need to do is, then you need to do many, many, many experiments like this, then on the average, you'll get 5 and 5.

1035
01:50:49.450 --> 01:50:50.520
Faculty (Olympus): Making sense?

1036
01:50:50.930 --> 01:50:53.279
Faculty (Olympus): Which, again, you can do with the tools I've shown you here.

1037
01:50:53.600 --> 01:50:54.620
Samrat Purkayastha .: Yes, yes.

1038
01:50:54.620 --> 01:51:02.869
Faculty (Olympus): Right? So you generate many of these, and then say 5, 5, power 5, and you'll get a distribution. In fact, you can doâ€¦ you can plot that distribution and see how it looks.

1039
01:51:03.670 --> 01:51:05.359
Samrat Purkayastha .: Okay, okay, thanks, thanks.

1040
01:51:08.290 --> 01:51:14.819
Faculty (Olympus): All right, folks, thank you for not asking too many questions. I need to now make my calls and find out what's happened, soâ€¦

1041
01:51:15.350 --> 01:51:19.870
Faculty (Olympus): See you on, Wednesday. Have a great weekend.

1042
01:51:19.870 --> 01:51:20.510
Anita Menon .: My pleasure.

1043
01:51:20.510 --> 01:51:21.789
Jasmine Samant .: Thank you so much, take care.

1044
01:51:21.790 --> 01:51:23.660
Kedar Digambar Gokhale .: Thank you. Take care, sir. Thank you.

1045
01:51:23.660 --> 01:51:24.200
Rahul Saini .: Beautiful.

1046
01:51:24.360 --> 01:51:25.070
Faculty (Olympus): Aye.

1047
01:51:29.890 --> 01:51:31.040
Faculty (Olympus): Stop shooting.

