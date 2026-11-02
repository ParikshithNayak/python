WEBVTT

1
00:11:21.600 --> 00:11:23.110
Faculty (Olympus): Good morning, everyone.

2
00:11:25.240 --> 00:11:25.680
Jasmine Samant: Good morning.

3
00:11:25.680 --> 00:11:26.590
Abhineet Bansal: Mutsu.

4
00:11:26.990 --> 00:11:28.360
Sejal Patil .: Enlighten.

5
00:11:28.940 --> 00:11:29.929
Sneha Bhide .: Good morning, Seth.

6
00:11:31.890 --> 00:11:32.710
Rajesh Kumar Singh .: Morning!

7
00:11:35.130 --> 00:11:37.150
Faculty (Olympus): And let me just set up myâ€¦

8
00:11:49.200 --> 00:11:52.950
Faculty (Olympus): Alright, so ifâ€¦ since we'll be waiting for 5 minutes, let's,

9
00:12:02.470 --> 00:12:05.889
Faculty (Olympus): You can start asking questions, and I will try to answer them.

10
00:12:10.160 --> 00:12:10.960
Faculty (Olympus): Stick.

11
00:13:11.170 --> 00:13:12.090
Faculty (Olympus): Spending?

12
00:13:23.870 --> 00:13:27.010
Faculty (Olympus): Alright, so if there are questions,

13
00:13:29.670 --> 00:13:32.509
Faculty (Olympus): Can you please raise your hands? I will try and answer.

14
00:13:34.570 --> 00:13:36.280
Faculty (Olympus): If there are none, we'll just start.

15
00:13:44.270 --> 00:13:46.870
Faculty (Olympus): Okay, so there are no questions at this point.

16
00:13:47.110 --> 00:13:49.960
Faculty (Olympus): Great, well, there are someâ€¦

17
00:13:55.220 --> 00:14:00.350
Faculty (Olympus): Yeah, okay, so don't worry about enrollment requests, we'll approve everything immediately.

18
00:14:02.170 --> 00:14:07.599
Faculty (Olympus): You're not supposed to upload doc or submission on your exporter. You're supposed to code it right there.

19
00:14:11.540 --> 00:14:12.390
Faculty (Olympus): Here?

20
00:14:12.620 --> 00:14:15.909
Faculty (Olympus): Submissions will only be on the JLP.

21
00:14:19.740 --> 00:14:22.540
Faculty (Olympus): Can you hear me? Can someone confirm that you can.

22
00:14:22.540 --> 00:14:23.420
Soumen Deb .: We can hear you.

23
00:14:24.150 --> 00:14:24.530
Abhishek Agrawal .: Yes, sir.

24
00:14:24.530 --> 00:14:25.069
Faculty (Olympus): Okay, great.

25
00:14:25.070 --> 00:14:26.870
Amlan Sarkar .: Yes, sir, yes, sir, we can hear you.

26
00:14:27.340 --> 00:14:46.750
Faculty (Olympus): Great. Okay, so since there are no questions, let's just jump in and start with the class, then we can make some good progress and maybe finish this notebook today. So, today's class will be focused on statistics, plotting, and numerics, so maybe I'll start with a couple of questions. What have you covered up to now?

27
00:14:46.780 --> 00:14:48.220
Faculty (Olympus): In your stats course?

28
00:14:48.630 --> 00:14:49.670
Amlan Sarkar .: All electric.

29
00:14:50.870 --> 00:14:52.819
Soumen Deb .: We have covered probability.

30
00:14:52.930 --> 00:14:55.310
Soumen Deb .: And basic, base theorem.

31
00:14:55.310 --> 00:14:56.509
Bipin Karyakarte .: counting and sampling.

32
00:14:57.130 --> 00:14:57.710
Faculty (Olympus): Okay.

33
00:14:58.350 --> 00:15:00.109
Faculty (Olympus): You've still not yet done,

34
00:15:01.100 --> 00:15:04.029
Faculty (Olympus): You've still not come to random variables and things like that?

35
00:15:04.030 --> 00:15:04.440
Soumen Deb .: No, no.

36
00:15:04.440 --> 00:15:06.460
Bipin Karyakarte .: Today, they will start the random variables.

37
00:15:06.460 --> 00:15:07.709
Faculty (Olympus): Today, you're starting.

38
00:15:07.710 --> 00:15:08.560
Bipin Karyakarte .: Possibly.

39
00:15:09.230 --> 00:15:10.449
Faculty (Olympus): Okay, very good.

40
00:15:11.880 --> 00:15:12.880
Amlan Sarkar .: No problem.

41
00:15:12.880 --> 00:15:13.630
Faculty (Olympus): So, so, okay.

42
00:15:14.140 --> 00:15:20.270
Faculty (Olympus): That's all right, so we'll go a bit ahead of your class, but that doesn't matter, it's all right, we'll, you know, hopefully this will sort of,

43
00:15:20.700 --> 00:15:22.240
Faculty (Olympus): Support your other class.

44
00:15:24.140 --> 00:15:25.090
Faculty (Olympus): Excuse me.

45
00:15:25.700 --> 00:15:26.160
Faculty (Olympus): That's what it is.

46
00:15:28.050 --> 00:15:34.460
Faculty (Olympus): Can you please mute yourselves if you areâ€¦ Not gonna ask a question.

47
00:15:37.340 --> 00:15:45.149
Faculty (Olympus): Alright, so this notebook has already been shared, we already looked at a small segment of it. What we'll do is, we'll sort of walk through this.

48
00:15:45.970 --> 00:15:53.560
Faculty (Olympus): And the initial part is going to be, you know, descriptive statistics, okay? And then, very soon, we'll come to

49
00:15:53.700 --> 00:15:58.069
Faculty (Olympus): Sort of more statistical plots.

50
00:15:58.400 --> 00:16:06.689
Faculty (Olympus): And then I'll start introducing some of the theories so that you can make the connections when you do your theory, okay? And it's very important that you keep this in mind.

51
00:16:06.860 --> 00:16:10.180
Faculty (Olympus): So we start with our usual imports, as always.

52
00:16:10.480 --> 00:16:15.579
Faculty (Olympus): And last class, I told you we have this data file. I hope this data file has been uploaded.

53
00:16:16.110 --> 00:16:17.100
Faculty (Olympus): Believe it is.

54
00:16:17.100 --> 00:16:17.660
Soumen Deb .: there.

55
00:16:17.660 --> 00:16:24.420
Faculty (Olympus): Okay, great, fine. So, you're all able to perhaps run these, you know, notebooks and all this. Soâ€¦

56
00:16:24.850 --> 00:16:28.580
Faculty (Olympus): In your setup, yeah, I think it'll be about the same.

57
00:16:29.540 --> 00:16:32.119
Faculty (Olympus): So there's a data directory, so you have to go out to the slideâ€¦

58
00:16:32.120 --> 00:16:43.309
Samar .: Sorry to interrupt. This notebook, at least I don't see on this Jupyter one, if we have to run it in the class,

59
00:16:43.310 --> 00:16:48.100
Faculty (Olympus): Yes, you should be able to see it. It's live, it's been live for several days.

60
00:16:48.450 --> 00:16:49.200
Samar .: Okay.

61
00:16:49.910 --> 00:16:51.080
Faculty (Olympus): And no one else has complained.

62
00:16:52.240 --> 00:16:56.790
Soumen Deb .: I'll bring you a link, I'll bring you a link, you can download it and run it in your local, yeah?

63
00:16:56.790 --> 00:16:57.570
Samar .: Thank you.

64
00:16:57.570 --> 00:17:00.419
Faculty (Olympus): Yeah, but you should be able to refresh and it should work.

65
00:17:00.630 --> 00:17:02.830
Samar .: Hmm, yeah. Anyways, let's continue.

66
00:17:02.830 --> 00:17:07.030
Faculty (Olympus): And it should definitely work. It's in the slides folder. It's the same place I've been.

67
00:17:07.030 --> 00:17:09.280
Samar .: Oh, okay, okay, okay, okay.

68
00:17:09.510 --> 00:17:14.639
Faculty (Olympus): It's in the same place, it's not changed at all since the first class. It's been the same place. Yes?

69
00:17:14.640 --> 00:17:21.750
Bipin Karyakarte .: Professor, this data.loadâ€¦ no, what is that file? Data.txt. Where is it available?

70
00:17:22.579 --> 00:17:23.829
Faculty (Olympus): Same place.

71
00:17:23.829 --> 00:17:24.609
Bipin Karyakarte .: Yeah.

72
00:17:24.609 --> 00:17:27.759
Soumen Deb .: It's in the data folder. It's in the data folder there.

73
00:17:28.180 --> 00:17:28.550
Soumen Deb .: investing.

74
00:17:28.550 --> 00:17:30.130
Faculty (Olympus): I mean, I don't understandâ€¦

75
00:17:30.130 --> 00:17:32.959
Bipin Karyakarte .: It's in the data folder. Fine, friends. Yeah, yeah, sorry.

76
00:17:32.960 --> 00:17:36.299
Faculty (Olympus): Sorry, Professor. Yeah, please, yeah, please explore this, right?

77
00:17:36.300 --> 00:17:37.209
Bipin Karyakarte .: Yeah, yeah, sure, sure.

78
00:17:37.210 --> 00:17:41.870
Faculty (Olympus): Sorry. Because I've tried to make sure that you have the data, but

79
00:17:42.200 --> 00:18:04.409
Faculty (Olympus): If there is an issue, please raise it, I will try to address it. Okay. So, the first thing is, you can right now ignore certain details about NumPy. We will be covering NumPy in, you know, great detail a little later, but I wanted to keep things fun for the initial part, and sort of introduce you to statistical concepts. So, don't worry about, you know, oh, I don't know what this data thing is, it looks like a matrix and stuff, we'll come back to this.

80
00:18:04.460 --> 00:18:18.860
Faculty (Olympus): But if you are assuming it looks like a matrix, yes, it is going to look like a matrix. So if you look at printlenov data, it says it has 100. So what that means is it has 100 rows, okay? And in each, you know, the file has 2 columns.

81
00:18:19.450 --> 00:18:20.670
Faculty (Olympus): Excuse me.

82
00:18:21.660 --> 00:18:36.869
Faculty (Olympus): And as you can see, if you just print out the first two rows, so that's the way to get the first two rows, right? Colon two. So the slicing syntax is very similar, it's just that the firstâ€¦ the slice that you place there is going to apply on the rows. Just keep that in mind.

83
00:18:37.050 --> 00:18:45.229
Faculty (Olympus): So now this gives you the first two rows, and you can see that the first two rows are these two, which is exactly the same as this. Some of you may get confused by this, but please remember.

84
00:18:45.340 --> 00:18:50.029
Faculty (Olympus): Yeah, this is, like, very long, but remember there's a plusâ€¦ the EE to the Eâ€¦

85
00:18:50.760 --> 00:18:58.630
Faculty (Olympus): plus 0, 1, right? So this number is basically the exponent, so it's 10 to the power 1, so it's actually 69.

86
00:18:58.860 --> 00:19:10.139
Faculty (Olympus): 308, right? So that's the number here, and that's the second row. So you have two columns. So this is somewhat inconvenient, unless you know Pythonâ€¦ sorry, NumPy very well.

87
00:19:10.840 --> 00:19:30.210
Faculty (Olympus): So, what we'll do now is, we'll use this unpack equal to true argument here, and what this does is, it'll return a tuple, essentially, or you can think of it as it'll return the two columns, rather than it'll return this complicated matrix object. Later, we'll understand how this actually works under the covers, but

88
00:19:30.220 --> 00:19:37.400
Faculty (Olympus): Don't worry about it for now. So now you have two things, both of which are numpy arrays, and both of them, essentiallyâ€¦ oopsâ€¦

89
00:19:38.550 --> 00:19:41.140
Faculty (Olympus): Okay, I didn't Velma.

90
00:19:41.440 --> 00:19:43.759
Faculty (Olympus): Okay, it involves. Okay.

91
00:19:44.020 --> 00:19:44.830
Faculty (Olympus): Good.

92
00:19:45.610 --> 00:19:54.300
Faculty (Olympus): Okay, fine. So now we have, two arrays, numpy arrays, and

93
00:19:54.530 --> 00:20:05.560
Faculty (Olympus): This, when you do X colon 2, this is going to give me the first two rows of X alone, which will just be this column, right? These two elements, this fellow, and this 50, okay, which is exactly what we have here.

94
00:20:05.660 --> 00:20:11.370
Faculty (Olympus): And now that we have these two quantities, we can do a bunch of little stats with these. So let's now look at this.

95
00:20:11.470 --> 00:20:19.749
Faculty (Olympus): The first thing is mean, we already looked at this in the last class, mean of Y, mean of X, and then we looked at the standard deviation. This is, by default.

96
00:20:20.180 --> 00:20:30.959
Faculty (Olympus): I don't cover this yet, but you will be covering this in a lot more detail in your stats course. But the idea is the following. Supposing you know the true mean.

97
00:20:31.790 --> 00:20:46.530
Faculty (Olympus): right, you know the true mean. Let's say it's not just X bar, but it is mu of the distribution. Then, you know, you can use this bias estimator, it doesn't matter. But usually, what you're doing is, you're estimating the standard deviation by estimating first the mean itself, by X bar.

98
00:20:46.530 --> 00:20:55.329
Faculty (Olympus): And in such a case, you've essentially lost one degree of freedom, and you have n-1 in the denominator. And the way to access that is to use this DDOF. Did someone have a question?

99
00:20:58.230 --> 00:21:09.389
Faculty (Olympus): Okay, varun, I'm just muting you. All right. And if you didn't understand this, you know, your stats course is going to cover this in some detail, but maybe we can revisit it later on after you do a little more stats.

100
00:21:09.570 --> 00:21:10.760
Faculty (Olympus): Then you can work immediately.

101
00:21:10.760 --> 00:21:13.059
varun kumar .: What did we mean by losing a freedom?

102
00:21:13.820 --> 00:21:14.680
Faculty (Olympus): Sorry, what?

103
00:21:15.100 --> 00:21:19.849
varun kumar .: You, you just, you said you lost a freedom of one. What that means?

104
00:21:21.470 --> 00:21:26.959
Faculty (Olympus): I just said, right, if you know the true mean, again, I don't know if you know enough about this.

105
00:21:27.340 --> 00:21:33.199
Faculty (Olympus): So, if you have a probability, associated with some quantity, okay?

106
00:21:34.570 --> 00:21:41.720
Faculty (Olympus): Let's say we have the weight of this, weight of all students showing up in PML in this course.

107
00:21:43.980 --> 00:21:47.510
Faculty (Olympus): Okay, and I say, that's a quantity I'm looking at.

108
00:21:47.690 --> 00:21:51.990
Faculty (Olympus): Now, this quantity Is inherently a variable.

109
00:21:52.220 --> 00:21:59.860
Faculty (Olympus): So if I suddenly pick one of the students and ask you your weight, it's going to be some number, right? It's going to be some positive number.

110
00:22:00.000 --> 00:22:02.770
Faculty (Olympus): Slightly less than 1000 kgs.

111
00:22:02.880 --> 00:22:17.629
Faculty (Olympus): And likely greater than 25 kgs, right? I'm just speaking to extremes, right? I don't believe any of you weighs a ton. I don't know if any of you weighs 25. It's unlikely to see those numbers. Again, it's unlikely. So, let's say myâ€¦

112
00:22:18.800 --> 00:22:22.630
Faculty (Olympus): Some 2-year-old or 3-year-old dentist, the weight is going to drop to, you know, less thanâ€¦

113
00:22:22.660 --> 00:22:41.800
Faculty (Olympus): Maybe 10 kgs, that's a different story. But let's assume people here are not 2-year-old, right? So your weights are going to be at least about 25, less than 1,000. But it's going to be some number in between this, and there's going to be a distribution. As in, there's going toâ€¦ if you were to look at how these things are distributed, as in, you take bins of this, and you start looking at them, you plot a histogram of this.

114
00:22:41.800 --> 00:22:45.990
Faculty (Olympus): you'll see them distributed in a specific fashion. Now, if I ask you.

115
00:22:46.110 --> 00:22:50.190
Faculty (Olympus): what is the mean of this? How are you going to be able to answer this question?

116
00:22:53.450 --> 00:22:54.890
varun kumar .: Yeah, Veena, I understand.

117
00:22:54.890 --> 00:22:57.309
Faculty (Olympus): No, no, no, no, no, you may not understand.

118
00:22:57.520 --> 00:22:59.920
Faculty (Olympus): When you say, do you understand, what do you mean by the mean?

119
00:23:00.900 --> 00:23:08.760
Faculty (Olympus): Will you take all the students in your class, find that, divide by the total number of students, find the total weight, and divide by the number of students, and give me an answer?

120
00:23:08.760 --> 00:23:10.760
Shravan Ganpur: Yes?

121
00:23:11.070 --> 00:23:11.410
Faculty (Olympus): Yes.

122
00:23:11.720 --> 00:23:12.590
Shravan Ganpur: Yes, that would be theâ€¦

123
00:23:12.590 --> 00:23:16.169
Faculty (Olympus): That, that happens to be an estimate of the mean.

124
00:23:16.780 --> 00:23:23.160
Faculty (Olympus): Okay, so this is a concept that you will be hammered in probably in your stats course. Maybe not, so I'll do it here.

125
00:23:24.170 --> 00:23:31.980
Faculty (Olympus): The point is, when I say I'm looking at any student who's ever going to show up, supposing I take the weights of all of you today.

126
00:23:32.310 --> 00:23:34.059
Faculty (Olympus): And I take the weights of all of you?

127
00:23:34.350 --> 00:23:37.640
Faculty (Olympus): A week from now. Do you think the rates are going to be the same for the same person?

128
00:23:38.060 --> 00:23:40.890
Faculty (Olympus): They're not. They're gonna move, right?

129
00:23:42.250 --> 00:23:53.139
Faculty (Olympus): So, the point is, if everything is changing every day, if I just take today's set of weights, and give you the mean of these, it's only an approximation to the true mean.

130
00:23:53.990 --> 00:23:56.399
Faculty (Olympus): Of your class. Does this make sense?

131
00:23:59.500 --> 00:24:01.730
varun kumar .: Yeah, yes, sir.

132
00:24:01.730 --> 00:24:02.950
Rahul Joshi .: Meanful today, right?

133
00:24:02.950 --> 00:24:03.680
Faculty (Olympus): No.

134
00:24:05.140 --> 00:24:08.519
Faculty (Olympus): The true mean for the abstract population that I'm talking about.

135
00:24:10.200 --> 00:24:12.190
Faculty (Olympus): Is this the only PML course?

136
00:24:12.570 --> 00:24:15.719
Amit Srivastava .: It's a kind of instance, we are saying, at the instance.

137
00:24:15.720 --> 00:24:16.390
Faculty (Olympus): Yes.

138
00:24:16.670 --> 00:24:21.840
Faculty (Olympus): But is this the true mean of the population? What is the population of all students who have ever attended PML?

139
00:24:22.430 --> 00:24:31.499
Faculty (Olympus): That would mean the population of all the students integrated over all the time they have spent in this course, integrated over all possible batches, current and future.

140
00:24:31.650 --> 00:24:34.490
Soumen Deb .: This is a sampleâ€¦ this is a sample unit.

141
00:24:34.490 --> 00:24:36.220
Faculty (Olympus): Exactly. So when I doâ€¦

142
00:24:36.350 --> 00:24:45.179
Faculty (Olympus): np.std of X, or whatever, npd.me of X, I'm taking a sample. From that sample, I'm giving you a number.

143
00:24:46.040 --> 00:24:49.109
Faculty (Olympus): Okay? But when I say true population mean.

144
00:24:49.620 --> 00:24:58.439
Faculty (Olympus): That is an abstract quantity that you're only going to get approximations of, unless I mathematically construct that quantity and say, okay, I will now do something.

145
00:24:58.720 --> 00:25:00.109
Faculty (Olympus): Am I making sense?

146
00:25:00.280 --> 00:25:09.850
Faculty (Olympus): In an idealized case, or if I'm generating this through a computer, I can say, oh, this is the true mean, or I can ideally say, okay, if this is the true mean of the population, I can do something.

147
00:25:11.020 --> 00:25:14.389
Faculty (Olympus): As in, I canâ€¦ I can analytically construct things from it.

148
00:25:14.580 --> 00:25:19.019
Faculty (Olympus): Right? We can imagine that there is a true population whose mean weight is 60 kilograms.

149
00:25:19.130 --> 00:25:22.679
Faculty (Olympus): Butâ€¦ This current population may not be that population.

150
00:25:22.810 --> 00:25:23.600
Faculty (Olympus): Okay?

151
00:25:23.880 --> 00:25:28.520
Faculty (Olympus): If at all, and if they are representing the same thing, this is an approximation to that population.

152
00:25:30.420 --> 00:25:38.880
Faculty (Olympus): And the way I will get better and better estimates of that true mean is going to be through larger and larger and larger and larger and larger samples in the limit of infinite samples.

153
00:25:39.620 --> 00:25:40.800
Faculty (Olympus): Is that clear?

154
00:25:41.040 --> 00:25:41.670
Soumen Deb .: Yep.

155
00:25:42.210 --> 00:25:47.140
Faculty (Olympus): Okay, so when I do X bar, X bar is the mean that you've computed from a sample.

156
00:25:49.910 --> 00:25:55.220
Faculty (Olympus): Okay? It turns out that if you were to take the expectation of this formula.

157
00:25:55.740 --> 00:26:01.919
Faculty (Olympus): That is, you find theâ€¦ on the average sigma squared from this formula, you'll find that there's a small bias.

158
00:26:02.330 --> 00:26:05.149
Faculty (Olympus): The only way to correct for that bias is to basically

159
00:26:05.360 --> 00:26:15.559
Faculty (Olympus): Divide by n-1 and not n. The reason for this, intuitively, is because your X bar is only an estimate that is computed using the same values that you're computing sigma squared.

160
00:26:16.270 --> 00:26:21.830
Faculty (Olympus): So, if you had N quantities, you already computed using these N quantities X bar.

161
00:26:21.990 --> 00:26:27.689
Faculty (Olympus): Right? And now you're computing sigma squared from the same set of quantities, so you can't use n anymore, you have to use n minus 1.

162
00:26:27.860 --> 00:26:31.670
Faculty (Olympus): Okay, this is a hand-waving argument for this, this is not a proof.

163
00:26:31.970 --> 00:26:33.800
Faculty (Olympus): Right? You can look at this.

164
00:26:34.270 --> 00:26:38.219
Faculty (Olympus): You can ask your stats instructors, right? I've already spent too much time on this.

165
00:26:39.330 --> 00:26:40.270
Faculty (Olympus): Alex?

166
00:26:41.200 --> 00:26:57.169
Faculty (Olympus): Do you understand what I'm saying? So X bar, remember, is not the mean of the population, it is the mean of the sample. Similarly, when you're doing numpy.std, very often, you know, you'll have to choose between the np.sttt without the DDOF, or you have to set a DDOF to 1.

167
00:26:57.340 --> 00:27:04.319
Faculty (Olympus): Now, when n is large, let's say you have a million samples, the N and N-1 probably make zero difference to you, okay? So it doesn't matter.

168
00:27:04.670 --> 00:27:09.320
Faculty (Olympus): But in small samples, it does make a big difference. So you have only 10 values, it makes a difference.

169
00:27:09.660 --> 00:27:19.780
Faculty (Olympus): So just keep this in mind, okay? This will be obvious to you when you're doing your calculations, when you learn little more stats. The next is median. Have you all done percentiles in your class?

170
00:27:20.810 --> 00:27:21.740
Soumen Deb .: Not yet.

171
00:27:21.940 --> 00:27:22.350
Faculty (Olympus): Not yet.

172
00:27:22.510 --> 00:27:24.629
Bipin Karyakarte .: No kidding. No kidding.

173
00:27:24.800 --> 00:27:25.890
Faculty (Olympus): Oh, okay.

174
00:27:28.500 --> 00:27:31.519
Faculty (Olympus): So, what isâ€¦ do you know what the definition of percentile is?

175
00:27:32.240 --> 00:27:32.870
Bipin Karyakarte .: Moses.

176
00:27:32.870 --> 00:27:37.980
Soumen Deb .: Yes, something between when you break the entire space from,

177
00:27:37.980 --> 00:27:38.630
Faculty (Olympus): 25.

178
00:27:38.630 --> 00:27:40.270
Soumen Deb .: It's the P7500.

179
00:27:40.270 --> 00:27:42.550
Faculty (Olympus): No, so let me explain to you, so what it is.

180
00:27:42.550 --> 00:27:43.900
Saurabh Puranik .: Well, isn't thatâ€¦

181
00:27:44.070 --> 00:27:46.240
Faculty (Olympus): So, percentile basically means

182
00:27:46.640 --> 00:27:57.279
Faculty (Olympus): If I give youâ€¦ if I'm talking in terms of 100 percentile, so I'm implicitly going to use this 100 percentile, okay? Which means 100 percentile means 100% of the population is less than that value.

183
00:27:57.920 --> 00:28:04.319
Faculty (Olympus): If I say 50 percentile, so I give you a population, let's say our weights in this class, and I say 50 percentile.

184
00:28:04.480 --> 00:28:09.139
Faculty (Olympus): The 50 percentile corresponds to a weight in your class.

185
00:28:09.640 --> 00:28:10.970
Faculty (Olympus): Such thatâ€¦

186
00:28:11.300 --> 00:28:22.839
Faculty (Olympus): 50% of the population is less than that number. So let me put it in terms of an actual number, okay? Let us say 50â€¦ the 50 percentile weight of this class today, right?

187
00:28:24.200 --> 00:28:28.530
Faculty (Olympus): of this class today isâ€¦ 65 kilograms.

188
00:28:28.950 --> 00:28:34.179
Faculty (Olympus): What this means is, if I were to take all the weights of this 185 participants today.

189
00:28:35.780 --> 00:28:41.099
Faculty (Olympus): I will find thatâ€¦ 50%, which is, like, 92.

190
00:28:41.540 --> 00:28:44.890
Faculty (Olympus): Okay, 92 people in this class.

191
00:28:49.150 --> 00:28:54.639
Faculty (Olympus): are less than the weight, or less than or equal to the weight of 65. Is this clear? That's what you mean by a.

192
00:28:54.640 --> 00:28:55.660
Soumen Deb .: Yes, yes.

193
00:28:55.660 --> 00:28:56.500
Siddharth Digambar Kulkarni .: That is the idea.

194
00:28:56.500 --> 00:28:57.870
Rahul Joshi .: 1 into median?

195
00:28:57.870 --> 00:29:09.480
Faculty (Olympus): And that is the median. Median happens to be the 50th percentile. But there are other percentiles. You can ask, what is 1 percentile? What is 99 percentile? What is 99.999 percentile? All of these questions you can ask, okay?

196
00:29:09.570 --> 00:29:25.789
Faculty (Olympus): So, given a set of data values, if I do np.median, it's going to just give me the 50 percentile, but in general, you can also use the percentile, np.percentile, right? But very often, you don't want just one percentile. You want to say, okay, give me the 25, 50, 75, and 90, okay?

197
00:29:25.840 --> 00:29:39.950
Faculty (Olympus): Now, typically, the difference between 75 percentile and 25 percentile is called the interquartile range, okay? So it's like a standard deviation. It is a measure of spread of your values, okay? The larger it is means there's more spread in the values.

198
00:29:40.030 --> 00:29:53.499
Faculty (Olympus): So here, the thing I'm trying to illustrate here is, with NP percentile, instead of calling this NP percentile 50, 25 separately, it's much more efficient to do this. The reason is, when you want to compute a percentile, the way it is actually done is, you sort the values.

199
00:29:53.930 --> 00:29:58.820
Faculty (Olympus): Right? And then you count what fraction of the population is to the left or to the right.

200
00:29:59.400 --> 00:30:09.570
Faculty (Olympus): Alright, so which means you have to keep sorting this data every time you do it. So it's going to save some cost, because you can sort it in one shot, and then find out all of these values. So it's faster to evaluate it this way.

201
00:30:10.670 --> 00:30:19.259
Faculty (Olympus): Alright, so I have an exercise for you. From the data above, for both X and Y, so maybe I will make that explicit here.

202
00:30:23.600 --> 00:30:31.440
Faculty (Olympus): For both columns, find the percentiles from 0 to 100 in unit steps, and plot these values.

203
00:30:32.120 --> 00:30:43.459
Faculty (Olympus): Okay, so please try this solution right away. It's just takingâ€¦ will take you a minute. It will also force you to engage with this question of what on earth is this percentile. Meanwhile, if you have questions, I'll answer them.

204
00:30:50.210 --> 00:30:54.010
Faculty (Olympus): So the path, some people are asking questions like, which path is this?

205
00:30:54.600 --> 00:30:59.540
Faculty (Olympus): if you notice that the files that I have uploaded are numbered, right? Soâ€¦

206
00:31:00.190 --> 00:31:09.729
Faculty (Olympus): You obviously don't want to do 0-1, that'll be first class, right? Alwaysâ€¦ this is theâ€¦ this is how I've been doing this. Every single class, we've already had the fifth class, okay?

207
00:31:09.910 --> 00:31:14.660
Faculty (Olympus): So, by this time, you should know the workflow. It's gonna be on that GitHub link.

208
00:31:15.320 --> 00:31:20.210
Faculty (Olympus): Okay, and it's gonna be the lastâ€¦ notebook or PDF on that.

209
00:31:20.500 --> 00:31:24.979
Faculty (Olympus): folder inside the slides folder. The data is inside the data folder, okay?

210
00:31:25.240 --> 00:31:26.250
Faculty (Olympus): All day.

211
00:31:27.300 --> 00:31:33.670
Faculty (Olympus): If someone has finished this exercise, please, raise your hand or do aâ€¦ actually, no, do a thumbs up.

212
00:31:34.080 --> 00:31:35.399
Faculty (Olympus): then I will know.

213
00:31:36.530 --> 00:31:40.309
Faculty (Olympus): And those of you who have questions, raise your hands, I will answer your questions.

214
00:31:42.870 --> 00:31:44.300
Faculty (Olympus): Okay, no questions.

215
00:31:47.190 --> 00:31:50.970
Faculty (Olympus): Oh, people are not asking too many questions today, okay? That's okay.

216
00:32:01.170 --> 00:32:02.960
Faculty (Olympus): Alright, Lakshmisha, please ask.

217
00:32:04.760 --> 00:32:17.500
Lakshmeesha J Rao .: Good morning, Professor. I downloaded the datatech.txt file onto my local system, but when I use the command, I'm getting an error, and I mightâ€¦

218
00:32:17.500 --> 00:32:20.209
Faculty (Olympus): You probably haven't put the right directory path.

219
00:32:20.420 --> 00:32:30.729
Lakshmeesha J Rao .: I did that. I changed the path to, direct it to my downloads folder, and then data.txt, but still I'm getting a syntax error, a code error.

220
00:32:31.000 --> 00:32:32.489
Lakshmeesha J Rao .: Something like that, soâ€¦

221
00:32:32.940 --> 00:32:34.200
Faculty (Olympus): Yeah, yeah, soâ€¦

222
00:32:34.310 --> 00:32:44.149
Faculty (Olympus): Again, my suggestion is you please move that file to the same directory you have your notebook, then life will be a little easier. You probably, if you have a syntax error, you've typed something wrong.

223
00:32:46.820 --> 00:32:47.440
Lakshmeesha J Rao .: A.

224
00:32:48.110 --> 00:32:49.600
Lakshmeesha J Rao .: Sure.

225
00:32:49.600 --> 00:32:52.350
Faculty (Olympus): The syntax error will actually tell you where the syntax error is.

226
00:32:53.260 --> 00:32:58.860
Lakshmeesha J Rao .: Yeah, it's pointing to the single quote that is there inâ€¦ inside the brackets.

227
00:32:59.350 --> 00:33:03.990
Faculty (Olympus): Yeah, so if you have space inside the bracket, something you've made, something's wrong.

228
00:33:04.670 --> 00:33:10.380
Faculty (Olympus): Maybe you can type yourâ€¦ you can cut-paste the code on the chat session, and a TM may answer your question.

229
00:33:12.130 --> 00:33:12.900
Lakshmeesha J Rao .: Sure.

230
00:33:13.420 --> 00:33:18.529
Faculty (Olympus): Right? Okay, folks, I don't see more people raising their thumbs up.

231
00:33:25.230 --> 00:33:30.989
Faculty (Olympus): Okay, soâ€¦ 7, 8, 10â€¦ are there people who are not able to answer this question?

232
00:33:33.990 --> 00:33:35.910
Abhineet Bansal: Yes, sir. Still trying.

233
00:33:36.800 --> 00:33:40.060
Faculty (Olympus): Okay, so the question is very straightforward, right? What is the question?

234
00:33:40.800 --> 00:33:42.670
Faculty (Olympus): So, I'll solve this problem.

235
00:33:42.960 --> 00:33:52.539
Faculty (Olympus): Okay, just so that you get some practice. So, what are theâ€¦ what is the data? We already have the data in the X and Y, right? Theseâ€¦ these two things that we already loaded, right? So, we have X and Y.

236
00:33:52.760 --> 00:34:00.489
Faculty (Olympus): what I want to do is find the percentile. So how do I find, say, if I want to find 0 percentile or something like that, I can say np.percentile.

237
00:34:01.560 --> 00:34:04.369
Faculty (Olympus): X, and then say 0.

238
00:34:04.510 --> 00:34:06.320
Faculty (Olympus): That gives me a number, right?

239
00:34:06.950 --> 00:34:14.649
Faculty (Olympus): Now, what I want to do is, I want to first create a plot where the x-axis is going to be from 0 to 100 in steps of 1.

240
00:34:14.800 --> 00:34:17.910
Faculty (Olympus): The Y axis is going to be the percentile values.

241
00:34:18.360 --> 00:34:21.650
Faculty (Olympus): Right? So I need to just create these two. So how do I do that?

242
00:34:21.929 --> 00:34:23.639
Faculty (Olympus): So, many ways to do this.

243
00:34:26.449 --> 00:34:32.389
Faculty (Olympus): There are many ways to do it. So one, you know, silly way to do it is to say X is, not X.

244
00:34:33.320 --> 00:34:42.270
Faculty (Olympus): X axis, because X is going to clobber that X, so I'm going to say X axis is list of range 0, 101.

245
00:34:43.440 --> 00:34:44.330
Faculty (Olympus): Okay?

246
00:34:45.190 --> 00:34:52.380
Faculty (Olympus): And then, I will sayâ€¦ YA is np.percentile of X8.

247
00:34:54.330 --> 00:34:57.039
Faculty (Olympus): And then PLT.lodic, stay A.

248
00:35:00.450 --> 00:35:01.410
Faculty (Olympus): Okay?

249
00:35:02.630 --> 00:35:05.840
Faculty (Olympus): Repeat the same thing forâ€¦

250
00:35:06.370 --> 00:35:08.890
Faculty (Olympus): For Y, you'll get something kind of similar.

251
00:35:16.740 --> 00:35:18.240
Atul Ashok Kumar Gupta .: Okay.

252
00:35:18.240 --> 00:35:18.850
Faculty (Olympus): Basically.

253
00:35:18.850 --> 00:35:19.390
Atul Ashok Kumar Gupta .: Nope.

254
00:35:19.390 --> 00:35:27.689
Faculty (Olympus): This is starting at 0, going all the way to 100, and these are the marks, so you want to make this slightly better looking, you can maybe say PLT.grid.

255
00:35:33.400 --> 00:35:36.030
Faculty (Olympus): A little easier to read this, okay?

256
00:35:42.230 --> 00:35:45.579
Abhineet Bansal: I thought the question meant that you have to plot X against Y.

257
00:35:51.430 --> 00:35:54.649
Kapil Shailesh Inamdar .: Yeah, even I did that plotted X against Y.

258
00:35:56.830 --> 00:36:00.369
Atul Ashok Kumar Gupta .: Prof, we can run a for loop for this, right?

259
00:36:00.840 --> 00:36:02.749
Anita Menon .: Yeah, even I did the four leak.

260
00:36:03.680 --> 00:36:11.310
Faculty (Olympus): Alright, so there are several places. You can do it in any number of ways, right? You could have also done this with lin space. You can say XA is lin space.

261
00:36:13.180 --> 00:36:21.700
Faculty (Olympus): 0â€¦ A little birdsâ€¦ With 101 points, okay? And then that will also work.

262
00:36:23.200 --> 00:36:24.040
Faculty (Olympus): Okay?

263
00:36:34.460 --> 00:36:35.370
Faculty (Olympus): Okay.

264
00:36:50.920 --> 00:36:53.739
Siddharth Digambar Kulkarni .: So, can you show the code again? I wasâ€¦ I wasâ€¦

265
00:36:56.890 --> 00:36:57.660
Siddharth Digambar Kulkarni .: Hello.

266
00:36:58.560 --> 00:36:59.300
Faculty (Olympus): Yes.

267
00:36:59.490 --> 00:37:00.890
Siddharth Digambar Kulkarni .: Can you show the code again?

268
00:37:13.720 --> 00:37:27.229
Faculty (Olympus): So, once again, everyone, you're not paying attention. All the data, the notebooks are available inside this folder, okay? It'sâ€¦ the slides are in slides, the data is in the data folder. Please go to the file browser and look at the files.

269
00:37:29.880 --> 00:37:36.090
Faculty (Olympus): I just keep seeing questions. Where do I download data.txt? It's in the data folder, and this should just run live.

270
00:37:40.890 --> 00:37:43.679
Faculty (Olympus): And this file was actually made available last week.

271
00:37:44.590 --> 00:37:46.990
Faculty (Olympus): Okay, is everyone done with this?

272
00:37:49.090 --> 00:38:01.979
Faculty (Olympus): Do you understand what's happening here? So basically, all we've done is we've created a set of values. You can use a for loop, but a for loop is going to be, you know, you have to write a bunch of code, there's just a couple of lines, and you're done. The rest is just plotting code, okay?

273
00:38:02.120 --> 00:38:03.779
Faculty (Olympus): Alright, so let's move on.

274
00:38:04.900 --> 00:38:11.880
Faculty (Olympus): Let's look at different kinds of plots. So, we already saw this in the last class. You can do what's called a scatter plot. A scatter plot basically puts

275
00:38:12.310 --> 00:38:22.929
Faculty (Olympus): takes each pair of points here, so it takes X and, let's say you have an array X and an array AY. It takes the X coordinate of the first point, Y coordinate of the second point, and plots that as a dot on the screen here.

276
00:38:23.030 --> 00:38:29.399
Faculty (Olympus): Okay, so that's what you have here. So the points, basically, areâ€¦ they form a scatter, yeah?

277
00:38:30.650 --> 00:38:44.189
Faculty (Olympus): Now, here I'm showing you the same data, but visualized slightly differently. So, very often, you may have a scatter plot, and you want to indicate some other quantity along with this, with that dot. So, for example.

278
00:38:44.760 --> 00:38:49.770
Faculty (Olympus): Let's say you have, A collection of points.

279
00:38:50.320 --> 00:38:56.089
Faculty (Olympus): You have a room at which you're measuring temperature, okay? So at each of these locations, you have a temperature variable.

280
00:38:56.220 --> 00:39:11.890
Faculty (Olympus): But you have an X and Y coordinate, so you basically have, you know, maybe on your floor you have some tiles, and you look at tile number, that could be a coordinate, roughly, and you basically measure the temperature at that point, and you want to make a skeptical. So you have X coordinate, Y coordinate, and you also have this temperature, right?

281
00:39:11.980 --> 00:39:24.800
Faculty (Olympus): So here, what I've done is I've just constructed a silly scalar quantity, which is not the temperature, it's something we've manufactured, where I'm saying, you just take X minus the mean of X, square it, Y minus the mean of X, square that.

282
00:39:24.810 --> 00:39:35.099
Faculty (Olympus): So this is basically going to beâ€¦ if youâ€¦ if you think about it, this is kind of going to look like a circle. This is the equation of a circle, right? So minus mean, center of this to the center. It's going to be centered atâ€¦

283
00:39:35.150 --> 00:39:45.610
Faculty (Olympus): the mean of X and the mean of Y, and then you'll say size, so this is the scalar value, so what I'm doing is, in the scatter, giving it X, Y. I'm saying that the color

284
00:39:45.780 --> 00:39:46.950
Faculty (Olympus): You should useâ€¦

285
00:39:48.840 --> 00:39:57.259
Faculty (Olympus): S for the color, and you should use the scalar S for the size, okay? So now let's look at this plot. You notice that this is the mean somewhere here, okay?

286
00:39:57.380 --> 00:40:04.119
Faculty (Olympus): Of each X and Y axis, and as you move away from it, the size of these fellows become bigger, and the color is also changing.

287
00:40:04.660 --> 00:40:08.330
Faculty (Olympus): Now, one thing that we can do isâ€¦ I can do more triangle.

288
00:40:10.390 --> 00:40:12.060
Faculty (Olympus): We go above.

289
00:40:14.160 --> 00:40:17.860
Faculty (Olympus): So you can actually see what these colors correspond to by using the color bar.

290
00:40:18.040 --> 00:40:18.720
Faculty (Olympus): Yep.

291
00:40:18.880 --> 00:40:31.909
Faculty (Olympus): So what it tells you is that these values are, you know, less than 100, and these values are greater than 600, these values here, things are in between. So this is a nice way to sometimes illustrate data with different sizes, and not just show you a scatter.

292
00:40:32.730 --> 00:40:39.260
Faculty (Olympus): Okay, so this is just showing you that you can do these kind of things. And if you suppress C is equal to S, you won't get any colors.

293
00:40:39.760 --> 00:40:41.789
Faculty (Olympus): Yep. So, bless this.

294
00:40:42.390 --> 00:40:45.079
Faculty (Olympus): Right, you'll just see the sizing.

295
00:40:45.200 --> 00:40:49.010
Faculty (Olympus): But if you see C is equal to S, and say, suppress this.

296
00:40:49.730 --> 00:40:54.890
Faculty (Olympus): You'll only see colors without the size. Sometimes it's nice to go a bit of both.

297
00:40:57.090 --> 00:41:06.630
Faculty (Olympus): Okay, so S is equal to and C is equal to are keyword arguments in this case, which tell you, you know, which tell Matplotlib, color it and size it looks.

298
00:41:08.100 --> 00:41:11.519
Siddharth Digambar Kulkarni .: What does C equal to S mean? C, color equal to what?

299
00:41:11.930 --> 00:41:15.430
Faculty (Olympus): So use this scalar to color these points.

300
00:41:15.430 --> 00:41:16.130
Siddharth Digambar Kulkarni .: Oh, good.

301
00:41:16.130 --> 00:41:17.770
Faculty (Olympus): And the color mapping is from here.

302
00:41:21.160 --> 00:41:24.220
Abhineet Bansal: How did it decide the color? I mean, like, was it random?

303
00:41:24.790 --> 00:41:35.710
Faculty (Olympus): Sorry, yeah, so by default, it picks a color map, and this color map happens to be the standard default, but you can choose different color maps also. So if you did Shift-Tab, you can see there's a CMAP argument.

304
00:41:35.940 --> 00:41:39.540
Faculty (Olympus): Where you can say, you know, for example, I can say, Jet.

305
00:41:45.270 --> 00:41:49.000
Faculty (Olympus): Give me a different I'll just use the default.

306
00:41:49.530 --> 00:42:05.579
Faculty (Olympus): If you want to look at all the color maps, you can go look at the Matplotlib documentation, or you can do plt.colormaps and call that function. It'll tell you a bunch of color maps. But this is all besides the point. What I'm trying to say is you can do these sort of things, and you are encouraged to go and explore

307
00:42:05.740 --> 00:42:17.810
Faculty (Olympus): all of the different arguments you have here, and things like that, okay? So if you look at Shift-Tab on this, you can see all the documentation you can do. You can give it an alpha, so which means you can make it slightly translucent.

308
00:42:18.670 --> 00:42:37.799
Faculty (Olympus): Alpha is 0.7, so it will make it slightly translucent. So we have multiple dots stacking on each other, makes it easier to see them. So this isâ€¦ each dot is given an alpha. Alpha basically means how much opacity does it have? 1 is fully opaque, 0 is fully transferable, okay? So you want something in between those two.

309
00:42:39.220 --> 00:42:40.929
Faculty (Olympus): So it'll be even more transparent.

310
00:42:41.960 --> 00:42:43.409
Faculty (Olympus): I'm removing this.

311
00:42:45.920 --> 00:42:46.800
Faculty (Olympus): Alright.

312
00:42:47.190 --> 00:42:52.290
Faculty (Olympus): Any questions at this point? If you have questions, raise your hands. Otherwise, I'm going to just move on.

313
00:42:55.850 --> 00:42:56.660
Sanketh Chiplunkar .: Sir, what doesâ€¦

314
00:42:56.660 --> 00:42:57.190
Faculty (Olympus): Okay, Abhine.

315
00:42:58.250 --> 00:42:59.070
Faculty (Olympus): Sorry?

316
00:42:59.070 --> 00:43:02.020
Sanketh Chiplunkar .: Sir, what does the color bar value represent? Is it the value of S?

317
00:43:02.440 --> 00:43:02.890
Faculty (Olympus): Yes.

318
00:43:02.890 --> 00:43:03.720
Sanketh Chiplunkar .: Okay, okay.

319
00:43:04.230 --> 00:43:12.679
Faculty (Olympus): There is nothing else here it can represent. So basicallyâ€¦ so let me explain once again. So you pickâ€¦ so now I've given you 3 pieces of data, X, Y, and S.

320
00:43:12.800 --> 00:43:17.939
Faculty (Olympus): You can think of S as something that I've created, okay? It doesn't matter. It could have been just some random set of values.

321
00:43:18.360 --> 00:43:28.799
Faculty (Olympus): But what I'm trying to illustrate here is, scatter allows you to takeâ€¦ so for each of these, it'll take the XY location, put a dot, and now it gives you the option of coloring this dot.

322
00:43:29.020 --> 00:43:31.910
Faculty (Olympus): Or, representing the size, okay?

323
00:43:32.370 --> 00:43:39.719
Faculty (Olympus): And for both of these, it will use the range of your scalar values that you have, this third quantity, this S,

324
00:43:40.260 --> 00:43:50.889
Faculty (Olympus): Right? And when you're doing the colors, it'll map this, so in this, depending on the color map that you use, it'll map the minimum to this thing here, and the maximum to this thing here.

325
00:43:51.220 --> 00:43:56.550
Faculty (Olympus): Okay, and plot it for you. So it's visually clear, it's easy for you to understand and interpret these figures.

326
00:43:56.880 --> 00:44:01.109
Siddharth Digambar Kulkarni .: So, the points in the center of this, plot.

327
00:44:01.220 --> 00:44:08.359
Siddharth Digambar Kulkarni .: Are the ones which are closest to the mean, and the points farthest are away from the mean.

328
00:44:08.360 --> 00:44:09.160
Faculty (Olympus): Yes.

329
00:44:09.850 --> 00:44:23.010
Siddharth Digambar Kulkarni .: Right? So, the yellow and the green plot, now, dots are farthest away from the mean for both X and Y, and, the points which are closer are nearest.

330
00:44:23.010 --> 00:44:34.629
Faculty (Olympus): Right, right. So that's the show, yeah, that's an interpretation of whatever, you know, the data set that you have, because I have constructed, in this case the scalar like that. If I constructed it in some different way, it'll look very different. So, for example, if I said.

331
00:44:35.410 --> 00:44:37.650
Faculty (Olympus): S is equal to X plus Y.

332
00:44:39.710 --> 00:44:41.109
Faculty (Olympus): It looked very disruptive.

333
00:44:43.990 --> 00:44:47.890
Faculty (Olympus): to our X minusâ€¦ Then we start home.

334
00:44:48.660 --> 00:44:50.469
Faculty (Olympus): That gets something, okay?

335
00:44:50.750 --> 00:44:53.669
Faculty (Olympus): Or if I say it is X star star 2â€¦

336
00:44:56.880 --> 00:45:06.570
Faculty (Olympus): I'll get something, right? This may not have anything to do with the mean. So that happens to be the case, because I constructed S this way. You can play with this however you want.

337
00:45:06.770 --> 00:45:16.279
Faculty (Olympus): So this is just a toy example. You'll have more realistic examples later. I just wanted to illustrate that you can do these kind of things with scatterplots, a very powerful plotting technique.

338
00:45:17.030 --> 00:45:17.920
Faculty (Olympus): All right.

339
00:45:18.300 --> 00:45:27.560
Faculty (Olympus): Okay, now we get to, you know, a very important part of this notebook, especially, and that is to look at histograms.

340
00:45:27.950 --> 00:45:43.070
Faculty (Olympus): So histograms are an extremely useful plotting technique to get a sense of the distribution of the data. So remember that question that I asked you, if I take the weight of the students in this class, and I wanted to say the distribution of these weights, how would you do this?

341
00:45:43.070 --> 00:45:49.139
Faculty (Olympus): What you would do is, you'd say, okay, let me takeâ€¦ let's assume that the weights are between 25 and, say, 200 kgs.

342
00:45:49.740 --> 00:45:52.490
Faculty (Olympus): And I'll make 5 kgas.

343
00:45:54.090 --> 00:45:58.860
Faculty (Olympus): I'll count the number of students who fall between 25 to 5â€¦ 30,

344
00:45:59.090 --> 00:46:03.429
Faculty (Olympus): Number of students who fall between 30 to 35, so on and so forth.

345
00:46:04.280 --> 00:46:05.669
Faculty (Olympus): And then plot those.

346
00:46:06.030 --> 00:46:11.730
Faculty (Olympus): Using bars, that gives me a sense of the distribution of this data. So let's do this for our

347
00:46:11.950 --> 00:46:13.620
Faculty (Olympus): Y values.

348
00:46:13.880 --> 00:46:18.490
Faculty (Olympus): Right? So you can immediately see that it has some sort of a structure of the distribution.

349
00:46:18.910 --> 00:46:19.820
Faculty (Olympus): Okay?

350
00:46:20.120 --> 00:46:25.830
Faculty (Olympus): Noâ€¦ The bins, in this case, by default.

351
00:46:26.010 --> 00:46:43.639
Faculty (Olympus): are only 10 bins, and this is usually not appropriate, okay? So the default in MatlotLib, unfortunately, happens to be 10, okay? So, it is always better to call, whenever you make a histogram, is to pass this additional keyword argument called bins is equal to auto, okay?

352
00:46:44.170 --> 00:46:50.300
Faculty (Olympus): And what auto does is, it looks at the size of your data and chooses an appropriate value. Okay, so let's just run this.

353
00:46:50.450 --> 00:46:54.430
Faculty (Olympus): In this case, it's going to be very similar, okay? It doesn't matter.

354
00:46:54.540 --> 00:47:14.279
Faculty (Olympus): But you can also supply an explicit number if you happen to know better. If you say, no, no, no, no, I wanted only 5KG bins, that's fine, right? So you can basically do that. You can say, here's 20 bins, right? And you can see, right? And obviously, if you use 200 bins or some crazy number like that, you'll get a really horrible-looking clock.

355
00:47:14.370 --> 00:47:19.249
Faculty (Olympus): Right, so this is always usedâ€¦ so using bin size is a bit of an art.

356
00:47:19.760 --> 00:47:21.839
Faculty (Olympus): Right? But use something that is reasonable.

357
00:47:22.900 --> 00:47:23.760
Faculty (Olympus): Alright.

358
00:47:25.250 --> 00:47:28.630
Faculty (Olympus): Okay, so you've done histograms in your stats course, right?

359
00:47:31.150 --> 00:47:35.720
Faculty (Olympus): Have you done histograms? Not yet. Not yet? Not yet, but, okay.

360
00:47:35.720 --> 00:47:37.250
Soumen Deb .: Aware of histograms.

361
00:47:37.490 --> 00:47:42.230
Faculty (Olympus): Great. Fine. So, If you noticeâ€¦

362
00:47:42.230 --> 00:47:42.990
Soumen Deb .: Regardless.

363
00:47:42.990 --> 00:47:45.980
Faculty (Olympus): Wrightly put thisâ€¦ Suti?

364
00:47:46.200 --> 00:47:46.830
Faculty (Olympus): You have a question?

365
00:47:46.830 --> 00:47:52.800
Soumen Deb .: It's basically thisâ€¦ it's basically the same scatter plot, but in a different dimension, right?

366
00:47:52.800 --> 00:47:53.450
Faculty (Olympus): No.

367
00:47:53.810 --> 00:47:54.870
Faculty (Olympus): It is not.

368
00:47:55.230 --> 00:47:57.559
Faculty (Olympus): It is very different from a scatterplot.

369
00:48:02.270 --> 00:48:03.900
Siddharth Digambar Kulkarni .: In scatterplot, we are plotting.

370
00:48:03.900 --> 00:48:04.579
Faculty (Olympus): It is totallyâ€¦

371
00:48:05.070 --> 00:48:06.400
Siddharth Digambar Kulkarni .: And why? Here we areâ€¦

372
00:48:07.580 --> 00:48:26.779
Faculty (Olympus): The scatter plot, you plot, yes, you take for each fellow your actual coordinates of those fellows and plot them on a two-dimensional graph, and then you basically put, you know, you can color those and size those. That's what you're doing in a scatter plot. A histogram is not doing that. A histogram is basically saying there are 10 dBas, I make 10 equal-sized bins between the minimum and the maximum value.

373
00:48:26.780 --> 00:48:30.460
Faculty (Olympus): And then I count the number of occurrences of the population in that bit.

374
00:48:31.030 --> 00:48:38.630
Soumen Deb .: Yeah, so my point was, yeah, so my point was, histogram is more one-dimensional, and scatterplot is two-dimensional.

375
00:48:38.630 --> 00:48:48.830
Faculty (Olympus): Yes, but they're fundamentally vastly different quantities. They are not the same. What you're plotting on each dot there in a scatterplot is not the same as a histogram. Absolutely not the same.

376
00:48:49.420 --> 00:48:52.020
Siddharth Digambar Kulkarni .: So here we get a distribution, here we get a.

377
00:48:52.020 --> 00:49:08.310
Faculty (Olympus): Yes. Here, you get a sense of, for example, here, immediately, when I look at X, I can immediately see that the values are between, you know, say 35 or something like that, to 90, right? And on this fellow, I can see that it's between 1.2 and 2.2. So at a glance, I tell you, and also, it tells you, there are more fellows in the middle here, right?

378
00:49:08.310 --> 00:49:17.849
Faculty (Olympus): There are alsoâ€¦ there are more follows in the middle, and suddenly this thing drops off. And this is gonnaâ€¦ I'm gonna start using some real data sets, and then we'llâ€¦ you'll actually see the value of this, okay? So.

379
00:49:18.180 --> 00:49:20.220
Faculty (Olympus): Something you should use, yeah, yeah.

380
00:49:20.220 --> 00:49:24.040
Ankit Mahajan .: Sir, sir, histogram is like relative frequencies of each,

381
00:49:24.040 --> 00:49:28.349
Faculty (Olympus): No, no, so we have not yet done the little, I'll come to theâ€¦ let me explain. Good question.

382
00:49:28.350 --> 00:49:28.910
Atul Ashok Kumar Gupta .: Absolutely.

383
00:49:28.910 --> 00:49:32.489
Faculty (Olympus): Can you please mute yourselves? Because it's cross-talk.

384
00:49:32.710 --> 00:49:40.740
Faculty (Olympus): If you have a question, please raise your hands. I'm watching. I have a participant thingy here, so I can see if you're raising your hands, and I would stop, okay?

385
00:49:41.090 --> 00:49:42.040
Faculty (Olympus): Sai?

386
00:49:45.500 --> 00:49:46.430
Faculty (Olympus): Ashish?

387
00:49:50.930 --> 00:49:52.390
Faculty (Olympus): You're muted, I can't hear you.

388
00:49:52.390 --> 00:49:58.569
Akondi Vyasa Sai Ashish Kumar .: Yeah, sorry, I was on mute. So here, does it convert into percentiles when we do bins or two?

389
00:49:58.910 --> 00:50:03.259
Akondi Vyasa Sai Ashish Kumar .: Because the x-axis changed the values.

390
00:50:03.750 --> 00:50:06.610
Akondi Vyasa Sai Ashish Kumar .: From the, initialâ€¦

391
00:50:07.160 --> 00:50:07.880
Faculty (Olympus): I didn't.

392
00:50:08.380 --> 00:50:13.590
Akondi Vyasa Sai Ashish Kumar .: No, when we plot histogram Y, in the x-axis, we see theâ€¦

393
00:50:13.990 --> 00:50:21.159
Akondi Vyasa Sai Ashish Kumar .: Values are maximum and minimum, but now when we do bench auto, then we see the x-axis change, right?

394
00:50:21.650 --> 00:50:24.769
Faculty (Olympus): Yeah, because it's picked the bins slightly differently, that's all.

395
00:50:25.060 --> 00:50:25.790
Akondi Vyasa Sai Ashish Kumar .: Okay, okay.

396
00:50:26.400 --> 00:50:42.979
Faculty (Olympus): It's still the same thing. It's still making the bins, okay? Still making bins, and then counting the number of occurrences in those bins. And please note, these are absolute counts, so these are actual count values. It's not relative, okay? So when you just do a PLT.hist, it's just doing counts in each of these bins.

397
00:50:44.030 --> 00:50:44.900
Faculty (Olympus): Okay?

398
00:50:45.610 --> 00:50:46.580
Faculty (Olympus): Sunil?

399
00:50:47.530 --> 00:51:02.159
Sunil Rawat .: Yes, Professor, good morning. So, scattered graph and histogram, which graph can be used to identify the outliers? Is it the histogram which we choose to find out, outliers in the distribution?

400
00:51:02.570 --> 00:51:05.559
Faculty (Olympus): Wait for your stats course.

401
00:51:06.810 --> 00:51:08.300
Sunil Rawat .: Yeah, because,

402
00:51:08.300 --> 00:51:16.439
Faculty (Olympus): It's not the scatter plot, no. You can get a sense of the scatterâ€¦ you can get it maybe with a scatterplot, but again, so if I have one-dimensional data.

403
00:51:17.510 --> 00:51:19.420
Faculty (Olympus): What kind of a scatterplot are you gonna get?

404
00:51:21.320 --> 00:51:24.109
Faculty (Olympus): Pratapot is useful when you have two quantities, typically.

405
00:51:24.110 --> 00:51:24.910
Sunil Rawat .: Okay.

406
00:51:24.910 --> 00:51:31.279
Faculty (Olympus): Especially the ones that we are plotting. They're typically meant forâ€¦ so if you're looking at correlations and things like that, scatterplots are useful.

407
00:51:31.280 --> 00:51:35.910
Sunil Rawat .: Okay, so when to choose a scattered floor, if there are two, two values, at least?

408
00:51:35.910 --> 00:51:39.199
Faculty (Olympus): Yeah, because you implicitly require an X and a Y coordinate, right?

409
00:51:39.200 --> 00:51:40.020
Sunil Rawat .: Okay.

410
00:51:40.020 --> 00:51:56.629
Faculty (Olympus): So, usually scatter plots, so it's a good question, you're glad you asked it. So, basically, yes, you can use it when you want to say correlation. How are these two pillows, you know, codependent? Are they all falling on a line? Do they fall all over the place? So you get a sense of how these two quantities are related to each other by looking at a scatterplot.

411
00:51:56.630 --> 00:51:57.630
Sunil Rawat .: Okay.

412
00:51:57.630 --> 00:52:03.640
Faculty (Olympus): And so, obviously, this doesn't scale for, you know, I have 300 quantities, and then you have to start doing pairwise catapults.

413
00:52:04.290 --> 00:52:05.720
Sunil Rawat .: Sure, thanks.

414
00:52:05.730 --> 00:52:10.080
Faculty (Olympus): Yeah, whereas histograms are telling you just the distribution of that particular quantity.

415
00:52:12.090 --> 00:52:14.489
Faculty (Olympus): Oleg? Sunil?

416
00:52:14.780 --> 00:52:15.889
Faculty (Olympus): Oh, was that you, Sonu?

417
00:52:15.890 --> 00:52:16.590
Sunil Rawat .: Yeah.

418
00:52:16.590 --> 00:52:17.399
Faculty (Olympus): Okay, okay.

419
00:52:19.450 --> 00:52:31.289
Faculty (Olympus): Anybody else? Questions? Okay, looks like I've answered everything. So, the other thing to keep in mind is, do not just use the default for hist. Always use either bins as auto, or you control the bins if you know better, okay?

420
00:52:31.540 --> 00:52:34.479
Faculty (Olympus): And again, read the documentation if you want to learn.

421
00:52:34.680 --> 00:52:49.939
Faculty (Olympus): Now, before we move on, I want you to understand something. When you do plt.hist, if I do not put this semicolon, it will return a bunch of stuff, okay? Which is why I actually put this semicolon, because this is annoying, because I want to see the histogram, and I don't want to see all of this stuff, okay?

422
00:52:51.360 --> 00:53:07.409
Faculty (Olympus): Alright? So, what is it returning? So, let's look at this. So, when I do this, it actually returns 3 things. It returns the counts, it returns the bins, and it returns something called patches. And patches is a matplotlib-specific thing, okay?

423
00:53:08.940 --> 00:53:13.039
Faculty (Olympus): So let me, we can settle hereâ€¦

424
00:53:14.500 --> 00:53:18.029
Faculty (Olympus): I'll explain to you what this is. So let's now look at the counts.

425
00:53:18.160 --> 00:53:20.189
Faculty (Olympus): So if I say landmuff counts.

426
00:53:21.700 --> 00:53:29.379
Faculty (Olympus): 9 counts, okay? Len of bins is going to be 10. So now let's look at these and say, counts.

427
00:53:29.780 --> 00:53:38.269
Faculty (Olympus): So this will be 3, 5, 12, 17, blah blah blah. So you can see this is 3, 5, 12, 17, blah blah blah. Okay, so these are the actual values of the counts.

428
00:53:38.410 --> 00:53:40.030
Faculty (Olympus): But if you look at the bins.

429
00:53:40.040 --> 00:53:51.010
Faculty (Olympus): It will be an array with 38.62, so the start of this bin is 38, the next fellow is at 44, then 50, 55, dot dot dot, all the way to 90.27.

430
00:53:51.010 --> 00:54:01.139
Faculty (Olympus): Okay? So this is actually very useful information, because it tells you where the bins are, and it tells you the number of fellows in each of those bins. Okay, so it's useful for you in case you want to do some furtherâ€¦

431
00:54:01.140 --> 00:54:04.490
Atul Ashok Kumar Gupta .: The bins automatically, on its own.

432
00:54:05.080 --> 00:54:07.019
Faculty (Olympus): Yes, because I said Benz's Auto.

433
00:54:07.180 --> 00:54:08.030
Atul Ashok Kumar Gupta .: Oh, no.

434
00:54:08.030 --> 00:54:16.879
Faculty (Olympus): Right? But, supposing you sayâ€¦ hang on, hang on, hang on, let me finish. Supposing you say, no, no, no, I don't want 38, and I want this, I want to create my own VINs.

435
00:54:17.040 --> 00:54:24.919
Faculty (Olympus): You will always do well to use equal-sized bins, otherwise you're fooling your readers, okay? So make sure the bins are equal size, but you can set manually these bins.

436
00:54:25.190 --> 00:54:34.409
Faculty (Olympus): Right? So you can actually say np.histogram, or what, sorry, np.prt.hist, and actually say, so if you look at the doc string for this, and look at bins.

437
00:54:35.660 --> 00:54:48.969
Faculty (Olympus): bins is int, sequence of float, STR, or none, okay? So you can actually give it a sequence of floating point values, and those will be the actual bins, which is the boundaries of the bins, which means start, next, next, next, next, next, all the way to the last one.

438
00:54:49.680 --> 00:54:52.260
Faculty (Olympus): Alright, so that's what this bins quantity is.

439
00:54:53.660 --> 00:54:55.319
Faculty (Olympus): Okay, Siddharth, quickly?

440
00:54:55.320 --> 00:54:59.280
Siddharth Digambar Kulkarni .: So, it looks like these beans are equally spaced here.

441
00:54:59.280 --> 00:54:59.990
Faculty (Olympus): They are.

442
00:54:59.990 --> 00:55:02.859
Siddharth Digambar Kulkarni .: In this case. But, will it always be the case?

443
00:55:03.550 --> 00:55:09.239
Faculty (Olympus): Yes, again, go back to your stat scores, it's a bad idea to have unequal sized bins.

444
00:55:09.240 --> 00:55:10.270
Siddharth Digambar Kulkarni .: Yes, yes.

445
00:55:10.760 --> 00:55:19.500
Faculty (Olympus): Because then it's not clear, right? You're counting a little more for these fellows, counting a little more for those fellows. So you're not used to seeing it that way, so typically you use equal-sized bits.

446
00:55:21.890 --> 00:55:29.099
Faculty (Olympus): Okay? Alright, so now, if you do not want the plot, but all you want is the bins and the counts.

447
00:55:29.620 --> 00:55:46.289
Faculty (Olympus): It turns out that mat.lib itself is delegating this functionality to NumPy itself. So NumPy itself has a function called np.histogram, which does this, and it has the same arguments, okay? So if you do bins is auto, in fact, matplotlib is just calling to NumPy, and it's passing this bins argument also to NumPy.

448
00:55:46.340 --> 00:55:53.979
Faculty (Olympus): So, in this case, you will just get count sentence. You will not get this patches business at the end, okay? Patches are, essentially.

449
00:55:54.260 --> 00:55:55.889
Faculty (Olympus): Might not limb things.

450
00:55:59.100 --> 00:56:02.780
Faculty (Olympus): some bar container or something, right? So this is not of importance.

451
00:56:04.910 --> 00:56:06.850
Faculty (Olympus): Bansal.

452
00:56:08.670 --> 00:56:10.560
Faculty (Olympus): I'll leave it at what VIN's was.

453
00:56:10.730 --> 00:56:12.320
Faculty (Olympus): And thoughts.

454
00:56:13.010 --> 00:56:18.719
Faculty (Olympus): Okay, so basically, every time you call hist, it's gonna return this, I'm just suppressing it over here.

455
00:56:19.450 --> 00:56:30.959
Faculty (Olympus): Okay, and if you want to useâ€¦ you don't want the plots, you just want the counts and the bins, we'll come to why this is useful very shortly. You can simply do C comma b, or counts comma bins is equal to np.histogram with the data.

456
00:56:31.640 --> 00:56:39.050
Faculty (Olympus): Okay, and now we can quickly verify whether this is the same, right? So, did I do the same thing up here? Yes, and the same thing, soâ€¦

457
00:56:41.340 --> 00:56:42.799
Faculty (Olympus): No, I didn't run this.

458
00:56:43.020 --> 00:56:48.129
Faculty (Olympus): Okay? So notice that they're exactly the same, they're all close to each other, same numbers and all that.

459
00:56:48.470 --> 00:56:51.230
Faculty (Olympus): All right, lots of questions here, Siddharth.

460
00:56:52.680 --> 00:56:55.369
Siddharth Digambar Kulkarni .: Allâ€¦ all clothes, what does it do, sir?

461
00:56:55.900 --> 00:56:57.300
Faculty (Olympus): Look at the doc string, please.

462
00:57:01.100 --> 00:57:05.850
Faculty (Olympus): In all these cases, again, There's only one instructor, but there areâ€¦

463
00:57:06.490 --> 00:57:11.089
Faculty (Olympus): 192 interpreters, I would hope, right? So you should ask your interpreter also.

464
00:57:12.530 --> 00:57:13.640
Faculty (Olympus): Soumen?

465
00:57:15.840 --> 00:57:21.100
Soumen Deb .: Yeah, so I don't know whether I missed it. What does patches stand for in,

466
00:57:21.100 --> 00:57:36.239
Faculty (Olympus): Okay, so patches isâ€¦ it's a matplotlib internal thing, that is, they areâ€¦ they are the things that areâ€¦ the objects that you can control. So you won't say change the color or something like that, you can probably manipulate it. So it is irrelevant as far as you are concerned, because I'm only going to focus on the counts and the bits. That's just some plotting data.

467
00:57:37.740 --> 00:57:38.969
Faculty (Olympus): Sure. Manu?

468
00:57:40.340 --> 00:57:41.460
Manu Gupta .: the mindset.

469
00:57:41.460 --> 00:57:41.880
Faculty (Olympus): Good morning.

470
00:57:42.130 --> 00:57:46.919
Manu Gupta .: So, here, the np.hist program is doing the same thing as pint.hist.

471
00:57:47.100 --> 00:57:52.470
Faculty (Olympus): Yes, pretty much. I mean, internally, it's doing the same counting. In fact, PLT.hist uses np.histor.

472
00:57:52.940 --> 00:57:55.579
Manu Gupta .: But it is not generating the graph.

473
00:57:56.540 --> 00:57:57.190
Faculty (Olympus): Yes.

474
00:57:57.590 --> 00:57:59.100
Faculty (Olympus): That's exactly what I said.

475
00:57:59.930 --> 00:58:05.480
Faculty (Olympus): That's exactly what I said. If you do not want the plot, and you just want to get the counts and the bins, you use NP.S.

476
00:58:05.720 --> 00:58:09.499
Faculty (Olympus): PLT.hist does exactly the same thing, it just makes the plot in addition to you.

477
00:58:10.080 --> 00:58:12.410
Faculty (Olympus): And most often, you're only interested in the plot.

478
00:58:12.610 --> 00:58:16.649
Faculty (Olympus): Sometimes, maybe in this course you'll be interested in C and D.

479
00:58:17.200 --> 00:58:18.130
Faculty (Olympus): Okay?

480
00:58:18.750 --> 00:58:30.720
Faculty (Olympus): All right, I quickly just, you know, I didn't mean to be rude, you know, but, you know, many of these questions you can answer by yourself because you have a live interpreter. All close basically asserts that two of these arrays have

481
00:58:30.840 --> 00:58:33.990
Faculty (Olympus): All of their values individually are very close to each other.

482
00:58:34.620 --> 00:58:35.670
Faculty (Olympus): Soâ€¦

483
00:58:35.700 --> 00:58:52.709
Faculty (Olympus): Basically, you can think of it as it takes the difference between these two, and ensures that each of them is close. And these are all close in terms of floating point numbers, so you have what's called an absolute tolerance and a relative tolerance. So it basically will check that the two are within some 10 to the minus 8 of each other, or something like that. In fact, you can look at these numbers.

484
00:58:52.710 --> 00:58:56.570
Faculty (Olympus): So, relative tolerance here isâ€¦ okay, let me do it here so I can see this.

485
00:58:56.570 --> 00:59:00.110
Faculty (Olympus): Yeah, it's 10 to the minus 5, and absolute tolerance is 10 to the minus 8.

486
00:59:00.580 --> 00:59:02.609
Faculty (Olympus): Okay, so it will do this for you.

487
00:59:02.900 --> 00:59:09.780
Faculty (Olympus): And it'll return a single boolean, okay? It's not an array or anything. So, given two arrays, np.allclose will tell you whether they're close.

488
00:59:10.220 --> 00:59:20.359
Faculty (Olympus): All right, so if you've understood so far, now is when we start, you know, connecting this to statistics. You have not yet seen this in statistics, so, you know, you're gonna have to be a bit patient.

489
00:59:20.580 --> 00:59:24.450
Faculty (Olympus): Vinayak, very quickly, if you have a question, I'll answer your question.

490
00:59:24.450 --> 00:59:35.450
vinay kaisar: Sir, here we are covering, comparing two, values, all close, and P, which is C, and B. Similarly, can we compare, 3 or 4 most?

491
00:59:36.860 --> 00:59:40.419
Faculty (Olympus): No, so you have twoâ€¦ it takes two arguments, right? Look at, again, the doc string.

492
00:59:40.600 --> 00:59:47.499
Faculty (Olympus): np.allclose takes two arguments, A and B, and the rest are keyword arguments. So any two arrays you want to compare, it's going to compare for you.

493
00:59:48.310 --> 00:59:52.910
vinay kaisar: So, is there anything else that we can use to compare more than two?

494
00:59:54.030 --> 01:00:00.730
Faculty (Olympus): Yes, you canâ€¦ you can compare one with the other, and the other with the other, right? You can do two calls, right? Transitivity.

495
01:00:01.310 --> 01:00:02.070
vinay kaisar: Nope.

496
01:00:02.370 --> 01:00:02.910
Faculty (Olympus): Yup.

497
01:00:03.890 --> 01:00:04.760
Faculty (Olympus): Alright.

498
01:00:05.140 --> 01:00:16.130
Faculty (Olympus): So now we jump into a little more stats, okay? And now I know I'm getting ahead of your stats course, but I think you can intuitively understand, okay, what's lying.

499
01:00:16.960 --> 01:00:18.010
Faculty (Olympus): Soâ€¦

500
01:00:18.280 --> 01:00:28.769
Faculty (Olympus): the key insight that I want you to understand is when you do a histogram, when you make a histogram, especially when you make what's called a relative histogram, or you say density plot.

501
01:00:29.260 --> 01:00:41.919
Faculty (Olympus): you end up getting what's called a probabilityâ€¦ an approximate probability density function, okay? So I will elaborate this in greater detail, but let's first look at the syntax on how to create what are called relative histograms.

502
01:00:42.270 --> 01:00:47.040
Faculty (Olympus): And the notation used in both NumPy

503
01:00:47.570 --> 01:01:00.279
Faculty (Olympus): and myplotlib is to use the keyword argument density, which means something very precise. I will explain to you exactly what this means in a short pipe. So what, the idea is, if I pass density is equal to true, okay.

504
01:01:01.170 --> 01:01:09.890
Faculty (Olympus): Okay, it will convert this into a relative, and also divide by the bin width, which means

505
01:01:10.530 --> 01:01:19.840
Faculty (Olympus): You'll understand this perhaps a little better when you do probability density functions, okay? Soâ€¦ Uff.

506
01:01:21.780 --> 01:01:23.600
Faculty (Olympus): Should have done this earlier.

507
01:01:33.160 --> 01:01:40.390
Faculty (Olympus): Okay, I completely forgot. So, if you give me a second, I will join this from myâ€¦

508
01:01:40.780 --> 01:01:54.869
Faculty (Olympus): iPad, so I can actually show you this, you know, and work out some theory. So maybe what I will do is, I willâ€¦ I will walk you through this syntax. We'll come back to the probability aspects when I, you know, take some questions, and then connect my iPad as well.

509
01:01:55.160 --> 01:02:02.420
Faculty (Olympus): Okay, soâ€¦ For now, all I want you to understand is when you say density is equal to true.

510
01:02:02.560 --> 01:02:06.679
Faculty (Olympus): You essentially get what's called an empirical probability density function.

511
01:02:07.160 --> 01:02:10.200
Faculty (Olympus): by using a histogram, okay?

512
01:02:12.240 --> 01:02:20.300
Faculty (Olympus): The next thing that you can do is what's called a cumulative histogram, okay? A cumulative histogram does

513
01:02:20.870 --> 01:02:27.660
Faculty (Olympus): instead of giving me the counts of each bin, it will cumulatively add these counts, okay?

514
01:02:41.880 --> 01:02:48.760
Faculty (Olympus): Right? So if I say PLTH hist, why bins is auto, and here I say cumulative is true. Now, notice what happens.

515
01:02:49.360 --> 01:03:04.920
Faculty (Olympus): Please note that even if I didn't have density is true, this will work, so I can say relative is true. This will give me the count, so I have 100 values, right? So this is going to give me counts in the first VIN, plus counts in the second bin, plus, plus, plus, plus, plus, plus all the other way.

516
01:03:05.070 --> 01:03:10.699
Faculty (Olympus): All the way to the end, okay? But this is not a density plot, this is the actual counts. The density plot

517
01:03:10.810 --> 01:03:17.069
Faculty (Olympus): Is made by, essentially, Dividing by the total number, okay?

518
01:03:17.410 --> 01:03:18.950
Faculty (Olympus): And also the VIN width.

519
01:03:20.810 --> 01:03:23.239
Faculty (Olympus): Yeah, so especially when you're looking at a density plot.

520
01:03:24.120 --> 01:03:27.000
Faculty (Olympus): Now, this plot here is equivalent

521
01:03:27.380 --> 01:03:31.239
Faculty (Olympus): Approximately, what's called a probability density function.

522
01:03:31.370 --> 01:03:37.510
Faculty (Olympus): And this is equivalent to what's called a cumulative density function, or cumulative distribution function.

523
01:03:40.260 --> 01:03:42.430
Faculty (Olympus): Okay,

524
01:03:43.360 --> 01:03:48.170
Faculty (Olympus): Do you have questions? Shall we come back to this a bit later, after I do box plots?

525
01:03:50.550 --> 01:03:52.290
Faculty (Olympus): Okay, lots of questions.

526
01:03:53.420 --> 01:03:58.799
Faculty (Olympus): Okay, so is this question about probability density function? Can first, Gaurav?

527
01:04:00.250 --> 01:04:05.159
Gaurav Singh .: Yes, Professor. So, yeah, this is a question regarding PDF. Soâ€¦

528
01:04:05.160 --> 01:04:09.460
Faculty (Olympus): Okay, so in that case, will you please give me a second,

529
01:04:09.820 --> 01:04:11.590
Faculty (Olympus): I will need to do something.

530
01:04:19.800 --> 01:04:24.410
Faculty (Olympus): So, because it's easier for me, I completely forgot that I had to do this today.

531
01:05:02.730 --> 01:05:04.360
Faculty (Olympus): Just a secondâ€¦

532
01:05:31.480 --> 01:05:32.340
varun kumar .: strategy.

533
01:05:32.340 --> 01:05:34.250
Faculty (Olympus): Excellent.

534
01:05:34.250 --> 01:05:38.409
varun kumar .: Department for Environment, Food, and Research.

535
01:05:38.510 --> 01:05:41.370
varun kumar .: My question is regarding policymaking.

536
01:05:41.530 --> 01:05:45.309
varun kumar .: And reduction inâ€¦ climate change.

537
01:05:45.840 --> 01:05:51.680
varun kumar .: So, the policies and Vinayak willâ€¦ Awareness Global Kumar Behera.

538
01:05:51.680 --> 01:05:54.850
Faculty (Olympus): Are you all getting someâ€¦ Noisel and, likeâ€¦

539
01:05:54.850 --> 01:05:55.350
Jasmine Samant: Yes, soâ€¦

540
01:05:55.350 --> 01:05:56.480
Abhishek .: Yes.

541
01:05:56.480 --> 01:05:58.400
Faculty (Olympus): Summon, is this me?

542
01:05:58.400 --> 01:06:01.370
Bipin Karyakarte .: Somebody's sitting on another call and forgot.

543
01:06:01.370 --> 01:06:02.060
Advait Ketkar: driven.

544
01:06:02.060 --> 01:06:03.909
Faculty (Olympus): Yeah, okay, please mute yourselves.

545
01:06:03.910 --> 01:06:06.150
Amit Srivastava .: Ron, can you be on mute?

546
01:06:06.830 --> 01:06:10.839
Faculty (Olympus): So, let meâ€¦ okay. Are you able to see myâ€¦

547
01:06:12.390 --> 01:06:14.820
Faculty (Olympus): Limitations, okay, let me go back to this.

548
01:06:17.130 --> 01:06:19.009
Faculty (Olympus): The problem is I need to mute.

549
01:06:20.620 --> 01:06:21.540
Faculty (Olympus): Okay.

550
01:06:28.850 --> 01:06:29.610
Faculty (Olympus): No one.

551
01:06:31.640 --> 01:06:35.320
Faculty (Olympus): Sorry about this, just a second. Disconnect audio.

552
01:06:38.260 --> 01:06:39.100
Faculty (Olympus): Okay.

553
01:07:19.530 --> 01:07:21.070
Faculty (Olympus): Yes, whoops.

554
01:07:21.360 --> 01:07:22.140
Faculty (Olympus): Soâ€¦

555
01:07:30.970 --> 01:07:32.729
Faculty (Olympus): Okay, fine.

556
01:07:33.120 --> 01:07:34.919
Faculty (Olympus): Oh, I meant to say hello, not him.

557
01:07:35.500 --> 01:07:42.380
Faculty (Olympus): All right, okay, so I can now illustrate stuff and answer questions. Okay, that's good.

558
01:07:42.620 --> 01:07:43.570
Faculty (Olympus): Second.

559
01:07:57.010 --> 01:08:04.150
Faculty (Olympus): Okay, fine. So, the thing is this. So, if you look at this plot here, I'm gonna maybe use this as a little plot here.

560
01:08:04.260 --> 01:08:11.740
Faculty (Olympus): So, what we have for a probability density function is, basically it's used in the context of,

561
01:08:12.120 --> 01:08:15.350
Faculty (Olympus): Quantities that are continuously varying, okay?

562
01:08:15.710 --> 01:08:18.130
Faculty (Olympus): And what you're saying is that

563
01:08:18.430 --> 01:08:25.249
Faculty (Olympus): This thing here, you know, this area that you see here, this area that you see here, right, the area under this curve.

564
01:08:25.490 --> 01:08:29.369
Faculty (Olympus): Okay? Corresponds to the probability, so areaâ€¦

565
01:08:35.080 --> 01:08:38.020
Faculty (Olympus): is approximatelyâ€¦ Probably.

566
01:08:44.620 --> 01:08:45.930
Faculty (Olympus): Aditya T.

567
01:08:46.420 --> 01:08:48.569
Faculty (Olympus): Okay? So,

568
01:08:50.450 --> 01:08:58.690
Faculty (Olympus): And therefore, the integral of all of these, right, so the integral of this, you know, say, so probability density function.

569
01:08:59.130 --> 01:09:04.250
Faculty (Olympus): Yeah, it should be 1. And in our case, the summation of all the bins.

570
01:09:07.210 --> 01:09:08.720
Faculty (Olympus): Boom. Yeah.

571
01:09:10.290 --> 01:09:13.019
Faculty (Olympus): And each of these, you can think of this as area I.

572
01:09:16.680 --> 01:09:23.080
Faculty (Olympus): Okay, so the areas are allâ€¦ Probabilities.

573
01:09:23.490 --> 01:09:25.530
Faculty (Olympus): So how does this become a probability?

574
01:09:25.689 --> 01:09:35.199
Faculty (Olympus): So you can think of it as, right, so remember that the integral is over a particular domain. So what you're saying is I have a bin. So in this bin, I'm basically saying the number of counts that I found.

575
01:09:35.560 --> 01:09:40.149
Faculty (Olympus): Okay, so this is a sort of approximate way to look at

576
01:09:40.640 --> 01:09:44.199
Faculty (Olympus): Your variation of the quantity that you're studying.

577
01:09:44.580 --> 01:09:46.699
Faculty (Olympus): Right, so in yourâ€¦ if you takeâ€¦

578
01:09:46.819 --> 01:09:55.970
Faculty (Olympus): like, the weight of this class, right? Unfortunately, this cannot be weight here, so maybe I should use X instead of Y. So.

579
01:09:57.150 --> 01:10:11.959
Faculty (Olympus): let's assume this is the weights of this class, and I say density is true. What it basically tells me is the weight, if I were to interpret this as a weight, you know, this quantity between, say, 70 and 80, so this vin here, you see here.

580
01:10:12.220 --> 01:10:13.110
Faculty (Olympus): Good?

581
01:10:13.460 --> 01:10:14.610
Faculty (Olympus): There areâ€¦

582
01:10:18.980 --> 01:10:28.160
Faculty (Olympus): So if I were to takeâ€¦ so notice that the bin width here is quite big, right? It's likeâ€¦ so if I look at this width here, what is the width of this? It's approximatelyâ€¦

583
01:10:28.660 --> 01:10:34.469
Faculty (Olympus): looks like 5, right? So it's like there's a 5KG dabba size, a bin, right?

584
01:10:34.680 --> 01:10:38.149
Faculty (Olympus): So, if I now were to say, inside this bin.

585
01:10:38.610 --> 01:10:53.310
Faculty (Olympus): there are some n number of people. If I were to divide this by the total number of people and the bin width, then if I add up all of these areas, right, I will end up with a quantity that is equal to 1.

586
01:10:54.180 --> 01:10:56.710
Faculty (Olympus): Okay, so the idea is,

587
01:10:57.720 --> 01:11:00.609
Faculty (Olympus): The height of this column, or the area of this

588
01:11:02.480 --> 01:11:05.600
Faculty (Olympus): The area of this should be equal toâ€¦

589
01:11:06.570 --> 01:11:11.490
Faculty (Olympus): Right? The area of that column should be equal toâ€¦ What?

590
01:11:12.910 --> 01:11:22.769
Faculty (Olympus): It should be equal to the probability of finding a person whose weight is between, say, what, 73 and whatever, 77, or whatever it is here. Does this make sense?

591
01:11:23.100 --> 01:11:23.430
Siddharth Digambar Kulkarni .: Absolutely.

592
01:11:24.310 --> 01:11:48.950
Faculty (Olympus): Okay? So you can think of this as, so let's say you are measuring weights, or temperatures, or whatever. You're essentially binning them into some intervals, and let's say you have a million values. Then the bin can be much smaller. Maybe you'll have, you know, 1KG weights. Let's say a million students, or you have a million large population, and you have 1KG weights, then you will have a lot of people in that one kilo, right? So then the numbers will be a little more reasonable. So this is where, you know, it becomes an approximate

593
01:11:48.950 --> 01:11:49.670
Faculty (Olympus): submission.

594
01:11:49.670 --> 01:11:51.849
Faculty (Olympus): Because it depends on the nature of your sample.

595
01:11:51.930 --> 01:12:07.030
Faculty (Olympus): Okay, which means if you have a large sample, then you can have smaller bins. If you have very few samples, you have to have larger and larger bips, right? But this relative measure of how many people are in that bin, divided by the bin width, tells you, you know, the probability of finding

596
01:12:07.330 --> 01:12:09.569
Faculty (Olympus): A person having such a way.

597
01:12:09.790 --> 01:12:21.040
Faculty (Olympus): Okay? So this is why this is an intimate connection between histograms and probability density functions. And a cumulative distribution function is nothing but, right? So it's going to be,

598
01:12:21.420 --> 01:12:27.850
Faculty (Olympus): So let me scroll down. Maybeâ€¦ shall I erase this on myâ€¦ Drawings here.

599
01:12:29.050 --> 01:12:30.110
Kapil Shailesh Inamdar .: Yes, please.

600
01:12:30.460 --> 01:12:30.980
Jasmine Samant: Yes, sir.

601
01:12:30.980 --> 01:12:32.629
Faculty (Olympus): Running out of charge, you know.

602
01:12:33.090 --> 01:12:34.160
Faculty (Olympus): And settled?

603
01:12:35.060 --> 01:12:36.310
Faculty (Olympus): Just a second.

604
01:12:36.810 --> 01:12:39.490
Faculty (Olympus): So, it is all my drawings.

605
01:12:39.660 --> 01:12:45.300
Faculty (Olympus): And so, cumulative distribution function is, by definition, if you say,

606
01:12:45.670 --> 01:12:50.260
Faculty (Olympus): Capital F, that's this one, okay, soâ€¦ Capital F.

607
01:12:52.510 --> 01:12:55.420
Faculty (Olympus): of X. This is what's called the CDF.

608
01:12:56.890 --> 01:13:02.420
Faculty (Olympus): This, by definition, the probability Is this not writing?

609
01:13:05.070 --> 01:13:05.810
Faculty (Olympus): Soâ€¦

610
01:13:09.120 --> 01:13:14.529
Faculty (Olympus): Probability of the random variable being less than are equal to X.

611
01:13:15.660 --> 01:13:26.419
Faculty (Olympus): Which means, what is the probability of findingâ€¦ so if you think of this as weights, what is the probability of finding, so if I say, the cumulative distribution function of 60,

612
01:13:27.100 --> 01:13:31.370
Faculty (Olympus): So let's redo this. I put this also as X, soâ€¦ oops, what did I do?

613
01:13:32.120 --> 01:13:33.880
Faculty (Olympus): Sorry, just a second.

614
01:13:35.930 --> 01:13:48.370
Faculty (Olympus): So now this is a cumulative distribution of the X, same weights, quantity. So if I look at 60, that's this value, okay? So it's going to be the probability of finding somebody below 60. So it's going to be the sum of all the areas up to that point.

615
01:13:49.400 --> 01:13:58.140
Faculty (Olympus): I hope this underâ€¦ you understand this, okay? So now, this will be a lot clearer when you do more stats, okay? But this is an empirical cumulative distribution function.

616
01:13:58.500 --> 01:14:04.900
Faculty (Olympus): Now, clearly, if I'm saying probability of X less than equal to X, it means that the sum of all the areas belongs.

617
01:14:06.110 --> 01:14:17.749
Faculty (Olympus): All right, so I hope this part is at least somewhat clear. If not, I think today or tomorrow, when you start doing, you know, random variables, this will be a little more clear, okay?

618
01:14:18.080 --> 01:14:20.030
Faculty (Olympus): Alright, so very quickly, Gaurav?

619
01:14:20.490 --> 01:14:35.740
Gaurav Singh .: Yeah, yeah, Professor. So, two queries, like, when we draw this PDF or CDF, we are considering the random, events are, like, equally likely, right? Like, that is whatâ€¦

620
01:14:36.090 --> 01:14:36.800
Faculty (Olympus): No.

621
01:14:37.470 --> 01:14:47.149
Faculty (Olympus): In fact, they're not equally likely, right? I'm more likely to find somebody between the weight of whatever, between 68 to 70, whatever, right? Or to 73.

622
01:14:47.400 --> 01:14:56.300
Faculty (Olympus): They're not equally likely. In fact, that's the beauty of a histogram. It tells you that there are more fellows or people between, you know, in this weight category, right?

623
01:14:56.300 --> 01:14:57.270
Gaurav Singh .: Okay, okay.

624
01:14:57.270 --> 01:14:58.779
Faculty (Olympus): You can see my mouse moving, right?

625
01:14:58.780 --> 01:14:59.480
Gaurav Singh .: Yeah, yeah.

626
01:14:59.480 --> 01:15:02.340
Faculty (Olympus): Right there, you can clearly say there's no one above 90 kilos.

627
01:15:02.740 --> 01:15:09.109
Faculty (Olympus): This is not data for this class, right? So this data is showing me there's no one above 90 kilos. It's a tiny data set.

628
01:15:09.400 --> 01:15:18.830
Gaurav Singh .: Yeah. And second point, like, when weâ€¦ you were drawing against Y, that was not the real picture, because that was not probabilities, if I'm not wrong, because the.

629
01:15:18.830 --> 01:15:32.740
Faculty (Olympus): Oh, why isâ€¦ why is some other quantityâ€¦ I couldn't use the analogy of weight for you to make it easy to understand. Why is some 1.2 to 1. something, right? So it's like, maybe I could use heights, right? Yeah. It could be heights, yeah, yeah.

630
01:15:33.430 --> 01:15:34.709
Gaurav Singh .: Thanks, thanks, Professor.

631
01:15:36.790 --> 01:15:37.580
Faculty (Olympus): Vamsi?

632
01:15:38.940 --> 01:15:54.659
Vamsi Krishna Mutnuri .: Yeah, good morning, Professor. Sir, can youâ€¦ can we takeâ€¦ for example, these are continuous variables, you said, where the variable might keep on changing values. So, can we do this analogy with something like a recording of hypertension in people, or sugar levels, andâ€¦

633
01:15:54.660 --> 01:15:59.590
Vamsi Krishna Mutnuri .: Say that, thisâ€¦ this comes under that category of class intervals or something.

634
01:16:01.030 --> 01:16:04.019
Faculty (Olympus): So, class intervals are somethingâ€¦ are something different.

635
01:16:04.180 --> 01:16:16.259
Faculty (Olympus): A histogram is very different. Histogram is saying, here is the data, or a probability density function is actually an idealization of this. It is in the limit of your bin size becoming infinitesimally small.

636
01:16:17.240 --> 01:16:21.599
Faculty (Olympus): If you're looking technically as a density, but we're never going to get there, we don't have that much data.

637
01:16:22.280 --> 01:16:29.829
Faculty (Olympus): So, class intervals are just making different, saying, okay, less than this. And even there, there is no requirement that those intervals actually be equal-sized.

638
01:16:31.320 --> 01:16:45.660
Faculty (Olympus): Okay, so that's a very different thing, it's a similar idea. Yes, there's similarity, you can break up things into all kinds of classes, but a histogram is a very precise idea, and there's a very deep connection to probability density function, and that's the important thing I wanted to teach you in this class.

639
01:16:45.660 --> 01:16:54.579
Faculty (Olympus): That is not just, oh, some plot, something has no connection to stats, no, it is intimately connected to statistics. And you can actually use this, and we will use it going forward.

640
01:16:55.180 --> 01:16:55.810
Faculty (Olympus): Okay?

641
01:16:55.810 --> 01:16:57.699
Vamsi Krishna Mutnuri .: Yes, sir. Just one more clarity.

642
01:16:57.700 --> 01:16:58.640
Faculty (Olympus): So, huh.

643
01:16:59.160 --> 01:17:16.350
Vamsi Krishna Mutnuri .: Sorry. One more small clarification is that by probability density function, we mean that, for example, if I take the analog of hypertension, a group of patients where I'm actually seeing the different BP levels, I can say that a particular set of people

644
01:17:16.350 --> 01:17:20.410
Vamsi Krishna Mutnuri .: have a high PDF of, you know, or in the higher PDF, for example.

645
01:17:20.410 --> 01:17:22.780
Faculty (Olympus): No high PDF. PDF is a function.

646
01:17:23.220 --> 01:17:35.469
Faculty (Olympus): You can say a particular group of people, or there's aâ€¦ there's a band ofâ€¦ there's a band of, say, BP values, which has a higher occurrence of the number of people. So you're basically saying, if I were to randomly sample the population.

647
01:17:35.780 --> 01:17:42.030
Faculty (Olympus): I would find a larger prevalence of people with that BP value, or that range of BP values.

648
01:17:42.940 --> 01:17:44.730
Vamsi Krishna Mutnuri .: Understood, sir. Understood. Thank you.

649
01:17:44.730 --> 01:17:45.290
Faculty (Olympus): Correct.

650
01:17:45.950 --> 01:17:46.590
Faculty (Olympus): Rahul?

651
01:17:46.900 --> 01:18:02.870
Rahul Joshi .: Sorry, Professor, if you can scroll slightly below just to see the x-axis. Yeah, yeah. So if you take this, yes, is it a correct understanding that, if we randomly select a student from this class, the probability that his weight will be between 70 to 80 is 0.025?

652
01:18:04.380 --> 01:18:05.030
Faculty (Olympus): Yes.

653
01:18:08.010 --> 01:18:09.260
Rahul Joshi .: That'sâ€¦ that's understanding, right?

654
01:18:09.670 --> 01:18:10.390
Faculty (Olympus): Yep.

655
01:18:10.390 --> 01:18:11.579
Rahul Joshi .: Okay, perfect, thank you.

656
01:18:13.720 --> 01:18:17.129
Faculty (Olympus): No, no, no, no, no, no, sorry, come again, come again. The probability ofâ€¦

657
01:18:17.660 --> 01:18:18.570
Rahul Joshi .: So, probability ofâ€¦

658
01:18:18.570 --> 01:18:19.400
Faculty (Olympus): a student.

659
01:18:19.670 --> 01:18:29.840
Rahul Joshi .: So if you randomly select a student from this class, the probability that his weight will be between whatever is that, 73 to 79, each 0.25, right?

660
01:18:30.220 --> 01:18:47.490
Faculty (Olympus): Actually, very good question. It is not exactly that. This is the probability density function. So, to actually find the true probability, you'll have to multiply it by the width of this above. So, whatever the 5KGs, or whatever is the 73 to 78, whatever you said, into .025 will be the weight.

661
01:18:47.700 --> 01:18:48.590
Faculty (Olympus): Got it?

662
01:18:49.390 --> 01:18:51.210
Rahul Joshi .: Sir, can you say it again? Sorry.

663
01:18:51.940 --> 01:18:54.840
Faculty (Olympus): This number is, say, 0.025, right?

664
01:18:55.120 --> 01:18:55.650
Rahul Joshi .: Yep.

665
01:18:56.110 --> 01:18:58.850
Faculty (Olympus): 0.025 times the width of the DBA.

666
01:19:00.640 --> 01:19:02.120
Faculty (Olympus): Will be the actual problem.

667
01:19:04.770 --> 01:19:05.520
Rahul Joshi .: You touched.

668
01:19:06.560 --> 01:19:07.689
Faculty (Olympus): Am I making sense?

669
01:19:09.260 --> 01:19:14.510
Rahul Joshi .: Then thatâ€¦ see, that graph will be more useful, right, than this one, then.

670
01:19:14.800 --> 01:19:17.770
Rahul Joshi .: Because you'll be interested in getting the actual probability, right?

671
01:19:17.770 --> 01:19:21.479
Faculty (Olympus): No, you can compute it however you want, but this is what a density plot is going to give you.

672
01:19:22.200 --> 01:19:23.630
Faculty (Olympus): This is a density plot.

673
01:19:23.810 --> 01:19:42.150
Faculty (Olympus): It corresponds to an idea that is in mathematics when you do your stats course. If I do something that's different here, you do something else different there, you'll get confused. So this corresponds to a density plot. A density plot, to findâ€¦ to read off probabilities from a density plot, you have to compute an area. To compute an area, you need the value of the height of the bar and the width of the bar.

674
01:19:42.780 --> 01:19:43.680
Faculty (Olympus): Simple.

675
01:19:43.870 --> 01:19:54.229
Rahul Joshi .: So, sorry, just a follow-up question. So, if we take this example, let's say 73 to 79, this entire area exactly indicates what? The total number of students

676
01:19:54.500 --> 01:19:56.369
Rahul Joshi .: Falling between those weight ranges.

677
01:19:56.370 --> 01:20:01.539
Faculty (Olympus): No, it will beâ€¦ the entire area of this curve will be 1. So, in fact, you can see that here.

678
01:20:01.640 --> 01:20:04.400
Faculty (Olympus): It goes to 1. Cumulative distribution hits 1.

679
01:20:04.580 --> 01:20:05.110
Rahul Joshi .: Yep.

680
01:20:06.930 --> 01:20:09.750
Faculty (Olympus): And the cumulative distribution is computed byâ€¦

681
01:20:11.560 --> 01:20:18.500
Faculty (Olympus): Sums of the weights, and here you can read off probabilities, because this is basically sum of the areas.

682
01:20:19.920 --> 01:20:26.400
Faculty (Olympus): If you remember the definition of capital F, which is the cumulative distribution, it is probability of the random variable less than or equal to X.

683
01:20:27.900 --> 01:20:42.309
Faculty (Olympus): Whereas the density function is just local density. It's like this. If you ask me what is the density of my arm, it may be about 900 kilograms per centimeter cubed, right? But if you ask me what is the weight of my arm, I need to give you a finite area, right? So the weight is what integrates out to probability.

684
01:20:43.030 --> 01:20:44.290
Faculty (Olympus): This is only density.

685
01:20:48.330 --> 01:20:52.700
Rahul Joshi .: Can you explain that topic again? In this graph?

686
01:20:52.880 --> 01:20:59.610
Rahul Joshi .: If weâ€¦ if we again say 73 to 79, and thatâ€¦ that area will indicate what exactly?

687
01:20:59.860 --> 01:21:00.480
Rahul Joshi .: None.

688
01:21:00.480 --> 01:21:05.229
Faculty (Olympus): area is the probability. The area is the probability, not the height of this clock.

689
01:21:06.850 --> 01:21:12.490
Faculty (Olympus): value 0.025 is not the probability that into the bin width is the probability.

690
01:21:12.490 --> 01:21:13.550
Rahul Joshi .: Okay, got it.

691
01:21:13.550 --> 01:21:27.770
Faculty (Olympus): the bin width is a constant, you can say, okay, relatively, this has more probability. That is a correct statement. So this fellow, for example, this Daba, has more probability of occurrence. That's perfectly correct. But if you want to say, no, it is THE probability, then you have to multiply by the bin width. Just be careful of this.

692
01:21:29.000 --> 01:21:29.760
Rahul Joshi .: Oh, okay.

693
01:21:29.990 --> 01:21:35.309
Faculty (Olympus): Alright, so for example, if I change this to YE, you'll notice that these numbers are very different, it's 2.

694
01:21:35.700 --> 01:21:37.200
Faculty (Olympus): This is not the probability.

695
01:21:38.120 --> 01:21:41.860
Faculty (Olympus): Thisâ€¦ because the VIN width here is small, so you want to multiply by the wind width.

696
01:21:42.590 --> 01:21:43.710
Rahul Joshi .: Okay, we got it here.

697
01:21:43.710 --> 01:21:44.440
Faculty (Olympus): Noted?

698
01:21:44.640 --> 01:21:54.769
Faculty (Olympus): Yep. Right, so if I stretch this, I have, you know, weight of elephants. This number will become smaller, right? Because weight of elephants will span, like, tons, and not just, you know, 70, 80 kilos.

699
01:21:56.530 --> 01:21:57.390
Faculty (Olympus): Alright.

700
01:21:58.450 --> 01:22:03.249
Faculty (Olympus): somebody here has chatted about help, so Shift-Tab will also give you the, you know.

701
01:22:06.300 --> 01:22:09.860
Faculty (Olympus): signature and documentation. Okay, Rahul?

702
01:22:10.530 --> 01:22:12.310
Rahul Joshi .: No, no, you answered my question, sorry.

703
01:22:12.310 --> 01:22:13.660
Faculty (Olympus): Okay, great. Vivek?

704
01:22:14.010 --> 01:22:19.500
Vivek Balachandran Nair .: Yes, sir. So, applying the same principle on the plane histogram in which you took the.

705
01:22:20.060 --> 01:22:21.229
Faculty (Olympus): My voice is too low.

706
01:22:21.820 --> 01:22:23.570
Vivek Balachandran Nair .: Are you able to hear me now?

707
01:22:23.870 --> 01:22:24.420
Faculty (Olympus): Yeah.

708
01:22:25.210 --> 01:22:31.710
Vivek Balachandran Nair .: So, applying the same principle to the plane histogram, where you took the counts versus the bucket.

709
01:22:31.850 --> 01:22:36.919
Vivek Balachandran Nair .: Does the area also here give the probability in a plain Instagram?

710
01:22:36.920 --> 01:22:37.730
Faculty (Olympus): No.

711
01:22:38.470 --> 01:22:39.930
Vivek Balachandran Nair .: Because this is gonna give me.

712
01:22:39.930 --> 01:22:44.759
Faculty (Olympus): the area under this curve is gonna be mega massive, right? It's going to be 100 people times thisâ€¦

713
01:22:45.730 --> 01:22:47.490
Faculty (Olympus): It's gonna be scaled out of whack.

714
01:22:47.830 --> 01:22:51.060
Faculty (Olympus): Here, this'll all add up to 100, the total number of fellows.

715
01:22:51.330 --> 01:22:54.960
Vivek Balachandran Nair .: Okay, just the plain counts, not theâ€¦

716
01:22:54.960 --> 01:22:57.170
Faculty (Olympus): Yeah, they're just plain columns.

717
01:22:58.030 --> 01:22:58.820
Vivek Balachandran Nair .: Thank you.

718
01:22:58.990 --> 01:23:04.390
Faculty (Olympus): That's why the argument given here is density. So it's very clear that it maps to a density function.

719
01:23:05.410 --> 01:23:08.060
Faculty (Olympus): Right, and this is a cumulative distribution function.

720
01:23:08.770 --> 01:23:15.359
Faculty (Olympus): And the other fellow is just cumulative counts, and just plain hist will just give me a counts and, you know, cumulative counts.

721
01:23:15.910 --> 01:23:16.529
Vivek Balachandran Nair .: Don't go.

722
01:23:17.180 --> 01:23:19.430
Faculty (Olympus): All right. Sunil?

723
01:23:19.740 --> 01:23:30.539
Sunil Rawat .: Yes, Professor. So, when we use cumulative, I can see on Y axis, it goes till 1. But if I'm not using cumulative, then what that number denotes?

724
01:23:31.140 --> 01:23:32.669
Faculty (Olympus): So you're not using Kumar.

725
01:23:32.670 --> 01:23:36.050
Sunil Rawat .: Yeah, here, the .04, the .0â€¦

726
01:23:36.050 --> 01:23:37.700
Faculty (Olympus): Like I said, this is a density function.

727
01:23:38.550 --> 01:23:41.930
Sunil Rawat .: So, howâ€¦ what do we call it onâ€¦ on Y-axis? I mean,

728
01:23:41.930 --> 01:23:43.529
Faculty (Olympus): Values of the density function.

729
01:23:43.860 --> 01:23:47.390
Faculty (Olympus): Multiply this by the bandwidth, you'll get probability in this DBA.

730
01:23:48.680 --> 01:23:52.540
Sunil Rawat .: Okay, so it basically calculates the density and plots it on the y-axis.

731
01:23:52.950 --> 01:23:54.510
Sunil Rawat .: Yeah. Is it something?

732
01:23:55.450 --> 01:23:56.080
Faculty (Olympus): Yes.

733
01:23:56.360 --> 01:23:57.740
Sunil Rawat .: Okay, yeah, thanks.

734
01:23:57.740 --> 01:24:04.779
Faculty (Olympus): You can think of it as relative histogram divided by the bandwidth. That's the value you see on this axis.

735
01:24:05.020 --> 01:24:05.860
Sunil Rawat .: Okay, okay.

736
01:24:05.860 --> 01:24:16.930
Faculty (Olympus): Because it has to correspond to a probability density, the area of this curve has to be 1, right? And that's the reason all thisâ€¦ this is why I'm trying to spend time on this, so that you clearly understand what this thing is, what density means.

737
01:24:17.190 --> 01:24:21.320
Faculty (Olympus): I know I've spent a lot of time, some of you advanced people will shout at me later on, butâ€¦

738
01:24:21.440 --> 01:24:26.190
Faculty (Olympus): This is important, you need to understand this, because you're going to be making histograms the rest of your life.

739
01:24:26.300 --> 01:24:32.290
Faculty (Olympus): But if you understand this once, you will never forget this. Basically, remember that it's a density, it's notâ€¦ it's aâ€¦ it'sâ€¦

740
01:24:32.390 --> 01:24:37.589
Faculty (Olympus): Histograms are directly related to probability measurements, so it's something you need to keep in mind.

741
01:24:38.290 --> 01:24:45.930
Sunil Rawat .: So, there is a way to getâ€¦ is there any way to get a count on these bars, Professor? I mean, so that we can get a certain number.

742
01:24:45.930 --> 01:24:47.959
Faculty (Olympus): Same thing, I already showed you.

743
01:24:48.150 --> 01:24:50.090
Faculty (Olympus): np.hist histogram.

744
01:24:50.360 --> 01:24:51.569
Faculty (Olympus): We'll give you counts.

745
01:24:51.730 --> 01:24:52.599
Faculty (Olympus): The same bars.

746
01:24:53.250 --> 01:25:01.540
Sunil Rawat .: On each bar, let's say I'm writing the 14, and on top of that bar, if there is a label I can get, how much count is there?

747
01:25:01.980 --> 01:25:06.649
Faculty (Olympus): No, you want to make this plot fancier. There are other tools that'll do it, I'm not going to cover that here.

748
01:25:06.650 --> 01:25:07.270
Sunil Rawat .: Oh.

749
01:25:07.270 --> 01:25:23.580
Faculty (Olympus): read up fast, Google, ask Jiminy, they will do all of this. What I'm telling you now is not there, people are not going to tell you, right? So I don't want to spend time embellishing this plot, making it fancy. There are hundreds of options, and you are encouraged strongly to, you know, find out these options by yourself. I'm not going to walk you through that.

750
01:25:23.580 --> 01:25:32.899
Sunil Rawat .: Sure, sure, because we are assuming that there isâ€¦ this bar is between 73 to 79, so if there is any way to get that width, then that will be helpful.

751
01:25:32.900 --> 01:25:40.009
Faculty (Olympus): And yeah, so you get all the widths, you get everything here. You get the actual bins and the actual counts with this. You have all of that data.

752
01:25:40.200 --> 01:25:41.080
Sunil Rawat .: Oh, oh.

753
01:25:41.080 --> 01:25:47.269
Faculty (Olympus): This is just a fancy plot of this by dividing by bin width and stuff. There's nothing major. In fact, you can construct from this fellow.

754
01:25:47.880 --> 01:25:50.210
Faculty (Olympus): This fellow. Or this fellow.

755
01:25:51.150 --> 01:25:54.090
Sunil Rawat .: Okay, thanks, Professor Singh. Got it. Thanks.

756
01:25:54.090 --> 01:25:55.060
Faculty (Olympus): Siddharth?

757
01:25:55.060 --> 01:26:00.270
Siddharth Digambar Kulkarni .: Sir, this is not, this cumulative is not density, right? This is distribution, right?

758
01:26:00.580 --> 01:26:02.790
Faculty (Olympus): Yes, this is cumulative distribution function.

759
01:26:02.790 --> 01:26:08.980
Siddharth Digambar Kulkarni .: So not, cumulative distribution function. And the previous one was a density function.

760
01:26:08.980 --> 01:26:09.660
Faculty (Olympus): Yes.

761
01:26:09.660 --> 01:26:10.659
Siddharth Digambar Kulkarni .: Okay, okay, good.

762
01:26:10.660 --> 01:26:11.300
Faculty (Olympus): Yes.

763
01:26:11.620 --> 01:26:15.600
Siddharth Digambar Kulkarni .: So that is why this distribution function is adding up to 1.

764
01:26:16.640 --> 01:26:17.290
Faculty (Olympus): Yes.

765
01:26:17.650 --> 01:26:18.390
Siddharth Digambar Kulkarni .: Oakland.

766
01:26:18.790 --> 01:26:23.449
Faculty (Olympus): So, and again, please remember, these are all approximations. This is not the true distribution or the true density.

767
01:26:23.650 --> 01:26:31.120
Faculty (Olympus): Given your sample, this is an approximation to that. So, it's a very useful mental model that you have. So, the reason I'm doing this so much is

768
01:26:31.680 --> 01:26:46.510
Faculty (Olympus): Most of your course in stats is going to be random variable, random variable, random variable, and many of you are like, yeah, random variable seems to be some unuseless thing, you know, but it's not at all useless, because every time you make a histogram, that is a density function, if its density is true.

769
01:26:46.570 --> 01:27:06.089
Faculty (Olympus): Every time you do a cuberative distribution, that's a distribution function, right? So, and then, you know, then it makes total sense. So, you know, I look at some data, I do a histogram, this actually gives me density, and from which I can calculate things, which we will do very soon, okay? So, Manu, Roshan, and Rahul, I will come back to you. I really want to finish a little bit more, okay?

770
01:27:06.510 --> 01:27:07.700
Faculty (Olympus): He'll come back to you.

771
01:27:07.960 --> 01:27:21.209
Faculty (Olympus): The next thing we look at is, we're looking at box plots. I just hope everyone understood histograms, the connection to density, and cumulative distribution, and when you go back to your stats course, you have this new set of tools and new understanding for this, okay?

772
01:27:21.210 --> 01:27:32.510
Faculty (Olympus): Alright, so box plots are a very powerful plotting utility, and again, they show distribution of the data at a glance, and they typically will show you the following. They'll show you the median, the first quartile, the third quartile.

773
01:27:32.810 --> 01:27:45.070
Faculty (Olympus): quartile and the interquartile range. First quartile is 25 percentile, third quartile is 75 percentile, median is 50 percentile. And IQR is the difference between the 75 percentile and the 25 percentile.

774
01:27:46.910 --> 01:27:59.359
Faculty (Olympus): Okay, so let's just run this, it's easier to see this visually. So the same X fellow looks like this. This is the X variable, and it hasâ€¦ these are called the box and whiskers. Okay, so the whiskers are typically

775
01:28:00.800 --> 01:28:07.799
Faculty (Olympus): Q1 minus 1.5 times the IQR. So this is the IQR. This box here is the interquartile range.

776
01:28:07.860 --> 01:28:26.440
Faculty (Olympus): This, orange colored line is the median, okay? These are the data values, okay? Somewhere between 35 to 92 or whatever, okay? This is the interquartered range. So this means this is the median. 50% of the population lies below this, 75 lies below this, 25 lies below. So you can actually get a sense of the distribution.

777
01:28:27.610 --> 01:28:44.000
Faculty (Olympus): 1.5 times the IQR. IQR is this DBA size. 1.5 times that is where they plot what's called a whisker, much, okay, for this thing. Beyond this, they will actually show you dots, okay, which are called outliers. This answers someone else's question, okay?

778
01:28:44.220 --> 01:28:55.239
Faculty (Olympus): The additional argument here, I'm saying show means is true, that is the one that's showing you this little triangle. This is the actual mean. And in this case, the mean and the median do not coincide.

779
01:28:56.160 --> 01:29:01.400
Faculty (Olympus): All right. Now, you can also show multiple box plots together, and this is the trick to do it.

780
01:29:01.980 --> 01:29:21.039
Faculty (Olympus): Now, here, I've given a bunch of additional arguments, you can explore this on your own time, but the key point here is you give this as a tuple of X comma Y, and you give these tick labels, whatever you want, you can make this, okay? Notice that you can put them in the same plot, and sometimes it doesn't make any sense, because this fellow is so Chota that his

781
01:29:21.100 --> 01:29:38.960
Faculty (Olympus): Distribution is very tiny, whereas the weights is very large, okay? So very often, you may have to rescale, and it makes sense to put box plots together if they are of the similar class of thing, right? So if you're comparing two backsmen, two bowlers, right? Then you put those two things together of the same class, okay?

782
01:29:39.180 --> 01:29:46.330
Faculty (Olympus): But basically, this tells you this is the box plot of this, and this is the box plot. This is unfortunately why it doesn't have much in comparison to X.

783
01:29:47.600 --> 01:29:49.450
Faculty (Olympus): Now, the next thing is,

784
01:29:49.990 --> 01:29:54.839
Bipin Karyakarte .: Professor, before moving on to violent parts, would it be possible for you to take a question?

785
01:29:55.740 --> 01:29:58.530
Faculty (Olympus): No, other people are waiting in line, so Iâ€¦ I thinkâ€¦

786
01:29:58.940 --> 01:29:59.580
Bipin Karyakarte .: Okay.

787
01:30:01.100 --> 01:30:07.020
Faculty (Olympus): I'll come back to you. I'll definitely stop for questions at 11 o'clock, okay? But I want to finish more, I wanted to finish this, but we gotâ€¦

788
01:30:07.270 --> 01:30:10.390
Faculty (Olympus): All theoretical in our, stuff.

789
01:30:10.590 --> 01:30:25.920
Faculty (Olympus): Because the last part of this notebook actually is fun, right? This is all boring stuff, right? So, the violin plots combine probability distribution functions and box plots. Okay, so what it does is, if I were to look at X, it does something like this. So, it kind of looks like a box plot. It's on its head.

790
01:30:26.080 --> 01:30:31.899
Faculty (Olympus): But, this plot that you see here is a smooth representation of your histogram.

791
01:30:32.340 --> 01:30:36.259
Faculty (Olympus): Okay, it's done using something called a kernel density estimator.

792
01:30:36.880 --> 01:30:42.639
Faculty (Olympus): But that is not important. But you can think of this as a smooth version of your density plot.

793
01:30:43.160 --> 01:30:46.790
Faculty (Olympus): So, in a sense, in one plot, you get

794
01:30:47.190 --> 01:30:49.730
Faculty (Olympus): The sense of how your data is distributed.

795
01:30:50.900 --> 01:30:57.309
Faculty (Olympus): Okay? So this is what is called a violin plot. Same way, if you do this for Y, you will get another violin plot.

796
01:30:57.450 --> 01:31:06.360
Faculty (Olympus): So, basically, if you'reâ€¦ some of you will be confused, what is the left side, what is the right side? They basically symmetrize it so that it looks like a violin, right?

797
01:31:06.870 --> 01:31:12.840
Faculty (Olympus): Okay, so this and this are exactly the same, there's no difference. Maybe visually it'll look different, right?

798
01:31:13.100 --> 01:31:19.270
Faculty (Olympus): But they're actually the same. Symmetrically placed around the midpoint, right? And you can see that this is the mostâ€¦

799
01:31:19.800 --> 01:31:21.739
Faculty (Olympus): Probable occurrence is here.

800
01:31:22.220 --> 01:31:24.470
Faculty (Olympus): And as you move away, the probability drops.

801
01:31:26.140 --> 01:31:27.090
Faculty (Olympus): Okay.

802
01:31:28.410 --> 01:31:29.930
Faculty (Olympus): Few more things here.

803
01:31:30.820 --> 01:31:39.379
Faculty (Olympus): I want to do the fun part, so let's finish this also. So there's another quantity that you're going to encounter in your stats course. Have you already seen Pierce's correlation coefficient?

804
01:31:39.890 --> 01:31:40.640
Soumen Deb .: I'm not behaving.

805
01:31:40.640 --> 01:31:42.060
Mayank Johri .: Yeah, excuse me.

806
01:31:42.060 --> 01:31:44.290
Faculty (Olympus): Some of you may already know it, but if youâ€¦

807
01:31:44.290 --> 01:31:45.019
Vivek Sahu .: Yes, we have done.

808
01:31:45.020 --> 01:31:45.680
Mayank Johri .: In the first place.

809
01:31:45.680 --> 01:31:53.210
Faculty (Olympus): So, okay, great. So if you've done Pierson correlation coefficient, you can trivially compute it with NP.Korkov. And don't read the diagonals.

810
01:31:54.720 --> 01:32:01.150
Faculty (Olympus): read the off-diagonal, okay? So it's symmetric, so you read any one of the off-diagnols. This is the correlation coefficient between X and Y.

811
01:32:02.110 --> 01:32:08.449
Faculty (Olympus): Okay? So, for example, if I did XN2 star X, We'll hit all one.

812
01:32:08.890 --> 01:32:09.960
Faculty (Olympus): plus what?

813
01:32:10.570 --> 01:32:22.950
Faculty (Olympus): Notice that these fellows are also strongly correlated, because X is dominating everything, okay? Or if I did even this, it's going to be strongly correlated, and correlation coefficient is close to 1, which means they are strongly, positively correlated.

814
01:32:23.270 --> 01:32:25.499
Faculty (Olympus): In this case, they are negatively correlated.

815
01:32:25.630 --> 01:32:26.750
Faculty (Olympus): Okay?

816
01:32:27.550 --> 01:32:31.790
Faculty (Olympus): To understand this perhaps a little better, you can do the following.

817
01:32:32.710 --> 01:32:33.470
Faculty (Olympus): Sweet.

818
01:32:35.920 --> 01:32:38.470
Faculty (Olympus): So, let me do an increase on PLT.

819
01:32:38.640 --> 01:32:40.030
Faculty (Olympus): scatterplot.

820
01:32:40.820 --> 01:32:46.310
Faculty (Olympus): Xâ€¦ sorry, not scatter, scatter, X minus X plus 1.

821
01:32:47.000 --> 01:32:48.170
Faculty (Olympus): Same tournament?

822
01:32:48.590 --> 01:32:52.649
Faculty (Olympus): Notice, they lie on a line, and the line is not negative, okay?

823
01:32:52.940 --> 01:32:59.450
Faculty (Olympus): That's why you get a negative correlation coefficient. On the other hand, if I did X minus Y, for example, this is going to be a positive straight line.

824
01:33:00.610 --> 01:33:20.010
Faculty (Olympus): Okay, so the correlation coefficient is busted. So what this fellow tells you, this Parrison correlation coefficient, it tells you how closely these quantities are linearly related. It does not tell you something. So, for example, if I were to do sine of 2 star np dot pi starâ€¦ actually, actually just be 2 star X.

825
01:33:23.500 --> 01:33:28.340
Faculty (Olympus): And Padolkarth Okay, so if I, for example.

826
01:33:28.450 --> 01:33:32.139
Faculty (Olympus): Let's just do this. Correlation coefficient of np dot sine

827
01:33:35.550 --> 01:33:41.820
Faculty (Olympus): You would think that if these two fellows are, they're directly related. One is simply the sign of that fellow, right?

828
01:33:42.090 --> 01:33:45.329
Faculty (Olympus): Unfortunately, the correlation quotient is telling me it's minusâ€¦

829
01:33:45.430 --> 01:34:01.050
Faculty (Olympus): Okay? So if the relationship between those two quantities is not linear, tear cells correlation is no good. It's not going to tell you anything useful. If it's a linear relationship, then it'll actually catch it and tell you that there is a linear relationship. So even if this was, like, say, 200 or 2000X, it's going to be 1.

830
01:34:01.440 --> 01:34:03.080
Faculty (Olympus): Okay? Soâ€¦

831
01:34:03.380 --> 01:34:13.459
Faculty (Olympus): Just because you have a correlation coefficient of 0 does not mean these two quantities are not related. All it means is they are not linearly related, okay? So just keep this in.

832
01:34:15.180 --> 01:34:21.600
Faculty (Olympus): And again, notice that a scatter plot is going to give you insight about, you know, correlations.

833
01:34:23.580 --> 01:34:28.920
Faculty (Olympus): Doesâ€¦ The next thing is, pie and bar charts.

834
01:34:30.560 --> 01:34:38.110
Faculty (Olympus): I usually do not suggest ever using pie charts, because pie charts are hard to read. The reason is, it's very hard to read an area

835
01:34:38.110 --> 01:34:52.599
Faculty (Olympus): Right? I know that some of you are going to say, no, it'sâ€¦ I know which pizza slice is the biggest pizza slice, but if I cut two pizza slices exactâ€¦ very, very close to each other, it's very hard to tell which is the bigger pizza slice, right? Because you have visual artifacts. When you start watching, you know, you have parallax errors.

836
01:34:52.600 --> 01:34:59.010
Faculty (Olympus): Right? You think they are different, but they're not different, right? So it's always better to use something like a bar chart.

837
01:34:59.690 --> 01:35:03.769
Faculty (Olympus): Okay, so here's aâ€¦ So, what did I do? It's a mistake here.

838
01:35:05.030 --> 01:35:05.720
Faculty (Olympus): Soâ€¦

839
01:35:06.360 --> 01:35:13.669
Faculty (Olympus): Okay, so this is a bar chart, right, but it's kind of hard to say. Here, it's easy. Bladder and melanoma cancer are, you knowâ€¦ sorry, this is a veryâ€¦

840
01:35:19.020 --> 01:35:33.859
Faculty (Olympus): It's cancer, so it's not a very pleasant topic, but anyway. But it's easier to see the difference when you have a bar chart, because I can actually see, hey, this string is higher than this. So bar charts isâ€¦ I feel that bar charts are much better to use, but lots of business types seem to like

841
01:35:34.010 --> 01:35:37.429
Faculty (Olympus): I charge, soâ€¦ How to use it to use it?

842
01:35:38.260 --> 01:35:47.909
Faculty (Olympus): All right, so now we come to the fun part. I have 5 minutes, so I'm going to use this time to try and finish this, and then I promise you I will answer most of your questions.

843
01:35:48.380 --> 01:35:59.499
Faculty (Olympus): So what I have is, we have all the ADI scores, sorry, ODI scores, of both Sachin and Vinath Kohli, and actually other batsmen as well. They are also in your data directory.

844
01:35:59.820 --> 01:36:03.260
Faculty (Olympus): So, Sachin.txt has Sachin's ordinaryâ€¦

845
01:36:04.640 --> 01:36:12.510
Faculty (Olympus): One day international scores, and COLE is one day international scores, okay? They each have a single column, which means their total career.

846
01:36:12.930 --> 01:36:14.779
Faculty (Olympus): all their ODI scores.

847
01:36:15.820 --> 01:36:16.870
Faculty (Olympus): Noâ€¦

848
01:36:17.560 --> 01:36:32.089
Faculty (Olympus): First task for you is to load these files using np.load.txt, okay? Show a density plot for each of these players, okay? And then show them together, and use the same approach that we did for the box plot.

849
01:36:32.440 --> 01:36:36.119
Faculty (Olympus): Okay? And then use a legend to set the legend so that we know who's who.

850
01:36:37.260 --> 01:36:46.050
Faculty (Olympus): Then show the data using a box plot, and show the data using a violin plot, okay? So for now, you don't have to do all of these. At least show me histograms for Sachin and Kunal.

851
01:36:46.650 --> 01:36:51.230
Faculty (Olympus): So, this is the first exercise. So maybeâ€¦

852
01:36:51.550 --> 01:37:01.279
Faculty (Olympus): You can type along, try as we go. I will go very slowly. So, I will say, Sachin's course is np.org.txt.

853
01:37:01.560 --> 01:37:03.269
Prathamesh Mone: There's some background noise.

854
01:37:08.080 --> 01:37:08.959
Faculty (Olympus): I don't know.

855
01:37:27.650 --> 01:37:30.279
Faculty (Olympus): You can also use tab completion to complete.

856
01:37:30.640 --> 01:37:37.189
Faculty (Olympus): And noâ€¦ I will simply do, so I've loaded these two fellows, that's very good.

857
01:37:37.810 --> 01:37:39.699
Faculty (Olympus): Let me add some cells.

858
01:37:43.630 --> 01:37:51.259
Faculty (Olympus): Now, let me do aâ€¦ There are codiPlotBlp.hist, Such in scores.

859
01:37:51.490 --> 01:37:53.409
Faculty (Olympus): Dins equal to auto.

860
01:37:54.340 --> 01:37:58.380
Faculty (Olympus): Density button throughâ€¦ Same problem.

861
01:37:58.890 --> 01:38:00.800
Faculty (Olympus): That is Sachin's scores.

862
01:38:00.920 --> 01:38:01.690
Faculty (Olympus): Nope.

863
01:38:02.430 --> 01:38:05.200
Faculty (Olympus): But now I also want to show you Coley's course.

864
01:38:08.030 --> 01:38:11.900
Faculty (Olympus): So, let me seeâ€¦ Bombing scores.

865
01:38:12.570 --> 01:38:16.359
Faculty (Olympus): Okay, also very different, okay? But I want to see them together.

866
01:38:16.570 --> 01:38:21.650
Faculty (Olympus): So, easy way of doing this is, I say, Saturn scores, Okay, scores.

867
01:38:22.380 --> 01:38:24.329
Faculty (Olympus): Let's say anything that I don'tâ€¦

868
01:38:42.780 --> 01:38:45.150
Faculty (Olympus): Now, immediately, you see something very interesting.

869
01:38:46.100 --> 01:38:46.910
Faculty (Olympus): Yeah?

870
01:38:47.680 --> 01:38:49.639
Faculty (Olympus): Right? So this is already very useful.

871
01:38:56.680 --> 01:39:01.070
Faculty (Olympus): Now, the other thing we could do is we could also do a box plot. So let's do box plot.

872
01:39:02.300 --> 01:39:15.700
Faculty (Olympus): ELTâ€¦ Vox blockâ€¦ Section, and then moving scoresâ€¦ Several roomsâ€¦

873
01:39:24.950 --> 01:39:29.669
Faculty (Olympus): Okay, this is nice, because you can see something interesting here. This is Sachin, by the way.

874
01:39:30.560 --> 01:39:38.019
Faculty (Olympus): Okay, so by the way, I have to use the same way to do this if you want the ticks to show up nicely. You have to say tick labels.

875
01:39:53.230 --> 01:40:02.189
Faculty (Olympus): Okay, so Sachin is here, Kohli is here. Immediately, you see some lot of things. In Sachin's case, you see there are a huge number of outliers.

876
01:40:03.020 --> 01:40:05.030
Faculty (Olympus): These are all outliers, okay?

877
01:40:06.270 --> 01:40:12.159
Faculty (Olympus): You can also see that the mean and the medianâ€¦ I can make a grid here so you can see the differences.

878
01:40:18.900 --> 01:40:27.809
Faculty (Olympus): Right? The mean Koli is higher, median is higher, and he has a larger interquartile range, and you can actually see that

879
01:40:28.240 --> 01:40:33.670
Faculty (Olympus): only seems to score a lot of high scores. In fact, this is kind of visible even in this histogram log.

880
01:40:33.820 --> 01:40:41.340
Faculty (Olympus): Notice that Coley'sâ€¦ the probability of Kohli scoring a higher score is actually higher.

881
01:40:42.570 --> 01:40:56.149
Faculty (Olympus): All right, so the cool thing here is, while you've seen a lot of these plots, of course, you can do violin plots and all of this. You can, you know, do that as homework exercise. Just give me a minute, I'll wrap this up.

882
01:40:56.740 --> 01:41:08.960
Faculty (Olympus): I'll just wrap this up here, we'll come back to this in the next class. So, we've seen various kind of plots, and we've seen that these are entirely visual, but the beauty of histograms is you can actually do very powerful numerical things with it, right?

883
01:41:09.120 --> 01:41:21.839
Faculty (Olympus): Because you have the counts of the number of occurrences, right? You have to be careful about choosing your VIN sizes carefully, so use auto is the first thing that I would suggest, okay? And we've seen that,

884
01:41:21.960 --> 01:41:34.490
Faculty (Olympus): there's an intimate connection between these histograms and probability density functions and cumulative distribution functions. So what this means is, you can actually ask questions like, what is the probabilityâ€¦ so, I think I have this here.

885
01:41:35.830 --> 01:41:47.639
Faculty (Olympus): What is the probability that Sachin will score less than 10? What is the probability that Sachin will score greater than 50? What is the conditional probability that he will cross 100, given that he crossed 50? These are questions that you can actually answer with this data.

886
01:41:47.670 --> 01:41:56.379
Faculty (Olympus): Okay? And that is why this business of histograms is not just to produce pretty plots, you can actually answer some really nice questions when you do this, okay?

887
01:41:56.950 --> 01:41:58.500
Faculty (Olympus): So I will stop here.

888
01:41:58.610 --> 01:42:01.609
Faculty (Olympus): Given that we areâ€¦ A bit late.

889
01:42:01.740 --> 01:42:02.789
Faculty (Olympus): Butâ€¦

890
01:42:02.910 --> 01:42:20.330
Faculty (Olympus): We will continue with this in the next class. I'll wrap this up so that we can answer these probability questions, but since the notebook is already up, I strongly encourage you to do this yourselves before the next Wednesday class, and then I will quickly go through the material and answer any questions. But for now, I will answer all your questions.

891
01:42:20.800 --> 01:42:25.789
Faculty (Olympus): So, let's start with, manu, we've been waiting for a while.

892
01:42:28.660 --> 01:42:45.179
Manu Gupta .: Yes, sir, thank you. I have a doubt regarding density function and cumulative density graphs. So, earlier during the discussion, it was mentioned that we had a weight between 73 to 79.

893
01:42:45.180 --> 01:42:45.660
Faculty (Olympus): Mhmh.

894
01:42:45.660 --> 01:42:56.400
Manu Gupta .: Of the density graph. So to, the area under that particular bar is the probability of, people having weights between 73 to 79.

895
01:42:56.650 --> 01:42:57.270
Faculty (Olympus): Got it.

896
01:42:57.270 --> 01:43:04.990
Manu Gupta .: what I get from that discussion. So, in the second graph of cumulative density, what does the area represent here?

897
01:43:04.990 --> 01:43:11.070
Faculty (Olympus): So here, if you find the area at this point minus the area at this point, that'll give you the probability of things inside this plan.

898
01:43:11.560 --> 01:43:16.590
Manu Gupta .: I guess because here the y-axis, directly give us the probability.

899
01:43:16.590 --> 01:43:23.799
Faculty (Olympus): Correct. But this is the probability of everything less than this value. So, less than 70 means I go to this graph, read it, and say, boom, 0.8.

900
01:43:24.340 --> 01:43:26.519
Faculty (Olympus): Volvity of less than 65?

901
01:43:26.840 --> 01:43:29.470
Faculty (Olympus): whatever, 0.55 water. Right?

902
01:43:29.470 --> 01:43:35.880
Manu Gupta .: Y axis giving us the probability. So, what is the area giving us here?

903
01:43:36.650 --> 01:43:43.289
Faculty (Olympus): Oh, so the area here is not of any relevance. Integral of the CDF is not really useful quantity.

904
01:43:43.580 --> 01:43:46.330
Faculty (Olympus): The derivative of this quantity gives you the density.

905
01:43:47.420 --> 01:43:48.740
Manu Gupta .: Okay, yes.

906
01:43:48.890 --> 01:44:05.020
Faculty (Olympus): Alright, so here it's directly read off, because this isâ€¦ so, as I said, if you remember the definition, the definition is f of x, which is capital F of X, which is your cumulative distribution function, is equal to the probability of the random variable, in this case weights or whatever, being less than the value that has been given, X, the argument.

907
01:44:05.270 --> 01:44:10.460
Faculty (Olympus): Right? So if I say f of x, that little x, probability of the quantity being less than x.

908
01:44:11.120 --> 01:44:13.660
Faculty (Olympus): So, it's very similar to person types.

909
01:44:14.430 --> 01:44:16.870
Faculty (Olympus): The fraction of the population less than this.

910
01:44:18.290 --> 01:44:35.040
Manu Gupta .: Oh, okay, so, so, walking on this, like, in the exercise, we had a concern, like, what is the probability such as score is Nesgenâ€¦ more than this thing, or Nesgen score? So, we, draw the, community density graph for that.

911
01:44:35.040 --> 01:44:36.760
Faculty (Olympus): Perfect. Absolutely right.

912
01:44:37.200 --> 01:44:43.469
Faculty (Olympus): You can do the cumulative density plot, but you can also explore it with just the PDF, multiply, and then do that.

913
01:44:43.600 --> 01:44:48.369
Faculty (Olympus): There are many ways, so I will sort of walk through this in little detail. You can also walk through the notebook yourself.

914
01:44:48.480 --> 01:44:52.970
Faculty (Olympus): Right? But there are many ways to do that. But yes, absolutely, you're absolutely correct.

915
01:44:54.240 --> 01:44:55.050
Manu Gupta .: Okay, thankâ€¦

916
01:44:55.350 --> 01:44:59.200
Faculty (Olympus): So, the idea is, it's very powerful, right, that you can do that.

917
01:44:59.390 --> 01:44:59.850
Manu Gupta .: Yes, sir.

918
01:44:59.850 --> 01:45:00.540
Faculty (Olympus): Perfect.

919
01:45:00.860 --> 01:45:01.840
Faculty (Olympus): Roshan?

920
01:45:02.410 --> 01:45:15.730
Roshan Mathane .: Yeah, so my question is regarding the cumulative distribution function. So, is this correct understanding that cumulativeâ€¦ the probability of cumulative distributive function will always be less than or equal to 1, depending on.

921
01:45:15.730 --> 01:45:20.730
Faculty (Olympus): So, can you rephrase? There's no probability of the cumulative distribution function.

922
01:45:21.250 --> 01:45:24.229
Roshan Mathane .: So theâ€¦ itâ€¦ it is adding it up to the 1, soâ€¦

923
01:45:24.230 --> 01:45:29.180
Faculty (Olympus): Yeah, yeah, yeah, but it's not probability of the cumulative distribution. It'll beâ€¦ the words have to be very carefully used, soâ€¦

924
01:45:29.180 --> 01:45:29.860
Roshan Mathane .: Mhmh.

925
01:45:30.160 --> 01:45:32.310
Faculty (Olympus): Yourâ€¦ whatâ€¦ can you rephrase your question?

926
01:45:34.270 --> 01:45:38.570
Roshan Mathane .: So, so when you say, it will always add up to the 1, soâ€¦

927
01:45:38.790 --> 01:45:46.320
Roshan Mathane .: what are we defining the 1 as? Is it a probability of theâ€¦ The wholeâ€¦

928
01:45:46.320 --> 01:45:50.420
Faculty (Olympus): If you write it down, it would be easier if I write it down. So F of Xâ€¦

929
01:45:51.500 --> 01:45:52.709
Faculty (Olympus): Maybe it doesn't open.

930
01:45:57.750 --> 01:46:00.540
Faculty (Olympus): It's defined to be the probability ofâ€¦

931
01:46:00.890 --> 01:46:03.590
Faculty (Olympus): The quantity in question, that is this random variable.

932
01:46:03.590 --> 01:46:04.160
Roshan Mathane .: Mhmh.

933
01:46:06.940 --> 01:46:08.610
Faculty (Olympus): Sound ridiculous.

934
01:46:10.720 --> 01:46:12.130
Faculty (Olympus): That is capitalist.

935
01:46:15.940 --> 01:46:21.019
Roshan Mathane .: And forâ€¦ with cumulative distributive functionâ€¦ distribution function, it will always be 1, right?

936
01:46:21.470 --> 01:46:23.010
Faculty (Olympus): Yeah, because it's a probability.

937
01:46:23.330 --> 01:46:24.680
Faculty (Olympus): It'll always be less thanâ€¦

938
01:46:27.880 --> 01:46:31.049
Roshan Mathane .: Okay, it will beâ€¦ so it, it, itâ€¦

939
01:46:31.050 --> 01:46:31.500
Faculty (Olympus): Stanley.

940
01:46:31.500 --> 01:46:34.299
Roshan Mathane .: It can be based on record, depending on the sample size.

941
01:46:34.300 --> 01:46:35.990
Faculty (Olympus): Yes, it's never gonna be negative.

942
01:46:36.580 --> 01:46:44.080
Faculty (Olympus): And this function is monotonically non-decre- non-decreasing function, right? It can be constant. Yeah. Yeah.

943
01:46:44.460 --> 01:46:44.970
Roshan Mathane .: Yeah.

944
01:46:45.430 --> 01:46:50.109
Faculty (Olympus): So that is the definition of the cumulative distribution. So this gives you an approximate cumulative distribution.

945
01:46:51.730 --> 01:46:53.219
Roshan Mathane .: Yeah, I'm justâ€¦ yeah, thanks.

946
01:46:54.750 --> 01:46:55.480
Faculty (Olympus): Rahul?

947
01:46:56.170 --> 01:47:14.980
Rahul Joshi .: So, Professor, just to reconfirm my understanding, in this CDF, is it a correct understanding that if I choose the random student from this class, the probability that the weight will be 60 or less than 60 will be 0.4?

948
01:47:16.350 --> 01:47:24.319
Faculty (Olympus): Yes, roughly 0.4, yes. Please, again, remember, this isâ€¦ we have only 100 weights here, so this is a very poor approximation, but it is an approximation.

949
01:47:24.610 --> 01:47:32.200
Rahul Joshi .: And follow-up question is, the summation of the area on the left-hand side of 60 is, again, 40% of the total, right?

950
01:47:34.080 --> 01:47:34.900
Faculty (Olympus): Yes.

951
01:47:35.220 --> 01:47:41.100
Faculty (Olympus): The area of the PDF. Area of the PDF becomes thisâ€¦ Cumulative distribution.

952
01:47:42.100 --> 01:47:44.210
Rahul Joshi .: Oh, sorry, can you say it again? It means, let's say if youâ€¦

953
01:47:44.210 --> 01:47:50.540
Faculty (Olympus): You take the probability density function, you're taking the area of this fellow and adding it up, that becomes your cumulative distribution.

954
01:47:52.100 --> 01:47:57.319
Rahul Joshi .: So, so, in this case, in the CDF, if weâ€¦ if we take aâ€¦ if you'reâ€¦ if you draw the vertical line at 60,

955
01:47:57.690 --> 01:48:03.190
Rahul Joshi .: Let's see, okay? What is the area on the left-hand side of the 60 will indicate?

956
01:48:03.190 --> 01:48:08.210
Faculty (Olympus): No, the area is different. So, here, you directly read off the value, this is the probability.

957
01:48:10.100 --> 01:48:13.039
Rahul Joshi .: Okay, so the area is not to be referred in this graph.

958
01:48:14.670 --> 01:48:22.590
Faculty (Olympus): Yeah, here you don't need area, because this is the computed area, this is the probability. This isâ€¦ this is the curve. Capital F of X is the probability less than this.

959
01:48:22.590 --> 01:48:29.000
Rahul Joshi .: Okay, can you scroll up then, in the other graph here? And then here, if you again draw the vertical line at 60.

960
01:48:29.220 --> 01:48:33.890
Faculty (Olympus): This is going to give me the density value, which means I have to now find the area to get the actual problem.

961
01:48:36.350 --> 01:48:42.190
Rahul Joshi .: And then, what exactly this density value indicates, actually, in terms of practical significance here?

962
01:48:42.190 --> 01:48:46.119
Faculty (Olympus): It is like my hand. The simplest way to think of density is like your hand.

963
01:48:46.540 --> 01:48:52.370
Faculty (Olympus): Right? Can you tell me what is the mass of my hand at this point? It's zero, because the point has no area.

964
01:48:53.660 --> 01:48:56.439
Faculty (Olympus): Right? But I can tell you what's the density of my hand.

965
01:48:56.580 --> 01:48:57.419
Faculty (Olympus): At that point.

966
01:48:59.040 --> 01:49:05.759
Faculty (Olympus): So, when you have continuously varying quantities, the probability at a point is a meaningless quantity to us.

967
01:49:06.870 --> 01:49:13.109
Faculty (Olympus): What is the probability that the student's weight is going to be exactly 70.0? It is essentially zero.

968
01:49:13.440 --> 01:49:18.290
Faculty (Olympus): I'm not ever going to find a student who's exactly zero down to infinite decimal places.

969
01:49:18.610 --> 01:49:26.260
Faculty (Olympus): Am I making sense? But if you say, hey, what's the probability of me finding a student between 69.9 and 70.1?

970
01:49:26.380 --> 01:49:28.790
Faculty (Olympus): That is a reasonable number that you will get.

971
01:49:28.920 --> 01:49:30.120
Faculty (Olympus): Am I making sense?

972
01:49:31.170 --> 01:49:39.489
Rahul Joshi .: Sorry, I'm a little confused, like, how to use this graph, actually, so in terms of numbers. If weâ€¦ if we get a value that, if you slightly scroll downâ€¦

973
01:49:39.490 --> 01:49:44.810
Faculty (Olympus): That way, I said, so if you look at this height, multiply by the width, you get the probability in this debug.

974
01:49:47.300 --> 01:49:51.010
Rahul Joshi .: Yeah, but you're anyway getting that exact value in the CDF, right?

975
01:49:51.010 --> 01:49:51.790
Faculty (Olympus): Sure.

976
01:49:51.950 --> 01:49:56.849
Faculty (Olympus): You can use this EDF. I'm not sayingâ€¦ these two are not different graphs. One is constructed from the other.

977
01:49:57.490 --> 01:49:58.120
Rahul Joshi .: Oh, okay.

978
01:49:58.800 --> 01:50:07.349
Faculty (Olympus): There's noâ€¦ this isâ€¦ there's nothing new here that is not here. So from this, you can get that, and from there you can get here, right? So both are the same, they're different ways of looking at the same thing.

979
01:50:08.750 --> 01:50:13.330
Faculty (Olympus): So what you choose to use is up to you. Just that this is a density, and this is aâ€¦

980
01:50:13.440 --> 01:50:14.630
Faculty (Olympus): Kumarative stuff.

981
01:50:16.470 --> 01:50:22.069
Faculty (Olympus): But the density also tells you where things are. Even the cumulative does, but it's a little harder to see sometimes.

982
01:50:22.480 --> 01:50:26.039
Rahul Joshi .: Yeah, can you explain that point again? Actually, I think that isâ€¦ that is what the difference is.

983
01:50:26.280 --> 01:50:27.890
Faculty (Olympus): This is your distribution here.

984
01:50:28.530 --> 01:50:37.039
Faculty (Olympus): This actually tells me the distribution of how my data is looked at. Here, I have to constantly differentiate in my head to find out where the differences are.

985
01:50:38.080 --> 01:50:44.189
Faculty (Olympus): According to this, it'll look like, oh, most probability is here. Can you tell me which region has the highest probability?

986
01:50:49.360 --> 01:50:52.809
Faculty (Olympus): In your class of this thing, 40 to 90.

987
01:50:53.220 --> 01:50:53.870
Siddharth Digambar Kulkarni .: from 17.

988
01:50:53.870 --> 01:50:56.390
Prathamesh Mone: Dumper width. It depends on the number width, is it?

989
01:50:56.390 --> 01:50:57.010
Faculty (Olympus): No, no, no.

990
01:50:57.010 --> 01:50:57.950
Siddharth Digambar Kulkarni .: 27 years old.

991
01:50:57.950 --> 01:51:01.640
Faculty (Olympus): A lot you can actually see here. This is the highest jump that you get.

992
01:51:01.820 --> 01:51:06.269
Faculty (Olympus): Yeah, but I mean, I have to look at height of step. I can just read off the value right here.

993
01:51:12.200 --> 01:51:17.530
Rahul Joshi .: Okay, so is it indicating that 40% of the population.

994
01:51:17.530 --> 01:51:20.430
Faculty (Olympus): No, there's about 40% of the population here.

995
01:51:22.690 --> 01:51:23.390
Rahul Joshi .: aren't food.

996
01:51:23.390 --> 01:51:25.229
Faculty (Olympus): Because it's divided by the bandwidth.

997
01:51:27.690 --> 01:51:31.679
Faculty (Olympus): So identity is a concept you need to be very clear about. If I give you a metal.

998
01:51:32.060 --> 01:51:39.929
Faculty (Olympus): Density of the metal is 7,000 or something. KG per meter cubed. Density of some human arm is, like, 900 or something, 950 of God knows what.

999
01:51:41.390 --> 01:51:44.060
Faculty (Olympus): Density is a different concept from mass.

1000
01:51:46.100 --> 01:51:47.910
Faculty (Olympus): This is why you're getting very confused.

1001
01:51:53.270 --> 01:51:55.679
Faculty (Olympus): So the equivalence is mass is probability.

1002
01:51:56.520 --> 01:52:05.139
Sunil Rawat .: So, Professor, does it mean that, sorry to jump in, that this bar, under 70 shows most of the students will fall under this, the density group?

1003
01:52:05.140 --> 01:52:06.630
Faculty (Olympus): Yes. Yes.

1004
01:52:06.680 --> 01:52:14.190
Faculty (Olympus): So that's what I'm trying to say. So if you look at a distribution, it tells me that, hey, there are very few people here, there are lots of people in thisâ€¦ in this Daba.

1005
01:52:14.200 --> 01:52:27.870
Faculty (Olympus): I can immediately see this. I look at a CDF, I'm like, I'm scratching my head. I'm like, yeah, I have to look at this height. Is this height bigger than this height? I have to start using measuring tape, right? So it's much easier for me to get a sense of the distribution of the density plot.

1006
01:52:27.890 --> 01:52:32.310
Faculty (Olympus): Right? On the other hand, if you want to read off probability values, it's much easier to use a cumulative distribution.

1007
01:52:32.760 --> 01:52:45.229
Faculty (Olympus): So, really, it depends on what you're plotting, right? So there's noâ€¦ it's not like one thing isâ€¦ will do everything. You can do both with the same plot, but some areâ€¦ some things are easier in the CDF, some things are easier in the PDF.

1008
01:52:46.020 --> 01:52:49.400
Sunil Rawat .: Okay, so here we have to look at the steps, how highly.

1009
01:52:49.400 --> 01:52:56.190
Faculty (Olympus): No, this is because you are forcing me to ask that question here. Saying, I give you a CDF, and you tell me where it is.

1010
01:52:56.640 --> 01:52:58.980
Faculty (Olympus): That's because you've asked the question in this fashion.

1011
01:52:59.980 --> 01:53:03.950
Faculty (Olympus): This is the definition of this plot. Cumulative distribution is simply this.

1012
01:53:04.180 --> 01:53:05.710
Faculty (Olympus): Right? Make of it what you will.

1013
01:53:06.150 --> 01:53:08.860
Faculty (Olympus): This is the density plot. Make of it what you want.

1014
01:53:09.360 --> 01:53:17.360
Faculty (Olympus): Right? So now you're asking me questions about how to interpret this, where this is useful, proof, useful for you to understand this, but you're trying to sort of

1015
01:53:17.980 --> 01:53:18.869
Faculty (Olympus): you knowâ€¦

1016
01:53:19.000 --> 01:53:27.889
Faculty (Olympus): push me into a corner and answer questions why this is better than that. I'm not sayingâ€¦ I never made any of those statements. I'm saying this is the cumulative distribution function, this is the density function. That's it.

1017
01:53:27.890 --> 01:53:40.470
Sunil Rawat .: Whyâ€¦ yes, Professor, we understand, but why it is confusing for us that under 19 and 18 in community distribution, we see the higher bars. I mean, those bars, no? Those are higher. They areâ€¦

1018
01:53:40.470 --> 01:53:42.069
Faculty (Olympus): Here, this one.

1019
01:53:42.070 --> 01:53:45.059
Sunil Rawat .: No, no, not here. This we understand, this one here.

1020
01:53:45.200 --> 01:53:56.970
Sunil Rawat .: So you can see the 80 and 90, those bars are higher than the left ones, because it is community, we understand, but how to read? That's what we want toâ€¦

1021
01:53:57.250 --> 01:53:57.830
Faculty (Olympus): So you read it by

1022
01:53:58.470 --> 01:54:14.949
Faculty (Olympus): understand F of X is probability of X less than this. At any point of time you read this, you read this point, it's like, okay, 95% of the, you know, probability of finding a value less than this number, what number, 75, is close to 98%.

1023
01:54:16.060 --> 01:54:17.320
Sunil Rawat .: Okay, okay.

1024
01:54:17.320 --> 01:54:22.430
Faculty (Olympus): Right? Probability of finding less thanâ€¦ like, a Sachin, youâ€¦ I think you only answered this, or somebody else answered this.

1025
01:54:22.550 --> 01:54:39.699
Faculty (Olympus): Oh, somebody else, I think somebody else answered this. Probability of Sachin scoring less than 60 will be this. This is not Sachin scores, right? So maybe I'll quickly go to Sachin scores, maybe make more sense here. So if I did a cumulative plot of this guy, I will be able to tell you, you know, if I say density is true and all of that.

1026
01:54:42.490 --> 01:54:43.930
Faculty (Olympus): It's accumulator.

1027
01:54:45.090 --> 01:54:51.070
Faculty (Olympus): Okay, this is too messy. We'll do that in the next class, but I'll explain it here itself. Probability ofâ€¦

1028
01:54:51.270 --> 01:54:56.549
Faculty (Olympus): This weight in our class, being less than 70, is going to be 0.8.

1029
01:54:57.320 --> 01:54:59.350
Faculty (Olympus): That's the value. I just read it off here.

1030
01:55:00.010 --> 01:55:01.919
Sunil Rawat .: Oh, yeah, got it. Okay.

1031
01:55:01.920 --> 01:55:08.569
Faculty (Olympus): Same way. Probability of me finding somebody less than 100 kgs is 100%. Means everybody in the class is, you know, less than 100 kg.

1032
01:55:09.760 --> 01:55:11.379
Sunil Rawat .: Okay, now what it is.

1033
01:55:11.380 --> 01:55:16.459
Faculty (Olympus): Yeah, and the probability of me finding somebody less than 35 is zero. There's nobody in class.

1034
01:55:17.010 --> 01:55:17.850
Sunil Rawat .: Hmm.

1035
01:55:17.850 --> 01:55:22.170
Faculty (Olympus): And you can see that this directly relates to percentiles as well, right?

1036
01:55:22.590 --> 01:55:25.900
Faculty (Olympus): It's allâ€¦ they're all related.

1037
01:55:26.600 --> 01:55:27.799
Sunil Rawat .: Yeah. Thanks, folks.

1038
01:55:27.800 --> 01:55:28.460
Faculty (Olympus): Guess.

1039
01:55:28.560 --> 01:55:30.000
Faculty (Olympus): Bipin?

1040
01:55:30.500 --> 01:55:32.119
Faculty (Olympus): Oh, sorry, is that,

1041
01:55:32.120 --> 01:55:40.359
Samar .: Yeah, actually, I had a small question, which is just since we are wrapping up this. So, in case CTF, what does densityâ€¦

1042
01:55:40.360 --> 01:55:43.190
Faculty (Olympus): Sorry, is this Rahul? Are you Rahul?

1043
01:55:43.190 --> 01:55:45.120
Samar .: This is somewhere. Okay.

1044
01:55:45.120 --> 01:55:50.040
Faculty (Olympus): Okay, so Iâ€¦ did I answer Rahul's question? I'm confused, because the hand raises are not obvious to me.

1045
01:55:50.040 --> 01:55:54.010
Rahul Joshi .: Yeah, no, no, you answered my question. Let me think over it and come back next.

1046
01:55:54.010 --> 01:55:58.810
Faculty (Olympus): Sure, okay, okay. So, I think whoever stepped in, please ask, and I'll finish it quick.

1047
01:55:59.040 --> 01:56:04.609
Samar .: So on this CDF, like, in PDF, we understand does TD present, like, we are theâ€¦

1048
01:56:04.790 --> 01:56:12.430
Samar .: probabilities concentrated, or let's say volume is concentrated. In case of CDF, what does density would represent, actually?

1049
01:56:12.430 --> 01:56:16.099
Faculty (Olympus): There's no density in PDF, in CDF. I meanâ€¦

1050
01:56:16.100 --> 01:56:18.119
Samar .: It's a cumulative test, theâ€¦

1051
01:56:18.120 --> 01:56:20.209
Faculty (Olympus): It's not cumulative. Cumulative distribution.

1052
01:56:20.210 --> 01:56:22.670
Samar .: Distributive, okay. So the definition.

1053
01:56:22.670 --> 01:56:25.369
Faculty (Olympus): is this. Whatever I have written here is the definition of the CDF.

1054
01:56:25.370 --> 01:56:25.890
Samar .: Okay.

1055
01:56:25.890 --> 01:56:27.699
Faculty (Olympus): I was hoping to finish this, but yeah.

1056
01:56:27.700 --> 01:56:28.650
Samar .: Yeah, thanks.

1057
01:56:28.820 --> 01:56:29.360
Faculty (Olympus): Yep.

1058
01:56:29.590 --> 01:56:34.939
Faculty (Olympus): This is the definition. And it is in terms of propius probability, so this, I think you understand, sir.

1059
01:56:34.940 --> 01:56:35.630
Samar .: Yeah.

1060
01:56:36.420 --> 01:56:37.199
Faculty (Olympus): on that.

1061
01:56:37.330 --> 01:56:38.270
Faculty (Olympus): Bipin?

1062
01:56:38.820 --> 01:56:43.740
Bipin Karyakarte .: Yeah, Professor, if you could go to the box plot the first time we plotted the box plot.

1063
01:56:46.910 --> 01:56:49.899
Faculty (Olympus): Box was after this, right? Yeah. Yeah, yeah.

1064
01:56:49.900 --> 01:57:01.250
Bipin Karyakarte .: Yeah, so I was hoping, actually, at that point in time, if we can take data, proper data, and thenâ€¦ then that would have made me more able to relate to this figure.

1065
01:57:02.470 --> 01:57:04.760
Faculty (Olympus): Well, you want proper data? Look at this fellow.

1066
01:57:08.490 --> 01:57:13.990
Bipin Karyakarte .: Because I didn'tâ€¦ I didn't understand the concept of the box plot itself, that's why I was asking, actually.

1067
01:57:13.990 --> 01:57:17.199
Faculty (Olympus): So, this fellow is the 25 percentile line.

1068
01:57:18.660 --> 01:57:22.200
Faculty (Olympus): Okay, so it looks like less than,

1069
01:57:25.220 --> 01:57:31.730
Faculty (Olympus): It looks like what thisâ€¦ let'sâ€¦ let's assume this is 10 months, 10â€¦ 10 runs, okay? 10 runs.

1070
01:57:32.060 --> 01:57:39.169
Faculty (Olympus): So, 25 percentile of Saxen scores are less than 10 runs. So, he scored a lot of no scores, okay?

1071
01:57:39.990 --> 01:57:40.550
Bipin Karyakarte .: Mhmh.

1072
01:57:40.550 --> 01:57:41.680
Faculty (Olympus): This is the median.

1073
01:57:42.330 --> 01:57:48.619
Faculty (Olympus): Which means 50% of Sachin scores are barelyâ€¦ are basically below 20â€¦ 30, okay?

1074
01:57:48.750 --> 01:57:50.489
Faculty (Olympus): 50% of his course.

1075
01:57:51.440 --> 01:57:58.059
Faculty (Olympus): 75% of his scores Are below this number, whatever it is, 16.

1076
01:57:59.070 --> 01:58:00.380
Faculty (Olympus): Oh, 65.

1077
01:58:01.470 --> 01:58:02.450
Faculty (Olympus): Okay?

1078
01:58:03.470 --> 01:58:04.190
Bipin Karyakarte .: Yup.

1079
01:58:04.190 --> 01:58:06.499
Faculty (Olympus): And this is the mean of his course.

1080
01:58:07.890 --> 01:58:10.440
Faculty (Olympus): Now, what else? What do you need to understand now?

1081
01:58:11.790 --> 01:58:16.140
Bipin Karyakarte .: Honestly, I have not got it. I will have to watch the recording a couple of times.

1082
01:58:16.140 --> 01:58:26.559
Faculty (Olympus): No, no, so that's it, that's all there is to it. That is the plot. This is the plot it's showing you. This fellow here is showing you whiskers. Whiskers is 1.5 times IQR,

1083
01:58:27.510 --> 01:58:31.720
Faculty (Olympus): Away from the 75% there. Do you understand percentiles?

1084
01:58:32.360 --> 01:58:39.480
Bipin Karyakarte .: Yes, to some extent, not fully. I need to brush up on that, but I was just trying to understand the box plot by itself.

1085
01:58:39.480 --> 01:58:42.340
Faculty (Olympus): If you don't understand percentiles, box plots are hard.

1086
01:58:42.790 --> 01:58:46.429
Bipin Karyakarte .: Yeah, that's right. No, I agree. I agree with that. Yeah.

1087
01:58:46.990 --> 01:58:56.029
Faculty (Olympus): So, basically, percentile is a simple idea. It's exactly what I said. 50% of such-end scores are less than 26 or 27.

1088
01:58:56.950 --> 01:58:57.480
Bipin Karyakarte .: Yeah.

1089
01:58:57.480 --> 01:58:59.290
Faculty (Olympus): Take all of his scores, sort them.

1090
01:58:59.410 --> 01:59:05.109
Faculty (Olympus): 50% will be less than 26, or something, whatever that number is. That's the median, that's this plot.

1091
01:59:05.680 --> 01:59:06.510
Bipin Karyakarte .: Okay.

1092
01:59:08.160 --> 01:59:16.140
Bipin Karyakarte .: Okay, fine, I will go through this recording a couple of times, and the first time you plotted box plot now, that is where I will try to focus a bit onâ€¦ try to understand.

1093
01:59:16.140 --> 01:59:19.560
Faculty (Olympus): Yeah, but if you want meaningful data, you may want to look at the Sachin and Kohli.

1094
01:59:19.560 --> 01:59:20.820
Bipin Karyakarte .: Yeah, yeah, that, that, that Iâ€¦

1095
01:59:20.820 --> 01:59:22.819
Faculty (Olympus): Or you play with your own data, it doesn't matter.

1096
01:59:22.820 --> 01:59:25.719
Bipin Karyakarte .: Yes, exactly, exactly. That's what I wanted. Thank you.

1097
01:59:26.370 --> 01:59:28.000
Faculty (Olympus): Sure. Pinaki?

1098
01:59:28.740 --> 01:59:40.449
Pinaki Ghosh .: Good morning, Professor, even though my questions are answered, but I just wanted to reconfirm my understanding. If you can kindly go up for the CDF and PDF, please, the graph, and just, I want to reconfirm here is that.

1099
01:59:40.560 --> 01:59:41.100
Faculty (Olympus): Huh?

1100
01:59:41.100 --> 01:59:49.140
Pinaki Ghosh .: If our objective, if there is a boundary condition, let's say, and the objective is to find what is the probability of students.

1101
01:59:49.280 --> 01:59:56.650
Pinaki Ghosh .: In a given sample size, having a weight less than 60, then CF is the right way of, going by.

1102
01:59:56.650 --> 01:59:56.980
Faculty (Olympus): Yes.

1103
01:59:56.980 --> 02:00:16.710
Pinaki Ghosh .: I'm answering that question. Now, usingâ€¦ if I only have the CDF, and if I want to say that what is the probability of students in a given sample, again, having weight between 60 and 70, then for you, if I have only CDF, then I have to do that, activity of finding that, height between 60 and 70â€¦

1104
02:00:16.710 --> 02:00:17.090
Faculty (Olympus): No, no.

1105
02:00:17.090 --> 02:00:17.500
Pinaki Ghosh .: those, right?

1106
02:00:17.500 --> 02:00:21.139
Faculty (Olympus): So you just have to take the difference between this point and this point. That's it.

1107
02:00:21.640 --> 02:00:23.440
Faculty (Olympus): That'll tell you the values between this.

1108
02:00:23.780 --> 02:00:27.509
Pinaki Ghosh .: But the easier way, again, would be to use PDF, because there.

1109
02:00:27.510 --> 02:00:28.620
Faculty (Olympus): Not necessarily easier.

1110
02:00:28.620 --> 02:00:29.210
Pinaki Ghosh .: Did you see that?

1111
02:00:29.210 --> 02:00:36.559
Faculty (Olympus): easier or not, it's actually easier to do it with the CDF. You just have to take CDF of this value, CDF of this value, difference, and done.

1112
02:00:37.420 --> 02:00:45.370
Faculty (Olympus): The difference of these two, I'll give it to you in one shot. But you can do it with probability mass or probability density function. You can do that.

1113
02:00:45.370 --> 02:00:47.620
Pinaki Ghosh .: Understood, understood, understood. Thank you, Professor.

1114
02:00:47.620 --> 02:00:48.350
Faculty (Olympus): That's so much.

1115
02:00:48.740 --> 02:00:49.770
Faculty (Olympus): Padih shit?

1116
02:00:49.960 --> 02:00:53.169
Faculty (Olympus): So, last two questions. I know there are five questions here, butâ€¦

1117
02:00:53.860 --> 02:00:57.390
Faculty (Olympus): It's already 11.20, and you have a class, right, at 11.30?

1118
02:00:59.390 --> 02:01:03.590
Faculty (Olympus): Yeah, those of you who are done, please leave, you need a break, and go to your class.

1119
02:01:04.870 --> 02:01:07.139
Faculty (Olympus): Yes, Harikshidh, please ask.

1120
02:01:12.790 --> 02:01:13.680
Faculty (Olympus): Okay.

1121
02:01:14.880 --> 02:01:18.770
Faculty (Olympus): Can't hear you. Maybe Ajay can start until you sort your mic. Ajay?

1122
02:01:18.770 --> 02:01:21.380
Ajay kumar Khetan: Yeah, so, can you hear me?

1123
02:01:21.380 --> 02:01:22.000
Faculty (Olympus): Yes.

1124
02:01:22.120 --> 02:01:41.399
Ajay kumar Khetan: My question was, like, when we are creating lists, the type of that list is list, but same thing when we are creating in NP, let's say, a number from 0 to 100, the type is NP array, so both are kind of different things. Can you explain what is the actual difference, and howâ€¦

1125
02:01:41.400 --> 02:01:54.810
Faculty (Olympus): So, I will do that when we do NumPy. I'm going to spend, like, aâ€¦ maybe a class or a class and a half on NumPy in detail. Okay. It'll be clear when we do that. It's a different object entirely. Lists are different. NumPy arrays are entirely different.

1126
02:01:55.120 --> 02:01:55.810
Ajay kumar Khetan: Okay, understood.

1127
02:01:55.810 --> 02:02:06.949
Faculty (Olympus): Right? Lists are very general purpose, they're Python, core Python data structure. NumPy is a separate package that we install, right, and makes available this array data structure.

1128
02:02:07.240 --> 02:02:09.669
Faculty (Olympus): Okay. It's different. They're entirely different.

1129
02:02:09.980 --> 02:02:14.709
Faculty (Olympus): And we'llâ€¦ we'll look at it in detail. I have just sort of skimmed the surface at this point.

1130
02:02:15.590 --> 02:02:16.640
Faculty (Olympus): Siddharth?

1131
02:02:16.920 --> 02:02:24.080
Siddharth Digambar Kulkarni .: One question, very specific question, the whiskers in the box plot, do they indicate the range, or they indicate theâ€¦

1132
02:02:24.080 --> 02:02:37.900
Faculty (Olympus): So they are actually drawn at this minus 1.5 times IQR, unless it exceeds the zero, for example, if it's all positive values, and 1 plus 1.5 times IQR. So take this fellow, put 1.5 IQR, and put on Discover.

1133
02:02:38.130 --> 02:02:49.040
Faculty (Olympus): There's some differences in the way different people plot it, but the idea is the box and whisker gives you a sense of the spread of the data, and tells you how far away things are, where you have outliers.

1134
02:02:49.040 --> 02:02:52.959
Siddharth Digambar Kulkarni .: If it is, if it goes above the whisker, then it's out there, right? Yes.

1135
02:02:52.960 --> 02:02:53.940
Faculty (Olympus): Yes, yes.

1136
02:02:53.940 --> 02:02:58.619
Siddharth Digambar Kulkarni .: Apower, below the whisker, then it's out there. But in the lower plot, in the Sachin plot.

1137
02:02:59.120 --> 02:03:02.200
Siddharth Digambar Kulkarni .: The Sachin plot, the lower.

1138
02:03:02.200 --> 02:03:09.090
Faculty (Olympus): It is truncated at zero, because all the scores are positive, right? You're never going to get an outlier to the left of this.

1139
02:03:09.090 --> 02:03:09.930
Siddharth Digambar Kulkarni .: Psalco.

1140
02:03:09.930 --> 02:03:12.830
Faculty (Olympus): That's just the nature of the data in this particular case.

1141
02:03:13.150 --> 02:03:23.160
Siddharth Digambar Kulkarni .: Okay, okay. So it is the, it is the, plus IQR, that is the, 75% plus 1.5 IQR, that is where the.

1142
02:03:23.160 --> 02:03:29.640
Faculty (Olympus): Yeah, and here it is, they've cut it off at zero, because it doesn't make sense in this plot, because all the values are positive.

1143
02:03:29.850 --> 02:03:34.159
Faculty (Olympus): So, it is assumed that the question, the, you know, quantities are all

1144
02:03:34.490 --> 02:03:36.830
Faculty (Olympus): You know, skewed distribution to the right.

1145
02:03:37.180 --> 02:03:38.980
Faculty (Olympus): So they cut it off at zero.

1146
02:03:38.980 --> 02:03:44.729
Siddharth Digambar Kulkarni .: And in the violin, you don't have these whiskers, right? It gives you just the distribution,

1147
02:03:44.730 --> 02:03:48.270
Faculty (Olympus): Yes, no whiskers. Yeah, it gives you a density function.

1148
02:03:48.490 --> 02:03:49.260
Siddharth Digambar Kulkarni .: Okay.

1149
02:03:49.670 --> 02:03:56.209
Siddharth Digambar Kulkarni .: So, it plots the density of the scores between the highest score and the lowest score.

1150
02:03:56.210 --> 02:03:56.760
Faculty (Olympus): Yup.

1151
02:03:57.220 --> 02:03:57.790
Siddharth Digambar Kulkarni .: Very direct.

1152
02:03:57.790 --> 02:04:01.390
Faculty (Olympus): So it doesn't actually show those individual scores that are beyond it.

1153
02:04:01.960 --> 02:04:02.840
Siddharth Digambar Kulkarni .: Right, right.

1154
02:04:03.600 --> 02:04:04.390
Siddharth Digambar Kulkarni .: Got it.

1155
02:04:05.070 --> 02:04:05.860
Faculty (Olympus): Vamsi?

1156
02:04:07.590 --> 02:04:21.669
Vamsi Krishna Mutnuri .: Sir, my question is that, regarding this box plot in the whiskers, when you say that, you know, the outliers are blown, this is something corresponding to a skewed, bell curve at the standard deviation, like, analogous to that, right?

1157
02:04:21.670 --> 02:04:28.949
Faculty (Olympus): sort of, but yeah, I don'tâ€¦ it's not directly related to those quantities at this point, it's just,

1158
02:04:29.550 --> 02:04:31.609
Faculty (Olympus): You can just think of it as aâ€¦

1159
02:04:32.100 --> 02:04:48.489
Vamsi Krishna Mutnuri .: different method of, quantum percentile method, and then there's a quantile method, and thenâ€¦ yeah. And, sir, my main question was on the density function, the probability function. So, will it be right if I say that

1160
02:04:49.020 --> 02:05:04.809
Vamsi Krishna Mutnuri .: Here, this value of 0.04 or 0.035 can be taken as something like, on the scale of a map, say, 1 kilometer, 1cm to 1000 kilometers. So, it is something like that, where there we are doing multiplication, but here we are seeing it by division with theâ€¦ this thing.

1161
02:05:07.590 --> 02:05:10.140
Faculty (Olympus): No, no, I don't know the analogy well enough.

1162
02:05:10.300 --> 02:05:17.430
Faculty (Olympus): I didn't understand this. See, in a map, you typically see contours, right? And they're equal height contours. That's not what this is.

1163
02:05:19.300 --> 02:05:20.330
Faculty (Olympus): focus on something.

1164
02:05:20.750 --> 02:05:35.680
Faculty (Olympus): count, so the number of people in this bin, right? And then divide it by the total number of people, and then divided by the VIN width. That's really all it is, right? It's the count in each DBA, divided by total numbers, divided by the VIN width. That's it.

1165
02:05:36.490 --> 02:05:42.719
Vamsi Krishna Mutnuri .: Yes, sir, and next, next, the next graph of, distribution, here, the differenceâ€¦

1166
02:05:42.720 --> 02:05:44.940
Faculty (Olympus): Yeah, it is.

1167
02:05:45.130 --> 02:05:56.979
Vamsi Krishna Mutnuri .: Yeah, different heights are because as we are going towards 90 and towards 1, you know, because 70 and 80 come before 90, and they are actually closer to 1, like, you know.

1168
02:05:56.980 --> 02:06:02.490
Faculty (Olympus): No, no, no, no, no, no, this is actuallyâ€¦ the reason they're adding in this way is because of the distribution being this way.

1169
02:06:03.520 --> 02:06:04.459
Faculty (Olympus): That's all.

1170
02:06:05.670 --> 02:06:11.150
Faculty (Olympus): The distribution is like this, so it adds up in this particularâ€¦ this is just a cumulative block, right? Soâ€¦

1171
02:06:12.710 --> 02:06:20.630
Vamsi Krishna Mutnuri .: Understood. But accumulation has to be done according to, like, you know, it has to go from 40, 50, 60, 70, like that. It cannot be random, like, 40, 60.

1172
02:06:20.630 --> 02:06:24.490
Faculty (Olympus): Yeah, yeah, yeah, it is a cumulative plot of this plot, that's it.

1173
02:06:25.300 --> 02:06:27.110
Vamsi Krishna Mutnuri .: Understood, sir. Understood.

1174
02:06:27.250 --> 02:06:27.650
Faculty (Olympus): Yeah.

1175
02:06:27.650 --> 02:06:38.429
Vamsi Krishna Mutnuri .: But, but, sir, in the, in the, you know, this thing, we areâ€¦ I am not able to personally get the Sachin and the Kohli files, interpreted, I don't know why. Though they areâ€¦

1176
02:06:38.430 --> 02:06:40.860
Faculty (Olympus): download them and see, I mean, byâ€¦

1177
02:06:41.970 --> 02:06:42.300
Vamsi Krishna Mutnuri .: Okay.

1178
02:06:42.300 --> 02:06:44.389
Faculty (Olympus): Does it not work on the live interface?

1179
02:06:44.400 --> 02:06:52.500
Vamsi Krishna Mutnuri .: Yeah, it isn't, like, I'm putting the function of that, I mean, the code of that, but it says find not found error, always. I don't know.

1180
02:06:52.840 --> 02:06:54.759
Faculty (Olympus): On your online interface.

1181
02:06:56.190 --> 02:06:59.429
Vamsi Krishna Mutnuri .: Yes, sir, yes, I, I have downloaded this from your,

1182
02:06:59.430 --> 02:07:06.230
Faculty (Olympus): No, no, no, you don't have to download it. I'm saying on the live Jupyter, that interface, PML, Nitin.io.

1183
02:07:06.580 --> 02:07:08.139
Vamsi Krishna Mutnuri .: Yes, yes, that only, sir.

1184
02:07:09.420 --> 02:07:14.790
Faculty (Olympus): You need to say yourâ€¦ no, I don't believe that. I'm gonnaâ€¦ then I'm gonna showâ€¦ We'll say this.

1185
02:07:15.900 --> 02:07:16.660
Faculty (Olympus): Soâ€¦

1186
02:07:27.190 --> 02:07:33.429
Siddhesh Dinesh Kadam .: Hey, I think the answer there is don't put relative reference, I think once you put relativeâ€¦

1187
02:07:33.610 --> 02:07:35.380
Siddhesh Dinesh Kadam .: Remove that related with words.

1188
02:07:38.980 --> 02:07:41.790
Faculty (Olympus): I don't even have this setup. If I did this, this does work.

1189
02:07:42.380 --> 02:07:42.980
Siddhesh Dinesh Kadam .: Yes, sir.

1190
02:07:42.980 --> 02:07:47.630
Vamsi Krishna Mutnuri .: The rest all worked. Those files which are in the data, I couldn't, but I will manage that, sir. Thank you.

1191
02:07:48.750 --> 02:07:49.370
Faculty (Olympus): Which, I meanâ€¦

1192
02:07:49.370 --> 02:07:54.240
Mayengbam Ronendro Singh .: Same for me, Professor, as well. I could not find this in my Jupiter Lite interface as well.

1193
02:07:54.740 --> 02:07:55.720
Faculty (Olympus): you're in data.

1194
02:07:55.720 --> 02:08:11.570
Vamsi Krishna Mutnuri .: Yeah, both the files are in the data, but when we are mentioning theâ€¦ in the code, a searching.txt or coli.txt, I am not able to execute those comments, like, run those comments, saying file not found error.

1195
02:08:12.090 --> 02:08:13.639
Faculty (Olympus): So it works for me here.

1196
02:08:13.640 --> 02:08:16.930
Gaurav Singh .: dot dot slash data.

1197
02:08:17.640 --> 02:08:19.960
Siddhesh Dinesh Kadam .: Yeah, just remove that, it worked for us.

1198
02:08:20.230 --> 02:08:22.450
Faculty (Olympus): Can you show me what you've actually typed?

1199
02:08:23.130 --> 02:08:29.460
Faculty (Olympus): And I'mâ€¦ I justâ€¦ I'm showing you that it works for me live. This is on the actual interface.

1200
02:08:29.650 --> 02:08:30.770
Faculty (Olympus): This is online.

1201
02:08:30.980 --> 02:08:34.259
Faculty (Olympus): I'm just using Chrome browser. It's not on my local machine.

1202
02:08:35.140 --> 02:08:38.929
Faculty (Olympus): So I can't understand why you're not able to execute this, which is running for me.

1203
02:08:39.910 --> 02:08:44.839
Faculty (Olympus): If you downloaded it to your local machine, then there's some path shenanigans that's going on.

1204
02:08:46.380 --> 02:08:49.610
Vamsi Krishna Mutnuri .: Yes, sir. I downloaded it, like, maybe that is the mistake.

1205
02:08:49.610 --> 02:08:55.090
Faculty (Olympus): Oh, then you downloaded it and ran it where? I mean, you ran it on a local JupyterLab instance on your local machine?

1206
02:08:57.800 --> 02:08:58.870
Vamsi Krishna Mutnuri .: Yes, sir, yes.

1207
02:08:59.170 --> 02:09:01.990
Faculty (Olympus): Huh. So then, where did you launch JupyterLab from?

1208
02:09:02.230 --> 02:09:12.540
Faculty (Olympus): If you're saying, see, all paths have to be relative to that, so my suggestion is you download it. Wherever you have downloaded this 05 statistics.ipinv file, same directory you put it. Then you just say, load text.

1209
02:09:12.600 --> 02:09:22.390
Faculty (Olympus): In the same directory, you just say whatever, searching.txt or data.txt, or you put a data directory, then you don't need the dot dot backslash data. It's just relative paths. And use a forward slash.

1210
02:09:23.560 --> 02:09:28.410
Vamsi Krishna Mutnuri .: Understood, sir. So I can use it live on the same thing. I don't need to download and again do all these things.

1211
02:09:28.410 --> 02:09:37.000
Faculty (Olympus): Well, yeah, youâ€¦ it'll be good for you to do it yourself, so good. Yeah, certainly you can do it on this. So, when I'm teaching the class, you don't have to, you know.

1212
02:09:37.290 --> 02:09:39.470
Faculty (Olympus): breaking your head with path through.

1213
02:09:39.930 --> 02:09:40.490
Faculty (Olympus): Stuff.

1214
02:09:40.490 --> 02:09:41.690
Vamsi Krishna Mutnuri .: understood that understood tanks.

1215
02:09:41.690 --> 02:09:45.070
Faculty (Olympus): And then, of course, you can try to resolve this with the TAs this evening.

1216
02:09:45.350 --> 02:09:46.170
Faculty (Olympus): Go and check.

1217
02:09:47.070 --> 02:09:47.590
Vamsi Krishna Mutnuri .: Shouldâ€¦

1218
02:09:47.590 --> 02:09:52.480
Faculty (Olympus): Alright, you have to go for your class, so I will stop here. See you next Wednesday.

1219
02:09:53.030 --> 02:09:54.100
Faculty (Olympus): Bye-bye.

1220
02:09:54.540 --> 02:09:56.260
Amlan Sarkar .: Thank you very much. Thank you.

1221
02:09:56.260 --> 02:09:56.770
Vamsi Krishna Mutnuri .: Break this up.

1222
02:09:56.770 --> 02:09:57.750
Amlan Sarkar .: Thank you, sir.

1223
02:09:57.750 --> 02:09:59.000
Faculty (Olympus): I have fun.

