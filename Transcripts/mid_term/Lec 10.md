WEBVTT

1
00:08:13.390 --> 00:08:14.830
Faculty (Olympus): Good evening, everyone.

2
00:08:17.020 --> 00:08:18.309
Kedar Digambar Gokhale .: Loonings up.

3
00:08:20.880 --> 00:08:22.079
Advait Ketkar: Good evening, sir.

4
00:09:16.280 --> 00:09:24.840
Faculty (Olympus): Okay, so, very quickly, if someone has questionsâ€¦ Please raise your hands, andâ€¦ Stop, sharpen.

5
00:09:25.400 --> 00:09:26.620
Faculty (Olympus): 2-3 minutes.

6
00:09:26.780 --> 00:09:28.109
Faculty (Olympus): And then we'll get started.

7
00:09:28.580 --> 00:09:34.970
Charu .: Hey, hi, Professor, good evening. I have another request, can you please, extend that mock test?

8
00:09:35.220 --> 00:09:36.489
Charu .: This is awesome.

9
00:09:36.950 --> 00:09:41.200
Faculty (Olympus): Oh, you want mock tests forâ€¦ Sorry?

10
00:09:42.910 --> 00:09:44.880
Charu .: Sorry, I got confused, sorry.

11
00:09:48.380 --> 00:09:51.060
Faculty (Olympus): Any other questions? If not, I'll start.

12
00:09:55.900 --> 00:09:57.610
Faculty (Olympus): Any more questions?

13
00:09:57.830 --> 00:10:04.760
Faculty (Olympus): 1, 2, 3â€¦ okay, we're done. So I'm going to start today, because we have a lot of ground to cover, andâ€¦

14
00:10:05.170 --> 00:10:10.710
Faculty (Olympus): I will have questions in between, and we'll also stop for questions at the end.

15
00:10:11.920 --> 00:10:21.709
Charu .: Okay, I'm so sorry for interrupting again. Actually, I was in an office meeting, so I won'tâ€¦ can you extend that, mock quiz, for oneâ€¦ one more day?

16
00:10:21.980 --> 00:10:25.000
Faculty (Olympus): So the mock quiz is just to make sure you get everything working.

17
00:10:25.000 --> 00:10:29.499
Charu .: But it is a mandatory, so I'm in a meeting till, you know, 11.

18
00:10:29.500 --> 00:10:30.220
Faculty (Olympus): Okay.

19
00:10:30.460 --> 00:10:30.780
Charu .: Soâ€¦

20
00:10:30.780 --> 00:10:39.919
Faculty (Olympus): Fine, you take it, you'll ask them to extend it, but if you have any issues, you need to have them resolved by tonight, because we have a special TA session, 9.30 to 11.

21
00:10:40.670 --> 00:10:47.590
Faculty (Olympus): If you don't resolve it by this day, and you have issues on the day of the exam, it's going to be a problem for you.

22
00:10:48.540 --> 00:10:53.039
Charu .: Okay, just extend for one day, I'll figure out if I'll stick, I'llâ€¦

23
00:10:53.330 --> 00:10:55.870
Faculty (Olympus): Yeah, I'll have to message the Teasâ€¦

24
00:10:55.870 --> 00:10:56.520
Charu .: Thank you so much.

25
00:10:56.520 --> 00:10:58.929
Faculty (Olympus): Is there a TA present here today?

26
00:11:00.550 --> 00:11:02.230
Faculty (Pranith): Yes, sir, I'm here, Iâ€¦

27
00:11:02.230 --> 00:11:06.100
Faculty (Olympus): Great. So, can you just remind me, or can you extend the deadline, please?

28
00:11:06.100 --> 00:11:07.549
Faculty (Pranith): Yes, sir, I'll extend it.

29
00:11:07.550 --> 00:11:09.370
Faculty (Olympus): Okay, thank you.

30
00:11:11.650 --> 00:11:25.630
Faculty (Olympus): Okay, I don't think there are any other questions, so let's get cracking. I'll quickly wrap up what we left behind the last class. I don't know if the TAs covered it during the TA session. Was it covered, the TA session?

31
00:11:28.770 --> 00:11:47.120
Faculty (Olympus): Okay, no one says anything, so I'm assuming it's not. So what we've looked at so far is NumPy basics. Basically, we looked at, you know, elementary operations with NumPy, slicing, array creation, we looked at multidimensional arrays, then we looked at image processing, solution of linear systems, and then we looked at some advanced concepts.

32
00:11:47.250 --> 00:11:51.630
Faculty (Olympus): So, I'm gonna skip a lot of this, except, of course, I need the imports.

33
00:11:53.640 --> 00:11:58.650
Faculty (Olympus): reportsâ€¦ Let me just go over very quickly the advanced material.

34
00:11:58.980 --> 00:12:01.520
Faculty (Olympus): Okay, this is done, dun dun-dun dun.

35
00:12:04.530 --> 00:12:10.600
Faculty (Olympus): So we looked at least squares. We'll be looking at least squares very soon, in a couple of classes when we start regression.

36
00:12:11.220 --> 00:12:15.819
Faculty (Olympus): So I don't think you'll forget it by then, so it should be alright.

37
00:12:16.130 --> 00:12:16.680
Lad Prachikumari Vijaykumar .: Yes, sir.

38
00:12:16.680 --> 00:12:18.690
Faculty (Olympus): Broadcasting. Yes, very quickly.

39
00:12:18.690 --> 00:12:23.130
Lad Prachikumari Vijaykumar .: Masquerade and mask, could you please just,

40
00:12:23.130 --> 00:12:37.359
Faculty (Olympus): I'm gonna do that. I'm gonna do that. I didn't cover that last class, and it doesn't look like the TSM Panet, so I'll quickly do that. So last class we looked at, we spent a lot of time on broadcasting and the broadcasting rules. We looked at special indexing and mass indexing.

41
00:12:37.410 --> 00:12:47.699
Faculty (Olympus): The last topic was left behind, I'll quickly cover that right now. And the idea behind broadcasting is, whenever there's an operation between two NumPy arrays.

42
00:12:48.110 --> 00:13:05.319
Faculty (Olympus): In fact, it's not just NumPy arrays. Even PyTorch arrays, TensorFlow arrays, the same kind of concepts are used. What is done is the shapes are compared element-wise, starting with the rightmost dimension, going to the left. And two dimensions are compatible if they are either equal, or one of them is one, or one of them is not array.

43
00:13:05.780 --> 00:13:23.449
Faculty (Olympus): Okay, so this allows us to do all nice things like these trivial things, as well as a lot more complicated cases like this. You have an image, you have a scale, you have a result, you have these very complicated four-dimensional arrays, and so on and so forth. So we looked at many of these. This is another example.

44
00:13:23.550 --> 00:13:39.339
Faculty (Olympus): We looked at a whole bunch of these, we spent a lot of time, I'm not gonna redo this. And towards the end, I showed you that it's very useful sometimes to reshapeâ€¦ to reshape on the fly another array, and the trick to do that is to, wherever you want the new dimension, you can basically put a none.

45
00:13:39.820 --> 00:13:42.390
Faculty (Olympus): Or a NP.no access.

46
00:13:43.300 --> 00:14:03.070
Faculty (Olympus): What this lets you do is, it lets you reshape one of the arrays so that you can essentially do an auto-product, which means one of them becomes four elements, the other is 3, 1, for example, then the 1 and the 4 are compatible, and so, essentially, you will end up with 4 columns or 4 rows, depending on what operations you do and what order you do the operations.

47
00:14:03.200 --> 00:14:07.400
Faculty (Olympus): So, this is something that's very useful, so it's a trick that is useful to keep in mind.

48
00:14:07.910 --> 00:14:20.029
Faculty (Olympus): So the reason a lot of this is useful is, instead of writing for loops, you can write what is called vectorized code. And this vectorized code can be extremely efficient, because it's usually implemented in a lower-level program.

49
00:14:21.750 --> 00:14:38.299
Faculty (Olympus): So, this is, again, commonly used, and even if, you know, you're saying, no, my programming language supports looping, that's fine. Even if you're going to do that, if you want to use something like, say, PyTorch or TensorFlow, you may not be in a position to do that. So, again, it's a good idea to do this.

50
00:14:45.770 --> 00:14:51.620
Faculty (Olympus): There seem to be some chat questions which are not raised with the hands, so Iâ€¦

51
00:14:51.770 --> 00:14:53.679
Faculty (Olympus): Don't know what to do about this.

52
00:14:55.390 --> 00:15:11.639
Faculty (Olympus): See, unfortunately, I can't quite do a revision for your quiz, because this quiz is just some 5-mark quiz. I still have so much to cover. I have to do, you know, text processing, dictionaries, pandas, scikit-learn, there's a lot of important concepts that need to be done.

53
00:15:11.800 --> 00:15:15.160
Faculty (Olympus): So, you know, I don't think it makes sense for me to do a revision.

54
00:15:15.390 --> 00:15:22.149
Faculty (Olympus): Easiest thing for you to do is take the notebooks, shove it into Notebook LM or something like that, and get a summary. That's a good start.

55
00:15:22.640 --> 00:15:28.670
Faculty (Olympus): And you can always revise the video lectures at 2x, or whatever speed that you want to do, especially for concepts that were difficult.

56
00:15:29.490 --> 00:15:36.660
Faculty (Olympus): Alright, so that is my suggestion to you, because it doesn't make sense for me to repeat the same thing. We spent quite a bit of time last class on this.

57
00:15:37.430 --> 00:15:56.299
Faculty (Olympus): The next thing we talked about was special indexing. The idea here is you can take arbitrary indices, just be aware that if you do this, the resulting array may notâ€¦ will not be a view, may not be a view of the original array. So very unlikely it's going to be a view, it will be a copy. In the other cases, you know, broadcasting and other things, things are, you know, copies are not made.

58
00:15:56.890 --> 00:16:07.390
Faculty (Olympus): Then we looked at, you know, similar cases with multidimensional indexing. This is, again, slightly more advanced, it doesn't really matter, it's okay. Just important that you know this.

59
00:16:07.980 --> 00:16:17.130
Faculty (Olympus): However, the indexing with a Boolean array, which is called masked indexing, this is extremely useful, very important, and something that you will be looking at even when you do Pandas.

60
00:16:17.140 --> 00:16:33.099
Faculty (Olympus): And the idea here is, just recall that if you have an umpire array and you do a logical operation like this, you know, A greater than 4, you'll find that every value is either false or true. So you don't get a single Boolean, but you get a set ofâ€¦ you'll get an array of booleans matching the, operands that you have.

61
00:16:33.100 --> 00:16:37.910
Faculty (Olympus): thisâ€¦ for example, if I have an array here and another array here, these two will be broadcast.

62
00:16:37.930 --> 00:16:39.989
Faculty (Olympus): To an equivalent,

63
00:16:40.080 --> 00:16:47.929
Faculty (Olympus): Set ofâ€¦ rather, both of the shapes would be broadcast to an equivalent shape, and then the operation would be performed at the limit cost.

64
00:16:48.440 --> 00:16:53.530
Faculty (Olympus): So again, broadcasting is used even here. You just don't see it, it's behind yourâ€¦ behind the back.

65
00:16:53.950 --> 00:17:01.920
Faculty (Olympus): The important thing is, if you want to just find the elements where this is true, you simply say A of B, and you'll get this resulted.

66
00:17:02.510 --> 00:17:14.960
Faculty (Olympus): The important thing to keep in mind here is, when you want to combine logical operations of this kind, that is, element-wise operations, you must use bitwise operations in order to assemble them together.

67
00:17:15.069 --> 00:17:20.349
Faculty (Olympus): If you use A and D or OR, you will get an error, and it won't rule what you're expecting.

68
00:17:21.720 --> 00:17:32.750
Faculty (Olympus): Okay, so I think this is where we stopped. I did not cover this. I'll quickly cover this in, you know, 10 minutes. So I'll stop here for a few questions. So, varun and Rahulâ€¦ varun, please start.

69
00:17:33.120 --> 00:17:44.999
varun kumar .: Yes, Professor, good morning, good evening. So, regarding that, you know, quiz, that assignment which is given, I was trying to solve one of the question number 3, which is on broadcasting rule.

70
00:17:45.270 --> 00:17:52.610
varun kumar .: Okay. I tried a good, I put quite a good effort on that, understanding, you know, the question and all.

71
00:17:52.680 --> 00:18:08.559
varun kumar .: And felt like, I still have doubt, understanding broadcasting, and how the operation happens on the, you know, when broadcasting happens, subtraction, multiplication, and all that. The question is asking about the Euclidean distance.

72
00:18:08.790 --> 00:18:15.159
varun kumar .: So, you know, is there any, you know, suggestion you can give me so that I can get.

73
00:18:15.160 --> 00:18:15.710
Faculty (Olympus): It's so wonderful.

74
00:18:15.710 --> 00:18:16.210
varun kumar .: Simple.

75
00:18:16.210 --> 00:18:23.259
Faculty (Olympus): The thing is, you can actually revisit the video that we've already done, and watch over the parts that you think are difficult.

76
00:18:24.120 --> 00:18:28.190
Faculty (Olympus): So, sometimes you may not understand because the language is a little confusing to you.

77
00:18:28.610 --> 00:18:36.220
Faculty (Olympus): So Euclidean distance is just the distance between two. So, if I give you a set of values, another set of values, I need to find the pairwise distance of these modules.

78
00:18:36.530 --> 00:18:40.499
Faculty (Olympus): So, one way of doing this is, you basically broadcast one of them

79
00:18:40.750 --> 00:18:45.239
Faculty (Olympus): Give it another access, and then do the operation. Then you'll get pairwise.

80
00:18:45.750 --> 00:18:46.809
Faculty (Olympus): Not all of them.

81
00:18:49.540 --> 00:18:50.360
varun kumar .: Okay.

82
00:18:50.810 --> 00:18:54.840
Faculty (Olympus): So, for example, if you do np.arrange, Say a 5.

83
00:18:55.480 --> 00:19:01.319
Faculty (Olympus): I get this, right? Now, if I do NP.Arange, plus NP.A.

84
00:19:02.500 --> 00:19:03.350
Faculty (Olympus): Hmm?

85
00:19:06.060 --> 00:19:06.939
Faculty (Olympus): to do it.

86
00:19:08.310 --> 00:19:10.170
Faculty (Olympus): And then they sayâ€¦

87
00:19:13.210 --> 00:19:14.050
Faculty (Olympus): Sweet.

88
00:19:19.510 --> 00:19:23.999
Faculty (Olympus): Notice what it does. Pay attention to what it does, and then things will be clear to you.

89
00:19:24.910 --> 00:19:33.749
Faculty (Olympus): All I've done here is I've just taken the same thing, I've taken two arrays, which are just 5 elements each, but I reshape one of them, and I get, you know, 5 across 5 elements, okay?

90
00:19:34.070 --> 00:19:37.759
Faculty (Olympus): So folks, sorry, I need a one-minute break here.

91
00:19:38.930 --> 00:19:41.509
Faculty (Olympus): Iâ€¦ I need to attend to something.

92
00:19:41.640 --> 00:19:44.279
Faculty (Olympus): At home, just one second, I'll be right back.

93
00:19:44.910 --> 00:19:45.650
varun kumar .: Yes, sir.

94
00:20:52.210 --> 00:20:53.470
Faculty (Olympus): My apologies.

95
00:20:54.550 --> 00:20:59.119
Faculty (Olympus): Okay, soâ€¦ varun, does this make things clearer?

96
00:21:00.040 --> 00:21:09.190
varun kumar .: Yeah, I mean, this is, this is two-dimensional array, so I was able to get what went into three-dimensional, so I'll do some more reports.

97
00:21:09.190 --> 00:21:16.049
Faculty (Olympus): When that happens. So in three dimensions, you'll end up with one more dimension. You have a matrix, two-dimensional matrix, and imagine you stack this in this direction.

98
00:21:18.200 --> 00:21:24.449
Faculty (Olympus): Okay? So, sometimes this is difficult, but okay, maybe you can even ask in the TA session if you have a specific question.

99
00:21:25.230 --> 00:21:28.910
Faculty (Olympus): Okay? There's a TA Session 930 to 11.

100
00:21:30.050 --> 00:21:31.020
Faculty (Olympus): Rahul?

101
00:21:32.120 --> 00:21:43.440
Rahul Joshi .: Sir, just one question, if you scroll slightly up where you have shown A of B. In this case, whether B has to be a Boolean, whenever we can do it, or what is the exact,

102
00:21:44.210 --> 00:21:47.340
Faculty (Olympus): It depends on what you're wanting. If you want a mastery, it has to be a Boolean.

103
00:21:47.480 --> 00:21:53.169
Faculty (Olympus): If you want, any index, special indexing will also work, right? So you can give any valid index here, and that will pull it out.

104
00:21:54.270 --> 00:21:56.950
Faculty (Olympus): This is the specific example of a Boolean array.

105
00:21:59.320 --> 00:22:03.009
Rahul Joshi .: So if it is a non-Boolean array, what exactly will be the operation performed?

106
00:22:03.010 --> 00:22:10.589
Faculty (Olympus): It depends, right? If it depends. So, if you ask me a question of someâ€¦ you go and give me a hypothetical case, give me a specific case, only then I can answer the question.

107
00:22:10.700 --> 00:22:29.809
Faculty (Olympus): I've seenâ€¦ I've shown you many indices, right? I can show you single index is an integer. If you give a floating point index, it's an error. If you give me a slice, it'll give you what a slice is. If you give me a set of integers, it'll give you something. If you give me a two-dimensional set of integers, it'll give me something else, right? So, without you telling me what the question is, I can't answer the question.

108
00:22:30.410 --> 00:22:36.339
Rahul Joshi .: Yeah, so actually my question is, what exactly A of B means in, in, in, conceptually, actually?

109
00:22:38.190 --> 00:22:43.629
Faculty (Olympus): So, wherever this conditional is true, it will return thoseâ€¦ it will give you those values.

110
00:22:47.560 --> 00:22:48.060
Rahul Joshi .: Yeah, soâ€¦

111
00:22:48.060 --> 00:22:52.780
Faculty (Olympus): However, this condition is true, you will get back all of the values of A, where this condition is true.

112
00:22:53.390 --> 00:23:03.249
Rahul Joshi .: Yeah, so if it is a Boolean array as a B, then it is easier to visualize, because it's a true or false. But if it's another array, a non-Boolean, a regular array.

113
00:23:03.510 --> 00:23:05.929
Rahul Joshi .: Then it will not work, right, in that way?

114
00:23:07.860 --> 00:23:13.140
Faculty (Olympus): That's what I said, right? If you tell me a non-Boolean array, if I give you an array of strings, it will not work.

115
00:23:13.780 --> 00:23:20.199
Faculty (Olympus): So, you need to have a more specific question. You're asking me some question which is very vague. You want to be precise about your question, then I can answer.

116
00:23:21.540 --> 00:23:24.070
Faculty (Olympus): If you give me something else, there are multipleâ€¦

117
00:23:24.070 --> 00:23:25.339
Rahul Joshi .: few things, actually, than I.

118
00:23:25.340 --> 00:23:32.350
Faculty (Olympus): Yes, yes, yes. If I give you a Boolean array, this is what it's gonna do. If you say, no, I'll give you something else, it depends on what that something else is.

119
00:23:36.040 --> 00:23:36.720
Rahul Joshi .: Thank you, Sachvi.

120
00:23:36.720 --> 00:23:38.000
Faculty (Olympus): Sure. Savalo?

121
00:23:39.270 --> 00:23:54.190
Savalo Naroji: Yeah. Hi, sir. I have a question regarding, like, are we supposed to know these formulas for Euclidean distance and all, or will there be something which will be provided if anything comes in exam?

122
00:23:54.810 --> 00:23:57.879
Faculty (Olympus): Euclidean distance, wellâ€¦

123
00:23:57.880 --> 00:23:58.260
Savalo Naroji: Jesse.

124
00:23:58.260 --> 00:24:03.800
Faculty (Olympus): know this? But otherwiseâ€¦ Otherwise, the questions will be such that it is not too difficult.

125
00:24:04.370 --> 00:24:09.050
Savalo Naroji: Okay, and what about the metrics operations? Are we supposed to know?

126
00:24:10.010 --> 00:24:12.200
Faculty (Olympus): Basic operations, you absolutely should know.

127
00:24:13.210 --> 00:24:15.240
Savalo Naroji: No, I mean, like, such, kind ofâ€¦

128
00:24:15.240 --> 00:24:18.470
Faculty (Olympus): Algebra? No, I don't expect that you know Indian algebra.

129
00:24:19.430 --> 00:24:25.749
Savalo Naroji: Okay, that somethingâ€¦ anything that needs to be calculated will be provided as a part of Kushal, right?

130
00:24:26.100 --> 00:24:27.460
Faculty (Olympus): To some extent, yes.

131
00:24:28.790 --> 00:24:30.850
Savalo Naroji: Okay, yeah, itâ€¦ Thanks!

132
00:24:30.850 --> 00:24:33.710
Faculty (Olympus): some extent, whatever. We can't give everything as, you know.

133
00:24:34.960 --> 00:24:36.429
Savalo Naroji: No, no, no, not like that.

134
00:24:36.430 --> 00:24:46.119
Faculty (Olympus): So, to the large extent, we will try to make it so that, you know, we don't expect you to remember that I say, singular valid decomposition of this, and interpret this in some way. We've not taught you that in class. We're not going to sort ofâ€¦

135
00:24:46.340 --> 00:24:47.900
Savalo Naroji: Yeah, something sort ofâ€¦ Let me mention.

136
00:24:48.010 --> 00:24:53.239
Savalo Naroji: Where it has a complex formula and it has a name, then are we supposed.

137
00:24:53.240 --> 00:24:57.220
Faculty (Olympus): So this is not an exercise, a quiz is not meant to be a test of your memory.

138
00:24:57.590 --> 00:24:57.930
Savalo Naroji: Okay.

139
00:24:57.990 --> 00:25:06.349
Faculty (Olympus): quizzes, but the memory will be necessary if you're writing code. So if you've been doing the assignment systematically, and you're able to do it without using an AI agent.

140
00:25:06.730 --> 00:25:14.110
Faculty (Olympus): then you should be fine. But if you've been just using an AI agent or just watching without doing or typing, you will suffer in the course. That I'm warning you.

141
00:25:14.540 --> 00:25:15.200
Savalo Naroji: Yeah.

142
00:25:15.230 --> 00:25:23.609
Faculty (Olympus): So the whole thing has been designed in such a way that you'reâ€¦ we're kind of pushing you to force you to do some code. You may say that, hey, this is not necessary anymore.

143
00:25:24.100 --> 00:25:37.379
Faculty (Olympus): But we can argue about that. I don't think that that is the case. You do need to do a little bit. Then you use an agent that's later on, later second half of the course, you know, Vinay will ask you to use agents, that's perfectly alright. But you need to know what you're doing, that's the idea.

144
00:25:37.760 --> 00:25:47.189
Faculty (Olympus): And if the agent gives you some code, you should be able to at least read it. It can't be like, I don't know, Ajit Nay DIA code, I don't know what it means. That should not be the case. That's the reason I'm forcing you to do things.

145
00:25:48.100 --> 00:26:04.019
Faculty (Olympus): So the intention is that the bare minimum you should remember, okay? But all of the questions will be given so that you have a JupyterLab instance. You will not beâ€¦ you'll only have the live documentation that you get if you did not have an agent, you don't have an internet connection.

146
00:26:04.420 --> 00:26:05.120
Faculty (Olympus): Butâ€¦

147
00:26:05.350 --> 00:26:13.860
Faculty (Olympus): It's not like you'll just have one text box and you have to write the code. Yes, you'll have a Jupyter notebook, so you can try, you can experiment, you can cut-paste from that to this, but nothing else.

148
00:26:15.530 --> 00:26:24.219
Anuj Kumar Gupta .: Sir, sorry, I mean, last thing, actually. Last question, on the part is, like, when we are talking about Jupyter, it says, I mean, the TAs might be into the call.

149
00:26:24.470 --> 00:26:27.430
Anuj Kumar Gupta .: It's not working seamlessly, circuit.

150
00:26:27.620 --> 00:26:34.950
Anuj Kumar Gupta .: So, it's not working with the copy-paste, actually. Even if you use a Jupyter, right, in theâ€¦

151
00:26:35.420 --> 00:26:38.920
Anuj Kumar Gupta .: Mmm, secure web, at least.

152
00:26:38.920 --> 00:26:41.930
Abhineet Bansal: Copy-paste is not working, sir, from Jupyter toâ€¦

153
00:26:42.310 --> 00:26:46.949
Faculty (Olympus): Okay, can you table all of these sort of questions to after the class? I don't want to, again, waste.

154
00:26:46.950 --> 00:26:48.729
Anuj Kumar Gupta .: Yeah, yeah, so, sure.

155
00:26:48.730 --> 00:26:54.070
Faculty (Olympus): questions, and now there are quiz questions. I don't want to answer any quiz questions now. I will not answer any quiz questions, no.

156
00:26:54.070 --> 00:26:57.970
Charu .: So, sorry for interrupting, is it possible to even postpone quiz for.

157
00:26:57.970 --> 00:26:58.440
Faculty (Olympus): No.

158
00:26:58.440 --> 00:26:58.970
Charu .: weâ€¦

159
00:26:59.140 --> 00:27:05.859
Faculty (Olympus): I will not answer any questions of that kind no. Please ask any of such questions about quizzes at the end of the class. Last class, I was told

160
00:27:06.030 --> 00:27:12.939
Faculty (Olympus): Too many of these questions are coming up during class. There are 200 people here waiting. Please don't ask me any quiz questions now.

161
00:27:15.690 --> 00:27:18.339
Faculty (Olympus): And postponing now is, like, very difficult.

162
00:27:18.800 --> 00:27:21.570
Faculty (Olympus): If you've wanted to postpone, you should have told us before.

163
00:27:21.810 --> 00:27:27.290
Faculty (Olympus): You mean things were already communicated. Anyway, any technical questions about broadcasting or anything else?

164
00:27:30.480 --> 00:27:42.209
Faculty (Olympus): All right, okay, so what I want to finish now is, you know, creating a grid of grid of points. This is just a useful convenience. Supposing, I say, create a grid of points from minus 2 to

165
00:27:42.310 --> 00:28:00.699
Faculty (Olympus): minus 2 comma 2 to plus 2 comma 2, right? So imagine I want to create a set of points in this, like a graph sheet, and what I want to do is, at every single point, I want to createâ€¦ I want to sample, say, some function. This could be some analytical function. For example, I could say sine of O x into cosine of Y.

166
00:28:01.020 --> 00:28:06.720
Faculty (Olympus): How do you know how this thing looks, right? Or, you know, things like that, if you want to create, how would you create it?

167
00:28:06.920 --> 00:28:15.809
Faculty (Olympus): So, in many contexts, this is useful. So, let's say I give you a function to minimize, a two-dimensional function to minimize. First thing you would want to do is say I want to plot it.

168
00:28:16.030 --> 00:28:17.479
Faculty (Olympus): How do you plot it?

169
00:28:17.590 --> 00:28:30.569
Faculty (Olympus): It turns out it's very easy to do with these sort of things with NumPy. So when you do optimization and things like that next semester, if you do it, right, these are useful tricks to keep in, you know, with you, so that you can quickly plot things like this.

170
00:28:31.200 --> 00:28:47.319
Faculty (Olympus): So here the exercise that I'm working out here is there's aâ€¦ I want to create a box of 25 across 25 products in this region from minus 2 to plus 2, and minus 2 to plus 2 on Y axis. So imagine minus 2 to plus 2 and minus 2 to plus 2, and thatâ€¦

171
00:28:47.500 --> 00:28:48.380
Faculty (Olympus): You know?

172
00:28:48.720 --> 00:28:54.209
Faculty (Olympus): segment of your XY plane, I want to create a uniformly spaced set of coins.

173
00:28:54.470 --> 00:29:08.270
Faculty (Olympus): Okay, so there are numâ€¦ very simple way that you have already seen to do this is, let's define the origin to be X naught y naught is minus 2 comma 2, minus 2 comma minus 2. I take n is 25 points, because it's the same NXNY, I'm not

174
00:29:08.430 --> 00:29:16.010
Faculty (Olympus): Because I want the same X and Y. I'm just taking N is 25. I'm saying DX and DY, which is the delta X, okay?

175
00:29:16.800 --> 00:29:18.829
Faculty (Olympus): is 4 by n-1.

176
00:29:19.470 --> 00:29:20.200
Faculty (Olympus): Meh?

177
00:29:22.290 --> 00:29:23.560
Faculty (Olympus): And then we haveâ€¦

178
00:29:23.680 --> 00:29:33.679
Faculty (Olympus): this np.from function, okay? So once again, this is a revision, maybe. Np.from function takes a single function, which takes two arguments, and in this case, I'm using a lambda function.

179
00:29:33.850 --> 00:29:46.539
Faculty (Olympus): It takes two arguments, and the arguments that will be passed to it are the indices, right? And the indices are determined from the shape, in this case, n cross n. So I want 25 plus 25. So it will basically start giving me 0, 1, 2, 3.

180
00:29:46.750 --> 00:29:51.939
Faculty (Olympus): So what this fellow returns is X values will be X naught plus i into dx.

181
00:29:52.120 --> 00:29:52.860
Faculty (Olympus): Right?

182
00:29:53.670 --> 00:30:06.109
Faculty (Olympus): For given any J, the value is simply going to depend on I. Given any i, the value is simply going to depend on J for the Y values. So I get X is equal to lambda i comma j, X naught plus idx, n comma i.

183
00:30:07.100 --> 00:30:16.229
Faculty (Olympus): So now X will be an in-cross NRA, having the X coordinates, so it'll be minus 2, whatever, minus 1.9, so on and so forth, all the way to 2.

184
00:30:16.440 --> 00:30:21.430
Faculty (Olympus): Then again, minus 2, minusâ€¦ right? If you think of the X coordinate for all of these points, that's what you're going to get.

185
00:30:22.200 --> 00:30:32.369
Faculty (Olympus): Same way for the Y coordinates, you're going to be starting at minus 2, all the way to plus 2, then I come back, minus 2, all the way to plus 2, right? That is exactly what this fellow is going to create.

186
00:30:33.340 --> 00:30:42.639
Faculty (Olympus): So maybe if I make this a 5 cross 5 fellow, you can see the values that show you this. X is going to be like this. Minus 2, minus 1, 0, andâ€¦

187
00:30:42.920 --> 00:30:44.890
Faculty (Olympus): NY is gonna be?

188
00:30:45.250 --> 00:30:46.650
Faculty (Olympus): Minus little one.

189
00:30:46.890 --> 00:30:47.910
Faculty (Olympus): Can you do that.

190
00:30:48.430 --> 00:30:49.490
Faculty (Olympus): Opposite dot.

191
00:30:49.850 --> 00:30:54.639
Faculty (Olympus): Okay, so let me go back to 25, so we can block this nicely.

192
00:30:54.900 --> 00:30:57.130
Faculty (Olympus): And now I'm going to do a scatter plot of this.

193
00:30:57.290 --> 00:30:59.160
Faculty (Olympus): Okay, notice that I get this.

194
00:30:59.640 --> 00:31:01.180
Faculty (Olympus): This is exactly what I wanted.

195
00:31:03.250 --> 00:31:11.659
Faculty (Olympus): Right? So it starts at minus 2, all the way to plus 2, minus 2 to plus 2. Okay, so this is a simple, easy way of doing it that you already know.

196
00:31:12.480 --> 00:31:25.300
Faculty (Olympus): But there's a simpler way, still, in NumPy, because it's very often used, is first you create A.P.lin space minus 2, in this case, it's minus 2 to plus 2, and say minus 22 plus 2, right?

197
00:31:25.590 --> 00:31:43.419
Faculty (Olympus): So if I had something else, we can, you know, change this, but we'll come back to that. So I'm going to say T is NPLint space minus 2 to 2, 25 points, and now I simply say, give me XY, and create a mesh grid, pass it T and T. So this is going to be for the X coordinates, this is going to be for the Y coordinates.

198
00:31:43.440 --> 00:31:54.920
Faculty (Olympus): And this fellow will take care of doing the outer product of these two and giving you back X dot shape. So notice that T is an array which has only 25 elements, it's a one-dimensional array. But X and Y are going to be 25 plus 5 each.

199
00:31:55.890 --> 00:31:56.790
Faculty (Olympus): All right?

200
00:31:57.380 --> 00:31:59.390
Faculty (Olympus): So it's the same as this.

201
00:31:59.950 --> 00:32:00.740
Faculty (Olympus): Okay?

202
00:32:02.750 --> 00:32:04.839
Faculty (Olympus): But it's a simpler syntax.

203
00:32:05.130 --> 00:32:09.040
Faculty (Olympus): Mesh Grid also has some additional options, but,

204
00:32:10.530 --> 00:32:13.529
Faculty (Olympus): We can look at the doc strings for that, okay?

205
00:32:13.960 --> 00:32:24.539
Faculty (Olympus): Now that we have X and Y, this 25 plus 25 array, I can now look at something like this. I can look at plot for me, np.sine, X star X plus Y star.

206
00:32:25.460 --> 00:32:27.659
Faculty (Olympus): Okay, so now if I run thisâ€¦

207
00:32:27.770 --> 00:32:31.940
Faculty (Olympus): I will get something. So this is sine of X star X.

208
00:32:32.430 --> 00:32:34.329
Faculty (Olympus): into White House, lifestyle.

209
00:32:34.590 --> 00:32:36.520
Faculty (Olympus): And what you see here areâ€¦

210
00:32:37.470 --> 00:32:41.720
Faculty (Olympus): This is a contour function, so this basically shows me colored contours.

211
00:32:42.070 --> 00:32:49.760
Faculty (Olympus): Whichâ€¦ so each of these colors represent different values. So again, sine is peaking here, and then dropping rapidly on it, so it's basically something else.

212
00:32:51.800 --> 00:32:55.130
Faculty (Olympus): So, this is whatâ€¦ This function looks like.

213
00:32:55.690 --> 00:33:06.979
Faculty (Olympus): We can't do three-dimensional plots, but I'm not going to do that here. Now, supposing you wanted different spacing, you say, I want only 25 points in X, but I want 20 points in Y.

214
00:33:07.690 --> 00:33:13.329
Faculty (Olympus): To do that, you can also do something like this. You can say t is NPLint space minus 2, 25.

215
00:33:13.550 --> 00:33:17.250
Faculty (Olympus): U is someâ€¦ Then space minus 2, okay?

216
00:33:17.450 --> 00:33:25.130
Faculty (Olympus): And then you say XY is NPMesh Correct TU. Okay, now let's look at the shape of this. The shape of this will be 20 cross 25, 20 cross 25.

217
00:33:26.640 --> 00:33:43.159
Faculty (Olympus): Now, the axis convention, notice here, if you look at this, it'll be, you know, this will be a star Xi. Star Xi basically means any number of arguments, so this will work for any number of dimensions, not just two dimensions. So if I want 3 dimensions, where I want whatever I want, it'll generate this, okay?

218
00:33:43.460 --> 00:33:48.079
Faculty (Olympus): Now, the way in which it generates the indices, the shape of this, notice.

219
00:33:48.470 --> 00:34:07.590
Faculty (Olympus): It is 20 cross 25. It is not 25 cross 25, because even though X is this. The reason is, the default for this is to basically use indexing in a specific way. To use either XY indexing, or to use what is called Ij indexing. Okay, so if you want XY coordinate indexing.

220
00:34:08.100 --> 00:34:15.220
Faculty (Olympus): No, it'll give it to you in one particular shape. If you give it an IJ indexing, it will be the transposer. So if I say indexingâ€¦

221
00:34:18.100 --> 00:34:18.949
Faculty (Olympus): Sit.

222
00:34:19.710 --> 00:34:32.110
Faculty (Olympus): Notice that it'll transpose this one. So this is basically to make it easier if I'm saying I want spatial coordinates, and I want to plot this, or I'm looking in matrix coordinates. If you remember, matrix coordinates, 00 is at the top left.

223
00:34:32.300 --> 00:34:35.109
Faculty (Olympus): So the origins at the top left, rather than at the bottom left.

224
00:34:35.370 --> 00:34:38.920
Faculty (Olympus): So that's the reason you may see some of these differences, okay?

225
00:34:39.070 --> 00:34:50.950
Faculty (Olympus): So there's finally an exercise here. I'll stop for questions here. This exercise, if you want, you can try right away. Then the exercise is plot the interior of the unit circle by generating a collection of points inside the circle.

226
00:34:51.440 --> 00:34:56.239
Faculty (Olympus): And the idea is, you have to use all that you have learned so far to do this without using a forum.

227
00:34:56.820 --> 00:35:04.970
Faculty (Olympus): Okay, so if you want, you can try this. I will stop for questions, and then we'll move on to the next notebook. Abhineet?

228
00:35:05.890 --> 00:35:08.409
Abhineet Bansal: So, can you scroll up where you use the lambda function?

229
00:35:11.420 --> 00:35:18.009
Abhineet Bansal: So, lambda i comma JX0 plus i into dx, sir, I mean, how do you explain this, sir?

230
00:35:18.230 --> 00:35:19.720
Faculty (Olympus): It takes two arguments.

231
00:35:19.880 --> 00:35:20.460
Abhineet Bansal: Yeah?

232
00:35:20.770 --> 00:35:21.740
Faculty (Olympus): Hi and J.

233
00:35:22.090 --> 00:35:27.810
Faculty (Olympus): Right? And simply returnsâ€¦ this expression here is the return value of that function.

234
00:35:27.810 --> 00:35:32.140
Abhineet Bansal: This expression isâ€¦ is a given function for us, or are we supposed to know this?

235
00:35:32.430 --> 00:35:33.880
Abhineet Bansal: to plot this, I mean, likeâ€¦

236
00:35:36.350 --> 00:35:42.110
Faculty (Olympus): Okay, so if you wanted to create this grid, how would you do this? If you wanted to create this with a loop, how would you do this?

237
00:35:43.570 --> 00:35:47.530
Abhineet Bansal: I understood the next functions are where you used aâ€¦ the nextâ€¦

238
00:35:47.530 --> 00:35:52.059
Faculty (Olympus): No, no, no, forget all that. I want you to tell me how you will write this with a form.

239
00:35:55.170 --> 00:35:56.080
Abhineet Bansal: ofâ€¦

240
00:35:56.880 --> 00:35:59.599
Faculty (Olympus): I wanted to create this array of points like this.

241
00:36:03.940 --> 00:36:08.370
Abhineet Bansal: So I'll define an array for minus 2 to 2.

242
00:36:08.890 --> 00:36:12.999
Faculty (Olympus): Howâ€¦ okay, but no, there's no hurry, I want a two-dimensional.

243
00:36:13.210 --> 00:36:20.540
Faculty (Olympus): I want a 25 plus 25 fellow like this. I want all the X coordinates, and I want all the Y coordinates. That's 2X. How will you generate this?

244
00:36:20.540 --> 00:36:22.209
Siddharth Digambar Kulkarni .: For loop inside a funnel.

245
00:36:22.470 --> 00:36:24.400
Faculty (Olympus): Yeah, so you write an estimate formula.

246
00:36:25.600 --> 00:36:26.070
Faculty (Olympus): Correct?

247
00:36:26.070 --> 00:36:26.580
Abhineet Bansal: Okay.

248
00:36:26.700 --> 00:36:27.530
Abhineet Bansal: Yes.

249
00:36:27.890 --> 00:36:31.860
Faculty (Olympus): So, what will the X coordinates of these fellows be? Minus 2, whatever.

250
00:36:31.980 --> 00:36:45.140
Faculty (Olympus): plus delta X, plus delta X, all the way to plus 2. Then again, you have minus 2, minus 2, da-da-da-da, minus 2, right? Those are the X coordinates, how would be the Y coordinates? Minus 2, minus 2, right?

251
00:36:45.530 --> 00:36:51.279
Faculty (Olympus): Now, what this fellow does is exactly the same as that. So, when I give you this.

252
00:36:51.410 --> 00:36:55.520
Faculty (Olympus): Fromâ€¦ from function, and basically call this for every pair of indices.

253
00:36:58.090 --> 00:36:59.580
Faculty (Olympus): Looping in some order.

254
00:37:01.330 --> 00:37:07.370
Faculty (Olympus): So I intend to beâ€¦ so this is going to give meâ€¦ so if this is the 0 comma 0 fellow, the 00 should be minus 2.

255
00:37:09.480 --> 00:37:11.980
Abhineet Bansal: Correct. And it's going to run this 25 times.

256
00:37:12.300 --> 00:37:15.789
Faculty (Olympus): Yeah, that's the FROM function. That's the FROM func- that's what FROM function does.

257
00:37:16.130 --> 00:37:20.080
Faculty (Olympus): Given a shape, this fellow's gonna call this fellow with every index in this shape.

258
00:37:21.860 --> 00:37:22.639
Abhineet Bansal: Got it, sir.

259
00:37:22.840 --> 00:37:23.600
Abhineet Bansal: Okay.

260
00:37:25.250 --> 00:37:31.099
Faculty (Olympus): So how would you generate it? You give it the origin, and you add i into delta X. You just keep on dumping, moving up.

261
00:37:32.820 --> 00:37:34.379
Abhineet Bansal: Got it, too. Thanks.

262
00:37:34.380 --> 00:37:35.890
Faculty (Olympus): True. Yadav?

263
00:37:36.530 --> 00:37:45.329
Gaurav Singh .: Yeah, Professor, same cell, if, in the first function, you have not considered J.

264
00:37:46.160 --> 00:37:46.840
Faculty (Olympus): Yeah.

265
00:37:46.840 --> 00:37:47.950
Gaurav Singh .: I meanâ€¦

266
00:37:47.950 --> 00:37:50.480
Faculty (Olympus): Because the X coordinate doesn't change with respect to J.

267
00:37:50.600 --> 00:37:54.650
Faculty (Olympus): It's always going from minus 2 to 2, minus 2 to 2, minus 2 to 2.

268
00:37:55.590 --> 00:37:58.890
Gaurav Singh .: Okay. Soâ€¦

269
00:37:59.380 --> 00:38:08.170
Gaurav Singh .: this, this function, takes two arguments you are saying, I comma J, and, it always takes, two arguments. I mean.

270
00:38:08.490 --> 00:38:16.920
Gaurav Singh .: could I have defined this lambda function only with I argument? Because anyways, this function is taking X0 plus i into G.

271
00:38:16.920 --> 00:38:21.559
Faculty (Olympus): Giving it a two-dimensional shape, so it's going to give you two arguments. How can you define it on a single argument?

272
00:38:23.600 --> 00:38:29.200
Gaurav Singh .: Oh, okay, okay. Because everyâ€¦ for calculating every delta, these two arguments will be taken.

273
00:38:29.200 --> 00:38:31.750
Faculty (Olympus): It is a perfectly legal function that I've given you here.

274
00:38:32.590 --> 00:38:33.889
Faculty (Olympus): This function is okay.

275
00:38:35.440 --> 00:38:37.600
Faculty (Olympus): Not using these arguments doesn't matter.

276
00:38:38.110 --> 00:38:39.470
Gaurav Singh .: -

277
00:38:39.770 --> 00:38:41.290
Gaurav Singh .: Okay, okay.

278
00:38:42.550 --> 00:38:46.080
Faculty (Olympus): Right? So this fellow is good. That's what I said, if I give you a two-dimensional array.

279
00:38:46.080 --> 00:38:46.890
Gaurav Singh .: Me?

280
00:38:46.950 --> 00:38:55.550
Faculty (Olympus): I'm going to give two indices. If I give you three-dimensional, I'm going to give you three indices. No, you can choose to say, I'll ignore the two indices, I'll use IE, I'll only use J, that's up to you.

281
00:38:56.180 --> 00:38:56.840
Gaurav Singh .: Yeah.

282
00:38:56.840 --> 00:39:04.880
Faculty (Olympus): If you have a mechanism by which, given an index ij, I can give you the coordinate? That's all it is. This is a function that maps ij to XY space.

283
00:39:05.570 --> 00:39:07.929
Faculty (Olympus): In this case, I'm only concerned about the X squad.

284
00:39:08.840 --> 00:39:09.790
Gaurav Singh .: Yeah.

285
00:39:10.090 --> 00:39:16.260
Faculty (Olympus): Right? So this fellow is just creating all the exponents, all the y coordinates. Then I can do a plt.scan.

286
00:39:17.260 --> 00:39:17.800
Gaurav Singh .: Yeah.

287
00:39:18.220 --> 00:39:18.750
Gaurav Singh .: Got it.

288
00:39:19.200 --> 00:39:30.559
Gaurav Singh .: Actually, I was not able to get the doc string because I ran that cell where you have ran the contour thing, no? It is still running in my Jupyter notebook, so I am not able to run theâ€¦

289
00:39:30.850 --> 00:39:34.789
Gaurav Singh .: Dog thing for this function. It is taking time, I don't know why.

290
00:39:34.790 --> 00:39:35.480
Faculty (Olympus): Okay.

291
00:39:36.100 --> 00:39:37.980
Faculty (Olympus): Alright. Shirley?

292
00:39:38.760 --> 00:39:46.529
Shirley Menezes .: Sir, the same cell that we discussed, why did you use DX as a 4.0, like, 1x6 of X?

293
00:39:46.530 --> 00:39:50.200
Faculty (Olympus): Oh, because it starts atâ€¦ what is the length of thisâ€¦ what is the length of thisâ€¦

294
00:39:51.300 --> 00:39:54.179
Faculty (Olympus): It's from 2 to minus 2, right? So it's 2 units.

295
00:39:54.390 --> 00:39:55.350
Shirley Menezes .: Okay, okay.

296
00:39:55.350 --> 00:40:01.590
Faculty (Olympus): So if I have to moveâ€¦ if I have to move by 25 fellows, I have to do, you know, 4 divided by n-1.

297
00:40:01.590 --> 00:40:05.340
Shirley Menezes .: Okay, okay, the length is 4 units, okay, so that's how we will calculate.

298
00:40:05.340 --> 00:40:06.860
Faculty (Olympus): Good. Good.

299
00:40:09.170 --> 00:40:16.909
Faculty (Olympus): Yeah, so this is a very pithy 4 or 5 lines, right? These four or five lines, right? I had written a long for loop, maybe to make it easier, butâ€¦

300
00:40:17.270 --> 00:40:18.359
Faculty (Olympus): Yeah, it's okay.

301
00:40:18.930 --> 00:40:21.690
Faculty (Olympus): I understand that you have questions with this.

302
00:40:23.470 --> 00:40:24.520
Faculty (Olympus): Happy Shaikh?

303
00:40:26.000 --> 00:40:29.160
Abhishek Raghuvanshi .: Yeah, good evening, Professor. Can we go to the mesh thing? Iâ€¦

304
00:40:29.550 --> 00:40:29.960
Faculty (Olympus): Okay.

305
00:40:29.960 --> 00:40:35.880
Abhishek Raghuvanshi .: I noticed that the shape of both X and Y is two-dimensional.

306
00:40:36.720 --> 00:40:37.670
Abhishek Raghuvanshi .: So, what?

307
00:40:37.670 --> 00:40:42.339
Faculty (Olympus): It's exactly the same as this. This also gives you two-dimensional, this also gives you twoâ€¦

308
00:40:44.330 --> 00:40:50.160
Abhishek Raghuvanshi .: Okay. Because one dimension, I can understand, so there are values of X.

309
00:40:50.430 --> 00:40:54.700
Abhishek Raghuvanshi .: So there is one more dimension, so the corresponding values ofâ€¦

310
00:40:55.070 --> 00:40:58.769
Abhishek Raghuvanshi .: Which are the corresponding values in the other dimension? I'm a bit confused.

311
00:40:59.530 --> 00:41:12.459
Faculty (Olympus): So these are all the X coordinates. If I list out all the X coordinates, this point, X coordinate is what? Minus 2. What is the X coordinate of this point? Plus 2. What is the X coordinate of this point? Minus 2. What is the X coordinate of this point? Plus 2, right?

312
00:41:12.810 --> 00:41:22.720
Faculty (Olympus): So I just have minus 1. So it'sâ€¦ basically, it's like lin space minus 222, I copy it multiple times in this dimension. Lin space minus 1 to 2, I copy it in this dimension, and I don'tâ€¦

313
00:41:22.920 --> 00:41:23.700
Faculty (Olympus): Right?

314
00:41:23.960 --> 00:41:24.980
Faculty (Olympus): I have XR.

315
00:41:24.980 --> 00:41:27.790
Abhishek Raghuvanshi .: What is the Xâ€¦ what is the x-axis in this, then?

316
00:41:28.840 --> 00:41:30.640
Abhishek Raghuvanshi .: What is X and Y here?

317
00:41:30.910 --> 00:41:35.259
Abhishek Raghuvanshi .: It's X and Y, that's what I was assuming. So this is X and this is Y.

318
00:41:35.780 --> 00:41:41.079
Faculty (Olympus): What is X, what isâ€¦ this is X and this is Y. I have not changed any sign conventions or any access conventions here.

319
00:41:41.650 --> 00:41:45.370
Abhishek Raghuvanshi .: Okay, but X is two-dimensional, so where is the second dimension in this?

320
00:41:46.030 --> 00:41:50.350
Faculty (Olympus): What is X is two-dimensional? You're saying the NumPy array is two-dimensional. Yes, it is.

321
00:41:51.170 --> 00:41:52.719
Abhishek Raghuvanshi .: Okay, okay. So hereâ€¦

322
00:41:52.720 --> 00:41:53.210
Faculty (Olympus): I mean, that'sâ€¦

323
00:41:53.210 --> 00:41:55.029
Abhishek Raghuvanshi .: Maybe you will.

324
00:41:55.030 --> 00:41:58.840
Faculty (Olympus): I didn't understand. So, scatter plot requires X values and Y values.

325
00:41:59.600 --> 00:42:07.400
Faculty (Olympus): I give you a two-dimensional array of XY, we have a two-dimensional array ofâ€¦ it's a bunch ofâ€¦ it doesn't matter. The dimensional array of this doesn't matter. So if I said flat of this.

326
00:42:07.950 --> 00:42:11.500
Faculty (Olympus): flat of this, it would still get the same thing. Doesn't matter.

327
00:42:12.190 --> 00:42:13.890
Abhishek Raghuvanshi .: Thank you.

328
00:42:14.140 --> 00:42:14.980
Abhishek Raghuvanshi .: Okay.

329
00:42:15.380 --> 00:42:19.970
Faculty (Olympus): Scatterplot doesn't care about this. Contour does care. You can't do flat here.

330
00:42:21.130 --> 00:42:29.719
Abhishek Raghuvanshi .: Okay, so in contour, we are, having theâ€¦ the expression that is getting plotted by theâ€¦

331
00:42:29.720 --> 00:42:30.119
Faculty (Olympus): No, no, no.

332
00:42:30.120 --> 00:42:30.740
Abhishek Raghuvanshi .: love.

333
00:42:31.370 --> 00:42:47.250
Faculty (Olympus): There's an implicit assumption of a topology, that is, of the connectivity between this point to the next, and the previous, and the other things, when you use contour. It needs to know that this point is next to that point. Otherwise, how will you plot a contour? How will you give your continuous curves like this? You're just giving me a set of points.

334
00:42:47.410 --> 00:42:48.210
Faculty (Olympus): Nope.

335
00:42:48.770 --> 00:42:53.219
Faculty (Olympus): So it's assuming that this is a graph sheet, and this is, like, a sampling of that graph sheet.

336
00:42:54.620 --> 00:42:55.340
Abhishek Raghuvanshi .: Okay.

337
00:42:55.340 --> 00:42:59.570
Faculty (Olympus): between two values, there is something. It's not a random set of points.

338
00:42:59.570 --> 00:43:00.740
Abhishek Raghuvanshi .: Okay.

339
00:43:00.740 --> 00:43:04.070
Faculty (Olympus): This point, then the next point, then the next point, and it has some specific order.

340
00:43:06.370 --> 00:43:08.509
Faculty (Olympus): So what is the question? I don't know what your question is.

341
00:43:08.840 --> 00:43:15.889
Abhishek Raghuvanshi .: No, no, so there areâ€¦ there are two variables, and both of them have two dimensions, so that's why I was not able to.

342
00:43:15.890 --> 00:43:28.889
Faculty (Olympus): So, answer to me this question. If I haveâ€¦ I want you to tell me all the X coordinates of thisâ€¦ for theâ€¦ for these points that I've plotted here. I want you to tell me all the Y coordinates of these points that are plotted here. What dimension do you think they will have?

343
00:43:30.750 --> 00:43:32.179
Faculty (Olympus): How many points should I have?

344
00:43:34.400 --> 00:43:39.450
Abhishek Raghuvanshi .: Yeah, 25, sorry, forâ€¦ But it's a multiplication of theâ€¦

345
00:43:40.090 --> 00:43:43.290
Faculty (Olympus): 625, right? 25 plusâ€¦

346
00:43:43.290 --> 00:43:44.220
Abhishek Raghuvanshi .: I will be good.

347
00:43:44.220 --> 00:43:46.400
Faculty (Olympus): 25 under 25 points, correct?

348
00:43:46.400 --> 00:43:46.970
Abhishek Raghuvanshi .: Yeah.

349
00:43:47.860 --> 00:43:53.040
Faculty (Olympus): So I should haveâ€¦ I should have 25 across 25 X coordinates, I should have 25 across 25 Y coordinates.

350
00:43:53.990 --> 00:43:54.690
Abhishek Raghuvanshi .: Right.

351
00:43:55.000 --> 00:43:57.609
Faculty (Olympus): And that's all this is. It's doing exactly that.

352
00:43:58.920 --> 00:43:59.580
Abhishek Raghuvanshi .: Okay, soâ€¦

353
00:43:59.580 --> 00:44:05.310
Faculty (Olympus): So I would suggest you go back, forget about this, like, NumPy array, create two lists, Okay?

354
00:44:06.650 --> 00:44:13.189
Faculty (Olympus): Create all the coordinates, X coordinates, all the Y coordinates, and plot it, and get exactly the same PLT.scatter.

355
00:44:13.450 --> 00:44:14.659
Faculty (Olympus): The good exercise.

356
00:44:16.430 --> 00:44:18.649
Faculty (Olympus): Once you do that, this will make a lot of sense.

357
00:44:19.130 --> 00:44:32.839
Abhishek Raghuvanshi .: Okay, so it's just repeating of that, soâ€¦ so it makes it easier. Andâ€¦ and for theâ€¦ for the, the graph, the contour function, it isâ€¦ theâ€¦ the color is the expression that you have put in, right? A sign.

358
00:44:32.840 --> 00:44:44.679
Faculty (Olympus): No, yeah, so this is the scalar value. The color is this color map. So if I want to change the color map, I can say CMAP is hot, which is what this fellow says. That'll give me a slightly diffâ€¦ very different looking plot. This is just aâ€¦

359
00:44:45.560 --> 00:44:48.180
Abhishek Raghuvanshi .: The color bar is for the expression, validated expression.

360
00:44:48.180 --> 00:44:51.750
Faculty (Olympus): Scalar bar basically maps the scalar value provided here to a color.

361
00:44:52.090 --> 00:44:53.110
Abhishek Raghuvanshi .: Okay, wonderful. Thanks.

362
00:44:53.110 --> 00:45:05.739
Faculty (Olympus): Okay, it'll look at the range of these values, so this is someâ€¦ here it is minus 1 to 1. It could be some minus 1000 to plus 1000, doesn't matter. It will color theseâ€¦ number these according to the data that you have, and color it appropriate.

363
00:45:08.970 --> 00:45:09.810
Faculty (Olympus): Okay?

364
00:45:09.810 --> 00:45:10.770
Abhishek Raghuvanshi .: Oh, good, thanks.

365
00:45:11.100 --> 00:45:11.780
Faculty (Olympus): Anand?

366
00:45:12.510 --> 00:45:20.950
Anand Kumar: So we're looking at, like, two dimensions right now, so this can easily be scaled to another dimension as well. Not a drug, but the values which we saw are.

367
00:45:21.400 --> 00:45:25.109
Faculty (Olympus): Yes. You won't be able to draw, I mean, matplotlib, you'll have to doâ€¦

368
00:45:25.450 --> 00:45:28.479
Faculty (Olympus): Lot of things to draw this. There are other tools.

369
00:45:28.980 --> 00:45:36.189
Faculty (Olympus): There are visualization tools that do this. For example, with Maya V, you can visualize this with, again, one line. You can say contour XYZ,

370
00:45:36.630 --> 00:45:43.949
Faculty (Olympus): No, sorry, it won't be contoured, it'll be isosuras. You can create isosurfaces in three dimensions. But then you can jack it up to 4 dimensions, and nobody can help you.

371
00:45:44.980 --> 00:45:54.500
Faculty (Olympus): Okay. But the idea here, that is the beauty, right? So it's a very useâ€¦ good question you asked. The beauty of doing mesh grid is that you can create a 10 cross 10â€¦

372
00:45:55.680 --> 00:45:59.469
Faculty (Olympus): Right? 10 cross 10 cross 10 cross 10. 10-dimensional cubed.

373
00:45:59.850 --> 00:46:13.669
Faculty (Olympus): some hypercube and sample. But of course, 10-dimensional cube, 10 elements, will give you 10 to the power 10. Yeah. Crazy number of values, okay? So, obviously, don't go something like that, but yeah, you can create 4-dimensional, 5-dimensional samples.

374
00:46:14.570 --> 00:46:15.710
Anand Kumar: Sure, thank you.

375
00:46:15.710 --> 00:46:16.320
Faculty (Olympus): Yes.

376
00:46:17.420 --> 00:46:18.450
Faculty (Olympus): Siddharth?

377
00:46:18.730 --> 00:46:36.890
Siddharth Digambar Kulkarni .: Yes, sir, if you want to plot a similar plot to one which you have plotted upward with this mesh grid, then in that case, the second argument of that T has to be reverse of the T, right? Reverse of the T. Because, theâ€¦ if youâ€¦ if you have a mesh grid.

378
00:46:36.890 --> 00:46:39.470
Siddharth Digambar Kulkarni .: TT, it will start the top from

379
00:46:39.470 --> 00:46:43.350
Siddharth Digambar Kulkarni .: Minus 2 and go to 2 downward.

380
00:46:43.350 --> 00:46:43.890
Faculty (Olympus): 8th.

381
00:46:44.040 --> 00:46:49.880
Faculty (Olympus): No, no. That's because the default indexing for Measure Grid is Fix what?

382
00:46:50.310 --> 00:46:56.189
Faculty (Olympus): And I only did a scatterplot. I didn't do an ins show or something. It'll become old-talk for me.

383
00:46:56.420 --> 00:46:58.759
Faculty (Olympus): So just be careful about those things.

384
00:46:59.190 --> 00:46:59.930
Siddharth Digambar Kulkarni .: Okay.

385
00:47:00.060 --> 00:47:11.249
Faculty (Olympus): And if you want, if you're not sure, hey, ka or I, you just always look at the values. You know, you can look at the index, I mean, X is just a two-dimensional numpy array, so you can get X of 00, and you'll find out what the origin is, what the value is.

386
00:47:11.630 --> 00:47:12.500
Siddharth Digambar Kulkarni .: Okay, okay.

387
00:47:13.080 --> 00:47:18.080
Faculty (Olympus): Right? So, for example, I'll just quickly show you this data cell here. Say X off.

388
00:47:18.550 --> 00:47:22.810
Faculty (Olympus): 0 comma 0, right? Let's see what the value is. It's going to be minus 2.

389
00:47:23.450 --> 00:47:24.050
Faculty (Olympus): Oh, look at me.

390
00:47:24.050 --> 00:47:27.359
Siddharth Digambar Kulkarni .: If you plot this, what will you get, sir, if you plot?

391
00:47:27.730 --> 00:47:28.540
Faculty (Olympus): Lord what?

392
00:47:28.930 --> 00:47:30.360
Siddharth Digambar Kulkarni .: X, and Y.

393
00:47:31.000 --> 00:47:34.900
Faculty (Olympus): You'll get the same thing as you get here, scattered from this. Get the same thing.

394
00:47:34.900 --> 00:47:42.870
Siddharth Digambar Kulkarni .: Okay. Then second question is, as the contour is a kind of way to visualize a three-dimensional graph, right?

395
00:47:42.870 --> 00:47:47.160
Faculty (Olympus): This is a carpet plot, yeah, you can think of it as a carpet. This is telling you the height on this.

396
00:47:47.160 --> 00:47:55.210
Siddharth Digambar Kulkarni .: Yes, yes, so, so how much, the contours means, how much deep or how much, towards you it is coming?

397
00:47:56.040 --> 00:47:56.900
Faculty (Olympus): Yeah.

398
00:47:57.060 --> 00:48:01.199
Faculty (Olympus): Right. Or away from me, in this case. All these fellows are going into the plane.

399
00:48:01.420 --> 00:48:02.050
Siddharth Digambar Kulkarni .: Yes, yes, yes.

400
00:48:02.050 --> 00:48:04.650
Faculty (Olympus): All the, you know, yellow fellows are coming out of the board.

401
00:48:04.650 --> 00:48:06.140
Siddharth Digambar Kulkarni .: Right, right, got it, got it.

402
00:48:06.140 --> 00:48:08.230
Faculty (Olympus): Okay, and 0 is, like, the green fellow, this fellow is 0.

403
00:48:08.590 --> 00:48:09.649
Siddharth Digambar Kulkarni .: Okay, okay.

404
00:48:09.650 --> 00:48:14.999
Faculty (Olympus): But again, doing this in 3D is much nicer, but, you know, I'm not showing you those things yet. We have to install stuff.

405
00:48:15.950 --> 00:48:18.080
Faculty (Olympus): But yeah, it's actually not very hard to go.

406
00:48:18.580 --> 00:48:23.609
Faculty (Olympus): I can show you in a few lines, but I don't want to get distracted. We are running short of time.

407
00:48:24.180 --> 00:48:25.090
Faculty (Olympus): Roshan?

408
00:48:26.410 --> 00:48:34.949
Roshan Mathane .: Yeah, probably my question is regarding this, access convention. I didn't get the part whereâ€¦ why did it show 20 by 25 for the shape?

409
00:48:35.150 --> 00:48:47.310
Faculty (Olympus): See, one of them is basicallyâ€¦ yeah, basically, the axis convention, there are two axis conventions. One is XY, the other is IJ. XY is the physical coordinates that are usually starting at minus 2 cool.

410
00:48:47.480 --> 00:48:49.450
Faculty (Olympus): Right, so the origin is at the bottom left.

411
00:48:49.720 --> 00:48:50.300
Roshan Mathane .: Beautiful.

412
00:48:51.020 --> 00:48:55.899
Faculty (Olympus): Right? So your matrix has to be ulta of what you normally think so. Matrix, you think is 00 at the top left.

413
00:48:57.340 --> 00:48:59.980
Faculty (Olympus): But physical coordinates, your origin is at the bottom left.

414
00:49:00.430 --> 00:49:01.130
Roshan Mathane .: Yeah.

415
00:49:01.530 --> 00:49:03.440
Faculty (Olympus): So, obviously, the matrix can't be the same.

416
00:49:04.820 --> 00:49:08.919
Roshan Mathane .: But, but when you define it, on, onâ€¦ No, no, no, no, no.

417
00:49:08.920 --> 00:49:10.189
Faculty (Olympus): No, hang on.

418
00:49:10.680 --> 00:49:12.160
Faculty (Olympus): If I look at this cell.

419
00:49:12.340 --> 00:49:21.080
Faculty (Olympus): If this was a matrix, this would be 00. If I prod for you a matrix like this, you'll be very confused, right? So that would be Ij indexing, which means you would not start from here.

420
00:49:22.790 --> 00:49:23.950
Faculty (Olympus): That's what you want.

421
00:49:24.310 --> 00:49:29.940
Faculty (Olympus): But if I want physical indexing, I want this to be here. If I want to move this fellow there, I have to basically do a transpose, right?

422
00:49:30.410 --> 00:49:31.090
Roshan Mathane .: Yeah.

423
00:49:32.210 --> 00:49:33.489
Faculty (Olympus): Like, this fellow would go dead.

424
00:49:36.780 --> 00:49:37.860
Roshan Mathane .: Yeah, okay.

425
00:49:38.150 --> 00:49:56.689
Faculty (Olympus): Right? So basically, what it does is, the indexing will flip around, so that you're able to, you know, do those kind of appropriate parts. If you want to create an image, and you want to plot it in image space, then you want it where, actually, IJ is the values. On the other hand, here, I'm looking at physical coordinates, right? I'm looking at this has to be minus 2, comma, minus 2.

426
00:49:57.200 --> 00:50:02.599
Faculty (Olympus): So, if you want that Right? Then it makes sense toâ€¦

427
00:50:03.060 --> 00:50:05.909
Faculty (Olympus): change the indexing on. That's all it is.

428
00:50:06.560 --> 00:50:12.229
Faculty (Olympus): But at the end of the day, it's just giving you a, you know, a numpy array which gives you X coordinates and numpy array which gives you Y coordinates.

429
00:50:12.890 --> 00:50:14.470
Roshan Mathane .: Yeah, understood, yeah.

430
00:50:15.090 --> 00:50:16.030
Faculty (Olympus): Rahul?

431
00:50:17.490 --> 00:50:29.020
Rahul Joshi .: Sorry, the contour, is it a correct understanding that for one value of X and Y, all the possible, values, will be calculated and connected, then the same thing will be repeated for.

432
00:50:29.020 --> 00:50:35.319
Faculty (Olympus): So, I will clarify a little bit. I think you got the right idea, but I think the words you used were not perfect.

433
00:50:35.500 --> 00:50:39.590
Faculty (Olympus): What it'll do is, it's called iso-compost, which means, given a scalar value.

434
00:50:39.780 --> 00:50:44.869
Faculty (Olympus): So let's say I look at the value of 1. So if you don't put CONTO ref file, you can just put CONTO.

435
00:50:45.140 --> 00:50:50.900
Faculty (Olympus): You'll just get contour lines. And in fact, here, you can say, there's an argument here, if you look at this.

436
00:50:51.440 --> 00:50:54.370
Faculty (Olympus): You can say one of the arguments is,

437
00:50:55.540 --> 00:51:09.049
Faculty (Olympus): Yeah, number and positions of the contour lines and things like that, right? So you can actually specify the actual, you know, the actual quantities that you want. So look at the arguments. There are many, many arguments. So if I say levelsâ€¦

438
00:51:09.550 --> 00:51:10.530
Faculty (Olympus): Summer.

439
00:51:13.010 --> 00:51:17.500
Faculty (Olympus): There are 3 contour lines.

440
00:51:18.050 --> 00:51:21.610
Faculty (Olympus): 0 is boring because it's a single point, so let me make it 0.5.

441
00:51:25.770 --> 00:51:28.450
Faculty (Olympus): So this is gonna be 0.5, this is going to be 1.

442
00:51:29.530 --> 00:51:34.210
Faculty (Olympus): This is going to be minus point, right? That's going to be minusâ€¦ Fuck.

443
00:51:35.690 --> 00:51:38.899
Rahul Joshi .: Yeah, so whenever you say minus 1, minus 0.5, this is a.

444
00:51:38.900 --> 00:51:39.940
Faculty (Olympus): So what is happening isâ€¦

445
00:51:39.940 --> 00:51:40.500
Rahul Joshi .: photo, etc.

446
00:51:40.500 --> 00:51:42.020
Faculty (Olympus): Cross the line?

447
00:51:42.490 --> 00:51:46.139
Faculty (Olympus): Okay, where the value of the contour is the same.

448
00:51:46.420 --> 00:51:51.040
Faculty (Olympus): So this will beâ€¦ right, so this is going to be 0.5, okay, plus 0.5.

449
00:51:52.890 --> 00:51:55.479
Rahul Joshi .: So, plus .5 for both X and Y, right?

450
00:51:55.710 --> 00:51:56.430
Faculty (Olympus): No.

451
00:51:56.610 --> 00:52:00.299
Faculty (Olympus): I'm missing the idea. At every point, imagine I have a temperature.

452
00:52:00.550 --> 00:52:11.979
Faculty (Olympus): I have a two-dimensional plane, or for example, there is a height map, there's a map, okay? This is a coordinate, latitude, longitude. If I'm saying this circle is here, it will tell you all the points on the circle are at the same height.

453
00:52:14.870 --> 00:52:20.530
Faculty (Olympus): So, ISO surface represents a value that you have is the same along thatâ€¦ along that line.

454
00:52:20.530 --> 00:52:23.259
Siddharth Digambar Kulkarni .: Pebble, the waves coming out of that pebble.

455
00:52:23.260 --> 00:52:24.030
Faculty (Olympus): Yes.

456
00:52:24.480 --> 00:52:34.239
Faculty (Olympus): And the wave, this is the height, all I equal height, equal height. So if the pebble, it's gonna get circular waves. In fact, that's what the equation is, np sine of X squared plus Y squared.

457
00:52:34.420 --> 00:52:40.099
Faculty (Olympus): X squared plus Y squared equal to constant is circles. Sine of that is also going to, you know, retain that shape.

458
00:52:41.500 --> 00:52:42.869
Faculty (Olympus): So that's all it is.

459
00:52:47.400 --> 00:52:48.150
Faculty (Olympus): Does that make sense?

460
00:52:48.150 --> 00:52:57.520
Rahul Joshi .: No, sorry, I'm a little confused. So, in this formula, do we have to calculate again and again with the different values of X and Y?

461
00:52:57.520 --> 00:52:59.950
Faculty (Olympus): Did Iâ€¦ what have I done? Did I do anything here?

462
00:53:00.480 --> 00:53:05.250
Faculty (Olympus): I didn't do anything, right? I have just computed np sine of X tier as Y squared, that's all I have done.

463
00:53:05.870 --> 00:53:09.140
Rahul Joshi .: No, but X and Y are multiple values, right, in that, array.

464
00:53:09.140 --> 00:53:16.010
Faculty (Olympus): Yeah, how do I getâ€¦ I need to get 625 values of sine of X squared into Y squared. Sine of X squared plus Y squared.

465
00:53:16.380 --> 00:53:17.559
Faculty (Olympus): How do I get that?

466
00:53:22.010 --> 00:53:26.300
Faculty (Olympus): You're not understanding what is happening. So, X and Y are 25 plus 25 arrays.

467
00:53:26.300 --> 00:53:26.850
Rahul Joshi .: Yep.

468
00:53:27.090 --> 00:53:32.499
Faculty (Olympus): Right? I now want to find the sine of X into X plus Y into Y. So when I do X into X, it's creating

469
00:53:32.780 --> 00:53:42.120
Faculty (Olympus): 625 fellows is doing multiplication. 625 fellows is doing multiplication. Then doing an add. Then it is finding the sign of the sum of all of those, for every one of these points.

470
00:53:42.370 --> 00:53:49.790
Faculty (Olympus): So this one line is doing a heck of a lot of work. And then ContourF is doing, and it's an algorithm which basically computes the contours.

471
00:53:50.140 --> 00:54:04.209
Faculty (Olympus): So it assumes that X and Y have some certain structure, right? That they are not random points, that they have this sort of an array structure, and then given a point, it'll trace out where the circle is. It'll trace out where that iso line is. It doesn't have to be a circle, for example.

472
00:54:13.360 --> 00:54:16.330
Faculty (Olympus): Now, it doesn't have to be a circle. I mean, we have some crazy thing like this.

473
00:54:19.180 --> 00:54:20.110
Faculty (Olympus): All right.

474
00:54:21.630 --> 00:54:23.299
Rahul Joshi .: Okay, let me read it so that when we don'.

475
00:54:23.300 --> 00:54:24.680
Faculty (Olympus): Yeah, you'll have to think about this.

476
00:54:25.330 --> 00:54:40.099
Faculty (Olympus): So again, think about a map. You have a latitude-longitude. When you see a line there, it basically means all those lines there are the same value. If you look at a weather plot, saying, here is the pressure contours, they're basically equal pressure lens, or ISO lens.

477
00:54:40.920 --> 00:54:52.730
Faculty (Olympus): So, this color indicates all equalâ€¦ roughly equal values, because these are discrete bins. So, let me make this levels is equal to 100. Be easier. Looks continuous, right?

478
00:54:53.090 --> 00:54:56.930
Faculty (Olympus): Well, I've made so many levels. By default, it's some 10 or 20 levels.

479
00:54:57.160 --> 00:55:02.699
Faculty (Olympus): 20 level, you can see this. So, which means this band is, like, largely between 0.9 and 1.

480
00:55:03.170 --> 00:55:12.979
Faculty (Olympus): This whole region is near zero, right? And it's increasing rapidly, and then sort of leveling off, which is exactly how sine looks. It increases linearly, and then drops off, and then drops down.

481
00:55:14.930 --> 00:55:16.370
Rahul Joshi .: Yep, bought it, sir.

482
00:55:16.840 --> 00:55:22.430
Faculty (Olympus): So basically, ISO contour, Marks out all the points that have the same value.

483
00:55:22.630 --> 00:55:24.039
Faculty (Olympus): I've notâ€¦ right?

484
00:55:24.920 --> 00:55:28.850
Faculty (Olympus): Alright, so I hope you've solved this exercise.

485
00:55:29.330 --> 00:55:31.220
Faculty (Olympus): Has anyone solved this exercise?

486
00:55:32.210 --> 00:55:33.440
Faculty (Olympus): How would you do this?

487
00:55:36.780 --> 00:55:41.820
Siddharth Digambar Kulkarni .: Use measures plus Y squared less than whatâ€¦

488
00:55:43.280 --> 00:55:44.070
Faculty (Olympus): Sorry?

489
00:55:45.040 --> 00:55:51.789
Siddharth Digambar Kulkarni .: X squared plus Y square less than 1. You mean, mesh grid, if you useâ€¦

490
00:55:53.560 --> 00:55:54.420
Faculty (Olympus): Okay?

491
00:56:01.520 --> 00:56:02.889
Faculty (Olympus): Okay, so now what do you do?

492
00:56:03.170 --> 00:56:07.270
Siddharth Digambar Kulkarni .: XY equal to np.meshgrid.

493
00:56:10.060 --> 00:56:10.770
Faculty (Olympus): An hour.

494
00:56:12.380 --> 00:56:13.599
Faculty (Olympus): No, this is fine.

495
00:56:13.600 --> 00:56:17.600
Siddharth Digambar Kulkarni .: X squared plus Y square, less than 1.

496
00:56:17.600 --> 00:56:20.290
Faculty (Olympus): So I get this, right? I want only the circle fellows.

497
00:56:20.290 --> 00:56:36.730
Nishtha Dutta .: Yeah, so we need to first make sure that the points we are plotting is under the circle of unit size, which she was telling that it should be lessâ€¦ X squared plus Y squared should be less than 1. We will plot only those points.

498
00:56:36.730 --> 00:56:40.799
Faculty (Olympus): Alright, so what I will do is I'll first expand this region, make it slightly bigger.

499
00:56:40.990 --> 00:56:44.359
Faculty (Olympus): I think it's 20 points. That's the inside is gonna beâ€¦

500
00:56:44.360 --> 00:56:45.040
Nishtha Dutta .: It's soâ€¦

501
00:56:45.040 --> 00:56:47.240
Faculty (Olympus): Y star X plus Y star Y.

502
00:56:47.550 --> 00:56:48.050
Nishtha Dutta .: Mr.

503
00:56:48.050 --> 00:56:49.619
Siddharth Digambar Kulkarni .: Thank you, God, bless them.

504
00:56:50.060 --> 00:56:50.750
Faculty (Olympus): Naked.

505
00:56:51.100 --> 00:57:03.420
Nishtha Dutta .: So inâ€¦ inside, we'll have true-false values, so we will only plot true. So, we need to pass the indexes of X and Y while plotting the scatter plot as insideâ€¦ yeah, correct.

506
00:57:05.340 --> 00:57:09.990
Faculty (Olympus): Does everybody get this? Now, this doesn't look very nice. I'll make this clear.

507
00:57:11.240 --> 00:57:12.500
Nishtha Dutta .: equalsâ€¦

508
00:57:12.500 --> 00:57:14.400
Saurav kumar: If we can repeat number of points.

509
00:57:16.270 --> 00:57:21.480
Faculty (Olympus): Okay, but even now, you have toâ€¦ this is very discreet, I would like something more better, so I'd like this 100.

510
00:57:25.370 --> 00:57:32.190
Faculty (Olympus): Alright, so the nice thing is, it just takes, like, few lines of code to actually do a lot of this. No loops, nothing.

511
00:57:34.130 --> 00:57:37.469
Faculty (Olympus): Alright, so this is kind ofâ€¦ we finished with this.

512
00:57:37.470 --> 00:57:43.790
Rahul Joshi .: Sir, what is theâ€¦ I think Iâ€¦ sorry, sir, to interrupt here. What is that inside logic? I did not get it here.

513
00:57:44.240 --> 00:57:46.250
Faculty (Olympus): All of these values are inside the circle, right?

514
00:57:46.250 --> 00:57:47.530
Siddharth Digambar Kulkarni .: Masking, masking.

515
00:57:50.420 --> 00:58:00.479
Faculty (Olympus): So, X squared plus Y squared equal to 1 will be the equation of the circle. X squared plus Y squared less than 1 is all the points inside this fellow. X squared plus Y squared greater than 1 is all the fellows outside.

516
00:58:00.840 --> 00:58:01.540
Rahul Joshi .: Oh, okay.

517
00:58:01.540 --> 00:58:04.410
Faculty (Olympus): separated this, and get thatâ€¦ and get the wholeâ€¦

518
00:58:05.920 --> 00:58:06.809
Rahul Joshi .: Got it, sir, thank you.

519
00:58:06.810 --> 00:58:19.100
Faculty (Olympus): Okay, don't do equal to. Floating point arithmetic, never do equal to, always look in a range. Less than, greater than is okay, but don't ever say X squared plus Y squared equal to zero. You will not findâ€¦ you may not find any points, you may find two points, right?

520
00:58:19.440 --> 00:58:21.039
Faculty (Olympus): Not 3 points, or 4 points.

521
00:58:21.040 --> 00:58:33.179
Lad Prachikumari Vijaykumar .: That's a quick question. Sir, sorry, just a quick question on this. Same, I'm pasting in chat. I'm not able to understand, meaning of this area of circle is pi.

522
00:58:33.630 --> 00:58:36.129
Lad Prachikumari Vijaykumar .: And the area of square is 4.

523
00:58:36.310 --> 00:58:40.990
Lad Prachikumari Vijaykumar .: So, fraction of point inside estimateâ€¦ Pi by 4.

524
00:58:41.490 --> 00:58:47.549
Lad Prachikumari Vijaykumar .: Print your estimate of pi and its absolute error. Soâ€¦

525
00:58:48.280 --> 00:58:51.210
Faculty (Olympus): No, you're asking about an exercise question that was given to you.

526
00:58:52.120 --> 00:58:53.740
Faculty (Olympus): This is not the time for that.

527
00:58:56.090 --> 00:59:01.000
Faculty (Olympus): So how will you estimate the area? You count the number of dots inside the square, like this, using a condition.

528
00:59:01.220 --> 00:59:03.120
Faculty (Olympus): No, no, no, total number of fillers.

529
00:59:07.600 --> 00:59:08.320
Lad Prachikumari Vijaykumar .: Boom.

530
00:59:11.590 --> 00:59:13.759
Lad Prachikumari Vijaykumar .: But that is a Piyh square, right?

531
00:59:16.270 --> 00:59:17.710
Faculty (Olympus): Yeah, soap?

532
00:59:18.870 --> 00:59:20.659
Faculty (Olympus): I didn't understand, what's the question?

533
00:59:21.190 --> 00:59:25.220
Faculty (Olympus): Area of this circle should be pi r squared, okay. What is R here? R is 1.

534
00:59:26.020 --> 00:59:26.370
Lad Prachikumari Vijaykumar .: Goodness.

535
00:59:26.370 --> 00:59:27.400
Faculty (Olympus): circulate.

536
00:59:29.320 --> 00:59:31.669
Faculty (Olympus): But if I'm only looking at this first quadrant.

537
00:59:32.280 --> 00:59:35.609
Faculty (Olympus): It'll be 5x4. It depends on the question that was asked.

538
00:59:38.690 --> 00:59:39.580
Lad Prachikumari Vijaykumar .: Okay.

539
00:59:40.450 --> 00:59:42.979
Lad Prachikumari Vijaykumar .: I willâ€¦ I will try by myself.

540
00:59:43.240 --> 00:59:48.579
Abhineet Bansal: I think the confusing part is, how is X squared plus Y square defining a circle?

541
00:59:50.160 --> 00:59:50.840
Lad Prachikumari Vijaykumar .: No, no.

542
00:59:50.840 --> 00:59:52.440
Siddharth Digambar Kulkarni .: What is mathematics?

543
00:59:52.440 --> 00:59:55.540
Faculty (Olympus): That basic mathematics.

544
00:59:56.750 --> 00:59:59.510
Faculty (Olympus): I don't thinkâ€¦ I don't think that was a question, but yeah.

545
00:59:59.510 --> 01:00:05.359
Lad Prachikumari Vijaykumar .: No, no, that is not the question. Actually, I'm confused about 5x4 something, soâ€¦

546
01:00:05.360 --> 01:00:09.049
Faculty (Olympus): It's okay, don'tâ€¦ it's okay. Maybe ask the TAs today at 9.30?

547
01:00:09.050 --> 01:00:14.259
Lad Prachikumari Vijaykumar .: Yeah, sure, sure. Actually, in last session, I did not get a chance, so that'sâ€¦

548
01:00:14.340 --> 01:00:21.229
Faculty (Olympus): No problem, no problem, okay. You can even ask ChatGPT, they're sometimes very good at solving these things and telling, orâ€¦

549
01:00:21.230 --> 01:00:25.820
Lad Prachikumari Vijaykumar .: Sir, already tried, but still not, so that's why.

550
01:00:25.820 --> 01:00:27.169
Faculty (Olympus): Okay, fine, perfect.

551
01:00:27.590 --> 01:00:34.520
Faculty (Olympus): Okay, I'm gonna moveâ€¦ See, everybody is complaining that a work pressure.

552
01:00:34.860 --> 01:00:38.300
Faculty (Olympus): See, my first thing is, if you're complaining about those things.

553
01:00:38.970 --> 01:00:43.840
Faculty (Olympus): SCB is one piece of software. I understand if you have an office laptop and you have to ask.

554
01:00:44.040 --> 01:00:47.869
Faculty (Olympus): No, someone to install stuff, that's gonna take time, I agree.

555
01:00:48.030 --> 01:00:54.069
Faculty (Olympus): I'm sure you must have some personal machine where you can install SAP. SAP is not that complicated.

556
01:00:54.260 --> 01:01:00.860
Faculty (Olympus): They're not asking you to install anything on your machine, just need to install SCB. But SCB is a hard requirement, in the sense that

557
01:01:01.510 --> 01:01:05.969
Faculty (Olympus): You must either have Mac or Windows, so I assume most of you don't have that problem.

558
01:01:06.320 --> 01:01:10.540
Charu .: But, sir, it was a very short notice, like, we were informed last Saturday only.

559
01:01:10.540 --> 01:01:14.210
Faculty (Olympus): But you should have known that they don't have a quiz. When do you expect me to do the quiz?

560
01:01:15.000 --> 01:01:16.900
Faculty (Olympus): You can do it right before the mid-summer, right?

561
01:01:16.900 --> 01:01:22.180
Charu .: But we should know before 2 weeks when there's a software installation. See, I just got free from my officeâ€¦

562
01:01:22.180 --> 01:01:23.140
Faculty (Olympus): one click.

563
01:01:23.530 --> 01:01:28.889
Faculty (Olympus): You see, the installation is a single click, you just need double click and it's installed, right? I don't understand the difficulty.

564
01:01:29.040 --> 01:01:34.290
Charu .: No, sir, it's not a one-click. I'm installing on Mac, my personal laptop.

565
01:01:34.290 --> 01:01:34.900
Faculty (Olympus): That's good.

566
01:01:34.900 --> 01:01:48.680
Charu .: some issue, and apart from that, we have to prepareâ€¦ like, we are working, right? So we have aâ€¦ and this is a year end. We have important deliverables. See, I'm working since morning 5, and I just, you know, I just finished the call.

567
01:01:48.680 --> 01:01:52.449
Faculty (Olympus): Anyway, okay, I really can't do too much, okay, at this point.

568
01:01:52.720 --> 01:01:53.520
Faculty (Olympus): Fine.

569
01:01:55.650 --> 01:02:00.379
Faculty (Olympus): Maybe you can send a ticket or whatever, and somebody will help you with this. It's difficult.

570
01:02:00.850 --> 01:02:16.840
Faculty (Olympus): Okay, so I have to move on, because at this rate, I will have to take one full course just for half of this material. So, we have a lot to do. I know a lot of you are getting very stressed about this. Please remember, this is only 5 marks. It's not going to be very difficult. You know, some of you are finding this

571
01:02:18.250 --> 01:02:19.270
Faculty (Olympus): Difficult.

572
01:02:22.950 --> 01:02:23.810
Faculty (Olympus): All right.

573
01:02:30.100 --> 01:02:37.380
Faculty (Olympus): Alright, so, do people want one more TA session over and above this 9.30 to 11?

574
01:02:39.000 --> 01:02:42.590
Anuj Kumar Gupta .: It depends, actually, how it goes, actually, today.

575
01:02:42.790 --> 01:02:46.910
Anuj Kumar Gupta .: Because we have the couple of questions on the copying of Jupyter, actually.

576
01:02:47.290 --> 01:02:49.779
Anuj Kumar Gupta .: to our, theâ€¦ Yeah, soâ€¦

577
01:02:50.210 --> 01:02:51.150
Rahul Joshi .: We think we just ordered.

578
01:02:51.150 --> 01:02:58.809
Faculty (Olympus): today, if you need more, you please tell the TA immediately, and I'll see ifâ€¦ I'll talk to the TAs after the TA session tonight. I mean, they need

579
01:02:59.260 --> 01:03:01.350
Faculty (Olympus): Cover one more, we'll do one more, that's okay.

580
01:03:01.350 --> 01:03:02.120
Anuj Kumar Gupta .: Perfect.

581
01:03:02.120 --> 01:03:05.570
Faculty (Olympus): we can do. Postponing the whole thing for the whole class, this is very.

582
01:03:05.570 --> 01:03:13.369
Anuj Kumar Gupta .: No, no, that's what we need to sell. I mean, the thing only PR-facing is that copying from the Jupyter notebook, right, from the portal is not.

583
01:03:13.370 --> 01:03:20.970
Faculty (Olympus): I willâ€¦ I willâ€¦ I will ask them to see if that can be fixed. But even otherwise, your programs are going to be very small, they're not going to be lumbar.

584
01:03:20.970 --> 01:03:31.299
Dinesh Devnath Yadav .: Even, sir, when I copy from Jupyter to export, right, even it is giving the syntax error. Syntax, not the syntax, indentation error.

585
01:03:31.300 --> 01:03:37.449
Faculty (Olympus): Indentation error you will run into with Yucks, simply because there is mixing of tabs and spaces when you write.

586
01:03:37.450 --> 01:03:37.939
Dinesh Devnath Yadav .: No, no.

587
01:03:37.940 --> 01:03:38.870
Faculty (Olympus): You're just, huh.

588
01:03:38.870 --> 01:03:41.920
Dinesh Devnath Yadav .: Yeah, I have directly copied from,

589
01:03:42.330 --> 01:03:45.280
Dinesh Devnath Yadav .: Jupyter. In Jupyter, it was working, andâ€¦

590
01:03:45.570 --> 01:03:47.430
Dinesh Devnath Yadav .: Simply, I have coffee in the past.

591
01:03:47.430 --> 01:03:52.540
Faculty (Olympus): I've seen this numerous times. I'm pretty sure there's a mixture of tabs and spaces somewhere.

592
01:03:52.970 --> 01:03:54.970
Dinesh Devnath Yadav .: Oh, okay.

593
01:03:55.110 --> 01:03:58.560
Faculty (Olympus): So you have justâ€¦ you have 5 lines of code, you can just look at it and finish it.

594
01:03:58.560 --> 01:03:59.980
Anuj Kumar Gupta .: I mean, like I said, I meanâ€¦

595
01:03:59.980 --> 01:04:00.490
Dinesh Devnath Yadav .: Yeah.

596
01:04:00.490 --> 01:04:01.960
Anuj Kumar Gupta .: The other is something, like, we can.

597
01:04:01.960 --> 01:04:12.540
Faculty (Olympus): Okay, fine. I'm going to move on. We have to start with simple text processing. I'm hoping to at least finish some of this today. So, the next thing we're going to look at is sample text processing with Python.

598
01:04:12.630 --> 01:04:24.280
Faculty (Olympus): And the idea here is we look at working with strings, we'll look at it again mostly by example, we'll quickly look at reading and writing simple text files, and then we look at working with dictionaries and look at other tools.

599
01:04:26.440 --> 01:04:35.910
Faculty (Olympus): So, the first thing is, you've already seen a lot of these, anything within quotes is a string, but again, don't try something like this, okay? This backtick and front tick.

600
01:04:36.020 --> 01:04:47.379
Faculty (Olympus): Right? Is not allowed. Whatever thing you have in the front is the same character you should use at the end of the string, okay? So it should not be backtick, and thenâ€¦ in fact, backtick will not do what you want.

601
01:04:47.490 --> 01:04:49.560
Faculty (Olympus): So, single quotes will work.

602
01:04:49.750 --> 01:04:58.279
Faculty (Olympus): Double quotes will work, okay? So be careful about Unicode characters that look like single code. What we mean here is the simple, you know.

603
01:04:58.570 --> 01:05:03.090
Faculty (Olympus): character that is available on your keyboards, right? The single quote and double quote.

604
01:05:03.900 --> 01:05:13.609
Faculty (Olympus): Now, in addition to this, we have triple-coated strings, we have already seen this. The nice thing about triple-coated strings is you can create very long strings, okay? So, for example.

605
01:05:14.850 --> 01:05:19.789
Faculty (Olympus): Some may ask, why do you need all of this? It's very convenient when I want to put a double coat inside a single coat.

606
01:05:20.920 --> 01:05:24.889
Faculty (Olympus): So here's a quotation inside a string, so do or do not know price, etc.

607
01:05:25.070 --> 01:05:30.430
Faculty (Olympus): Okay, and a single quote, if you put here, you can do that. All of these are legal strings.

608
01:05:30.910 --> 01:05:38.290
Faculty (Olympus): So basically, if you have an outer coat, inside that coat, you can put anotherâ€¦ the opposite, the, you know, other kind of coat. Double quote outside, single quote.

609
01:05:38.760 --> 01:05:44.789
Faculty (Olympus): But the nice thing about triple-coated strings is that you can span multiple lines, like this, whereas you can't do the same thing here.

610
01:05:44.910 --> 01:06:03.929
Faculty (Olympus): Okay, you'll have to basically do something like this, okay? Put a backspace at the previous line, whereas here, you don't need any such thing. It's just, you can put as much lineâ€¦ as many lines of text as you want. So all documentation strings, for example, will always be in triple-coded single quotes, triple-coded strings, single quotes, or double quotes.

611
01:06:05.220 --> 01:06:17.759
Faculty (Olympus): Now, accessing strings is just like this, so we have this string here, hello, if I don't print W , so first fellow, second fellow, and this, as you always already know, it's the last.

612
01:06:17.900 --> 01:06:19.330
Faculty (Olympus): H-E-O.

613
01:06:20.250 --> 01:06:22.940
Faculty (Olympus): Same way, len will produce the length of the string.

614
01:06:23.120 --> 01:06:29.629
Faculty (Olympus): But one thing to keep in mind with strings in Python is that they are immutable, okay? Like, tuples, you can't change

615
01:06:29.700 --> 01:06:45.139
Faculty (Olympus): a string. So if I can't say, okay, make this uppercase, you know, just change the first fellow to an uppercase H, it's going to give you an exception. It's going to say type error, STR object, so STR, the type of W, so let me,

616
01:06:45.860 --> 01:06:46.590
Faculty (Olympus): Oops.

617
01:06:46.840 --> 01:06:48.170
Faculty (Olympus): So if I go typeâ€¦

618
01:06:48.520 --> 01:06:58.129
Faculty (Olympus): of W, it'll tell me that it's a string type, okay, str. So typeâ€¦ the STR object does not support item ascend. This is exactly the same error that you'll get to the top.

619
01:06:59.970 --> 01:07:12.540
Faculty (Olympus): Now, so just keep this in mind when you do string process. If there is something that says, give me uppercase, it's going to give you a fresh string. It is not going to modify that string in place, because you cannot modify strings in place. Strings in Python are immutable.

620
01:07:13.190 --> 01:07:19.750
Faculty (Olympus): So here is an example of other kind of string operations. So you can say S plus P is going to do the concatenation of the two.

621
01:07:19.940 --> 01:07:32.790
Faculty (Olympus): S into 4 is going to give me 4 times, just like a list, same thing. But this is obviously illegal, okay? Because it'll say type error, can't multiply sequence by non-integer type of STR. You've already seen this with lists, same kind of thing.

622
01:07:34.070 --> 01:07:40.200
Faculty (Olympus): But just like lists, we also have methods, for lists, for strings, right? So if you take this hello world.

623
01:07:43.050 --> 01:07:45.420
Faculty (Olympus): There are many built-in methods for strings.

624
01:07:46.180 --> 01:07:50.670
Faculty (Olympus): So this one is, okay, does it start with this character? Please note.

625
01:07:51.120 --> 01:08:00.330
Faculty (Olympus): Things are, case sensitive. So, if I did this, it will be true, but if I did this, it will be false. So, case sensitivity does.

626
01:08:00.800 --> 01:08:03.370
Faculty (Olympus): Same way, there's an endsWith method, which says.

627
01:08:04.180 --> 01:08:19.330
Faculty (Olympus): you know, allows you to check if some substring, this original string A ends with some substring, you can check for this. You can convert A to an uppercase, and notice that here, A is unchanged. This is going to be a new string, which is all uppercase.

628
01:08:19.790 --> 01:08:24.879
Faculty (Olympus): Same way you want to lowercase something, this will convert everything to lowercase case.

629
01:08:25.930 --> 01:08:45.420
Faculty (Olympus): There are other useful methods as well, so sometimes you may have some extra space, right, after and before the word. If you do A.script, it will remove this, you know, space before and after, okay? There are other methods as well, so if you look at A.Tab, you will see a whole bunch of other methods. You can look atâ€¦ there are some other variants of script.

630
01:08:45.939 --> 01:08:48.310
Faculty (Olympus): I'm just walking you through some of the most common.

631
01:08:48.540 --> 01:08:58.560
Faculty (Olympus): B.Index will show you the first occurrence of this substring in that, okay, so it will tell you lowest index in S, where the substring sub is found, such that sub is contained within S starter.

632
01:08:59.240 --> 01:09:11.099
Faculty (Olympus): So there are additional optional arguments as well, so you can read the doc string to understand this. The idea here is, this will tell you the first location where this double Lâ€¦ LL is going to show up. So if you have two places, it'll only show you the first.

633
01:09:11.890 --> 01:09:23.700
Faculty (Olympus): you can use replace to, again, generate a new string that will replace whatever string withâ€¦ whatever substring with whatever word, right? So if you say hello word, and say, replace hello with goodbye, it will do a goodbye word.

634
01:09:23.830 --> 01:09:25.830
Faculty (Olympus): Anuj, do you have a quick question?

635
01:09:28.710 --> 01:09:31.909
Anuj Kumar Gupta .: Can you go above a screen?

636
01:09:32.250 --> 01:09:33.250
Anuj Kumar Gupta .: Good setup.

637
01:09:34.100 --> 01:09:36.420
Anuj Kumar Gupta .: Since we are talking about this in Greater Akshay.

638
01:09:36.540 --> 01:09:41.040
Anuj Kumar Gupta .: So, can you go a bit up down, where we are actually changing the cell?

639
01:09:41.520 --> 01:09:43.389
Anuj Kumar Gupta .: Format of it?

640
01:09:44.520 --> 01:09:46.240
Anuj Kumar Gupta .: a bit thumbs up.

641
01:09:48.090 --> 01:09:53.220
Anuj Kumar Gupta .: So, when we're, changing it, right, sir, actually, to the word to hello or something.

642
01:09:53.890 --> 01:09:56.850
Anuj Kumar Gupta .: So, since this is, immutable, right?

643
01:09:57.370 --> 01:09:58.670
Faculty (Olympus): Veena, we can't change it.

644
01:09:59.070 --> 01:09:59.780
Anuj Kumar Gupta .: Hmm.

645
01:10:01.030 --> 01:10:02.960
Faculty (Olympus): So, what is the question? I don't understand your question.

646
01:10:03.130 --> 01:10:09.179
Anuj Kumar Gupta .: We can't change it, right? I mean, but downside, I mean, we are changingâ€¦ it's not creating a copy of it, right?

647
01:10:09.180 --> 01:10:10.859
Faculty (Olympus): A new string, I've already explained.

648
01:10:10.860 --> 01:10:11.859
Anuj Kumar Gupta .: Creating a copy.

649
01:10:11.860 --> 01:10:16.150
Faculty (Olympus): I already said this, when you do A.upper, it creates a new string, it does not modify A.

650
01:10:18.620 --> 01:10:20.889
Anuj Kumar Gupta .: Okay, let me modify that thing.

651
01:10:22.450 --> 01:10:24.640
Anuj Kumar Gupta .: Because it was immutable, actually.

652
01:10:24.640 --> 01:10:26.780
Faculty (Olympus): Again, please try this on your own notebooks.

653
01:10:27.050 --> 01:10:27.770
Anuj Kumar Gupta .: Here's delicious.

654
01:10:27.770 --> 01:10:28.370
Faculty (Olympus): thisâ€¦

655
01:10:28.700 --> 01:10:30.010
Anuj Kumar Gupta .: Yeah, exactly.

656
01:10:30.360 --> 01:10:30.920
Faculty (Olympus): Okay.

657
01:10:31.150 --> 01:10:32.030
Anuj Kumar Gupta .: Yeah, thank you, Susan.

658
01:10:32.030 --> 01:10:33.379
Faculty (Olympus): Okay, that's the Victus.

659
01:10:34.190 --> 01:10:36.009
Faculty (Olympus): The AO stands, too.

660
01:10:36.370 --> 01:10:39.629
Faculty (Olympus): Yeah, please try these things on the notebook if you have questions.

661
01:10:39.830 --> 01:10:43.740
Faculty (Olympus): Komala, I'll come back to you a little later, okay?

662
01:10:44.080 --> 01:10:59.610
Faculty (Olympus): The next set of methods that are very useful is split and join. These are very useful when you're doing string crossing kind of things. So, for example, let's say we have these characters A, B, and C, with space between them. If I do cars.split, I will get a list

663
01:11:00.110 --> 01:11:01.520
Faculty (Olympus): of values.

664
01:11:01.670 --> 01:11:08.780
Faculty (Olympus): of, you know, substrings, which are split by default on whitespace. Okay, so if we look at the split,

665
01:11:09.300 --> 01:11:18.770
Faculty (Olympus): It says split separationâ€¦ separator is none. And if it is none, it will be theâ€¦ anywhitespace character, including slash N, slash R, slash D, and slash F.

666
01:11:18.770 --> 01:11:32.419
Faculty (Olympus): And you basically break on all of those, okay? But if you say, look, I have comma, okay, and I want to split with comma, you can use that also, okay? So we look at that in a brief file. So again, this takes a string and converts this into a list.

667
01:11:32.690 --> 01:11:37.299
Faculty (Olympus): No? Ofâ€¦ A, D, and C. There are 3 elements in this.

668
01:11:38.580 --> 01:11:56.010
Faculty (Olympus): Now, there's an opposite operation also. Supposing I want to say, I give you a list of fellows, and I want you to give me ABC from them, a string ABC from them. JOIN will do an opposite of split. So, split will take a string and split out a list. List will take aâ€¦ sorry, join will take a list and give you back a string.

669
01:11:56.630 --> 01:11:59.490
Faculty (Olympus): So, these two are kind of opposites themselves.

670
01:11:59.590 --> 01:12:11.300
Faculty (Olympus): So here, for example, is a similar, another example, where I have, alpha is the variable here I'm using, is ABC, and I'm going to do this on this string. So this is the string.

671
01:12:12.130 --> 01:12:19.489
Faculty (Olympus): And this fellow is going to be joined with A, B, and C, which means it'll be A, comma space B, comma space C.

672
01:12:19.780 --> 01:12:27.839
Faculty (Olympus): This is what you would get. So notice that the syntax is maybe a little weird for you. What this is telling you is this is the separator on which these fellows are to be joined.

673
01:12:28.870 --> 01:12:44.869
Faculty (Olympus): So, if you do some examples of this, this will become more, familiar to you. Now, if you want to go back from this ABC, A comma, B, C, right? We can again do split, but use comma space as the separator. So any substring can be used as a separate. So now I've brought you back AB itself.

674
01:12:45.110 --> 01:13:03.900
Faculty (Olympus): So you can imagine where this is useful. Imagine I have a text file with values separated by commas, with reading a CSV file. Don't write a reader for CSV, there are plenty of good readers, much better readers of CSV. But let's say you had to write something for some, you know, bespoke file format, then you want to split it, you want to parse the values into individual things, you can use things like split.

675
01:13:03.910 --> 01:13:05.170
Faculty (Olympus): Okay, things like that.

676
01:13:06.090 --> 01:13:09.270
Faculty (Olympus): The next topic is a little tricky,

677
01:13:09.890 --> 01:13:15.690
Faculty (Olympus): So if you know C, this syntax will make a lot of sense. If you do not know C,

678
01:13:15.690 --> 01:13:26.470
Faculty (Olympus): this will be, like, what on earth is this percentage S? So, I am not going to really spend much time discussing this, I'm just saying that this kind of formatting options are available in Python.

679
01:13:26.470 --> 01:13:40.949
Faculty (Olympus): So you can do things like what you would do in C. You can say X is percentage S, Y is percentage S, in which case X and Y will be represented as strings and printed, you know, inserted, injected into that string. So X is 1 and Y is 1.

680
01:13:41.750 --> 01:13:45.120
Faculty (Olympus): Okay, so what this will essentially do is it will call str on this.

681
01:13:45.990 --> 01:13:50.130
Faculty (Olympus): Okay, so if you don't know what STR is, STR ofâ€¦

682
01:13:51.300 --> 01:13:59.780
Faculty (Olympus): X. It'll give me a string form of whatever the object you pass to it. So if I say str of y, it'll give me a string form of that.

683
01:13:59.780 --> 01:14:17.509
Faculty (Olympus): This is 1.234. So the idea here is you can interpolate these values by using these special formatter kind of things, and these things only C programmers or, you know, people who have some experience with programming will understand. If you do not know this, it is okay, they're not going to insist that you understand this.

684
01:14:17.510 --> 01:14:22.349
Faculty (Olympus): You should at least learn how to use what are called F-strings, and I'll come to F-strings in a short while.

685
01:14:22.490 --> 01:14:25.330
Faculty (Olympus): Pretty quickly.

686
01:14:26.490 --> 01:14:32.510
Faculty (Olympus): Someone had some questionsâ€¦ okay, no one has raised their hands. I'll come back to questions. Please raise your hands in the next,

687
01:14:32.750 --> 01:14:41.100
Faculty (Olympus): Next break, I will look at, you know, answering some questions. So, F-strings are much easier, so if you know C, you know, this is kind ofâ€¦ you can use this, that's fine.

688
01:14:41.100 --> 01:14:55.119
Faculty (Olympus): But F-strings are super convenient and extremely easy to use. Again, F-strings have their own mini-language. It'sâ€¦ it can get pretty complicated, but there's reasonable documentation that you can read to understand. But I'm going to just show you the basic elements of F-strings.

689
01:14:55.420 --> 01:15:04.379
Faculty (Olympus): So here's a simple example. We'll start with 3 variables that we have. We have a string here, we have two integers, age and weight. So name, RAM, age 25, weight is 60, okay?

690
01:15:04.590 --> 01:15:12.130
Faculty (Olympus): Now, I want to print a string, okay? And notice inside the string here, oops, is aâ€¦

691
01:15:12.360 --> 01:15:21.240
Faculty (Olympus): There's inside the print function, there is this string. But there's this funny character F in front of the string, and that's the reason it's called an F string, right? F string.

692
01:15:21.970 --> 01:15:25.450
Faculty (Olympus): So it's basically a string with a little character in front of it, called F.

693
01:15:26.440 --> 01:15:28.350
Faculty (Olympus): This makes this an F string.

694
01:15:28.460 --> 01:15:35.190
Faculty (Olympus): And inside this, there is this special syntax. The syntax is, you put curly braces and the name of the variable.

695
01:15:35.680 --> 01:15:41.809
Faculty (Olympus): Okay? So you can say bracket, curly bracket name is curly bracket age, and weighs

696
01:15:41.920 --> 01:15:57.239
Faculty (Olympus): And these names are pulled from the local namespace, right? So whatever variables you have right here will be available, and they will be automatically interpolated. So if you run this, say, RAM is 25 and weighs 65 inches. And notice that this string is very easy to read.

697
01:15:58.050 --> 01:16:00.190
Faculty (Olympus): You don't have to do anything major here.

698
01:16:00.370 --> 01:16:02.970
Faculty (Olympus): You can use either small if or capital if.

699
01:16:03.090 --> 01:16:04.389
Faculty (Olympus): Both are and ligand.

700
01:16:04.540 --> 01:16:12.370
Faculty (Olympus): But you can do a lot of other interesting, cool things inside. Inside this curly brace, we can actually call methods. You can call, you know, methods of that object.

701
01:16:12.470 --> 01:16:24.639
Faculty (Olympus): So you can say, no, no, no, I want RAM in uppercase, right? Or I want to say I want to print age plus 1 for whatever reason your age started wrong, or whatever. You know, and you want to say where it should be, you know, you may have some function which does

702
01:16:24.640 --> 01:16:33.409
Faculty (Olympus): KG to pound, or whatever else, right? You can do all of those things inside those curly braces. So I run this, say, capital Raum is 26, and weigh 65.

703
01:16:34.340 --> 01:16:41.159
Faculty (Olympus): Now, here is where this thing gets a little more complicated. So, these simple cases are fine. Usually, that is enough for you.

704
01:16:41.270 --> 01:16:50.660
Faculty (Olympus): But you can also do slightly more complicated things. So, for example, if I say, look, show me age, in this case, it's all right. So here, I'm simply saying.

705
01:16:50.890 --> 01:17:10.539
Faculty (Olympus): represent age as a decimal, okay? And wait, I don't want to see multiple, so if it's 60.123, don't show me 123, just show me 60.1. So, you can say, put the name of the variable, colon, and you can do this format specifier, which basically says 0.1F, which means show me only one decimal place.

706
01:17:11.310 --> 01:17:14.560
Faculty (Olympus): So you do that, and that's what you'll get, 60.0 kgs.

707
01:17:15.280 --> 01:17:29.410
Faculty (Olympus): You can also do strange things like this padding. So supposing you want to create a table, right, and you want to have everything aligned, right? So you can put a width here, you can give it an integer, and you make sure that the name fits within 10 spaces, okay?

708
01:17:31.260 --> 01:17:37.429
Faculty (Olympus): by default, put them. So if you want a table, and you want to align everything by columns, you can do these kind of things.

709
01:17:37.530 --> 01:17:51.849
Faculty (Olympus): Now, I'm not going to spend too much time on this, but this, again, is something that you should be aware of. I'm not going to ask you exam questions of strange, crazy string formatters, so don't worry about this, don't be asked this in an exam.

710
01:17:51.950 --> 01:18:08.340
Faculty (Olympus): But I'm giving you links to the documentation that you can read, if you really want to understand this and learn this a little better. It'sâ€¦ you might see code being used where people do things like this. This is a good way to, you know, read the documentation to understand how you can do these kind of interesting formatting.

711
01:18:08.540 --> 01:18:16.240
Faculty (Olympus): So, in most of the cases, you may not need this. This is only necessary if you're sometimes writing a library or something where you want to do some

712
01:18:16.600 --> 01:18:19.979
Faculty (Olympus): Careful formatting of your, things you're printing.

713
01:18:21.300 --> 01:18:25.350
Faculty (Olympus): All right, so let's, pause for a few questions. Roshan?

714
01:18:25.750 --> 01:18:31.179
Roshan Mathane .: Yeah, so quickly, this padding is by default, right padding, or can be defined on the.

715
01:18:31.180 --> 01:18:34.489
Faculty (Olympus): Yeah, I think you can change theâ€¦ whether it's left padding or right padding.

716
01:18:34.930 --> 01:18:37.560
Faculty (Olympus): Don't ask me to remember, because I don't remember, and I'm not going.

717
01:18:37.560 --> 01:18:38.800
Roshan Mathane .: But we can do that, right?

718
01:18:39.070 --> 01:18:39.999
Faculty (Olympus): I think you can, yes.

719
01:18:40.000 --> 01:18:41.520
Roshan Mathane .: Okay, thanks.

720
01:18:43.830 --> 01:18:45.219
Faculty (Olympus): No other questions?

721
01:18:46.000 --> 01:18:48.210
Siddharth Digambar Kulkarni .: D stands for decimal, right?

722
01:18:48.210 --> 01:18:58.869
Faculty (Olympus): Yes, B stands for despot. So if you look at the F string docs in the format specification, it'll tell you all of these things. What are all of these? You know, so it'sâ€¦ you'll have to read it a little carefully to understand.

723
01:18:59.250 --> 01:19:04.760
Faculty (Olympus): Okay? But it's there. Again, I'm not expecting that you learned this, butâ€¦

724
01:19:04.940 --> 01:19:22.139
Faculty (Olympus): at the very least, you should know how to use basic F-strings. Forget about the format specifiers. But if you see a format specifier, don't get confused. All it is is tellingâ€¦ this is some additional detail about how to format this quantity inside this string. That's really all it is doing.

725
01:19:24.980 --> 01:19:25.930
Faculty (Olympus): Abhineet?

726
01:19:26.340 --> 01:19:29.489
Abhineet Bansal: So we can apply formulas also, right?

727
01:19:29.490 --> 01:19:29.910
Faculty (Olympus): Yeah.

728
01:19:29.910 --> 01:19:33.320
Abhineet Bansal: Converted into pounds, so multiply by 0.5, something like that.

729
01:19:33.330 --> 01:19:37.370
Faculty (Olympus): Yeah, I would imagine so. Let's try this.

730
01:19:45.320 --> 01:19:47.609
Faculty (Olympus): No, it's not the right size.

731
01:19:50.380 --> 01:19:51.060
Faculty (Olympus): Excellent.

732
01:19:53.480 --> 01:19:54.210
Faculty (Olympus): Yeah.

733
01:19:57.060 --> 01:19:57.450
Abhineet Bansal: Got it.

734
01:19:57.450 --> 01:20:00.270
Faculty (Olympus): Again, try all of these things.

735
01:20:02.870 --> 01:20:05.289
Faculty (Olympus): Try, play around with this. Okay, fine.

736
01:20:07.820 --> 01:20:16.149
Faculty (Olympus): Alright, so no more questions, so great. So the other couple ofâ€¦ one very useful operator that is used very often in

737
01:20:16.390 --> 01:20:33.990
Faculty (Olympus): any container in Python is the in operator, okay? So if I have a list of fruits, sorry, a string of fruits, in this case, apple, banana, and pear, you can just check whether apple is inside this fruits by saying apple in fruits, okay? Or if you're worried, hey, apple is the first element, so it doesn't have to be.

738
01:20:34.570 --> 01:20:36.709
Faculty (Olympus): Banana and fruits is also going to be good.

739
01:20:36.840 --> 01:20:40.629
Faculty (Olympus): Okay? Same way, potato and fruits is going to give me thoughts.

740
01:20:40.790 --> 01:20:41.790
Faculty (Olympus): But let us know.

741
01:20:42.770 --> 01:20:53.490
Faculty (Olympus): All right. So, very quick exercise here. I'm going to just run through this exercise, because, you know, we're short on time, and I've anyway given you the solution. So, given a two-digit integer.

742
01:20:53.740 --> 01:20:55.639
Faculty (Olympus): Find the digits of the number.

743
01:20:55.770 --> 01:20:58.889
Faculty (Olympus): Okay? So, for example, let's say X is 38,

744
01:20:59.080 --> 01:21:03.879
Faculty (Olympus): I want you to give me A is 3, and B is equal to 8, using X.

745
01:21:04.230 --> 01:21:09.950
Faculty (Olympus): Right? So one easyâ€¦ one way of doing this is, if you know it's two digits, you just find

746
01:21:10.220 --> 01:21:11.979
Faculty (Olympus): floor divide X.

747
01:21:12.170 --> 01:21:15.420
Faculty (Olympus): And then you find the reminder of this, and you can assert that this is true.

748
01:21:15.570 --> 01:21:16.390
Faculty (Olympus): Right?

749
01:21:16.940 --> 01:21:28.460
Faculty (Olympus): This does the job. But here's a sneaky solution, because here I can say, make this into a string, then find the first part by just taking integer of that first fellow, and the integer of the second fellow.

750
01:21:28.960 --> 01:21:30.349
Faculty (Olympus): And this'll also work.

751
01:21:30.690 --> 01:21:48.429
Faculty (Olympus): Now, this is nice, because if I have a long string, and I don't know how many digits it has, you can even count the number of digits by doing trick strings, right? Even an arbitrary integer, count the number of digits it has, right? Sneaky solution is, you just convert this into a string and find the length of that. You get the number of digits. You don't have to doâ€¦

752
01:21:48.650 --> 01:21:52.109
Faculty (Olympus): While loop, divide until this fellow goes to zero, none of that.

753
01:21:54.000 --> 01:21:55.220
Faculty (Olympus): Alright? Soâ€¦

754
01:21:55.220 --> 01:21:55.960
Saurav kumar: works in, right?

755
01:21:56.000 --> 01:22:01.190
Faculty (Olympus): Doing these sort of string manipulations can sometimes solve a problem in a very different way.

756
01:22:01.370 --> 01:22:03.080
Faculty (Olympus): That'sâ€¦ that's all I'm trying to solve.

757
01:22:04.540 --> 01:22:07.950
Faculty (Olympus): All right, any questions at this point?

758
01:22:13.500 --> 01:22:17.520
Savalo Naroji: But if we want to print curly brackets in the string.

759
01:22:18.340 --> 01:22:20.730
Faculty (Olympus): Read the documentation. What do you think you'll have to do?

760
01:22:21.950 --> 01:22:24.680
Savalo Naroji: Some sort of escape character?

761
01:22:25.770 --> 01:22:28.620
Faculty (Olympus): Wellâ€¦ Let's do this.

762
01:22:31.250 --> 01:22:33.469
Abhineet Bansal: Put the curly bracket within inverted.

763
01:22:34.550 --> 01:22:36.000
Saurav kumar: double ports, curly bit.

764
01:22:36.000 --> 01:22:37.270
Abhineet Bansal: Yeah, within double quotes.

765
01:22:37.530 --> 01:22:38.260
Abhineet Bansal: Yeah.

766
01:22:40.210 --> 01:22:40.790
Faculty (Olympus): Correct.

767
01:22:44.010 --> 01:22:45.420
Faculty (Olympus): Okay, you can do this.

768
01:22:47.480 --> 01:22:50.239
Saurav kumar: But if half bracket is there, then I would love toâ€¦

769
01:23:00.520 --> 01:23:01.150
Faculty (Olympus): Also, it's not.

770
01:23:01.150 --> 01:23:01.930
Saurav kumar: Of course.

771
01:23:06.350 --> 01:23:09.609
Faculty (Olympus): So how would you do something like that? I want a single half bracket.

772
01:23:12.310 --> 01:23:14.030
Faculty (Olympus): Remember, this is just a string.

773
01:23:14.130 --> 01:23:18.960
Faculty (Olympus): You can always decompose it. So you canâ€¦ don't need F-strings for everything. You can compose.

774
01:23:18.960 --> 01:23:20.199
Abhineet Bansal: It's normally pink.

775
01:23:22.110 --> 01:23:22.720
Faculty (Olympus): Sorry?

776
01:23:22.720 --> 01:23:24.159
Dinesh Devnath Yadav .: Maybe double quotes, single quote?

777
01:23:24.160 --> 01:23:30.219
Faculty (Olympus): No, no, if I want to compose a string, a string is just a fancy string, right? It's going to give you a string, this is just a string.

778
01:23:30.440 --> 01:23:35.879
Faculty (Olympus): So you can always add two silos. You can say, okay, put curly gray separately and do the F string for the interpolation elsewhere.

779
01:23:40.450 --> 01:23:41.080
Soumen Deb .: Slash.

780
01:23:41.330 --> 01:23:43.179
Faculty (Olympus): This may work. No, it doesn't work.

781
01:23:43.540 --> 01:23:45.649
Faculty (Olympus): Yeah, a string cannot include this.

782
01:23:46.130 --> 01:23:47.550
Faculty (Olympus): Saini Muslims.

783
01:23:47.870 --> 01:23:48.989
Faculty (Olympus): Say it doesn't alert.

784
01:23:50.710 --> 01:23:51.450
Faculty (Olympus): No.

785
01:23:53.140 --> 01:23:54.030
Faculty (Olympus): No.

786
01:23:54.370 --> 01:23:58.450
Anita Menon .: Just two curly braces of the same side, whatever we want to cut.

787
01:23:58.580 --> 01:23:59.460
Anita Menon .: That's okay.

788
01:24:01.950 --> 01:24:02.720
Faculty (Olympus): Not alone.

789
01:24:02.890 --> 01:24:03.300
Dinesh Devnath Yadav .: Brother.

790
01:24:03.300 --> 01:24:05.269
Anita Menon .: Not this. No, no, double, doubleâ€¦

791
01:24:05.270 --> 01:24:07.260
Dinesh Devnath Yadav .: quotes and single quote, sir, maybe.

792
01:24:07.260 --> 01:24:08.309
Ramneek Grover .: and thenâ€¦

793
01:24:08.310 --> 01:24:09.000
Dinesh Devnath Yadav .: Singhalcot.

794
01:24:09.480 --> 01:24:18.729
Faculty (Olympus): You guys try this on your own time, okay? So please try this by yourselves. There are 200 of you who can try all of these experiments. There's also the documentation that you can read.

795
01:24:18.920 --> 01:24:21.399
Faculty (Olympus): Okay? This is not important in this pump.

796
01:24:23.080 --> 01:24:26.899
Faculty (Olympus): And as I said, I'm not gonna ask questions, sneaky questions about this.

797
01:24:27.160 --> 01:24:34.029
Faculty (Olympus): Alright, next thing is reading and writing files. I think this is more important than figuring out how to take a single quote, curly brace, right?

798
01:24:35.890 --> 01:24:42.110
Faculty (Olympus): And you don't have to stick it inside an F string, is what I'm trying to say. There are other ways to do the same exact thing. You can justâ€¦

799
01:24:42.590 --> 01:24:47.929
Faculty (Olympus): Wherever you want the F string, you use an if string. Where you want to do the interpolation. Where you don't want the interpolation, leave it out.

800
01:24:48.240 --> 01:24:51.529
Faculty (Olympus): You don't need to just put everything into an F string because it's convenient.

801
01:24:51.980 --> 01:24:57.640
Faculty (Olympus): All right, so reading and writing files, again, very high-level introduction, there are much,

802
01:24:58.310 --> 01:25:12.459
Faculty (Olympus): There are lots of details about files that you need to be aware of, but at this point, we're just keeping it extremely simple. The simplest way you can open a file is just using the open built-in function. What this does is you give it a path, which is essentially

803
01:25:12.570 --> 01:25:14.140
Faculty (Olympus): In this case, a string.

804
01:25:14.470 --> 01:25:20.840
Faculty (Olympus): And this is, in this case, a relative path. If it is a, if you have something like

805
01:25:26.980 --> 01:25:31.999
Faculty (Olympus): Many of you are on Windows, so if you say F is equal to open and not on Windows.

806
01:25:32.320 --> 01:25:38.689
Faculty (Olympus): Then you say something like C colon backslash, right? We have a problem, because backslash and, let's say, new.

807
01:25:39.790 --> 01:25:44.980
Faculty (Olympus): This backslash new is not what you think it is, right? This new will become slash n.

808
01:25:45.050 --> 01:26:00.839
Faculty (Olympus): Slash n is a new line character. So the way you do this is you use what are called raw strings. I don't know if you have covered this before, but if you prepend an R character before this, it will not interpret this as a slash n. It will interpret this as slash.

809
01:26:00.930 --> 01:26:05.419
Faculty (Olympus): And N, okay? So, in such cases, you can do things like this.

810
01:26:05.640 --> 01:26:07.620
Faculty (Olympus): So, just keep this in mind.

811
01:26:09.040 --> 01:26:26.130
Faculty (Olympus): comment this out so someone doesn't execute it. Alright, so here, this is the name of a file. By default, files will be opened for reading, not for writing, okay? So if I wanted to just read the entire contents of this file, as soon as I do this, I get a file object for F.

812
01:26:26.220 --> 01:26:34.530
Faculty (Olympus): And F has a read method, where it can basically read the entire data. So if it's a multi-gigabyte file, don't do this. This will basically read that entire thing.

813
01:26:35.400 --> 01:26:46.639
Faculty (Olympus): Okay, and once you've finished reading the data, you must close a file. Okay, so always close the file using f.close. There's a smarter way of doing this, which we'll look at in a short while.

814
01:26:47.210 --> 01:26:54.639
Faculty (Olympus): Now, let's look at the type of data in this case. Data will be a string. In particular, this is a Unicode string. All strings in Python are Unicode.

815
01:26:55.080 --> 01:26:59.529
Faculty (Olympus): And again, length of data is 5,000, so there are 5,000 characters in this.

816
01:26:59.720 --> 01:27:01.290
Faculty (Olympus): data set, soâ€¦

817
01:27:01.530 --> 01:27:08.410
Faculty (Olympus): Now, if you want to do the same thing, if you want to, sorry, here is an example where you explicitly say, I want to read it.

818
01:27:08.670 --> 01:27:18.629
Faculty (Olympus): So the second argument to the file, to the open, is basically the mode. The mode defaults to R, okay? Therefore, I didn't have to specify it before, and so this is the same as above.

819
01:27:19.040 --> 01:27:35.769
Faculty (Olympus): Now, instead of using f.read and reading the whole thing into a massive string, you can also use other methods. So, one of them is called readLine. So if you want to sort of read line by line, you can do f.readLines, right? And what this will do is, this will give you a list of strings.

820
01:27:36.040 --> 01:27:49.569
Faculty (Olympus): So the data type here will be, list, and so you'll have a list with 100 elements. Each element is basically going to be one line. Okay, so this is another way to read this, okay? So you can choose to do it however you want to do it.

821
01:27:50.460 --> 01:28:06.810
Faculty (Olympus): So keep in mind, you must always close a file, and the reason this is important is an operating system typically has a limit on the number of concurrent open files you have. So if you just open 300 files, somebody else may not be able to open the file, because the operating system cannot manage too many open files.

822
01:28:07.440 --> 01:28:14.770
Faculty (Olympus): Same way on Windows, if someone is already working on a file, someone else cannot, you know, again, work on the same file, so be careful about things like that.

823
01:28:16.190 --> 01:28:31.679
Faculty (Olympus): Now, instead of always having to keep track of, okay, I opened a file, I have to go and close that file, Python provides this very convenient syntax, which is called a context manager. So basically, this is the syntax. You can say with

824
01:28:32.320 --> 01:28:35.459
Faculty (Olympus): openâ€¦ whatever file.

825
01:28:35.630 --> 01:28:39.779
Faculty (Olympus): This object, this file object that is created here.

826
01:28:40.360 --> 01:28:59.590
Faculty (Olympus): this variable F will be a name for that object. So instead of saying width, F is equal to this is not the syntax, the syntax is with, open this as F, right? And this as F is actually optional. You don't need it, but we need it in this case because I want to be able to read that file, okay? So as F, with open as F,

827
01:28:59.680 --> 01:29:04.930
Faculty (Olympus): data is f dot readlines. Now, in this case, this width fellow, oopsâ€¦

828
01:29:06.090 --> 01:29:14.510
Faculty (Olympus): will ensure that when this is finished, that this file object is gonna be closed automatically. You don't have to do anything to do f.close.

829
01:29:14.650 --> 01:29:18.890
Faculty (Olympus): And even if you ran into an exception, even if you ran into an error in this line.

830
01:29:18.990 --> 01:29:36.740
Faculty (Olympus): this file will be automatically closed, which would not necessarily happen if this happens. If you ran into an exception in this line, you will notâ€¦ this line will never be executed, so you'll run into a problem. Whereas when you use the width syntax, it'll ensure that no matter what, this file object is going to be closed.

831
01:29:37.170 --> 01:29:46.560
Faculty (Olympus): And there are many contexts in which this width is going to be used in Python. I don't think in our course we'll be using it, but there are many places where it will be useful.

832
01:29:46.710 --> 01:29:55.399
Faculty (Olympus): Okay, so just keep this in mind. Instead of using this sort of old way of doing it, please use this syntax, right? With something as if.

833
01:29:55.640 --> 01:29:57.599
Faculty (Olympus): This does the same thing in this case.

834
01:29:57.740 --> 01:30:04.220
Faculty (Olympus): So when I did read lines here, remember, data is going to be a list of, cold.

835
01:30:04.410 --> 01:30:12.190
Faculty (Olympus): list of strings, and now I've printed the length, which is 100 rows, and I've printed the first row.

836
01:30:13.190 --> 01:30:31.280
Faculty (Olympus): So, width introduces a new block, and notice the as-if syntax is just a summary of what we've looked at. It automatically closes the file on exit, and every line also has a line ending. So please note this. When you do f.readLines, every line, that new line at the end, will also be there in that string. It's not going to remove that. You'll have to strip it if you want to remove it.

837
01:30:32.370 --> 01:30:40.680
Faculty (Olympus): Okay, so there are lots of questions. I'll finish writing files, and then the next exercise, I'll stop for questions. So writing files is also very easy.

838
01:30:40.890 --> 01:30:47.709
Faculty (Olympus): Now, instead of just saying with open, you know, whatever, without this mode, if you set the mode to W, it will write the flag.

839
01:30:48.560 --> 01:31:07.470
Faculty (Olympus): But please beware of this, beware of this. If you have an existing junk.txt in the current directory, it will wipe it out, and that file is gone, okay? So please be very, very careful before you do this on file names that are very important to you. So just be careful for this. So here we say with open junk.txt.

840
01:31:07.860 --> 01:31:10.920
Faculty (Olympus): Please note the W argument as F.

841
01:31:11.280 --> 01:31:18.219
Faculty (Olympus): F.Write. So the argument, please remember the method to use is write. Here we used read and read lines, here we're using write.

842
01:31:18.360 --> 01:31:20.589
Faculty (Olympus): And also note that

843
01:31:20.860 --> 01:31:30.479
Faculty (Olympus): You must pass a new line in when you're writing stuff. Otherwise, you'll just keep on writing in the same line. So every time you want to say, hello world, new line, and something else, please, you must add the new line.

844
01:31:31.770 --> 01:31:40.910
Faculty (Olympus): You can also do write lines, just like read lines, and data here has to be a list, okay? And list of values, and you can write this.

845
01:31:41.780 --> 01:31:55.440
Faculty (Olympus): And again, please note, f dot rightlines does not add a new line to the line, so whatever is there in that data, it'll just put, okay? So if you want a new line, you must put a slash in, in each of those, you know, elements of that list.

846
01:31:55.570 --> 01:31:56.520
Faculty (Olympus): Great talent.

847
01:31:57.500 --> 01:32:11.930
Faculty (Olympus): Okay, so here's an exercise. Read the data file, data.txt, and write every alternate line to a new data file called junk.txt. That's an exercise. I'll answer quick questions. Actually, they're only 7 minutes, but okay, quickly. Randeep.

848
01:32:14.620 --> 01:32:20.890
Randeep Singh .: Professor, my question is a bit generic, so I'm okay if we take it after yourâ€¦

849
01:32:20.890 --> 01:32:21.989
Faculty (Olympus): Can we take it at the end, please?

850
01:32:22.470 --> 01:32:23.250
Faculty (Olympus): board strings, yeah.

851
01:32:23.250 --> 01:32:23.750
Randeep Singh .: Yashi.

852
01:32:23.750 --> 01:32:25.339
Faculty (Olympus): Sure, sure. Abhineet?

853
01:32:25.460 --> 01:32:28.950
Abhineet Bansal: Sir, can we open and read video files also like this?

854
01:32:29.110 --> 01:32:35.840
Faculty (Olympus): A file is just a file. The only thing is, if it's a binary file, you may want to add WB. The mod should be binary.

855
01:32:36.040 --> 01:32:38.200
Faculty (Olympus): This is going to assume that it's a text file.

856
01:32:38.990 --> 01:32:48.319
Faculty (Olympus): If you want a binary file, any binary file is the same exact syntax, and just, you have to be careful that when you read a binary file, you will get back bytes. You will not get back string.

857
01:32:48.920 --> 01:32:50.120
Faculty (Olympus): By binary, you meanâ€¦

858
01:32:50.120 --> 01:32:51.349
Abhineet Bansal: it's a video.

859
01:32:52.560 --> 01:32:55.860
Faculty (Olympus): binary file. A file is just a set of bytes.

860
01:32:56.870 --> 01:33:01.360
Faculty (Olympus): There's no difference between anything. File is just a collection of ones and zeros on your disk.

861
01:33:01.570 --> 01:33:06.640
Faculty (Olympus): But if I'm assuming it's a text file, then I'm saying that, look, there is some encoding.

862
01:33:06.900 --> 01:33:12.249
Faculty (Olympus): that every one of those is basically a string. I'm expecting a string output.

863
01:33:12.890 --> 01:33:23.330
Faculty (Olympus): But if it's a true binary file, then what you want is, you basically have the individual bytes, and you have to then interpret those bytes however you want. So if you need aâ€¦ if you have a video file and you have a file format.

864
01:33:23.580 --> 01:33:27.309
Faculty (Olympus): You have to know the file format, and then interpret those bytes in the appropriate order.

865
01:33:27.600 --> 01:33:30.310
Faculty (Olympus): By the end of the day, a file is just a stream of bits.

866
01:33:31.340 --> 01:33:32.100
Abhineet Bansal: Credits.

867
01:33:33.110 --> 01:33:39.570
Faculty (Olympus): Okay? And you can read it with the same syntax. There are libraries that'll do the reading of the fact, but if you really want to do it by yourself, you can do it yourself.

868
01:33:41.070 --> 01:33:42.040
Faculty (Olympus): Charles?

869
01:33:43.180 --> 01:33:46.389
Charles Ravi Kiran Mutsu .: Sir, in theâ€¦ a bit,

870
01:33:46.800 --> 01:33:54.429
Charles Ravi Kiran Mutsu .: If you scroll up a little bit, like, yeah, here, so the context of print is not in the same indentation, but.

871
01:33:54.430 --> 01:34:04.949
Faculty (Olympus): It is not. It's not. Here, it's outside. What I did was I finished reading all the lines, and I'm done with the file. It's exactly the same as what I did here. I opened the file, I did read lines, I closed the file.

872
01:34:05.300 --> 01:34:07.470
Faculty (Olympus): Okay, this is identical to that.

873
01:34:09.010 --> 01:34:10.240
Faculty (Olympus): These two lines.

874
01:34:10.860 --> 01:34:12.779
Faculty (Olympus): Just that I don't need an F dot close of them.

875
01:34:13.900 --> 01:34:18.329
Charles Ravi Kiran Mutsu .: Got it, but the print is in a different indentation altogether, soâ€¦

876
01:34:18.330 --> 01:34:21.550
Faculty (Olympus): Yeah, it doesn't matter. So this is still in the scope.

877
01:34:22.250 --> 01:34:29.359
Faculty (Olympus): Any variables declared here are not outside the scope. They're still within the scope outside. I mean, after this block.

878
01:34:29.670 --> 01:34:31.560
Faculty (Olympus): You know, these variables are still available.

879
01:34:32.790 --> 01:34:34.120
Charles Ravi Kiran Mutsu .: Okay, yep, thank you.

880
01:34:35.000 --> 01:34:37.130
Faculty (Olympus): Roshanâ€¦

881
01:34:37.640 --> 01:34:46.649
Roshan Mathane .: Yeah, so, Prasanna, this read lines, it reads by default for the slash, and so what if I have slash or slash, or if I have JSON file?

882
01:34:47.770 --> 01:34:48.779
Faculty (Olympus): I didn't understand.

883
01:34:48.950 --> 01:34:50.919
Roshan Mathane .: So, do you have a Jason?

884
01:34:50.920 --> 01:34:53.289
Faculty (Olympus): JSON file is also a text file, you can read it.

885
01:34:53.290 --> 01:34:58.660
Roshan Mathane .: Yeah, but, we have a few line devilators, slasher and Slash, orâ€¦

886
01:34:58.660 --> 01:35:00.989
Faculty (Olympus): It'll drink Doesn't mark up.

887
01:35:01.150 --> 01:35:03.270
Roshan Mathane .: So, read lines method will support it.

888
01:35:03.270 --> 01:35:07.680
Faculty (Olympus): Yes. If it's a text file, it'll read it. The only thing you have to be worried about is encoding.

889
01:35:09.390 --> 01:35:15.010
Faculty (Olympus): It's gonna assume it's a UTF encoding. If you have different encoding, then you must pass the encoding arc.

890
01:35:17.190 --> 01:35:19.130
Faculty (Olympus): So, if you understand Unicode, you know this.

891
01:35:19.130 --> 01:35:19.619
Roshan Mathane .: What does this mean?

892
01:35:19.620 --> 01:35:21.469
Faculty (Olympus): If you don't good, justâ€¦

893
01:35:21.470 --> 01:35:25.829
Roshan Mathane .: So it will handle non-branding characters as well, Western European, likeâ€¦

894
01:35:25.990 --> 01:35:41.329
Faculty (Olympus): Yeah, so if your encoding is set up correctly, it will read the file, and you'll get Unicode. So strings are Unicode. So if you set the right encoding, then it'll be actually those Unicode characters, you can print it, you have some crazy characters, you have Kanji, you have, you know, Tamil or Hindi Devendagiri characters, they can really print.

895
01:35:41.580 --> 01:35:43.800
Roshan Mathane .: Yeah, so everything under UTF8 will be supported, right?

896
01:35:43.800 --> 01:35:47.259
Faculty (Olympus): Not just any encoding. If you specify the encoding, it will support.

897
01:35:47.480 --> 01:35:49.739
Roshan Mathane .: Now, if I don't specify, it will support UTF.

898
01:35:49.740 --> 01:35:56.680
Faculty (Olympus): No, you won't know. By default, it'll assume UTF-8, I think, right? It's according to the default encoding.

899
01:35:57.860 --> 01:36:01.089
Faculty (Olympus): Or it may do something which is based on your,

900
01:36:03.730 --> 01:36:05.770
Faculty (Olympus): There are some environment variables, right?

901
01:36:07.330 --> 01:36:10.519
Faculty (Olympus): So it doesn't exactly say what the encoding is.

902
01:36:13.620 --> 01:36:17.000
Faculty (Olympus): Yeah, I think it's going to assume UTF rating probably. You can check

903
01:36:17.160 --> 01:36:21.390
Faculty (Olympus): You can check online for this. I don't know why they don't document it here.

904
01:36:22.230 --> 01:36:22.910
Faculty (Olympus): Yeah.

905
01:36:22.910 --> 01:36:24.299
Roshan Mathane .: Yeah, sure, yeah, we'll do it.

906
01:36:24.730 --> 01:36:27.159
Faculty (Olympus): Next door's at Rahul?

907
01:36:27.980 --> 01:36:34.089
Rahul Joshi .: Just one question. You mentioned that read will read the complete file, and read lines will read one line at a time.

908
01:36:34.090 --> 01:36:34.529
Faculty (Olympus): No, really?

909
01:36:34.530 --> 01:36:35.370
Rahul Joshi .: Also.

910
01:36:35.370 --> 01:36:37.809
Faculty (Olympus): the complete file. Readlines are also in the complete file.

911
01:36:38.070 --> 01:36:40.840
Rahul Joshi .: Correct. And what is the reason to use one?

912
01:36:41.760 --> 01:36:43.040
Faculty (Olympus): One will give you aâ€¦

913
01:36:43.150 --> 01:36:52.930
Faculty (Olympus): massive text, the other will give you every line. So if you have something which is a line-oriented file, right, like JSON. Normal text file, you have everything as lines, and you can read them as lines.

914
01:36:53.400 --> 01:36:57.970
Faculty (Olympus): Otherwise, here, you'll have to count the number of slash ends to find, you know, where the line ends.

915
01:36:58.140 --> 01:37:06.450
Faculty (Olympus): Right? Also, if you want to only read some part of it, you can specify a size. You say, no, I don't want to read the whole thing, I want to read 1024 chunks, you can do that.

916
01:37:07.560 --> 01:37:09.070
Faculty (Olympus): Until you hit end of 5.

917
01:37:10.490 --> 01:37:12.430
Faculty (Olympus): So you can do that also, butâ€¦

918
01:37:12.830 --> 01:37:14.740
Faculty (Olympus): I've just shown you the simplest possible thing.

919
01:37:14.860 --> 01:37:15.860
Faculty (Olympus): Siddhesh?

920
01:37:18.660 --> 01:37:23.760
Siddhesh Dinesh Kadam .: Hey, sorry, I think I got the answer. I wanted to ask, how do you append instead of overwrite, I think.

921
01:37:23.760 --> 01:37:25.940
Faculty (Olympus): Yeah, there's a board. Yes, it was easy.

922
01:37:25.940 --> 01:37:26.510
Siddhesh Dinesh Kadam .: Got it.

923
01:37:26.510 --> 01:37:28.119
Faculty (Olympus): Got it, got it, got it, inside.

924
01:37:28.520 --> 01:37:34.189
Faculty (Olympus): Okay, we have only 2 more minutes, so Nayogi, is there anything else here? I think this is easy.

925
01:37:34.740 --> 01:37:49.689
Faculty (Olympus): All right, so the rest is, you know, I think we'll come back to this in the next class. Maybe I'll just finish this counting words with one minute and come back to you all with questions. So, here is an example, and next set, next lecture, I'm basically going to look at counting words in a string.

926
01:37:49.850 --> 01:37:58.300
Faculty (Olympus): I'm going to look at counting words in an entire novel, okay? Not just counting words, doing processing of that novel, which is where this notebook is headed.

927
01:37:58.880 --> 01:38:01.240
Faculty (Olympus): But let's say I have a single paragraph, right?

928
01:38:01.370 --> 01:38:10.670
Faculty (Olympus): From Alice in Wonderland. It says, Alice was beginning to get very tired, blah blah blah. I want to do a simple count of the words seen in this paragraph. You know, if I want to know,

929
01:38:11.290 --> 01:38:16.219
Faculty (Olympus): You know, what is the most frequent word? How would we do this? You know, that's the kind of problem we would like to solve.

930
01:38:16.430 --> 01:38:32.269
Faculty (Olympus): So the first thing is, if I know a specific word, if I want to say, what are the number of times Alice has been used in this, I can simply say para.lower, which will convert this to lowercase, right? Because I don't know, maybe there's a typo in the book, and they've misspelled capital A, they put little a, for example.

931
01:38:32.520 --> 01:38:37.970
Faculty (Olympus): If I just do para.lower and count Alice, that'll give me an answer. It's all identifying this para.

932
01:38:38.510 --> 01:38:41.120
Faculty (Olympus): Right, so it says 2 times Alice's occurrence.

933
01:38:41.820 --> 01:38:46.449
Faculty (Olympus): If I want to count the number of occurrences of the, I can simply say, okay, para.cover.count the.

934
01:38:46.970 --> 01:39:06.569
Faculty (Olympus): But next, what I want is, I want more. I want to see all the words that are there, and I want to count all of them. Okay, so how do we do this? So in the next class, I'll introduce you to dictionaries, where we can say that we can very easily solve these problems. There are other data structures as well, which we'll show you maybe in the exercises, but I will stop here, and I can answer

935
01:39:06.620 --> 01:39:08.989
Faculty (Olympus): All types of questions.

936
01:39:09.090 --> 01:39:12.530
Faculty (Olympus): Except, I do need to go at 9.15, soâ€¦

937
01:39:12.720 --> 01:39:14.459
Faculty (Olympus): I hope we can keep it to that.

938
01:39:15.210 --> 01:39:20.050
Faculty (Olympus): And once again, please, if you have issues, that are still unresolved as of

939
01:39:20.490 --> 01:39:32.150
Faculty (Olympus): Today, please let the TAs know, message them, send a chat, we'll see if we can set up one more short TA session before the exam. And also, please remember, during the exam.

940
01:39:32.370 --> 01:39:40.439
Faculty (Olympus): I think the announced time, I don't know, I don't remember the exact announced time. There was one slot where the TA will actually be present.

941
01:39:40.920 --> 01:39:53.729
Faculty (Olympus): I think, okay, I thought it was 5â€¦ 4 to 5 p.m. If you attend that slot, you will beâ€¦ the TA will be there, so you can quickly, you know, if there's an issue, you can always raise it, and they will help you. So try to see if you can take the test at that time.

942
01:39:54.400 --> 01:39:55.300
Faculty (Olympus): Alright.

943
01:39:55.820 --> 01:39:56.750
Faculty (Olympus): Randeep?

944
01:39:57.430 --> 01:40:13.230
Randeep Singh .: Yes, sir. So, I had a question. Are there any limitations or advantages of this type of file reading over what we do in Pandas? I know you'll cover Pandas in future sessions, but just wanted.

945
01:40:13.230 --> 01:40:24.850
Faculty (Olympus): No, so this is for the cases whereâ€¦ see, sometimes you'll do Pandas, yeah, sure, but sometimes you have a file which is some, you know, something which is not relevant to Pandas, or Pandas does not parse that file.

946
01:40:25.200 --> 01:40:29.309
Randeep Singh .: But in Pandas, I think all major type of files areâ€¦

947
01:40:29.310 --> 01:40:33.989
Faculty (Olympus): For example, it will not parse, say, a VTK file or some bizarre, some file format that you're not familiar with.

948
01:40:33.990 --> 01:40:34.730
Randeep Singh .: Okay.

949
01:40:34.970 --> 01:40:47.729
Faculty (Olympus): Pandas is only meant for tabular data, right? So only tabular-related things, it's CSV files, you know, Parquet files, Arrow files, SQL, all of those things, it'll pass. That's all fine, right? But you may have some, you know, faster file, right? And there are readers

950
01:40:48.150 --> 01:40:53.360
Faculty (Olympus): Or you may have a text file on your machine, like this Allison Waterland text, right? You've got aâ€¦ you've got a book.

951
01:40:53.690 --> 01:41:06.479
Faculty (Olympus): And you want to, you know, get all the occurrences of different things in that, right? So you have a simple text file, or you have a PDF, and you converted that to text, and now you want to do some string searching in that and find how many occurrences, you know.

952
01:41:06.550 --> 01:41:18.149
Faculty (Olympus): there's a court case that has come, and you want to say, hey, was I named in that court case? You want to quickly search through it. Of course, you can do Ctrl-F, right? Or you can say, I want to find all the people who have been named on this, or whatever it is that you want to study, right?

953
01:41:18.580 --> 01:41:19.520
Randeep Singh .: Yeah, okay.

954
01:41:19.520 --> 01:41:21.710
Faculty (Olympus): Still those kind of processing when you need

955
01:41:21.990 --> 01:41:26.620
Faculty (Olympus): That's all. So I'm just showing you the basics of, if you want to just read a file, you can do so.

956
01:41:26.760 --> 01:41:28.030
Randeep Singh .: Alrighty, thank you so much.

957
01:41:28.030 --> 01:41:29.750
Faculty (Olympus): Sure. Siddharth?

958
01:41:30.170 --> 01:41:46.429
Siddharth Digambar Kulkarni .: The load text, what I understand, if you use a NumPy load text, it will read the text and convert it into NumPy array, right? In this case, it is reading the text only in text format, right? Am I correct in understanding this?

959
01:41:46.430 --> 01:41:52.790
Faculty (Olympus): Absolutely correct. So, this will only give you strings. Everything is strings. You have to now convert those strings into

960
01:41:54.330 --> 01:42:02.540
Faculty (Olympus): floating-point numbers, or, you know, inject it into a numpy array, that's up to you. In fact, pandas and np.loadText does the same thing. It'll read the file.

961
01:42:02.690 --> 01:42:09.980
Faculty (Olympus): And then, you know, construct the quantities, and then put it into another area and return it to you. Someone has done that work for you.

962
01:42:11.190 --> 01:42:19.120
Siddharth Digambar Kulkarni .: So, second things are, read lines, by default, it, checks the new line character. Does it include the new line character?

963
01:42:19.120 --> 01:42:23.970
Faculty (Olympus): Yes, yes, yes, yes. It includes every line, we'll have that slash at the end.

964
01:42:23.970 --> 01:42:27.999
Siddharth Digambar Kulkarni .: So when you do right lines, you don't need to add the new line character again.

965
01:42:28.000 --> 01:42:35.909
Faculty (Olympus): If you have done it through read lines, yes, but if you're composing, somehow you have a list of string values, right, and you didn't put the slash in, you'll just put them in one line.

966
01:42:36.230 --> 01:42:37.299
Siddharth Digambar Kulkarni .: Oh, go, go.

967
01:42:39.780 --> 01:42:44.239
Faculty (Olympus): So, write lines will not inject a new slash in. Whatever is there, it'll print.

968
01:42:44.240 --> 01:42:51.759
Siddharth Digambar Kulkarni .: So, every element in the read line, every element of the list in the read line will have a slash N at the end.

969
01:42:51.760 --> 01:42:53.269
Faculty (Olympus): Yes, yes, it will be.

970
01:42:53.270 --> 01:42:53.830
Siddharth Digambar Kulkarni .: Oh, good.

971
01:42:53.830 --> 01:42:58.269
Faculty (Olympus): I've written it here because this is a common issue for people, right?

972
01:43:01.630 --> 01:43:02.950
Siddharth Digambar Kulkarni .: Okay, thank you, sir.

973
01:43:02.950 --> 01:43:03.480
Faculty (Olympus): shouldn't.

974
01:43:03.960 --> 01:43:06.340
Faculty (Olympus): Charu?

975
01:43:09.900 --> 01:43:14.579
Charu .: Yeah, sorry, Professor Ignore. I was stuck on numpy issue.

976
01:43:14.990 --> 01:43:15.690
Faculty (Olympus): Okay.

977
01:43:15.690 --> 01:43:16.060
Charu .: fine door.

978
01:43:16.060 --> 01:43:19.560
Faculty (Olympus): No, you had some other issues, no, nonâ€¦ nonâ€¦ whatever, nonâ€¦

979
01:43:19.760 --> 01:43:33.930
Charu .: Yeah, it is the non-technical, but like what to say, I'm just requesting, if not possible, till next weekend, at least till Sunday would be better. But still, if it is not, I'll assume, like, I have some deadline.

980
01:43:33.930 --> 01:43:40.650
Faculty (Olympus): So you just, yeah, you just prepare for the thing, and if you have issues with the setup and things like that, you can ask for aâ€¦

981
01:43:41.040 --> 01:43:45.410
Faculty (Olympus): Maybe a separate TA session. I'll request the TAs if they can spare some time.

982
01:43:46.340 --> 01:43:52.190
Charu .: Yeah, sure, but still, again, I'm saying, if it's possible, extend it till Tuesday and Sunday.

983
01:43:52.310 --> 01:43:53.570
Charu .: So thatâ€¦

984
01:43:54.240 --> 01:43:58.079
Faculty (Olympus): You mean to say you want to take the test on Sunday? As it is, we're doing somethingâ€¦

985
01:43:58.380 --> 01:43:59.959
Faculty (Olympus): Which is usually not done.

986
01:44:00.250 --> 01:44:05.739
Faculty (Olympus): Just, you know, extend this for the whole day. Usually it's fixed last year and all, it was fixed hours.

987
01:44:06.470 --> 01:44:09.220
Faculty (Olympus): 10 to 12, something like that, and that's it.

988
01:44:09.330 --> 01:44:09.830
Faculty (Olympus): Cliffs.

989
01:44:09.830 --> 01:44:13.749
Charu .: Certainly, I got 11 production issues, so I'm working for an investment bank.

990
01:44:13.750 --> 01:44:16.139
Faculty (Olympus): Okay, it's only 5 marks, Silta, it's okay.

991
01:44:17.250 --> 01:44:19.289
Faculty (Olympus): I think just attempt it, don't worry too much about.

992
01:44:19.290 --> 01:44:25.180
Charu .: No, actually, I have a go-live all of a sudden, like, it is a patch release, so I will beâ€¦ the whole day, I will be busy.

993
01:44:26.330 --> 01:44:26.950
Faculty (Olympus): That'sâ€¦

994
01:44:26.950 --> 01:44:33.769
Charu .: It'sâ€¦ all of a sudden, it'sâ€¦ it came. Iâ€¦ like, Iâ€¦ I'm working till morning, you know, starting from morning 5.

995
01:44:34.760 --> 01:44:39.339
Charu .: I'm working with investment bank for trading projects, and it's, like, critical.

996
01:44:42.650 --> 01:44:45.210
Faculty (Olympus): I'm sorry, I can't do much about this, soâ€¦

997
01:44:45.550 --> 01:44:46.829
Charu .: Okay, I'll try toâ€¦

998
01:44:46.830 --> 01:44:58.260
Faculty (Olympus): Because there are 200 people, so I don't know if they will all be, you know, fine with changing the schedule now. It's been announced. Now, if we do something, people would have made travel plans, things would have changed, so, you knowâ€¦

999
01:44:58.820 --> 01:45:08.510
Charu .: Yeah, I agree, I understand, and I also came to know this issue this week, and we are, you know, going to deliver on Saturday only, so that's the issue.

1000
01:45:08.830 --> 01:45:11.849
Faculty (Olympus): So, they've allowed you to take it any time in the day, right?

1001
01:45:13.360 --> 01:45:14.229
Charu .: Is it interesting?

1002
01:45:14.230 --> 01:45:14.779
Faculty (Olympus): There's aâ€¦

1003
01:45:14.990 --> 01:45:22.669
Faculty (Olympus): I think there's a significantâ€¦ there's a big window that you can take the test. We're just recommending that you do it 5 to, whatever, 4 to 5, so that TAs are there.

1004
01:45:23.070 --> 01:45:26.090
Faculty (Olympus): Other ways, it's like aâ€¦ Who canâ€¦

1005
01:45:26.090 --> 01:45:28.609
Charu .: Can I take in the night also, like, around 7 a.m.

1006
01:45:28.610 --> 01:45:29.999
Faculty (Olympus): The timers were announced.

1007
01:45:30.130 --> 01:45:32.550
Faculty (Olympus): Can someone else tell me what the timings was? I don't remember.

1008
01:45:32.550 --> 01:45:33.300
vinay kaisar: Yeah, you see me?

1009
01:45:33.300 --> 01:45:37.210
Komal Chandra .: Morning, 9â€¦ morning, 9 to 9â€¦ night, 12th.

1010
01:45:37.210 --> 01:45:50.040
Faculty (Olympus): Yeah, so it's, like, crazy. I mean, no quiz instructor would allow you to do something like this, right? Morning, night, soâ€¦ right? So we're trusting that you don't do any, you know, hanky-panky. We're giving you plenty of flexibility to do this.

1011
01:45:50.040 --> 01:45:50.750
Charu .: That isâ€¦

1012
01:45:50.750 --> 01:45:58.559
Saurav kumar: due to some reason the laptop restarts or something happens, then are we going to allow people to restart the quiz? Because.

1013
01:45:58.560 --> 01:46:02.639
Faculty (Olympus): No, you can go back into the quiz. The quiz will not shut down if you lost your internet connection.

1014
01:46:02.980 --> 01:46:21.450
Faculty (Olympus): But your timer starts, let's say you start the quiz now, the timer is going to end. That's why we have that the TA session, special session is there, because if there is an issue, tell the TAs or send a ticket, in your case. We'll see what we can do. If you have some real emergency, you tell us. But if you do it in 4 to 5, TAs can actually help you.

1015
01:46:24.050 --> 01:46:27.270
Charu .: Okay, thanks, thanks, Professor, I was not aware about that.

1016
01:46:27.270 --> 01:46:32.190
Faculty (Olympus): Yeah, yeah, so it's already, we have, like, made it very flexible and all this, just to avoid these things.

1017
01:46:32.190 --> 01:46:36.320
Charu .: Yesterday night, I was working with the US team, so it's, like, a very hectic format.

1018
01:46:36.320 --> 01:46:37.580
Faculty (Olympus): That's helpful.

1019
01:46:37.580 --> 01:46:38.140
Charu .: of this.

1020
01:46:38.530 --> 01:46:40.500
Faculty (Olympus): Okay. So, Ankit?

1021
01:46:42.770 --> 01:46:46.190
Ankit Singh: Sir, I have a question on Singh formatting. Could you please scroll up?

1022
01:46:46.190 --> 01:46:46.850
Faculty (Olympus): Sure.

1023
01:46:48.250 --> 01:46:49.649
Faculty (Olympus): Dev strings, or this one?

1024
01:46:49.650 --> 01:46:51.710
Ankit Singh: AI string formatting, that's one.

1025
01:46:52.440 --> 01:46:58.859
Ankit Singh: little, where we mention X percent S and Y percent S.

1026
01:46:58.860 --> 01:47:00.110
Faculty (Olympus): Oh, this one, huh, okay.

1027
01:47:00.110 --> 01:47:16.049
Ankit Singh: Yeah, yeah. So, you have, defined the variable XY something. So, ifâ€¦ if you are not going to write X as something and Y is something percent S, still we are going to get print X1, print Y is whatever you defined. So, what is the benefit behind to write this?

1028
01:47:16.210 --> 01:47:17.609
Ankit Singh: Apart from XY.

1029
01:47:20.190 --> 01:47:24.119
Faculty (Olympus): I didn't understand your question. So, oh, you're saying, why do you want to put percentages?

1030
01:47:24.290 --> 01:47:29.780
Ankit Singh: Yeah, yeah. Because if we are not going to write this, still we are going toâ€¦ So how will you then make a difference?

1031
01:47:30.180 --> 01:47:38.860
Faculty (Olympus): No, no, how will you print X? How will youâ€¦ how will you makeâ€¦ I'm not printing here. I've just created a string. I'm not printing here. Printing is easy, right? I can just say print.

1032
01:47:41.550 --> 01:47:44.149
Faculty (Olympus): That is easy, right? Or I can say.

1033
01:47:46.170 --> 01:47:50.429
Faculty (Olympus): That's not what I'm doing here. And creating a string, single string like this.

1034
01:47:52.220 --> 01:47:52.890
Ankit Singh: Okay.

1035
01:47:53.380 --> 01:47:57.780
Faculty (Olympus): Right? If I want to create the string with those values interpolated into that string, how do you do it?

1036
01:47:58.350 --> 01:47:58.990
Ankit Singh: Hmm, okay.

1037
01:47:58.990 --> 01:48:03.989
Faculty (Olympus): You can't do it. So I can say X is, then say plus, then say STR of X.

1038
01:48:04.790 --> 01:48:07.610
Faculty (Olympus): plus, then comma Y is.

1039
01:48:07.960 --> 01:48:13.120
Faculty (Olympus): Right? So it's aâ€¦ Yeah, yeah. I can say it, isâ€¦

1040
01:48:13.730 --> 01:48:16.130
Faculty (Olympus): Plus, let's say I have an X.

1041
01:48:16.280 --> 01:48:17.190
Faculty (Olympus): Thus.

1042
01:48:20.480 --> 01:48:22.630
Faculty (Olympus): Wrong. Right. Yes.

1043
01:48:23.610 --> 01:48:24.450
Faculty (Olympus): Thank?

1044
01:48:24.920 --> 01:48:25.650
Ankit Singh: Yeah.

1045
01:48:26.390 --> 01:48:27.420
Faculty (Olympus): It's ugly.

1046
01:48:28.580 --> 01:48:31.630
Faculty (Olympus): So, you can do traditionalâ€¦ this is the old way of doing things.

1047
01:48:31.630 --> 01:48:33.320
Ankit Singh: That would be a little nanny.

1048
01:48:33.790 --> 01:48:44.290
Faculty (Olympus): Yeah, very lengthy. This is one small example. Imagine a longâ€¦ it's an annoying thing, right? I have to do this, add this, add thisâ€¦ there I can directly interpolate, which is why F-strings are very convenient.

1049
01:48:45.240 --> 01:48:52.059
Faculty (Olympus): Okay, so I can just put it, and it's easy to read also. Here, I don't know if you have four arguments, right? You don't know which one is what.

1050
01:48:53.070 --> 01:48:57.839
Faculty (Olympus): That is here, because it's just the direct variable name. Variable names are reasonable.

1051
01:48:57.990 --> 01:48:59.440
Faculty (Olympus): Well, very easy to read.

1052
01:49:01.160 --> 01:49:02.780
Ankit Singh: Yeah, okay, yep, thank you, sir.

1053
01:49:02.940 --> 01:49:03.670
Faculty (Olympus): No problem.

1054
01:49:04.290 --> 01:49:05.330
Faculty (Olympus): Harshad?

1055
01:49:05.940 --> 01:49:13.499
Harshad Dilip Behere .: Good morning, Professor. Good evening. So, here, when we are talking about file, we are just opening the file. Nowhere we have closed the file.

1056
01:49:13.750 --> 01:49:15.310
Harshad Dilip Behere .: I mean, is it?

1057
01:49:15.310 --> 01:49:16.669
Faculty (Olympus): We did. We closed the Feder.

1058
01:49:17.210 --> 01:49:17.970
Harshad Dilip Behere .: Okay.

1059
01:49:18.280 --> 01:49:23.980
Faculty (Olympus): And when you do this withâ€¦ when you lose this width construction, it is automatic, and that's the beauty. And not only that.

1060
01:49:23.980 --> 01:49:24.490
Harshad Dilip Behere .: Okay.

1061
01:49:24.490 --> 01:49:32.329
Faculty (Olympus): if I did this, right, so let's say, let's say I did this, and Iâ€¦ let's say this is not the only code, let's say I did some other junk here, okay?

1062
01:49:32.880 --> 01:49:40.780
Faculty (Olympus): Right? For example, let's say I have a big file, and I'm parsing the file, and I'm converting fellows to integers or floating point numbers, and somehow there's a mistake in the file.

1063
01:49:41.320 --> 01:49:42.669
Faculty (Olympus): You'll get an exception.

1064
01:49:42.940 --> 01:49:47.860
Faculty (Olympus): If you get an exception, this f2.close will never be called, that file will still be open sitting there.

1065
01:49:48.960 --> 01:49:49.930
Harshad Dilip Behere .: Okay.

1066
01:49:49.930 --> 01:49:56.319
Faculty (Olympus): Right? Until, of course, if your Python crashes, then okay, everythingâ€¦ the process will release all the resources. That's different.

1067
01:49:56.450 --> 01:50:02.179
Faculty (Olympus): But if you're running and you're catching an exception, you may forget to do this, or sometimes people just genuinely forget.

1068
01:50:02.380 --> 01:50:05.540
Faculty (Olympus): Here, when you exit this block.

1069
01:50:05.640 --> 01:50:14.349
Faculty (Olympus): No matter how you exit, whether it's a legal line of code, everything worked fine, or if it had an exception, no matter what, F will be closed.

1070
01:50:15.700 --> 01:50:22.350
Faculty (Olympus): And that's why this is the recommended way of using this, you know? It always will close it, regardless of what happens.

1071
01:50:23.670 --> 01:50:29.939
Harshad Dilip Behere .: And, I mean, we should not be opening this file again and again, right? We should open it only once and do the.

1072
01:50:29.940 --> 01:50:34.960
Faculty (Olympus): that is allâ€¦ that is application dependent, right? So sometimes, yeah, it does makeâ€¦ it's aâ€¦

1073
01:50:35.260 --> 01:50:38.139
Faculty (Olympus): It's cheap, you have to then assess the cost of that.

1074
01:50:39.550 --> 01:50:50.460
Harshad Dilip Behere .: Okay, and one non-technical question, Professor. We have a submission tomorrow by 11.55 in the night for the assignment, so is it possible for us to increase a day orâ€¦

1075
01:50:50.630 --> 01:50:51.700
Faculty (Olympus): Sure, sure, sure.

1076
01:50:51.700 --> 01:50:52.440
Harshad Dilip Behere .: Maybe one day.

1077
01:50:52.440 --> 01:50:55.450
Faculty (Olympus): Yes, can you please increase by 2 days?

1078
01:50:56.400 --> 01:50:58.079
Harshad Dilip Behere .: Thank you so much, Professor. Thank you so much.

1079
01:50:58.080 --> 01:51:01.230
Faculty (Olympus): VA, are you, Pranit? I don't know. Is that you?

1080
01:51:01.550 --> 01:51:06.629
Rahul Joshi .: till Sunday will be helpful, sir, so that we can do afterâ€¦ even after the exam. Thank you, sir.

1081
01:51:08.510 --> 01:51:13.249
Faculty (Olympus): TA, can you please, I don't know who's around today, butâ€¦ Please take a note.

1082
01:51:14.890 --> 01:51:18.600
Saurav kumar: Yeah, Pranav was here, I think he dropped another person in 15 minutes.

1083
01:51:19.030 --> 01:51:20.769
Faculty (Olympus): Okay, fine. Gaurav?

1084
01:51:21.610 --> 01:51:25.879
Gaurav Singh .: Your professor in, in context manages syntax, right, with Open Scenario.

1085
01:51:26.280 --> 01:51:34.760
Gaurav Singh .: when we assign this data variable to the app.readlines, it is accessible outside the scope of the.

1086
01:51:35.730 --> 01:51:36.879
Faculty (Olympus): Yes, it is.

1087
01:51:37.830 --> 01:51:41.559
Gaurav Singh .: Soâ€¦ I mean, in Python, is it allowed?

1088
01:51:41.560 --> 01:51:52.370
Faculty (Olympus): Yeah, yeah. This isâ€¦ see, otherwise, you can't do things like this, right? Because I willâ€¦ very often, I want to do something, get something out of the file, and then use it later. So yes, width will not, you knowâ€¦

1089
01:51:52.490 --> 01:51:57.510
Faculty (Olympus): It's not like a function which introduces a whole new scope that is gone after the function is called, no.

1090
01:51:57.880 --> 01:52:01.230
Faculty (Olympus): This is still in the same namespace, and you still have access to data.

1091
01:52:02.300 --> 01:52:03.240
Gaurav Singh .: Got it.

1092
01:52:04.130 --> 01:52:04.670
Gaurav Singh .: Thank you.

1093
01:52:05.500 --> 01:52:06.410
Faculty (Olympus): Rahul?

1094
01:52:07.000 --> 01:52:12.029
Rahul Joshi .: Quick question. In the quiz, like, till what, workbook we are going to cover it, like, the.

1095
01:52:12.030 --> 01:52:12.430
Faculty (Olympus): number.

1096
01:52:12.430 --> 01:52:12.940
Rahul Joshi .: sleep.

1097
01:52:13.230 --> 01:52:14.110
Faculty (Olympus): Pil nompati.

1098
01:52:14.500 --> 01:52:15.390
Rahul Joshi .: Still not work.

1099
01:52:16.580 --> 01:52:17.320
Rahul Joshi .: Thank you.

1100
01:52:18.940 --> 01:52:19.960
Faculty (Olympus): Anne?

1101
01:52:20.850 --> 01:52:23.020
Faculty (Olympus): Including, okay, up to and including.

1102
01:52:23.020 --> 01:52:28.090
Saurav kumar: But thereâ€¦ will there be any plotting question in quiz, though? Because that will not rely on that.

1103
01:52:28.090 --> 01:52:34.949
Faculty (Olympus): It's gonna be run on Yuck, so there's no plotting. So everything, if there is a plotting question, it'll be like, okay, give a list of these values, or something like that.

1104
01:52:35.840 --> 01:52:38.760
Saurav kumar: Okay, but so Matplotlib Library is not even there, though.

1105
01:52:39.040 --> 01:52:40.209
Saurav kumar: Yeah, they won't need.

1106
01:52:40.210 --> 01:52:41.679
Faculty (Olympus): You're not gonna need none.

1107
01:52:41.930 --> 01:52:49.100
Faculty (Olympus): But you can plot it on your Jupyter notebook to get some, you know, say, this looks like this, or whatever, that's fine. For your debugging purpose, do whatever you want.

1108
01:52:49.440 --> 01:52:52.610
Faculty (Olympus): But on the interface, you'll not be asked any plotting questions, no.

1109
01:52:53.420 --> 01:52:53.950
Saurav kumar: Thanks.

1110
01:52:53.950 --> 01:53:01.330
Faculty (Olympus): So again, it's very simple, it's notâ€¦ we're not asking you very complicated things, but programming questions will be, you know, you'll have to think for some of those questions.

1111
01:53:04.170 --> 01:53:06.289
Ann G. .: So, non-technical question.

1112
01:53:06.450 --> 01:53:06.870
Faculty (Olympus): Yes.

1113
01:53:06.870 --> 01:53:12.630
Ann G. .: Yeah, regarding the mock quiz, when I was taking it today, I was not able to get out of Yux.

1114
01:53:12.820 --> 01:53:16.709
Ann G. .: I was only able to access Yogksha and Jupyter Notebook, so if Iâ€¦

1115
01:53:16.710 --> 01:53:17.379
Faculty (Olympus): That is the idea.

1116
01:53:17.380 --> 01:53:21.560
Ann G. .: Cool. Yes. So, whatâ€¦ If I'veâ€¦

1117
01:53:21.560 --> 01:53:21.930
Faculty (Olympus): Please call.

1118
01:53:21.930 --> 01:53:27.920
Ann G. .: contact a TA for help. It has to be in the case that if the test crashes only, right? Not with.

1119
01:53:27.920 --> 01:53:35.610
Faculty (Olympus): Well, so supposing there is an emergency, and you're like, okay, I have to end the quiz. You end the quiz, usually there'll be an exit password that is given to you.

1120
01:53:36.340 --> 01:53:37.420
Faculty (Olympus): You exit.

1121
01:53:38.200 --> 01:53:47.099
Faculty (Olympus): Using the exit password, and then you will quit. If you log back into Yash, again through the safe browser, you will resume where you left off, if there is time left.

1122
01:53:49.080 --> 01:53:49.900
Ann G. .: Okay,

1123
01:53:49.900 --> 01:53:54.260
Faculty (Olympus): You can just exit the browser. See, because every time you send a request to Yash.

1124
01:53:54.950 --> 01:53:59.819
Faculty (Olympus): It's gonna assume you're logged in. If you log in from some other computer, for example, it'll log you out of this computer.

1125
01:54:00.460 --> 01:54:06.079
Faculty (Olympus): Right? So, but that session is running, your quiz is running, your timer is running. That is the only downside.

1126
01:54:07.210 --> 01:54:07.760
Ann G. .: Okay,

1127
01:54:07.760 --> 01:54:14.070
Saurav kumar: It asks for password also. We are starting theâ€¦

1128
01:54:14.330 --> 01:54:14.920
Faculty (Olympus): Sorry, what?

1129
01:54:14.920 --> 01:54:15.919
Saurav kumar: Yash with him.

1130
01:54:16.150 --> 01:54:18.050
Saurav kumar: So, for me, it crashed.

1131
01:54:18.260 --> 01:54:25.089
Saurav kumar: And then when I restarted that, I clicked on Confuse, find it, opened the browser, and there was a red screen asking me for password.

1132
01:54:25.720 --> 01:54:32.269
Faculty (Olympus): Yeah, so there'll be a startâ€¦ startâ€¦ same start password will be there, and there'll be an end password. I don't know if they have configured it like that.

1133
01:54:33.320 --> 01:54:35.169
Ann G. .: There wasn't quit password.

1134
01:54:35.170 --> 01:54:36.959
Amit Srivastava: Onlyâ€¦ and password.

1135
01:54:37.160 --> 01:54:37.590
Faculty (Olympus): Okay.

1136
01:54:37.590 --> 01:54:44.819
Saurav kumar: I use same end password only, because my laptop crashed, so most probably that session did not end cleanly.

1137
01:54:45.210 --> 01:54:52.479
Faculty (Olympus): Okay, if your laptop crashed, yes, then you'll have to exit, right, because the safe browser will basically lock up your computer, unfortunately.

1138
01:54:52.480 --> 01:54:54.050
Saurav kumar: Yeah, yeah, that is what happened.

1139
01:54:54.050 --> 01:55:07.029
Faculty (Olympus): No, and I'm asking you to do it with the Safe Browser this time, so that, you know, there is someâ€¦ everybody understands how to use it for the quiz, because when we do the mid-semester, then, you know, it gives me more confidence that, you know, it will be fair andâ€¦

1140
01:55:07.340 --> 01:55:18.579
Faculty (Olympus): I know that, you know, it's not proctored, but even, for example, in the end semester, we ask you some basic, say, half an hour of programming. You know the interface, and you know, okay, this is how it should work, if we choose to use it.

1141
01:55:18.880 --> 01:55:24.630
Saurav kumar: So, for instance, let me say two parts, one part where we have programs, and one part where we write on paper.

1142
01:55:24.630 --> 01:55:26.370
Faculty (Olympus): Sorry for the end semester.

1143
01:55:26.550 --> 01:55:27.290
Saurav kumar: Yeah.

1144
01:55:27.560 --> 01:55:33.040
Faculty (Olympus): Yeah, very often it may not be paper, but it will be, you know, there will be two parts, typical.

1145
01:55:34.720 --> 01:55:37.450
Faculty (Olympus): One where you're allowed to use the internet and things like that.

1146
01:55:37.450 --> 01:55:38.060
Saurav kumar: Correct.

1147
01:55:38.770 --> 01:55:39.500
Faculty (Olympus): Siddhi?

1148
01:55:39.750 --> 01:55:42.540
Saurav kumar: Will it be in the lab in Society Bombay, or inside.

1149
01:55:42.540 --> 01:55:42.890
Faculty (Olympus): Yes.

1150
01:55:42.890 --> 01:55:45.570
Ann G. .: So, can I finish my midterm question? Oh, sorry.

1151
01:55:45.570 --> 01:55:47.910
Faculty (Olympus): Yes, yes, yes, please.

1152
01:55:47.910 --> 01:55:49.859
Ann G. .: just,

1153
01:55:49.960 --> 01:55:58.679
Ann G. .: So my question was, maybe Pranav will cover this later, but, the only way to contact the TA would be through the Great Learning Portal, orâ€¦

1154
01:55:59.220 --> 01:56:01.449
Faculty (Olympus): Good question.

1155
01:56:02.150 --> 01:56:06.170
Faculty (Olympus): What I think we can do is we can maybe set up a Zoom session.

1156
01:56:06.670 --> 01:56:08.720
Faculty (Olympus): Where they're just there, like a TA session.

1157
01:56:09.890 --> 01:56:14.319
Faculty (Olympus): And you can just join that Zoom call. That may makeâ€¦ that's the easiest, right, for you?

1158
01:56:15.100 --> 01:56:16.619
Faculty (Olympus): Would that be the easiest thing?

1159
01:56:16.620 --> 01:56:18.400
Soumen Deb .: Yes, it'll be easiest for everyone.

1160
01:56:18.400 --> 01:56:27.469
Faculty (Olympus): Yeah, because then the TA is just sitting there. If anyone pops in with a question, they just answer it, and you're done. You don't have to send a ticket, and God knows when it'll be answered, right? You get an immediate response.

1161
01:56:29.800 --> 01:56:31.300
Ann G. .: Okay, thank you, sir.

1162
01:56:31.300 --> 01:56:33.809
Faculty (Olympus): Sure. Okay, I will ask them to set it up like that.

1163
01:56:34.610 --> 01:56:43.519
Faculty (Olympus): So you need the extension of the deadline to Sunday, and you also want a TA session to be clear. Sorry, theâ€¦

1164
01:56:43.970 --> 01:56:47.089
Faculty (Olympus): 4 to 5 things, there should be a Zoom call. Okay.

1165
01:56:47.840 --> 01:56:49.100
Faculty (Olympus): Two things to begin with.

1166
01:56:49.100 --> 01:56:56.220
Randeep Singh .: Are we still gonna have the TA session on Saturday? The question-solving sessions, or not?

1167
01:56:56.530 --> 01:56:59.730
Faculty (Olympus): I don't think so, right? Because usually that's at the same time slot.

1168
01:57:00.700 --> 01:57:02.859
Faculty (Olympus): And also, we will have class, you know, in the morning.

1169
01:57:02.860 --> 01:57:06.470
Randeep Singh .: Yeah, yeah, I mean, just wanted clarification on that.

1170
01:57:07.170 --> 01:57:12.289
Randeep Singh .: on Saturday, two classes, and two TAs, so just wanted to understand.

1171
01:57:12.660 --> 01:57:13.709
Faculty (Olympus): Oh, okay.

1172
01:57:15.340 --> 01:57:19.069
Faculty (Olympus): Yeah, we can scrap that TS session, and then maybe move it to another day.

1173
01:57:22.140 --> 01:57:25.870
Randeep Singh .: Of course, so we'll get notified about this, right?

1174
01:57:25.870 --> 01:57:31.069
Faculty (Olympus): Yeah, I'll talk to the TAs today, and we'll talk to GNN, have them send you aâ€¦

1175
01:57:31.750 --> 01:57:33.380
Faculty (Olympus): Message about this, okay.

1176
01:57:34.260 --> 01:57:35.480
Randeep Singh .: All right, thank you.

1177
01:57:36.080 --> 01:57:39.210
Faculty (Olympus): Yeah, thank you. Siddhesh?

1178
01:57:46.220 --> 01:57:47.640
Faculty (Olympus): Siddhesh, you're muted.

1179
01:57:48.740 --> 01:57:51.819
Siddhesh Dinesh Kadam .: Yeah, can you hear me now? Yeah.

1180
01:57:51.940 --> 01:58:02.910
Siddhesh Dinesh Kadam .: Sorry, a bit technical question, can we read specific lines, in any form? Like, is there a funcâ€¦ I tried using, Char GPT or Copilot.

1181
01:58:03.300 --> 01:58:06.009
Siddhesh Dinesh Kadam .: Did not give an answer, so I'm assuming no.

1182
01:58:06.010 --> 01:58:12.749
Faculty (Olympus): Oh, no, you can. So, if in any file, you can do f.seek. So, if you know where you want to go, seek will go to that

1183
01:58:13.540 --> 01:58:16.120
Faculty (Olympus): Specific point in the file.

1184
01:58:16.700 --> 01:58:17.830
Siddhesh Dinesh Kadam .: Hood Max.

1185
01:58:17.830 --> 01:58:19.720
Amit Srivastava: Justâ€¦ Never go ahead, go ahead.

1186
01:58:20.300 --> 01:58:25.530
Siddhesh Dinesh Kadam .: First, it will read everything, or it will actually read only that specific line? How do you write it?

1187
01:58:25.530 --> 01:58:27.899
Faculty (Olympus): It won't, it won't, thank God, so let me just say.

1188
01:58:28.270 --> 01:58:31.060
Faculty (Olympus): So let me just do this at Rizwan.

1189
01:58:38.630 --> 01:58:40.309
Faculty (Olympus): Yeah, so now let me doâ€¦

1190
01:58:40.970 --> 01:58:43.039
Faculty (Olympus): And we don't have another food sensor.

1191
01:58:45.480 --> 01:58:47.530
Faculty (Olympus): And then let me say F dotâ€¦

1192
01:58:48.100 --> 01:58:51.180
Faculty (Olympus): Read. Say, let me read 5 characters, okay?

1193
01:58:51.180 --> 01:58:52.989
Piyush Rustagi .: Hmm, so it shouldn'tâ€¦

1194
01:58:52.990 --> 01:58:56.059
Faculty (Olympus): Okay, so it gives me this. I can say f dotsek

1195
01:58:56.650 --> 01:58:59.150
Faculty (Olympus): We'll go to the 500th character.

1196
01:58:59.570 --> 01:59:01.020
Faculty (Olympus): MCF.wheel.

1197
01:59:02.760 --> 01:59:05.109
Faculty (Olympus): Oh, sorry, I didn't go read, I slowed down.

1198
01:59:05.830 --> 01:59:07.290
Faculty (Olympus): Let me do this again.

1199
01:59:09.150 --> 01:59:09.900
Faculty (Olympus): Soâ€¦

1200
01:59:17.870 --> 01:59:24.040
Faculty (Olympus): So I'll start again, and read 5 bytes from here, 5 characters from here, and read 5 more characters.

1201
01:59:25.970 --> 01:59:27.879
Faculty (Olympus): Then you can say, okay, go back.

1202
01:59:28.270 --> 01:59:34.840
Faculty (Olympus): Go seek toâ€¦ I go back, like, it doesn't read anything in Book.

1203
01:59:36.500 --> 01:59:39.340
Faculty (Olympus): Only thing is, you need to know how far you're going to go ahead.

1204
01:59:39.980 --> 01:59:42.460
Faculty (Olympus): You need to have some sense of how long the fight is.

1205
01:59:43.310 --> 01:59:44.770
Faculty (Olympus): Does that answer your question?

1206
01:59:48.730 --> 01:59:49.689
Faculty (Olympus): To this?

1207
01:59:50.610 --> 01:59:53.750
Siddharth Digambar Kulkarni .: It is moving the cursor. Sikk is moving the cursor.

1208
01:59:54.920 --> 01:59:58.880
Faculty (Olympus): No, there's no cursor in this sense, but yeah, it's using theâ€¦ moving the fine pointer at all.

1209
02:00:02.130 --> 02:00:03.070
Faculty (Olympus): Garof?

1210
02:00:04.180 --> 02:00:07.919
Gaurav Singh .: Professor, for the quiz, we will be getting a separate SCB config file.

1211
02:00:08.520 --> 02:00:09.310
Faculty (Olympus): Yeah, yeah.

1212
02:00:09.700 --> 02:00:11.400
Faculty (Olympus): Okay. Of course, yeah, yeah.

1213
02:00:11.720 --> 02:00:14.520
Faculty (Olympus): There'll be a separate quiz created, and then whatever.

1214
02:00:14.520 --> 02:00:17.090
Piyush Rustagi .: completionâ€¦ completion.

1215
02:00:17.310 --> 02:00:20.309
Faculty (Olympus): Yeah, you'll have to download the config file, and then click on that, andâ€¦

1216
02:00:20.610 --> 02:00:21.760
Gaurav Singh .: Okay, understood.

1217
02:00:21.760 --> 02:00:23.800
Faculty (Olympus): And both for me and his team works.

1218
02:00:24.070 --> 02:00:30.830
Faculty (Olympus): That's why we wanted you to do the mock test, so that we know for sure that you know how to take it with the SCP config.

1219
02:00:31.060 --> 02:00:37.120
Faculty (Olympus): We don't want a situation where someone comes on the Saturday and says, hey, this is not working, that is not working.

1220
02:00:38.370 --> 02:00:39.550
Gaurav Singh .: Wonderful. Thank you.

1221
02:00:40.530 --> 02:00:41.290
Faculty (Olympus): Dinesh?

1222
02:00:42.350 --> 02:00:57.180
Dinesh Devnath Yadav .: Yeah, Roshan, so I have two questions. So, first one, if something goes wrong, right, after completing, let's say, question number 3, right, so, and we restart ACB, right, it will directly, we can start from question 4, orâ€¦ Yeah, yeah. Right?

1223
02:00:57.180 --> 02:01:01.810
Faculty (Olympus): So, the way it works, the Yashi interface, is like, every time you hit check answer, right?

1224
02:01:02.550 --> 02:01:04.110
Faculty (Olympus): That answer is actually locked.

1225
02:01:05.210 --> 02:01:06.820
Dinesh Devnath Yadav .: Okay. Okay, so we know nearâ€¦

1226
02:01:06.820 --> 02:01:09.389
Faculty (Olympus): We did 100 attempts, all 100 attempts, we have.

1227
02:01:09.890 --> 02:01:14.219
Dinesh Devnath Yadav .: Okay, so no need to, solve again first three questions, we can directly.

1228
02:01:14.220 --> 02:01:16.999
Faculty (Olympus): In fact, it should show you that those are done green, the Kaeger, no.

1229
02:01:17.000 --> 02:01:17.820
Dinesh Devnath Yadav .: Okay.

1230
02:01:17.820 --> 02:01:25.489
Faculty (Olympus): It should show you they're done, and you should just be able to continue. If there's an issue, that's where you, you know, you exit and you go and ask the TA for help.

1231
02:01:26.110 --> 02:01:27.160
Faculty (Olympus): And then we could see.

1232
02:01:27.550 --> 02:01:39.420
Dinesh Devnath Yadav .: Okay, thanks, processor. And the second question is, like, when I was attempting the mock quiz, for the last question only, it took almost 4 minutes to show the syntax error.

1233
02:01:39.930 --> 02:01:40.610
Dinesh Devnath Yadav .: So, I wasâ€¦

1234
02:01:40.610 --> 02:01:41.080
Faculty (Olympus): Boom.

1235
02:01:41.080 --> 02:01:42.290
Dinesh Devnath Yadav .: Waiting for, like.

1236
02:01:42.300 --> 02:01:43.380
Faculty (Olympus): Soâ€¦

1237
02:01:43.380 --> 02:01:45.470
Dinesh Devnath Yadav .: It is refreshing, refreshing.

1238
02:01:45.470 --> 02:01:52.910
Faculty (Olympus): So, I don't know, it's possible sometimes something on the server wasâ€¦ because I don't know, the mock test was taken all over the time, as inâ€¦

1239
02:01:53.080 --> 02:01:53.430
Dinesh Devnath Yadav .: Hmm.

1240
02:01:53.430 --> 02:01:58.620
Faculty (Olympus): You know, all over theâ€¦ so it may be that something happened in between on the server.

1241
02:01:58.780 --> 02:02:03.770
Faculty (Olympus): In this case, I'll have to ensure that on Saturday, there's noâ€¦ nothingâ€¦

1242
02:02:03.770 --> 02:02:04.170
Dinesh Devnath Yadav .: Yeah.

1243
02:02:04.170 --> 02:02:05.979
Faculty (Olympus): The server is in good condition.

1244
02:02:06.380 --> 02:02:21.949
Dinesh Devnath Yadav .: Even in the second attempt, Iâ€¦ intentionally, I put the error. Okay, I wasâ€¦ I thought maybe, due to my internet connection, it was taking more time, but again, in the second time, again, it took almost the same time, right?

1245
02:02:22.350 --> 02:02:24.069
Dinesh Devnath Yadav .: So maybeâ€¦ yeah.

1246
02:02:24.360 --> 02:02:28.580
Amlan Sarkar .: Sir, I also have the same problem in question number 4.

1247
02:02:28.860 --> 02:02:37.969
Amlan Sarkar .: So, first time I have, submitted the quiz, but when I tried second time in the fourth question, this indentation issue was there, I have not been able to submit.

1248
02:02:38.230 --> 02:02:40.299
Amlan Sarkar .: It took so much a long time.

1249
02:02:40.300 --> 02:02:43.379
Faculty (Olympus): The indentation, every time you hit check, it is actually submitted.

1250
02:02:43.590 --> 02:02:45.070
Faculty (Olympus): It's never not submitted.

1251
02:02:45.400 --> 02:02:55.670
Faculty (Olympus): That's gone, you've got an indentation error. Indentation error, easiest way to resolve it is in every line. So let's say you got an indentation error. Just quickly, just listen, hear me out. Many people turn into this. You go back.

1252
02:02:55.770 --> 02:03:01.870
Faculty (Olympus): You go back, And you ensure that you type whatever four spaces or whatever you want.

1253
02:03:02.280 --> 02:03:08.850
Faculty (Olympus): So check every line from the stop to the bottom, and then you'll find somewhere there's a mixture of tabs and spaces.

1254
02:03:08.850 --> 02:03:18.780
Amlan Sarkar .: Sir, sir, I follow your suggestion, but inâ€¦ I've never, never seen that kind of issue in the years, but during this test exam, na.

1255
02:03:18.980 --> 02:03:24.080
Amlan Sarkar .: Just one occasion, I find that, that's why I'm telling you. Yeah, it's possibleâ€¦ I don't know what is the reason.

1256
02:03:24.080 --> 02:03:42.789
Faculty (Olympus): So, let'sâ€¦ see, one thing is, sometimes if the TAsâ€¦ the exam has already a snippet. In that snippet, let's say they accidentally put a tab, then that could cause a problem, right? It's not code that you entered, but then you may be putting spaces, and they have put tab, or they have put tab, and you're putting spaces. So, sometimes this mess happens.

1257
02:03:43.250 --> 02:03:44.480
Faculty (Olympus): Unfortunately.

1258
02:03:44.780 --> 02:04:01.080
Faculty (Olympus): And in Python, there's no way to distinguish, because tab is not a hard-set 8 spaces. Tab can be anything you choose. In which case, it makes a difference if you use mixed tabs and spaces, it's impossible for Python to figure out where the indentation is, because if something is space, something is tab.

1259
02:04:01.330 --> 02:04:03.440
Faculty (Olympus): It can be anything, right? So thenâ€¦

1260
02:04:03.550 --> 02:04:04.180
Amlan Sarkar .: True.

1261
02:04:04.180 --> 02:04:05.770
Faculty (Olympus): That's the reason it's a problem.

1262
02:04:06.220 --> 02:04:09.980
Faculty (Olympus): So, just consistently use one, and you should be good.

1263
02:04:10.520 --> 02:04:11.340
Faculty (Olympus): Don't panic.

1264
02:04:11.340 --> 02:04:17.610
Amlan Sarkar .: copying from the Jupyter network to That's sometimes giving problem.

1265
02:04:17.610 --> 02:04:20.980
Faculty (Olympus): Yeah, many people were reporting this. I will talk to the Teas to sayâ€¦

1266
02:04:20.980 --> 02:04:37.349
Amlan Sarkar .: The interesting thing is that when I tried the first question, I copied and pasted in Jupyter Notebook and do the same thing, which worked. But when I'm trying in the second question, the details of first question kept in the memory or something like that, so even.

1267
02:04:37.350 --> 02:04:38.309
Siddhesh Dinesh Kadam .: So the clipâ€¦

1268
02:04:38.310 --> 02:04:38.840
Amlan Sarkar .: Eastern.

1269
02:04:38.840 --> 02:04:41.759
Siddhesh Dinesh Kadam .: Clipboard gets locked, I think, that's a problem.

1270
02:04:42.130 --> 02:04:46.459
Faculty (Olympus): Okay, maybe I'll ask the TAs to test this out a little more rigorously.

1271
02:04:46.460 --> 02:04:49.019
Amlan Sarkar .: I have, I have raised a ticket on that also.

1272
02:04:49.020 --> 02:04:50.180
Faculty (Olympus): Okay, sure.

1273
02:04:50.810 --> 02:04:53.410
Faculty (Olympus): Okay, so three things. One is copy-paste.

1274
02:04:53.970 --> 02:05:00.440
Faculty (Olympus): Second is Zoom. The first one is assignment extension. Okay, three things to keep in mind. Yeah.

1275
02:05:00.440 --> 02:05:03.789
Dinesh Devnath Yadav .: So even copy-paste is, like, it is popping a single line.

1276
02:05:04.680 --> 02:05:06.850
Faculty (Olympus): I don't think so, RaviPace, it's justâ€¦

1277
02:05:07.040 --> 02:05:23.349
Faculty (Olympus): You don't need copy-paste, you don't even need the Jupyter notebook. I mean, if you can answer the question. This is just a convenience, because many people feel, I don't get documentation, I can't do this, I can't experiment, I don't understand the error message, or whatever, right? So in that case, we're just saying, okay, here's a notebook.

1278
02:05:23.680 --> 02:05:25.320
Faculty (Olympus): Go with it as you please.

1279
02:05:30.650 --> 02:05:32.920
Faculty (Olympus): Alright, so I really have to go now.

1280
02:05:33.120 --> 02:05:35.910
Faculty (Olympus): Wish you all the best for your test.

1281
02:05:36.430 --> 02:05:37.309
Faculty (Olympus): Thank you, bro.

1282
02:05:37.310 --> 02:05:39.439
Soumen Deb .: Thank you. We will meet on a Saturday.

1283
02:05:39.610 --> 02:05:42.089
Faculty (Olympus): See you on Saturday morning, then. Bye.

1284
02:05:42.820 --> 02:05:44.209
Sejal Patil .: Bye, sir, thank you.

1285
02:05:44.210 --> 02:05:46.150
Faculty (Olympus): Good luck. Don't worry, don't panic.

1286
02:05:46.150 --> 02:05:48.240
Dinesh Devnath Yadav .: Excuse me.

1287
02:05:48.730 --> 02:05:49.660
Faculty (Olympus): Okay.

1288
02:05:50.060 --> 02:05:51.040
Dinesh Devnath Yadav .: Thank you, sir.

