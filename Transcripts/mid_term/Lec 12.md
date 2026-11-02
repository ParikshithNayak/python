WEBVTT

1
00:10:49.090 --> 00:10:50.580
Faculty (Olympus): Good evening, everyone.

2
00:10:53.080 --> 00:10:53.930
Amlan Sarkar .: Renee instead.

3
00:10:54.220 --> 00:10:54.690
Samar .: Hello, sir.

4
00:10:54.690 --> 00:10:55.090
Sunil Rawat .: beans.

5
00:10:55.490 --> 00:10:56.030
Faculty (Olympus): Noâ€¦

6
00:10:56.060 --> 00:10:57.730
Shravan Kumar Ganpur .: I think so.

7
00:10:57.730 --> 00:10:58.570
Dr Milind Vaishnav .: Billions ofâ€¦

8
00:10:59.310 --> 00:11:00.470
Faculty (Olympus): Good evening.

9
00:11:23.920 --> 00:11:29.100
Faculty (Olympus): All right, if there are any questions, I will again have to step out for a couple minutes.

10
00:11:33.810 --> 00:11:38.689
Faculty (Olympus): In between, soâ€¦ Let's see what it's going.

11
00:11:45.920 --> 00:11:50.050
Faculty (Olympus): Alright, so Iâ€¦ if you have any questions, we canâ€¦

12
00:11:51.020 --> 00:11:54.480
Faculty (Olympus): take them. Otherwise, I'm gonna just get back to Pandas.

13
00:11:57.620 --> 00:12:03.010
Faculty (Olympus): Okay, I don't see any hand raises, so I'm gonna assume there are no Questions?

14
00:12:03.210 --> 00:12:07.700
Faculty (Olympus): So let us get, let us get back to what we were looking at.

15
00:12:08.990 --> 00:12:12.309
Faculty (Olympus): You're able to hear me, see my screen, and see me, and all that, right?

16
00:12:12.310 --> 00:12:13.380
Dinesh Devnath Yadav .: Yes, yes, sir.

17
00:12:13.570 --> 00:12:14.270
Faculty (Olympus): Correct.

18
00:12:14.380 --> 00:12:15.120
Faculty (Olympus): Thank you.

19
00:12:15.580 --> 00:12:16.490
Faculty (Olympus): All right.

20
00:12:17.150 --> 00:12:20.570
Faculty (Olympus): So, we'll continue working with this, notebook.

21
00:12:20.720 --> 00:12:28.570
Faculty (Olympus): There is one small thing. I made a few changes. I added some additional content on multiâ€¦ multiâ€¦ multipleâ€¦

22
00:12:28.680 --> 00:12:31.150
Faculty (Olympus): Multi-indexing or hierarchical indexing.

23
00:12:31.310 --> 00:12:34.929
Faculty (Olympus): In the same notebook. So, if you want to access that.

24
00:12:35.100 --> 00:12:38.039
Faculty (Olympus): You know, delete your local version and refresh.

25
00:12:38.200 --> 00:12:42.489
Faculty (Olympus): the live version, you should get the latest version.

26
00:12:42.690 --> 00:12:49.799
Faculty (Olympus): But it's okay. Right now, if, you know, things are not working perfectly, it's okay. You can always get back, access to this.

27
00:12:50.430 --> 00:12:57.380
Faculty (Olympus): Alright, soâ€¦ I'm talking everything.

28
00:12:57.530 --> 00:13:00.109
Faculty (Olympus): All right, so,

29
00:13:00.380 --> 00:13:14.989
Faculty (Olympus): what we were looking at is this set of different types of objects that are available in Pandas, and we said that there are three important things. The most important is, of course, the data frame, and the data frame is something that is used to,

30
00:13:15.550 --> 00:13:17.870
Faculty (Olympus): Deal with tabular data.

31
00:13:18.180 --> 00:13:23.420
Faculty (Olympus): And series and indexes are essentially building blocks to build such a data structure.

32
00:13:23.850 --> 00:13:31.630
Faculty (Olympus): And the important fact about both data frames and series is that all of the data is aligned using an index.

33
00:13:31.770 --> 00:13:36.150
Faculty (Olympus): And so that is the key differentiator from this and just plain numpy arrays.

34
00:13:36.870 --> 00:13:53.009
Faculty (Olympus): Then we looked at, you know, series, spent some time looking at series, and I showed you here that there are two ways to access. One is by looking at the row number, which is, in some of your cases, will probably be not allowed, but in older versions of Pandas, you'll get a deprecation one.

35
00:13:53.070 --> 00:14:05.759
Faculty (Olympus): But the idea is, whenever you want to index into one of these, you must use, ideally, the index, okay? Later on, we saw lock and ILOC as well, which allow you to be a little more specific about which manner you want to do the indexing.

36
00:14:06.720 --> 00:14:15.760
Faculty (Olympus): We looked at series objects, then looked at basic operations, and then I showed you examples where we have indices which are non-integers.

37
00:14:15.860 --> 00:14:21.839
Faculty (Olympus): And then jumbled up, and then we looked at operations, and it lookedâ€¦ showed you that very clearly they align all this.

38
00:14:22.110 --> 00:14:27.709
Faculty (Olympus): And then we looked at the NAN, which is not a number, but still the number, part of your number system.

39
00:14:28.200 --> 00:14:40.979
Faculty (Olympus): which allows you to represent with the same data type, floating point data type, missing variables. And it is used in both NumPy, SciPy, as well as Pandas. So it's a standard thing that is used in

40
00:14:41.520 --> 00:14:42.970
Faculty (Olympus): these languages.

41
00:14:43.070 --> 00:14:45.690
Faculty (Olympus): We looked at various different methods.

42
00:14:45.930 --> 00:14:52.810
Faculty (Olympus): understood the ramifications of this. And then we jumped into data frames, and I showed you that you can construct data frames using different approaches.

43
00:14:52.970 --> 00:15:05.140
Faculty (Olympus): The first was to just create series objects with a common index, and then set it up using a dictionary which refers to each of these series, and then you ended up with a data frame.

44
00:15:08.310 --> 00:15:24.209
Faculty (Olympus): Then I also showed you that you can create a data frame by supplying lists or numpy arrays, which we showed later on, but the more common thing that you would find people doing, especially if you have columns or, you know, numpy arrays of data, you can always set it up using a dictionary.

45
00:15:25.700 --> 00:15:32.619
Faculty (Olympus): And this, in this particular case, the index was implicit, but you can always pass an explicit index and use that as an index.

46
00:15:33.010 --> 00:15:39.730
Faculty (Olympus): Then I also showed you that you can create it with a two-dimensional numpy array, so you can think of a data frame as a generalized two-dimensional array.

47
00:15:40.590 --> 00:15:41.360
Faculty (Olympus): Boop?

48
00:15:41.480 --> 00:15:46.329
Faculty (Olympus): Then we looked at the index object, and here is something which I want to clarify.

49
00:15:46.500 --> 00:15:57.580
Faculty (Olympus): The first thing is, so I said, okay, you can construct an index explicitly, and in some cases, it is implicitly constructed for you when you create, say, a series object, and don't pass, you know, you don't pass an explicit index.

50
00:15:57.830 --> 00:16:04.190
Faculty (Olympus): Then I said that you can do these union, intersection, and other kind of operations, okay? Butâ€¦

51
00:16:04.680 --> 00:16:14.680
Faculty (Olympus): Right? There was this doubt about whether indices need to be unique or non-unique. And I said that initially, the mapping that you should have is that it's like a primary key, you know, database.

52
00:16:15.180 --> 00:16:19.089
Faculty (Olympus): The reality is, indices do not need to be unique in panels.

53
00:16:19.470 --> 00:16:36.309
Faculty (Olympus): It's only a problem when you do certain kinds of operations with series or pandas or data frame objects, when those operations expect unique case, but for basic operations, you really don't need them to be unique, okay? So here are some examples which I've added. So let's look at this and just walk you through this example.

54
00:16:36.310 --> 00:16:48.159
Faculty (Olympus): So I'm saying IDX in this case. IDX is pandas.index, same old index fellow that we have, index object, and I'm passing it a list of integers, which refer to

55
00:16:48.210 --> 00:16:53.330
Faculty (Olympus): the indices. And notice that I have repeated values. I have 2, 2, 3, twice, okay?

56
00:16:53.940 --> 00:17:06.719
Faculty (Olympus): Now what I'm going to do is, I'm going to say A is pandas.series, a range 5, which means it's 0, 1, 2, 3, 4, and these are the index values, 1, 2, 2, 3, okay? And then I have B is pandas.series.

57
00:17:06.849 --> 00:17:10.270
Faculty (Olympus): NP.1s, so it's all five ones with the same index.

58
00:17:11.099 --> 00:17:18.419
Faculty (Olympus): Now, if I did A comma B, it will tell you what it looks like, and it looks exactly like what we say it is, so it's not illegal to do this.

59
00:17:18.680 --> 00:17:24.990
Faculty (Olympus): And here you haveâ€¦ 0123412233. And here you have all of them being months.

60
00:17:25.420 --> 00:17:26.600
Faculty (Olympus): So far, so good.

61
00:17:26.869 --> 00:17:36.430
Faculty (Olympus): Now, if I did A plus B, don't get surprised, this will work, okay? In fact, it'll do the exact right thing. It'll actually add 1 to each of these, so you'll get 1, 2, 3, 4, 5.

62
00:17:37.220 --> 00:17:38.120
Faculty (Olympus): All right?

63
00:17:38.420 --> 00:17:41.420
Faculty (Olympus): Now, here comes a slightly more complicated scenario.

64
00:17:41.730 --> 00:17:53.620
Faculty (Olympus): And I take this case, B is PD.series, and I say NP.Once, and I say index is 1, 2, 3, okay, so that's okay, and now I do A plus B, this will also work.

65
00:17:54.540 --> 00:17:56.240
Faculty (Olympus): And it'll give you the same result.

66
00:17:58.120 --> 00:18:04.660
Faculty (Olympus): Alright? Because what will happen is, when it does the operation, it'll look for the fellow with the same index and add that value.

67
00:18:06.360 --> 00:18:22.799
Faculty (Olympus): All right? So, you need to be a little careful about, you know, doing operations. Generally, you may not run into scenarios where the index is the same, but I just wanted to show you that you need not have unique indices. It's legal in the Pandas library.

68
00:18:22.800 --> 00:18:27.950
Faculty (Olympus): Okay? Whether you use it or not is up to you, but it is possible. Rahul?

69
00:18:28.690 --> 00:18:36.980
Rahul Joshi .: Sir, in this case, whenever, you did A plus B, whenever the index was same, let's say 2, it added,

70
00:18:37.420 --> 00:18:41.719
Faculty (Olympus): Whatever value was assigned to that particular invoice. So it was 1. In all of this, it's only 1.

71
00:18:41.920 --> 00:18:45.699
Rahul Joshi .: Yeah, but the final value of A plus B is,

72
00:18:45.700 --> 00:18:46.819
Faculty (Olympus): Same as before.

73
00:18:47.140 --> 00:18:56.189
Faculty (Olympus): Because all of them are 1. So it'll keep adding 1 to everyone, because when I look for the index of 2, it'll be 1. So when I see this fellow, it'll add 1. When I see this fellow also, it'll add 1.

74
00:18:57.230 --> 00:18:59.279
Faculty (Olympus): Because here, it is unique, in this case.

75
00:19:00.510 --> 00:19:05.450
Rahul Joshi .: Yeah, but then it should be 2 plus 1, 3, right? Original value was 2, isn't it? For index 2.

76
00:19:12.840 --> 00:19:13.730
Faculty (Olympus): Hang on.

77
00:19:15.230 --> 00:19:16.570
Faculty (Olympus): No, it was one.

78
00:19:17.460 --> 00:19:22.420
Faculty (Olympus): We were getting confused by the previous one. This is A plus B. Yeah, yeah, right? It's 0, 1, 2, 3, 4.

79
00:19:24.230 --> 00:19:26.439
Faculty (Olympus): 0 onto the four, right? It's okay.

80
00:19:26.650 --> 00:19:30.829
Faculty (Olympus): I suddenly, I got shocked. I was like, wait a minute, did I make a mistake? No, okay.

81
00:19:31.130 --> 00:19:33.279
Faculty (Olympus): Alright, so it's okay, it's consistent at this point.

82
00:19:34.320 --> 00:19:35.500
Faculty (Olympus): No, you may.

83
00:19:35.500 --> 00:19:36.040
Rahul Joshi .: Sorry if I justâ€¦

84
00:19:36.040 --> 00:19:38.060
Faculty (Olympus): Supposing I did thisâ€¦

85
00:19:42.560 --> 00:19:43.940
Faculty (Olympus): Also works.

86
00:19:44.100 --> 00:19:46.429
Faculty (Olympus): But notice, this is a bit messed up now.

87
00:19:48.180 --> 00:19:53.900
Faculty (Olympus): It does 1, 2, 2, 3. Because it's going to treat each of these twos as separate fellows.

88
00:19:54.130 --> 00:19:59.350
Faculty (Olympus): Right, so this starts getting messy, so generally, I would suggest

89
00:19:59.730 --> 00:20:06.649
Faculty (Olympus): Not doing things like this, where indices are repeated, because it becomes very hard for somebody to understand what is going on.

90
00:20:06.830 --> 00:20:16.309
Faculty (Olympus): Okay? And I don't want to spend time on this, because my recommendation is don't use indices that are the same, simply because it becomes very difficult for someone to figure out what's going on.

91
00:20:16.870 --> 00:20:19.549
Faculty (Olympus): Okay? But I'm just wanting to clarify

92
00:20:20.210 --> 00:20:22.960
Faculty (Olympus): It is not required that they are Junk.

93
00:20:23.440 --> 00:20:29.350
Faculty (Olympus): Okay, so since I mentioned someone, I think asked a related question, and I said something, I wanted to correct that, alright?

94
00:20:29.600 --> 00:20:40.629
Faculty (Olympus): So I don't want to, you know, continue this thing, because I don't use it simply because it's a mess like this, you know? You may get into some funny situations. All of these become special cases, which in general, avoid.

95
00:20:41.610 --> 00:20:44.200
Siddharth Digambar Kulkarni .: These are hierarchical indexes where.

96
00:20:44.200 --> 00:20:45.520
Faculty (Olympus): No, they're not.

97
00:20:46.470 --> 00:20:48.260
Faculty (Olympus): You know, we'll come to that.

98
00:20:48.590 --> 00:21:06.680
Faculty (Olympus): Then we looked at this toy example, and the idea here was to show you some simple, easy-to-understand thing, like, you know, X is linen space, 0 to 2 pi, and then we did sine and cosine of that, and then we constructed this silly data frame, very silly data frame. But the interesting thing is, I can now ask, tell me all the data values, or the rows, where the

99
00:21:06.680 --> 00:21:10.709
Faculty (Olympus): You know, sine is positive, cosine is positive, and things like that.

100
00:21:10.880 --> 00:21:26.090
Faculty (Olympus): Okay, so once again, we looked at various methods. I'm not going to repeat this. And then we spent quite a bit of time doing this, you know, indexing. You know, I listed out various ways by which you can do indexing into this. Rahul, I think you've, can I lower your hand?

101
00:21:26.090 --> 00:21:32.230
Rahul Joshi .: No, no, just one question, sir. So, whatever you mentioned about repeat indices for rows, is it the same concept for columns as well?

102
00:21:33.330 --> 00:21:34.710
Faculty (Olympus): Good question.

103
00:21:36.140 --> 00:21:38.140
Faculty (Olympus): Good question. You can try.

104
00:21:38.770 --> 00:21:39.919
Faculty (Olympus): Then let me know.

105
00:21:41.520 --> 00:21:42.020
Rahul Joshi .: We'll do that.

106
00:21:42.020 --> 00:21:44.300
Faculty (Olympus): I would imagine, yes, you can do it.

107
00:21:44.410 --> 00:21:52.579
Faculty (Olympus): But again, don't do it, because it's ridiculously confusing, right? I'll give you two columns with the same name, with different data values, God knows what you're doing, right?

108
00:21:52.680 --> 00:21:55.709
Faculty (Olympus): So, even if it does work, please avoid doing it.

109
00:21:55.940 --> 00:21:56.880
Rahul Joshi .: I'll do that again.

110
00:21:57.140 --> 00:22:12.649
Faculty (Olympus): Okay? And I'll show you hierarchical indexing, where a lot of these things will be kind of easily solved. You know, if you say, look, I have the same fellow, I have two different ears of that fellow, and I still want to use it as an index, you can. Okay, so we'll look at that very quickly. Anyway, we spent a lot of time looking.

111
00:22:12.650 --> 00:22:14.420
Rahul Joshi .: Just one more question, sorry.

112
00:22:14.420 --> 00:22:15.629
Faculty (Olympus): Can you hold your questions towards the.

113
00:22:15.630 --> 00:22:16.540
Rahul Joshi .: Okay, okay.

114
00:22:16.670 --> 00:22:20.589
Faculty (Olympus): Let me finishâ€¦ I'm still only doing summaries, I'm not even started on the main content.

115
00:22:20.800 --> 00:22:22.969
Faculty (Olympus): Okay, so he'llâ€¦ unless it'sâ€¦

116
00:22:23.510 --> 00:22:25.180
Rahul Joshi .: No, no, that's fine, we can wait till I have here.

117
00:22:25.180 --> 00:22:30.409
Faculty (Olympus): Yeah, we'll wait, I'll move ahead, and then, you know, let's do that. I want to finish Pandas for sure today.

118
00:22:30.970 --> 00:22:49.079
Faculty (Olympus): We looked at selecting columns, so if I do DF, give it a column name, it'll give you the column name, and that's usually this kind of indexing that you do. Otherwise, you can do slice of rows, or you can do Boolean vectors, okay? But if you want to really look at access through labels, right, so you select a row by label, you can use DF.lock.

119
00:22:49.080 --> 00:23:04.100
Faculty (Olympus): If you want to select it by numerical index, which is like the row number of your spreadsheet, then you use iloc, okay? And then there's the extended syntax, where you can do both the selection of rows and columns, and again, I have a typo here, which I have not fixed.

120
00:23:05.190 --> 00:23:06.190
Faculty (Olympus): Oops.

121
00:23:07.260 --> 00:23:10.399
Faculty (Olympus): Columns. Volume typos.

122
00:23:11.830 --> 00:23:22.230
Faculty (Olympus): Okay, and then you give it a Boolean vector, or something likeâ€¦ you can do the same thing for lock and ilock. You can say DF lock, comma, and give it a bunch of labels for your columns, and it'll give you both. It'll do row and column.

123
00:23:22.930 --> 00:23:28.069
Faculty (Olympus): The reason Nylock and lock are useful is because using just square brackets is very confusing.

124
00:23:28.820 --> 00:23:33.889
Faculty (Olympus): Okay, there's something else called IX, but I don't want to get into IX, because again, it's a hybrid between lock and IX.

125
00:23:34.270 --> 00:23:49.690
Faculty (Olympus): Alright, then we looked at various examples to understand this, and Iâ€¦ in order to explain iLoc better, because here, our data frame had an implicit index, and where the differenceâ€¦ this is not obvious, because the index is the same as 0, 1, 2, 3, 4, so it doesn't make a difference. Row number is the index.

126
00:23:49.770 --> 00:24:08.130
Faculty (Olympus): Right? So when we took an example with a non-integer index, and I showed you that, you know, you can do lock of A, lock of A colon B, and here, please remember, when you do lock of A colon B with labels, it will always include the last index. Okay, so this is unlike normal Python slicing. Just keep this as a warning in your head.

127
00:24:08.130 --> 00:24:12.549
Faculty (Olympus): And iLog, of course, will not do that. iLog, when you put a slice, it will exclude the last time.

128
00:24:12.660 --> 00:24:16.689
Faculty (Olympus): Only for labels, this, you know, different thing happens.

129
00:24:17.030 --> 00:24:25.470
Faculty (Olympus): All right, then we looked at conditional indexing, or rather, conditional or Boolean vectors, and how this is very useful, when we are doing

130
00:24:25.580 --> 00:24:29.339
Faculty (Olympus): Playing with data flames, and this allows you to subset your rows.

131
00:24:29.590 --> 00:24:48.120
Faculty (Olympus): Right? So, based on conditions, and it's very easy to write. It's the same idea as what we did with NumPy arrays, and only thing to remember is, you must always put brackets between your conditions, and do not use AND, OR and NOT and things like that. You must use the bitwise operators, which is pipe, ampersand, tilde, and Kat.

132
00:24:48.120 --> 00:24:49.700
Faculty (Olympus): All of those liquid noobs.

133
00:24:50.260 --> 00:25:02.970
Faculty (Olympus): Then we looked at how do you add a new column. You simply say DF of whatever column name, and then supply it with an appropriate Pandas Array, or sorry, Panda's series object.

134
00:25:03.620 --> 00:25:05.959
Faculty (Olympus): And then I showed you by doing Dell.

135
00:25:06.310 --> 00:25:11.650
Faculty (Olympus): DataFrame of a specific column name, it will delete or remove that column.

136
00:25:12.340 --> 00:25:31.980
Faculty (Olympus): Then we looked at operations and index alignment. So far, it's only construction and slicing and, you know, all of those. Now the question is, okay, if I have two data frames, and I'm going to do, you know, adding them and things like that, what happens? And we immediately saw that when you add these two fellows, what it does is it adds NANs wherever the data is missing in the other fellow.

137
00:25:32.260 --> 00:25:47.510
Faculty (Olympus): And so one way to avoid this NAN, if you really want to avoid it, is, you know, you can use the fill value when you use the functional form, the method form, so you can do A.add, B, and give it the fill value, okay? Similarly, there are many of these other methods, so you can do this.

138
00:25:49.260 --> 00:25:50.870
Faculty (Olympus): Okay,

139
00:25:51.290 --> 00:26:02.170
Faculty (Olympus): Then we looked at missing values, and again, this is just to tell you that in series objects, when you create an object like this, it just lists, none is also acceptable, as is np.man.

140
00:26:02.170 --> 00:26:13.800
Faculty (Olympus): But here, please note that this object type here is object. So if I ran this, notice that it gives me object data, which is really not a good idea, because I will not get any statistics for things like this, because it cannot treat this as any

141
00:26:13.900 --> 00:26:24.159
Faculty (Olympus): set of floating point numbers. So when you have floating point numbers, it cannot support things like none. You will always use NAN values, which are part of your floating point number system.

142
00:26:24.710 --> 00:26:42.279
Faculty (Olympus): Then I showed you that you can use isNull, not null, drop na, and fill na. All of these methods are useful to manipulate your series object or your data frame. You canâ€¦ the same kind of methods are there in your data frame also, where you can essentially drop all null values or fill null values with a specific value.

143
00:26:43.870 --> 00:26:49.609
Faculty (Olympus): This is where we stopped, so I will now resume from here. Rahul, very quickly, if you have a question, I will answer your question.

144
00:26:50.080 --> 00:27:03.439
Rahul Joshi .: Okay, thank you, sir. Sir, from the database perspective, if you try to correlate, we allâ€¦ we have a concept of joint primary key, where two columns will act as a primary key. Is something available here? Like, two things will collectively become an index.

145
00:27:03.610 --> 00:27:12.039
Faculty (Olympus): I don't know, I don't think that analogy is very, you know, I don't know, you know, if it makes sense, but a multi-index does correspond to somewhat what you're saying.

146
00:27:12.940 --> 00:27:22.010
Faculty (Olympus): Okay, but I don't know the subtleties of, you know, joint column index being primary key in your database example. So, to that extent, yes, a multi-index will go.

147
00:27:23.220 --> 00:27:30.919
Faculty (Olympus): All right, so moving on, when we look at assignment of values, this is something very important, so I'd like you to please pay attention to this.

148
00:27:31.030 --> 00:27:38.140
Faculty (Olympus): Especially when you're doing manipulations or assigning values, using And as data frames.

149
00:27:38.360 --> 00:27:46.290
Faculty (Olympus): So, what I'm going to do here is, I'm gonna look at this D. I don't know where I created it. Okay, I think it's this fellow. So, let me construct this. Okay.

150
00:27:46.430 --> 00:27:59.419
Faculty (Olympus): This is our D, data frame, so it's 0, 1, 2, A, B, C, D are the columns, okay? Now, what I would like to do is, I would like to look at all of the columns, this is a littleâ€¦

151
00:27:59.780 --> 00:28:04.700
Faculty (Olympus): I'll run it again, because I have all of those values are actually less than pipe.

152
00:28:05.060 --> 00:28:19.269
Faculty (Olympus): Okay, fine. So this is our D, okay? Alright, this is D. I re-ran it because my next line is saying d dot A is greater than 5. Everything was actually less, you know, not greater than 5, so I'll get the whole data frame.

153
00:28:19.390 --> 00:28:23.190
Faculty (Olympus): So, supposing I did this T, index.

154
00:28:23.450 --> 00:28:26.639
Faculty (Olympus): D dot A greater than 5. What should I get back?

155
00:28:27.410 --> 00:28:28.649
Faculty (Olympus): What should this result?

156
00:28:28.650 --> 00:28:29.729
Siddharth Digambar Kulkarni .: What's two rows.

157
00:28:31.790 --> 00:28:37.139
Faculty (Olympus): Correct. Okay, this will give me the first two routes. So it'll give me a data frame with the same columns and just the first roots.

158
00:28:37.250 --> 00:28:52.519
Faculty (Olympus): Okay? Now, in NumPy, we would have said, hey, I want to set all those fellows to some number, okay? I want to take all the A values here, which are greater than 5, and Usme, I want to set them to some, you know, minus 1, God knows, whatever value, right?

159
00:28:53.390 --> 00:28:59.359
Faculty (Olympus): If I wanted to do that, the natural way I can do this in Pandas is to think, oh, okay, I'll do D dot

160
00:28:59.480 --> 00:29:01.930
Faculty (Olympus): Day off, D.A of 5.

161
00:29:02.320 --> 00:29:04.090
Faculty (Olympus): Then access the A,

162
00:29:04.640 --> 00:29:09.519
Faculty (Olympus): Then set it to 25. Okay, now I could have done it with either this square bracket.

163
00:29:09.670 --> 00:29:13.300
Faculty (Olympus): Or I could have put it inside here, Okay?

164
00:29:13.540 --> 00:29:19.570
Faculty (Olympus): Doesn't matter, okay? Or I could have said dot capital A, whatever be the mechanism.

165
00:29:19.980 --> 00:29:29.489
Faculty (Olympus): I'm now going to set this to 25, okay? Now, when I run this, I will get an exception, okay? Or actually, not an exception in this case. Some of you might get an exception, okay?

166
00:29:30.220 --> 00:29:31.779
Faculty (Olympus): What this is doing isâ€¦

167
00:29:32.630 --> 00:29:41.529
Faculty (Olympus): It is saying, sitting with a copy warning, okay? Again, read this carefully. A value is trying to be set on a copy of a slice from a data frame.

168
00:29:42.210 --> 00:29:45.860
Faculty (Olympus): And it also tells you the answer, you know, how do you fix this?

169
00:29:46.370 --> 00:29:56.080
Faculty (Olympus): try using .loc row indexer, call it, okay? So when you do slicing or indexing of your data frame using this raw syntax.

170
00:29:56.160 --> 00:30:07.860
Faculty (Olympus): It is actually not allowed, and in fact, it did not do the trick. It did not set these fellows to 25, right? If you look at the result, I printed, I've shown you what D is. It's still 9-9. It's not 25.

171
00:30:08.520 --> 00:30:14.459
Faculty (Olympus): So the way to fix this is, you do something like this, d.loc, D of A, comma A,

172
00:30:14.590 --> 00:30:20.099
Faculty (Olympus): is equal to 25. Now, notice the difference is only the use of the LOC. When you do this.

173
00:30:20.100 --> 00:30:38.060
Faculty (Olympus): It is absolutely clear to Pandas what you mean and what you're doing, and in this case, there will be no warning, and it'll do what you expect, okay? So whenever you see this, I've specifically put this in a section in this notebook, because this is something you will run into, and when you see this, you will freeze. Oh, I have to see this document, it's pointing to some HTML document.

174
00:30:38.060 --> 00:30:43.960
Faculty (Olympus): Feel free, you know, don't worry about it. All it is is, it's telling you this, please carefully read it, and it actually tells you what.

175
00:30:44.310 --> 00:30:49.770
Faculty (Olympus): Okay? When you are setting this, don't just use that, use .locos. Is that okay?

176
00:30:50.070 --> 00:31:03.130
Faculty (Olympus): So just keep this in mind, okay? So always beware of this setting with copy warnings. Avoid ever setting values on slices subsets without due care, which means don't do things like this. Always use it through Ellis.

177
00:31:03.350 --> 00:31:05.850
Faculty (Olympus): Alright? That's one warning to keep in mind.

178
00:31:06.550 --> 00:31:14.859
Faculty (Olympus): Okay, so the next thing is string processing. This is, again, extremely useful, so I'll finish that, and then we'll get to RTMS.

179
00:31:15.390 --> 00:31:17.060
Faculty (Olympus): So, it's string processing.

180
00:31:18.260 --> 00:31:24.529
Faculty (Olympus): You're always going to run into situations where you have a Pandas data frame, and the values in that

181
00:31:24.730 --> 00:31:41.270
Faculty (Olympus): in that column are some strings, and you may want to process those strings. For example, you may say, okay, capitalize it, or, you know, make it all caps, or, you know, cut and show me only the first three characters. You know, whatever. You may want to do some processing, okay? So what I'm going to do here is, I'm going to basically show you

182
00:31:41.270 --> 00:31:47.009
Faculty (Olympus): a littleâ€¦ some examples that will give you an idea of a feel for how to do this with Pandas, okay?

183
00:31:47.150 --> 00:32:04.009
Faculty (Olympus): So, let's create this pandas.series with an implicit index, and here I have A, B, C, A, whatever, some bunch of things. One missing value in between, okay, and then some other strings, and I'm setting explicitly the data type to string, okay? So, if I were to do thisâ€¦

184
00:32:04.570 --> 00:32:09.360
Faculty (Olympus): And above here, I'm going to sayâ€¦ let's look at S.

185
00:32:09.950 --> 00:32:13.249
Faculty (Olympus): Okay, it says data type string, ABC, blah blah blah.

186
00:32:13.870 --> 00:32:14.720
Faculty (Olympus): Okay.

187
00:32:15.160 --> 00:32:21.339
Faculty (Olympus): Now, if I want to say, give me lower on all of these, we have our old familiar string methods.

188
00:32:21.500 --> 00:32:31.179
Faculty (Olympus): Now, instead of beingâ€¦ you can't do s.lower, because that is not a method for series objects. But seriesâ€¦ S series objects have this strâ€¦

189
00:32:31.360 --> 00:32:49.580
Faculty (Olympus): accessor function, okay? This is an accessor, little fellow here. You do s.Str, it'll basically allow you to use any of the string methods. Okay, so if I did this, there are other accessors as well in Python, like datetime and things like that, but, you know, let's just look at this. If I do s.str.lower.

190
00:32:49.600 --> 00:32:54.959
Faculty (Olympus): It'll give me another series object, which is all of the values lowercase.

191
00:32:55.000 --> 00:32:57.260
Faculty (Olympus): Okay, same way you can do uppercase.

192
00:32:57.500 --> 00:33:02.899
Faculty (Olympus): And then you can do chaining of these methods. So, for example, I say, give me all of them into upper.

193
00:33:03.290 --> 00:33:13.200
Faculty (Olympus): put a .STR on that, and then say replace C, the occurrence, with XX. Okay, so let's say, okay, let's do that, and we get this. All right? So this makes it very easy

194
00:33:13.200 --> 00:33:23.350
Faculty (Olympus): to do these quick replacements, or checks, or whatever you will, if you want to do, you can do using these string methods. And I think if you do str.tab.

195
00:33:25.510 --> 00:33:28.390
Faculty (Olympus): You would see all of the different You know.

196
00:33:29.970 --> 00:33:34.180
Faculty (Olympus): methods that are available, okay? And some of these may be more than

197
00:33:34.420 --> 00:33:39.839
Faculty (Olympus): you know, what is available typically in, SDR. Maybe, maybe not.

198
00:33:40.300 --> 00:33:41.150
Faculty (Olympus): Okay?

199
00:33:43.180 --> 00:33:59.749
Faculty (Olympus): So you'll find a lot of these methods. All right, is that okay? So string processing is also very easy, so you justâ€¦ so basically, if you have a data frame and you want to say, yank this column and want to update that column, you do this. You say df.lock, whatever thing you want to access, you get the column.

200
00:34:00.010 --> 00:34:02.410
Faculty (Olympus): Then you can basically reset that call.

201
00:34:02.860 --> 00:34:03.670
Faculty (Olympus): G.

202
00:34:03.890 --> 00:34:06.979
Faculty (Olympus): Or you can change some values by doing pd.

203
00:34:08.020 --> 00:34:16.509
Faculty (Olympus): Sorry, you can get that string from a specific column, which is a series object, and that .str.whatever methods you want to do, and thenâ€¦

204
00:34:17.000 --> 00:34:17.960
Faculty (Olympus): Now, thisâ€¦

205
00:34:18.650 --> 00:34:29.769
Faculty (Olympus): This is not the only kind of processing. You can do. If you read Panda's documentation, there are other things you can do. You can apply functions to every row, right? I don't want to get into that. I'm only sort of giving you an overview of a flavor for Pandas.

206
00:34:31.010 --> 00:34:41.430
Faculty (Olympus): So now we enter into multi-index, and I don't see any hand raises, so I'm assuming there are no questions, and I'm going to carry on. Is that okay? Because we still have quite a bit to cover.

207
00:34:41.889 --> 00:34:43.270
Faculty (Olympus): banners.

208
00:34:43.489 --> 00:34:49.830
Faculty (Olympus): All right, so I added this material. Okay, Rahul has some questions. Yes, quickly.

209
00:34:49.830 --> 00:34:55.389
Rahul Joshi .: Sir, the seriesâ€¦ every row is a series, right, in Panda.

210
00:34:56.440 --> 00:34:59.629
Faculty (Olympus): every rowâ€¦ I mean, it depends on how you access it.

211
00:34:59.920 --> 00:35:04.759
Faculty (Olympus): If you access out a single row, you'll get a series object. You access toâ€¦ Okay.

212
00:35:04.760 --> 00:35:09.429
Rahul Joshi .: Yeah, so in this example, wherever, like, the series was,

213
00:35:09.650 --> 00:35:20.790
Rahul Joshi .: created, and then we wanted to change it for the, using the string. You said that it will work for columns as well, but whenever we look up for a column, it is not a series, right? It is aâ€¦

214
00:35:20.790 --> 00:35:25.699
Faculty (Olympus): Of course it is a series. That's the first thing we discussed. Every column axis is a series object.

215
00:35:25.700 --> 00:35:28.630
Rahul Joshi .: A column is also a series, okay. So both rows and column is a series, okay.

216
00:35:28.630 --> 00:35:33.749
Faculty (Olympus): Again, you try it. Please try it. Again, I can't make a blanket statement, because if I yank two rows out.

217
00:35:33.890 --> 00:35:35.370
Faculty (Olympus): It'll give me a data frame.

218
00:35:36.070 --> 00:35:39.349
Faculty (Olympus): So please try it, please try it. Soumen?

219
00:35:40.440 --> 00:35:44.189
Soumen Deb .: Small doubt, though. So, have you uploaded the latest notebook?

220
00:35:44.190 --> 00:35:50.879
Faculty (Olympus): I have. So what you have to do is, you will have to delete your old ones and refresh, because I made changes after I uploaded it last time.

221
00:35:51.140 --> 00:35:53.040
Soumen Deb .: Okay, I hope it's there.

222
00:35:53.040 --> 00:35:59.920
Faculty (Olympus): If it is not there, next time, you know, I don't know, maybe your cache, whatever, hard reset, hard refresh.

223
00:36:00.330 --> 00:36:01.129
Soumen Deb .: No, no, I'll go.

224
00:36:01.130 --> 00:36:07.639
Faculty (Olympus): Anyway, by next class, it'll beâ€¦ I guess the TAs will upload the thing on GL also, so don't worry.

225
00:36:07.730 --> 00:36:17.400
Faculty (Olympus): All right, so here, I'm just looking at advancedâ€¦ this is veryâ€¦ this is sort of advanced. I usually didn't want to do it, but since there were questions, I thought I'd quickly introduce it, and it's actually very, very powerful.

226
00:36:17.460 --> 00:36:29.320
Faculty (Olympus): So, you can think of multi-index as hierarchical indexing, and what it allows you to do is allows you to do multiple indexing levels. Okay, so again, I'm basing this around some of the material available in Jake's book.

227
00:36:29.320 --> 00:36:38.019
Faculty (Olympus): the Python Data Science Handbook. The example is, of course, different, but I'm kind of using that example to illustrate to you what the power of this approach is, okay?

228
00:36:38.160 --> 00:36:57.580
Faculty (Olympus): So let's have this example data. There are 3 people, this is, of course, fake data. There are 3 people, and they did annual medical tests for 2 years, 2025 and 2026, and they have the BP measurement, systolic and diastolic, right? I hope you all know systolic. 120 by 80, 120 is systolic, 80 is your, you know, diastolic value.

229
00:36:57.710 --> 00:37:15.310
Faculty (Olympus): So, we have Amar, and I have just put the data here to give you a feel for the data. 2025 isâ€¦ he has 125 and 82, and 2026, he has 130 and 90, so on and so forth. So, I have Amar, Apwar and Anthony, all of them have some, you know, scores, as in, some values. And you can clearly see that

230
00:37:15.450 --> 00:37:20.080
Faculty (Olympus): Amar is one person, and he has two years, and then there are two measures.

231
00:37:20.690 --> 00:37:35.130
Faculty (Olympus): So, in some sense, you can think of this as, okay, if I list out all the systolics, I'll get 125, 130, 127, 120, 132, 125, which is what I've done here. And similarly, list all the diastolics, and I put them into a range. So, this looks like I have two columns.

232
00:37:36.060 --> 00:37:36.850
Faculty (Olympus): Okay?

233
00:37:37.040 --> 00:37:52.169
Faculty (Olympus): Which is fine, right? Now we can do a very kind of poor man's approach to do this. In principle, my index can be anything, right? So I can put an index to saying Anar 2025, Amar 2026, Akbar 2025, Akbar 2026.

234
00:37:53.390 --> 00:37:56.660
Faculty (Olympus): Okay? Now, if I did this, it will work. Wait a minute.

235
00:37:57.030 --> 00:38:00.020
Faculty (Olympus): I know Ran these fellows.

236
00:38:00.440 --> 00:38:16.300
Faculty (Olympus): Okay, now this is a little ugly. Firstly, this naming, numbering is like a mess. And now, let's say I want you to give me everybody's 2025 data. You will have to write a bunch of for loops to get this out. It's not straightforward to extract, okay? Because

237
00:38:16.490 --> 00:38:26.670
Faculty (Olympus): The index inside it isâ€¦ each element is a tuckle. From that tuple, you have to yank out, you know, the second element, and then extract that somehow. So it becomes a bit of a pain, okay?

238
00:38:27.630 --> 00:38:42.590
Faculty (Olympus): A natural approach of handling this data is to use the multi-index. So, when you do multi-index, all you need to do is you say pandas.multi-index. This has a special constructor or a class method, which is called from tuples. What it does is.

239
00:38:42.730 --> 00:38:44.660
Faculty (Olympus): Given this index.

240
00:38:45.260 --> 00:39:01.870
Faculty (Olympus): the same set of tuples that we had, it will construct what is called a multi-index, okay? And then I repeat the same thing. This is the same old fellow, pandas.dataframe. Earlier, I had this index is equal to that index, which is just the tuples, list of tuples. Here, I'm saying.

241
00:39:02.620 --> 00:39:06.629
Faculty (Olympus): index is equal to IDX, okay? So note that I'm using index as IDX here.

242
00:39:07.240 --> 00:39:09.179
Faculty (Olympus): And now, let's say how this looks.

243
00:39:09.660 --> 00:39:24.000
Faculty (Olympus): Now this looks beautiful, right? It has Amar, 2025, 2026, Aquar, 2025, 26, so on and so forth. And please note, you can use multi-indices even for the columns, right? So you can do this, so you can really have fairly complicated-looking spreadsheet, okay?

244
00:39:24.550 --> 00:39:34.550
Faculty (Olympus): Now, I can use this in multiple ways. I can say, give me all the systolic, it'll do what you expect. It'll do Amar, then 2026, blah blah blah, and there's only systolic, right?

245
00:39:34.990 --> 00:39:46.379
Faculty (Olympus): You can also find only Akbar's data and say df.loc Akbar. And notice, it has given you a sort of subset in a smaller data frame without the multi-index in this case.

246
00:39:47.060 --> 00:39:48.610
Faculty (Olympus): Okay?

247
00:39:49.470 --> 00:40:01.830
Faculty (Olympus): But now, if I want to say, okay, give me only his historic, that is also easy, right? But now comes a slightly more complex one. Supposing I want to give me all the 2025 fellow values, right?

248
00:40:02.310 --> 00:40:12.050
Faculty (Olympus): Now, you can do this using slices, but the syntax for this is a bit of a mess. You'll have to create slice objects like this.

249
00:40:12.490 --> 00:40:14.300
Faculty (Olympus): Right? And then do this.

250
00:40:14.430 --> 00:40:22.839
Faculty (Olympus): And let's see what we get. It works, Amar2025, but 25. Again, I didn't have to write a for loop, but writing this is messy, and, you know.

251
00:40:24.000 --> 00:40:25.569
Faculty (Olympus): This is not the best way to do it.

252
00:40:26.400 --> 00:40:35.670
Faculty (Olympus): It turns out there is this pandas.index slice, which makes this syntax much easier. So you can basically do this, you can say df.loc.

253
00:40:35.840 --> 00:40:49.150
Faculty (Olympus): pd.index slice, so notice I've not done anything new. Instead of giving itâ€¦ so ideally, I don't want it this to work, right? I just want to say df.loc, colon, comma 2025, comma, colon, right? Unfortunately, that will not work.

254
00:40:49.600 --> 00:40:53.270
Faculty (Olympus): But this will work. So if I were to do this, this will work.

255
00:40:53.910 --> 00:41:04.030
Faculty (Olympus): And it'll do exactly the same thing. So using this index slice object is very useful. You'll sometimes see same examples by looking like this IDS is a control kd.

256
00:41:04.680 --> 00:41:08.559
Faculty (Olympus): That's nice. And then we can shorten this to ideals.

257
00:41:09.140 --> 00:41:11.210
Faculty (Olympus): Okay, so it's the same thing.

258
00:41:11.360 --> 00:41:26.760
Faculty (Olympus): I just replaced this upon that. So once again, when you want to create multi-indexes, or hierarchical indexing, you can use this tuple syntax. There is also another way, so if you look at multi-index.tab.

259
00:41:26.910 --> 00:41:35.869
Faculty (Olympus): Start fromâ€¦ tuplesâ€¦ Saurabh also, I think, is there.

260
00:41:37.410 --> 00:41:52.960
Faculty (Olympus): I don't know, maybe it's for whatever reason, it's not completing for me here. There are other ways to initialize multi-index objects, okay? So you can look at multi-index, look at the documentation, and you'll find for in this particular case, so for example, we have two fellows, two indices.

261
00:41:53.870 --> 00:42:02.380
Faculty (Olympus): You can supply that. Another simple way of creating a multi-index, so maybe I'll show you that, Isâ€¦

262
00:42:04.270 --> 00:42:06.360
Faculty (Olympus): Soâ€¦ backâ€¦

263
00:42:15.750 --> 00:42:16.580
Faculty (Olympus): No.

264
00:42:17.780 --> 00:42:20.009
Faculty (Olympus): Yes, I see it.

265
00:42:21.540 --> 00:42:25.780
Faculty (Olympus): Index equal toâ€¦ I think you can give it a list of lists.

266
00:42:26.500 --> 00:42:30.970
Faculty (Olympus): So, Amoveâ€¦ What?

267
00:42:33.180 --> 00:42:33.950
Faculty (Olympus): Boss?

268
00:42:46.110 --> 00:42:49.480
Faculty (Olympus): Yeah, this is a pain, butâ€¦ Tim, you get the idea.

269
00:42:55.140 --> 00:42:56.870
Faculty (Olympus): So, close this.

270
00:42:59.440 --> 00:43:02.980
Faculty (Olympus): This is, 2025.

271
00:43:03.260 --> 00:43:05.150
Faculty (Olympus): 2026.

272
00:43:05.450 --> 00:43:06.859
Faculty (Olympus): Different effect.

273
00:43:07.120 --> 00:43:08.109
Faculty (Olympus): So, excuse me.

274
00:43:09.770 --> 00:43:12.269
Faculty (Olympus): Since I hope and pray this works.

275
00:43:14.340 --> 00:43:19.570
Faculty (Olympus): And it does, okay? So, in some of these cases, you can just supply the index

276
00:43:19.800 --> 00:43:32.680
Faculty (Olympus): the way it is, and that will work, but it's also useful to be able to know these methods exist, okay? So, I didn't want to spend too much time on this, but I want to show you that you can indeed have multi-units, okay? You can

277
00:43:32.960 --> 00:43:37.939
Faculty (Olympus): And you canâ€¦ you can do more. It's not just one index, you can have multiple such indexes.

278
00:43:39.850 --> 00:43:43.189
Siddharth Digambar Kulkarni .: That index value can go up a little bit.

279
00:43:43.590 --> 00:43:44.210
Faculty (Olympus): Pardon?

280
00:43:44.730 --> 00:43:48.750
Siddharth Digambar Kulkarni .: Like, index, above, a little bit above.

281
00:43:52.270 --> 00:43:57.030
Siddharth Digambar Kulkarni .: From tuples, index you've written? Index of this. Okay, okay.

282
00:43:59.030 --> 00:44:11.889
Faculty (Olympus): Yeah, you can anyway walk through this notebook on your own later on, and you can play with this little example. Just to give you a feel for this, you can also do the same thing with columns. Set the columns to something like this, and set those values.

283
00:44:11.900 --> 00:44:19.699
Faculty (Olympus): And again, I would strongly suggest you read the Data Science Handbook, because now that you have familiarity, it's very easy to read those and pick it up.

284
00:44:20.460 --> 00:44:23.829
Faculty (Olympus): So I'll now move to the next topic, which is plotting.

285
00:44:24.030 --> 00:44:27.629
Faculty (Olympus): So, are there any questions at this point?

286
00:44:31.420 --> 00:44:33.250
Faculty (Olympus): I don't see any questions.

287
00:44:35.600 --> 00:44:36.390
Faculty (Olympus): Okay.

288
00:44:36.610 --> 00:44:39.900
Faculty (Olympus): So now we'll look at something very nice,

289
00:44:40.090 --> 00:44:48.050
Faculty (Olympus): Unfortunately, I have messed up my data frame here to go back to our original data frame that I was playing around with.

290
00:44:49.520 --> 00:44:50.909
Faculty (Olympus): Just like tingâ€¦

291
00:44:55.540 --> 00:44:58.520
Faculty (Olympus): So, DF is here, sorry.

292
00:44:59.070 --> 00:45:00.649
Faculty (Olympus): Let me just do this.

293
00:45:02.270 --> 00:45:04.110
Faculty (Olympus): Oh, I didn't run this, sir.

294
00:45:06.880 --> 00:45:09.080
Faculty (Olympus): I will also delete the rows.

295
00:45:09.850 --> 00:45:12.050
Faculty (Olympus): Sorry, the additional columns?

296
00:45:15.440 --> 00:45:20.309
Faculty (Olympus): Alright, so now, what I would like to do is, I'd like to show you some plotting.

297
00:45:21.160 --> 00:45:22.410
Faculty (Olympus): done all of this?

298
00:45:22.920 --> 00:45:31.149
Faculty (Olympus): Sorry about the scrolling. Okay, so that's our old data frame, so maybe I will show you the data frame again. Let's say df.red.

299
00:45:32.010 --> 00:45:34.250
Faculty (Olympus): And we have this, all the good.

300
00:45:34.510 --> 00:45:37.090
Faculty (Olympus): Now, I want to do a plot of this.

301
00:45:37.410 --> 00:45:45.350
Faculty (Olympus): Now, the standard, easy way of doing this plotting is, you can simply say, madplotlibâ€¦ sorry.

302
00:45:45.570 --> 00:45:51.040
Faculty (Olympus): Import plt.plot, df.x, df.sign, I think like that, right?

303
00:45:51.110 --> 00:46:05.729
Faculty (Olympus): But it turns out that Matplotlib itself, sorry, Pandas itself supplies some convenient plotting functions. So on the face of it, it looks straightforward, but if I just did this, what this will do is it will plot all the values against the index by default, okay?

304
00:46:07.030 --> 00:46:20.609
Faculty (Olympus): So by default, it takes whatever data frame you have, plots all of the columns that it possibly can, using the index. And in this case, the index is 01234, okay? And I think there were 100 values, and so you can see that.

305
00:46:21.390 --> 00:46:32.620
Faculty (Olympus): Now, if you want to plot, like, actually sine versus cosine, you can modify this by passing additional keyword arguments to tf.plot, and say line X is equal to X, and Y is whatever sine and

306
00:46:32.850 --> 00:46:34.869
Faculty (Olympus): Design column names that you want.

307
00:46:34.990 --> 00:46:50.949
Faculty (Olympus): And this will do what you expect. It'll also give you this nice legend. So basically, and it labels this fellow as x-axis, right? So it basically does a nice job, automatically gives you a plot in one shot, right? So you don't have to write multiple lines of code with Matplotlib and things like that.

308
00:46:51.120 --> 00:46:57.209
Faculty (Olympus): So this is a useful feature. Under the covers, it is using, Matwa.

309
00:46:57.440 --> 00:46:59.170
Faculty (Olympus): Now,

310
00:46:59.410 --> 00:47:18.039
Faculty (Olympus): There are other libraries, like Altair and other things, which are very well suited for plotting data online or in notebooks, and they also have plugins which will allow you to do plotting through a data file. Okay, so for that, you please go and look up their respective documentation, but in this particular case, this is using Matlock for the plot.

311
00:47:18.320 --> 00:47:19.290
Faculty (Olympus): Abhineet?

312
00:47:20.160 --> 00:47:22.179
Abhineet Bansal: What happens if there's a NAND value?

313
00:47:23.310 --> 00:47:24.160
Faculty (Olympus): You've tried.

314
00:47:24.700 --> 00:47:26.530
Faculty (Olympus): It will not plot those values.

315
00:47:27.110 --> 00:47:28.599
Faculty (Olympus): Missing values would be ignored.

316
00:47:29.310 --> 00:47:30.399
Abhineet Bansal: will be ignored.

317
00:47:30.400 --> 00:47:38.589
Faculty (Olympus): Yes. That even works with Matplotl. Try it with Matplotl. Create two NumPy arrays, put some NANs. It'll basically break the line there.

318
00:47:39.970 --> 00:47:40.530
Abhineet Bansal: Trust me.

319
00:47:40.940 --> 00:47:41.650
Faculty (Olympus): Okay?

320
00:47:44.600 --> 00:48:00.359
Faculty (Olympus): All right, so here is another example. We're doing DF, I'm now subsetting it. I'm saying, give me all the fellows which are X-ordered in this case. I'll just say AND in this case. I plot them, I do a line, I say X is X, and I use a marker of

321
00:48:00.740 --> 00:48:03.240
Faculty (Olympus): Okay, also, if I run this, I will get this.

322
00:48:05.280 --> 00:48:06.060
Faculty (Olympus): Good?

323
00:48:06.270 --> 00:48:07.750
Faculty (Olympus): Soâ€¦

324
00:48:10.870 --> 00:48:13.729
Faculty (Olympus): So it takes care of a lot of things when you own this.

325
00:48:13.860 --> 00:48:23.770
Faculty (Olympus): Now, you can also do histograms. For example, in this case, df.plot.hist, and I say, give me Y is the cosine, in this case, and give me density is true, it'll give me a density.

326
00:48:24.700 --> 00:48:32.170
Faculty (Olympus): Okay, so the nice thing is, if you want a quick plot, right, and you don't want to write 3-4 lines of Matplotlib code.

327
00:48:32.220 --> 00:48:45.910
Faculty (Olympus): You want a quick plot, maybe you're not going to be able to customize it too much, but I think there are plenty of options here, so if you look at the documentation, it will tell you, you know, all kinds of keyword arguments. These keyword arguments are actually documented in dataframe.plot.

328
00:48:45.990 --> 00:48:48.859
Faculty (Olympus): Right? And they are passed along.

329
00:48:49.380 --> 00:48:57.179
Faculty (Olympus): Okay. So you can read up the dataframe.plots keyword arguments to learn more about this.

330
00:48:59.040 --> 00:49:06.510
Faculty (Olympus): So, yeah, I didn't want to spend too much time on this, just wanted to show you very quickly that Pandas can also do some clocking. Abhineet, do you still have a question, orâ€¦

331
00:49:06.940 --> 00:49:07.870
Faculty (Olympus): Can I lower you?

332
00:49:07.870 --> 00:49:08.779
Abhineet Bansal: It's answered.

333
00:49:08.780 --> 00:49:09.710
Faculty (Olympus): Okay, great.

334
00:49:10.170 --> 00:49:22.210
Faculty (Olympus): All right, so now we come to perhaps the most important topic, well, maybe not the most, the most useful, because this is really where, you know, you can do data science by yanking existing data sets that you may already have, right?

335
00:49:22.690 --> 00:49:29.189
Faculty (Olympus): Now, Pandas can read a whole host of different file formats. I will only show you CSV in this case.

336
00:49:31.200 --> 00:49:34.080
Faculty (Olympus): But it has a lot of this functionality. You can read.

337
00:49:34.400 --> 00:49:46.000
Faculty (Olympus): variety of different file formats. Some of these, for example, if you want to read Excel, you may readâ€¦ you may need a plugin. Okay, you may need to install an additional package, and usually Pandas will tell you this, or you can

338
00:49:46.020 --> 00:49:56.150
Faculty (Olympus): Of course, Google it up and find top. But built-in will alwaysâ€¦ CSV will always be available, so CSV is available. We'll play with CSV for now, okay?

339
00:49:56.310 --> 00:50:04.629
Faculty (Olympus): So the first thing is our original data frame, right? You can save it to a CSV file. I'm going to just run this. If I run thisâ€¦

340
00:50:04.710 --> 00:50:18.409
Faculty (Olympus): What this will do is it'll dump a file called sinecos.csv, and it will not write the index. And the reason I'm not writing the index is, in this case, the index is one trivial index. It is just 0 to 99, or something like that.

341
00:50:18.640 --> 00:50:35.829
Faculty (Olympus): Since I don't care about that, when I read the CSV file, the index will anyway be created for it, because it is implicit index. I no need to write this explicito file. So I'm just saying index is false. So if youâ€¦ if you take a look at that sign cost file, you'll find that that first column

342
00:50:36.150 --> 00:50:39.949
Faculty (Olympus): willâ€¦ willâ€¦ will be simply the XYs. It will not be 0 onto the 4.

343
00:50:41.000 --> 00:50:48.389
Faculty (Olympus): Now, to read this CSV, so I'm going to do the reverse. I'm creating the dataset here. We look at other, you know, nicer data sets, a little later.

344
00:50:48.770 --> 00:50:54.409
Faculty (Olympus): I just say pd.readCSV and give it the name of the file.

345
00:50:54.820 --> 00:51:03.309
Faculty (Olympus): Now, this read CSV is fairly complicated. It has many, many command linesâ€¦ sorry, many, many keyword elements, okay?

346
00:51:03.640 --> 00:51:14.829
Faculty (Olympus): Most useful, perhaps, will be separator, or the delimiter, which is in between these two fellows. The character used to differentiate between one column and the next column.

347
00:51:14.980 --> 00:51:17.030
Faculty (Olympus): You know, you want toâ€¦

348
00:51:17.080 --> 00:51:36.229
Faculty (Olympus): you want to basically treat something as a header, you can say so. You can give it names, okay? And let's not do all of them, because there are many of them. Look at that, I don't want to go through each of these, right? So, what else can we look at? The other one which is very, very useful is that you can give it a set of D types, that's okay.

349
00:51:36.300 --> 00:51:38.909
Faculty (Olympus): You can give it used calls.

350
00:51:39.350 --> 00:51:44.989
Faculty (Olympus): Which means, use only these columns to read. Don't read, you know, let's say you have a CSV file with 300.

351
00:51:45.170 --> 00:51:50.750
Faculty (Olympus): columns. You wantâ€¦ I only want the first temp. You can basically say, give it, you know, whichever columns that you want.

352
00:51:51.040 --> 00:52:02.309
Faculty (Olympus): Then there is index call, which is, you say, this column is the index, right? So you can do that. You can also supply a mapping, which basically allows you to do conversion, okay?

353
00:52:02.470 --> 00:52:06.830
Faculty (Olympus): So if you encounter something, you want to convert it into something, you can do the same.

354
00:52:08.120 --> 00:52:27.809
Faculty (Olympus): Similarly, you can have aâ€¦ supposing you have strings for true values and false values. Let's say you put capital T and capital F for something, or Y and N, but you want to map them into true and false values. You can actually supply them as true values and give it a list of characters that you want, or strings that you would like to treat as true, okay?

355
00:52:28.060 --> 00:52:40.689
Faculty (Olympus): But perhaps the most important will be NA values. So, if there's missing values, very often, different CSV files will have different standards as to how to import the NA missing value. Some will be NA, some will be null.

356
00:52:40.780 --> 00:52:51.360
Faculty (Olympus): Right? Some will be NA, and God knows, right? So in each of these cases, pandas may not know and may not do the right thing. So you can explicitly specify, you know, a list of values.

357
00:52:51.520 --> 00:52:55.569
Faculty (Olympus): That it should treat us, missing values.

358
00:52:56.490 --> 00:53:02.399
Faculty (Olympus): So yeah, there are several other features that you can pass dates, you can do compression.

359
00:53:02.720 --> 00:53:04.749
Faculty (Olympus): You know, you can treatâ€¦

360
00:53:06.010 --> 00:53:17.390
Faculty (Olympus): So various things, right? So again, if you really want to look at this, you can look at the documentation. It's extensive, and I think at the end you may see some little examples. Like, this example is trivial, right? Butâ€¦

361
00:53:17.500 --> 00:53:22.260
Faculty (Olympus): There's a lot of information on this, right? So I'm not going to show youâ€¦

362
00:53:22.750 --> 00:53:37.839
Faculty (Olympus): All of those things, but just keep in mind that you can immediately read this, so I'll run this, and we'll see what it does. It gives me back that original thing that I got. Nothing fancy here, okay? You get fancier when you have more interesting data sets, not our toy dataset.

363
00:53:38.500 --> 00:53:57.589
Faculty (Olympus): Now, there are many other things in input-output, so this whole section is about input-output. CSV is one particular thing, but there are other things that you can do with Pandas that many people kind of don't know, and it turns out to be very useful in different contexts. One of it is, if I have a data frame, and you're writing, say, a paper in LaTeX or something, or Markdown, for example, you want to generate

364
00:53:57.590 --> 00:53:59.739
Faculty (Olympus): You know, the appropriate

365
00:53:59.930 --> 00:54:15.589
Faculty (Olympus): you know, table in LaTeX format, or markdown format, or HTML format, you can simply use the 2 underscore LaTeX. So if I were to run this, it'll give me the actual LaTeX code. You can cut-paste this and put it in your paper. Or you can put this in a, you know, markdown cell here.

366
00:54:15.800 --> 00:54:19.279
Faculty (Olympus): I think this should work. Try this.

367
00:54:26.980 --> 00:54:28.400
Faculty (Olympus): Oh, son.

368
00:54:29.010 --> 00:54:29.690
Faculty (Olympus): Sweet.

369
00:54:35.340 --> 00:54:39.990
Faculty (Olympus): I don't know if this will work, No, didn't work.

370
00:54:42.070 --> 00:54:46.189
Faculty (Olympus): I think there's a specific markup that I should use for LaTeX.

371
00:54:47.820 --> 00:54:48.800
Faculty (Olympus): Forget it.

372
00:54:51.850 --> 00:54:55.520
Faculty (Olympus): Sorry about that, but if this was a LaTeX file, this would work.

373
00:54:56.350 --> 00:54:58.219
Faculty (Olympus): It's not math, mockups.

374
00:54:59.930 --> 00:55:00.810
Faculty (Olympus): Anything.

375
00:55:01.730 --> 00:55:08.490
Faculty (Olympus): The other thing that's very useful is, not this one, HTML. So if you want to just spit out HTML, you can do HTML.

376
00:55:11.340 --> 00:55:20.709
Faculty (Olympus): Right? So, normally, when I wouldâ€¦ when I do just this DF.head, notice that it does this, right? So if you want to render out this HTML to see what it looks like.

377
00:55:20.710 --> 00:55:31.679
Faculty (Olympus): IPython gives you this thing from IPython.display import.html, and if I were to do this, this will actually show me the same thing. So under the covers, whenever I did df.head and whatever.

378
00:55:31.710 --> 00:55:47.080
Faculty (Olympus): it's actually doing this for me. It's basically showing me the HTML version on your browser. So by default, it's doing this, but if you wanted, for whatever reason, to dump this to an HTML file to put on a website or whatever else, or you want to cut-paste it into some HTML, you can use this.

379
00:55:48.420 --> 00:55:55.049
Faculty (Olympus): All right, so there are many such things in, you know, data frames. So DF.2, if you look at it.

380
00:55:55.530 --> 00:56:02.640
Faculty (Olympus): to clipboard, to CSV, to dictionary, Excel, Feather, GBQ, HDF, HTML, JSsembly, Tech, Markdown, NumPy, yeah.

381
00:56:02.790 --> 00:56:08.670
Faculty (Olympus): Some of these you will not even know what they are, right? So there are a whole bunch of these options, which are very useful.

382
00:56:09.960 --> 00:56:16.429
Faculty (Olympus): Now, one useful thing that is available is selecting from a clipboard.

383
00:56:17.340 --> 00:56:21.640
Faculty (Olympus): Noâ€¦ It's like this.

384
00:56:22.790 --> 00:56:24.670
Faculty (Olympus): I'm going to selectâ€¦

385
00:56:27.800 --> 00:56:30.349
Faculty (Olympus): I can say index is equal to false.

386
00:56:34.950 --> 00:56:36.560
Faculty (Olympus): It is, and then I'll justâ€¦

387
00:56:37.230 --> 00:56:43.609
Faculty (Olympus): copy, I'm just doing CTRL-C, copying the clipboard, and now if I were to do this, I get it back.

388
00:56:44.880 --> 00:56:55.649
Faculty (Olympus): I've not cheated here. This is DF2, I'm reading from control. So this can sometimes be extremely useful. So if you have some easy enough to parse,

389
00:56:57.760 --> 00:57:07.260
Faculty (Olympus): table that you see somewhere, say on Wikipedia or something, you can just select it, and say, read report, and convert into a data frame. Now, this sometimes may not work 100%,

390
00:57:07.480 --> 00:57:11.240
Faculty (Olympus): And then, you know, you have to fine-tune it, but it's a useful feature.

391
00:57:11.390 --> 00:57:13.980
Faculty (Olympus): In fact, they'll use it very soon, doing some stuff.

392
00:57:14.530 --> 00:57:23.220
Faculty (Olympus): The other thing that you can do with ReadCSV is it's not just files that you have, right? So here is a file that I had uploaded on Drive a long time ago.

393
00:57:23.440 --> 00:57:38.169
Faculty (Olympus): And I hope this still works. So what this is going to do is gonna hit this. Of course, I've made thisâ€¦ I've shared this on Google with permission so that anybody can read it and stuff like that, so you need to know the URL. And here, this file actually uses a separator of semicolon.

394
00:57:38.540 --> 00:57:41.900
Faculty (Olympus): So, since I already know that, I can read this.

395
00:57:42.660 --> 00:57:44.759
Faculty (Olympus): And it's gonna take some time.

396
00:57:45.530 --> 00:57:47.189
Faculty (Olympus): And it gives me the data field.

397
00:57:47.320 --> 00:57:49.500
Faculty (Olympus): Yeah, notice that it gives me this dataset.

398
00:57:50.760 --> 00:57:55.059
Faculty (Olympus): Okay, so if I were to describe this dataset, this hasâ€¦

399
00:57:57.340 --> 00:58:00.540
Faculty (Olympus): 14. It's a small file, there's a larger file as well.

400
00:58:00.890 --> 00:58:03.440
Faculty (Olympus): And then tells me all the statistics of all this.

401
00:58:04.040 --> 00:58:04.810
Faculty (Olympus): Okay.

402
00:58:05.240 --> 00:58:16.309
Faculty (Olympus): There are some missing values as well, you can see here. Alright, so basically, now that you can read and output and input CSV files, there's a lot of fun things that you can do.

403
00:58:17.650 --> 00:58:21.010
Faculty (Olympus): Now, the last part of what I'm going to discuss about Pandas

404
00:58:21.120 --> 00:58:24.239
Faculty (Olympus): Is kind of an applied example, okay?

405
00:58:24.450 --> 00:58:29.550
Faculty (Olympus): So what I'm going to do is, I'm going to go and grab Coley's batting sports, okay?

406
00:58:29.970 --> 00:58:33.509
Faculty (Olympus): Okay, so I want to find all the ODI scores for Kira Pudi.

407
00:58:33.720 --> 00:58:36.850
Faculty (Olympus): Okay, and I'm going to show you how, using Pandas.

408
00:58:37.050 --> 00:58:39.700
Faculty (Olympus): We can actually construct this data frame.

409
00:58:39.890 --> 00:58:42.529
Faculty (Olympus): Very quickly, and dump a nice CSV file.

410
00:58:43.240 --> 00:58:45.490
Faculty (Olympus): So, for now, what I'm gonna do isâ€¦

411
00:58:46.340 --> 00:58:50.909
Faculty (Olympus): I'm going to visit this website, Get something along.

412
00:58:52.130 --> 00:58:53.160
Faculty (Olympus): Good girl.

413
00:58:53.980 --> 00:58:58.260
Faculty (Olympus): Cool, this looksâ€¦ Okay.

414
00:59:00.180 --> 00:59:02.889
Faculty (Olympus): Can you see my screen?

415
00:59:03.420 --> 00:59:06.789
Faculty (Olympus): Yeah, let me see if you're still seeing what I'mâ€¦ yeah, yeah, exactly.

416
00:59:06.790 --> 00:59:07.180
Abhishek Agrawal .: Yes.

417
00:59:09.100 --> 00:59:12.510
Faculty (Olympus): Soâ€¦ Wanted over.

418
00:59:15.860 --> 00:59:31.650
Faculty (Olympus): Now, what I can do is, this is all of his scores, I have found this URL, okay? So, you may requireâ€¦ to find bowling, for example, you would have to go looking at the stats and finding this. Now, I know this is my table of interest, okay? So I can cut thisâ€¦

419
00:59:32.670 --> 00:59:34.300
Faculty (Olympus): Start looking at this.

420
00:59:36.480 --> 00:59:39.470
Faculty (Olympus): So I've selected this whole thing here.

421
00:59:41.000 --> 00:59:41.890
Faculty (Olympus): Oops.

422
00:59:42.950 --> 00:59:45.230
Faculty (Olympus): Yeah, obviously I have to select this a bit carefully.

423
00:59:45.820 --> 00:59:50.270
Faculty (Olympus): Pasting it into myâ€¦ Copying it into my clipboard.

424
00:59:50.770 --> 00:59:52.480
Faculty (Olympus): Now let's get back here.

425
00:59:53.170 --> 01:00:01.069
Faculty (Olympus): Now, if I run thisâ€¦ This is the first exercise I did, so let me actually split this cylinder.

426
01:00:02.700 --> 01:00:04.359
Faculty (Olympus): Let me show you the abstract.

427
01:00:08.390 --> 01:00:14.480
Faculty (Olympus): Great. So it has done something, right? As 314 rows and 14 columns.

428
01:00:14.840 --> 01:00:17.220
Faculty (Olympus): It seems to have gotten something, right?

429
01:00:17.480 --> 01:00:19.120
Faculty (Olympus): Suck.

430
01:00:21.660 --> 01:00:29.340
Faculty (Olympus): So, I didn't call them a function, so okay. So, runs, minutes, the same thing it's gotten. There are some columns that were unnamed.

431
01:00:29.550 --> 01:00:31.909
Faculty (Olympus): So it sort of puts a name line, whatever.

432
01:00:32.200 --> 01:00:33.310
Faculty (Olympus): Lots of things explored.

433
01:00:35.090 --> 01:00:45.149
Faculty (Olympus): But so far, so good. It's already done some reasonable job of this, okay? Now, for the data that I shared with you for doing the, you know, Sachin versus Kohli analysis.

434
01:00:45.380 --> 01:00:49.270
Faculty (Olympus): What did I do? I only generated the scores, the runs, okay?

435
01:00:49.490 --> 01:00:52.360
Faculty (Olympus): So now notice, when we look at runs,

436
01:00:56.460 --> 01:01:03.880
Faculty (Olympus): Let me actually split this into another cell, so I don't want to keep reading crib board every time. So if I look at df.runs, notice

437
01:01:04.440 --> 01:01:06.489
Faculty (Olympus): The data type of this is an object.

438
01:01:07.660 --> 01:01:11.140
Faculty (Olympus): Which is a problem. So, for example, if I did DF30 in 4,

439
01:01:11.840 --> 01:01:16.719
Faculty (Olympus): It'll tell me all of these things. So notice, runs has been passed into an object.

440
01:01:16.830 --> 01:01:18.010
Faculty (Olympus): This is a problem.

441
01:01:18.420 --> 01:01:22.090
Faculty (Olympus): Because runs, I would expect, and you would expect as well, to beâ€¦

442
01:01:22.580 --> 01:01:26.290
Faculty (Olympus): Integers, or floating point numbers, okay, in the worst case.

443
01:01:26.680 --> 01:01:31.310
Faculty (Olympus): Similarly, minutes batted for balls faced, I think, BF.

444
01:01:31.630 --> 01:01:37.339
Faculty (Olympus): 4, 6, all of these should actually have been values, except this unnamed fellow, which has

445
01:01:37.940 --> 01:01:51.839
Faculty (Olympus): zero non-null elements, right? Everything else is an object. So something went wrong in our parser. So this is usually the first problem you'll run into when you just get some random file, or you yanked it from somewhere like this, okay? So the first exercise isâ€¦

446
01:01:51.880 --> 01:02:04.110
Faculty (Olympus): In our case, the first simple exercise we want to look at is, how do you generate that one column of files, which I created, you know, save text? I had coli.txt that you have. How did we generate that? So, we first look at

447
01:02:05.760 --> 01:02:17.310
Faculty (Olympus): dayf.runs, it's a string, so I can call str.replace, so when Iâ€¦ so you need to look at the column a little bit before you can actually, you know, understand this a little bit, so let meâ€¦

448
01:02:19.100 --> 01:02:20.740
Faculty (Olympus): Add this.

449
01:02:20.970 --> 01:02:21.860
Faculty (Olympus): Oops.

450
01:02:22.860 --> 01:02:31.500
Faculty (Olympus): Okay, you see, now, it's not obvious here, okay? So maybe let's look at, first, the values?

451
01:02:32.220 --> 01:02:35.120
Faculty (Olympus): Now you start seeing all these issues.

452
01:02:35.330 --> 01:02:43.460
Faculty (Olympus): So, it says 2 star. Obviously, that's not of an integer. It says TDB, T, D, NB, okay?

453
01:02:43.890 --> 01:02:45.480
Faculty (Olympus): Did not bat, basically.

454
01:02:45.640 --> 01:02:46.110
Soumen Deb .: Yeah.

455
01:02:46.110 --> 01:02:47.360
Faculty (Olympus): How can I start.

456
01:02:47.630 --> 01:02:56.630
Faculty (Olympus): Right? So, all of these, obviously, Pandas doesn't know what to do, so we need to do something about it. So, what we do is, first thing we do is,

457
01:02:56.800 --> 01:03:01.780
Faculty (Olympus): df.runs.str.replace star with black, first thing, right?

458
01:03:02.290 --> 01:03:07.350
Faculty (Olympus): Star basically means it was not open, right? There's another column for that, but we can figure those things out later.

459
01:03:08.230 --> 01:03:12.670
Faculty (Olympus): Then, once I got thatâ€¦ series.

460
01:03:12.810 --> 01:03:18.279
Faculty (Olympus): I can now find all of those scores where it does not contain DMV.

461
01:03:18.560 --> 01:03:24.800
Faculty (Olympus): So wherever it did not match, I don't want those scores. So I say R, whatever, this series object.

462
01:03:25.330 --> 01:03:29.019
Faculty (Olympus): And I say, not the string contains DN. Simple.

463
01:03:29.130 --> 01:03:32.180
Faculty (Olympus): Okay? So all simple things that you've already seen so far.

464
01:03:33.130 --> 01:03:40.100
Faculty (Olympus): Once I have this, I have R1, but again, R1's data type, so let me walk you through this. So, R1.

465
01:03:40.810 --> 01:03:58.340
Faculty (Olympus): is going to be, again, type object, okay? So now there are multiple things we can do. For a simple thing that we wanted to do, I wanted to just save a text file. In principle, I don't need to do anything more, but what I've done is I've converted this to R1 to NumPy. So R1, if you look at .2,

466
01:03:58.990 --> 01:04:00.110
Faculty (Olympus): Bompeii?

467
01:04:00.460 --> 01:04:04.220
Faculty (Olympus): This, for whatever reason, this doesn't work for me.

468
01:04:04.490 --> 01:04:13.189
Faculty (Olympus): If I run this, okay, so it tells you this is the signature of R1 to NumPy. We can give it a specific D-type, you can say, you know.

469
01:04:13.440 --> 01:04:15.470
Faculty (Olympus): Various things about it, okay?

470
01:04:16.890 --> 01:04:29.549
Faculty (Olympus): I don't know why my version doesn't do this. Okay, so now I just say, convert this to a NumPy, represent it as a 32-bit integer, and format it using a percentage D, which is make it just a, you know, aâ€¦

471
01:04:29.770 --> 01:04:34.820
Faculty (Olympus): PercentageD is a format specifier for any integer, okay? So if you run this.

472
01:04:35.240 --> 01:04:39.480
Faculty (Olympus): It will save temp only.txt with the data that we generate.

473
01:04:39.810 --> 01:04:51.900
Faculty (Olympus): Is that okay? So this is a very simple task. In fact, it's a boring task because we really would like to have a nice data frame with all of these fellows with the right appropriate frame, okay? So now we'll work on that. That's the next exercise we will look at.

474
01:04:52.160 --> 01:04:55.670
Faculty (Olympus): So again, I read the clipboard, and I get the whole data.

475
01:04:55.780 --> 01:04:58.949
Faculty (Olympus): Okay, Iâ€¦ whoop, this is the right thing.

476
01:05:04.350 --> 01:05:06.410
Faculty (Olympus): Yes, okay, so this has all the data.

477
01:05:06.850 --> 01:05:13.760
Faculty (Olympus): Now, some of you will find that you are unable to use the clipboard because you're using the online interface, JupyterLite.

478
01:05:14.280 --> 01:05:16.799
Faculty (Olympus): Right? So what you can do is you can cut-paste.

479
01:05:17.040 --> 01:05:25.870
Faculty (Olympus): the data, and paste it into a simple text file, and then use pd.readTable and give it that file, okay? So if you're not able to, for whatever reason.

480
01:05:26.000 --> 01:05:33.850
Faculty (Olympus): you know, cut-paste it intoâ€¦ copy-paste it. You can go to a browser, Open the browser window.

481
01:05:34.160 --> 01:05:52.179
Faculty (Olympus): So, the reason why this doesn't work is on Jupyter Lite, if you paste, sometimes it won't do the right thing, okay? It won't readâ€¦ sorry. JupyterLite is running on your browser, so pandas.readClipboard will not be able to read your clipboard. That's a security violation, right? If a website is able to read your clipboard, you're in trouble.

482
01:05:53.240 --> 01:06:01.980
Faculty (Olympus): So, the browser, because of its sandboxing, will not be able to read your clipboard, okay? So, the way around this is, you simply cut-paste

483
01:06:02.400 --> 01:06:07.440
Faculty (Olympus): Save it to a file on your local machine, and then use pd.readTable, okay?

484
01:06:08.080 --> 01:06:08.960
Faculty (Olympus): Other.

485
01:06:09.440 --> 01:06:11.390
Faculty (Olympus): Now, the first thing we want to do isâ€¦

486
01:06:11.570 --> 01:06:25.190
Faculty (Olympus): We have these columns, so let's look at the columns. If there is any white space and stuff like that, we want to remove it. In this case, there is nothing, so we are okay. But if you wanted to, you can do something like this. You can say data.columns.

487
01:06:25.190 --> 01:06:37.920
Faculty (Olympus): is data.columns.str.strip. If you remember what strip does, it removes leading and trailing space, okay? So this will just change the names of the columns and remove any space if there was a space. There is nothing, so it's okay, this is normal.

488
01:06:38.810 --> 01:06:45.599
Faculty (Olympus): Now, the next thing we want to do isâ€¦ I don't want this unnamedâ€¦ unnamed 13, they're not of any use to me, yeah?

489
01:06:45.790 --> 01:06:57.019
Faculty (Olympus): So, we remove all of those columns that are completely empty, or were artifacts of the import process, okay? That's also theâ€¦ we want to do a couple of these things. So, I'll first find all the unnamed columns. To do that.

490
01:06:57.360 --> 01:07:08.590
Faculty (Olympus): I'm doing a list comprehension here. This is the same as doing this code here. So, one line versus one, two, three, four lines. So I'll maybe show you this, and then you can

491
01:07:08.840 --> 01:07:27.360
Faculty (Olympus): understand this line of code by yourself, at your own time. So we say unnamed calls is empty. For column in data.columns, you can iterate over index objects. If unnamed in column, because every column that you're going to get those values are all strings, you can just check if unnamed in column. Unnamed calls.append.

492
01:07:29.160 --> 01:07:32.919
Faculty (Olympus): Alright, so if I run this, I will get all of the unnamed columns.

493
01:07:33.810 --> 01:07:38.290
Faculty (Olympus): Now I can tellâ€¦ I can say, data, drop these columns.

494
01:07:38.480 --> 01:07:47.069
Faculty (Olympus): So this is, again, oops, something that's very useful. Want to drop some columns, you just say data.drop and give it the name of the columns, it'll drop those and spit back up.

495
01:07:47.280 --> 01:07:52.179
Faculty (Olympus): data frame. So data is equal to data.drop. So that old data is gone.

496
01:07:52.550 --> 01:08:07.439
Faculty (Olympus): If you don't like that, you can make this data one or whatever else a 2. So I'm going to run this. Please note that these four lines of code are exactly the same as what this is doing. So this is basically, it's called a list comprehension, and we say for column in data.columns.

497
01:08:07.650 --> 01:08:11.870
Faculty (Olympus): If unnamed in column, Then put that column into this list.

498
01:08:12.210 --> 01:08:19.120
Faculty (Olympus): Okay, and this doesn't have toâ€¦ can be any expression here. It can be column plus column dot upper, right? So whatever you want to do.

499
01:08:20.380 --> 01:08:23.940
Faculty (Olympus): Any expression is okay, and you'll get the list of unknown problems.

500
01:08:24.930 --> 01:08:27.389
Faculty (Olympus): Maybe I will split this into two.

501
01:08:27.899 --> 01:08:30.420
Faculty (Olympus): And show you the unnamed gods.

502
01:08:34.569 --> 01:08:37.950
Faculty (Olympus): So, unnamed 9 and unnamed 30. So, this will basically remove this.

503
01:08:38.210 --> 01:08:41.239
Faculty (Olympus): Alright, so, so far, this is an easy, easy step.

504
01:08:42.260 --> 01:08:44.520
Faculty (Olympus): The next one is a little more complicated.

505
01:08:44.850 --> 01:08:50.760
Faculty (Olympus): Now, we need to build on what we did for our coli.txt file, right? So, what we want to do now isâ€¦

506
01:09:00.350 --> 01:09:18.200
Faculty (Olympus): So what we do is, we remove the star, but when we do this replace, you know, there is an option to treat this as a regular expression, okay? So you have to be careful thatâ€¦ because star is a special character that's used in regular expressions, so we're explicitly saying, do not use a regular expression.

507
01:09:18.950 --> 01:09:36.569
Faculty (Olympus): Okay, do not treat this as a regular expression. Note that this is unlike normal string methods. So, note that these methods are juiced-up methods that are suitable for Panda's operations. Okay, so do not treat this as a regular expression, because star will mean something special. Star means,

508
01:09:36.729 --> 01:09:52.099
Faculty (Olympus): multiple occurrences of the previous character, of the previous seconds. So, be careful about doing things like star. So, it's saying explicitly, do not treat this as a regular expression. Just take the literal character star and replace it with a single, you know, empty string.

509
01:09:52.870 --> 01:09:59.230
Faculty (Olympus): Then, it chains another operation, it says str replace DNB with np.nan, okay?

510
01:09:59.490 --> 01:10:01.320
Faculty (Olympus): So, replace it not bad with any.

511
01:10:05.130 --> 01:10:09.139
Faculty (Olympus): Let me go back to this and see, does it really TMB, or is itâ€¦

512
01:10:13.270 --> 01:10:14.260
Faculty (Olympus): Ding, ding.

513
01:10:16.200 --> 01:10:16.890
Faculty (Olympus): Hmm.

514
01:10:19.690 --> 01:10:21.550
Faculty (Olympus): So, yeah, we're goingâ€¦

515
01:10:23.020 --> 01:10:23.980
Roshan Mathane .: It is DC.

516
01:10:23.980 --> 01:10:25.780
Soumen Deb .: Team did not a bad time.

517
01:10:25.780 --> 01:10:27.160
Faculty (Olympus): Yeah, so it's bull.

518
01:10:27.480 --> 01:10:33.149
Faculty (Olympus): Right? So we may need to do both, but here, what we're going to do, I'm going to show you this. Let's see if this works. Let's try this.

519
01:10:33.380 --> 01:10:45.379
Faculty (Olympus): So, let's just keep this for now. Don't worry about this so much. So, I'm now replacing DND with NAM, okay? And then what I'm going to do is I'm going to say pandas.2numeric.

520
01:10:46.110 --> 01:10:49.170
Faculty (Olympus): data runs, take the series that you're gonna get.

521
01:10:49.390 --> 01:11:07.030
Faculty (Olympus): Remember, I've replaced this data of runs with this, right? So it's already changed. I've already removed all the stars, I have replaced all D&B with NANs, right? I've done all of that stuff. Now, what I'm going to do is I'm going to say, coerce this fellow into a numeric data. So you're basically telling Pandas, whatever is there in this, you try your best.

522
01:11:07.610 --> 01:11:08.500
Faculty (Olympus): Fucked!

523
01:11:08.730 --> 01:11:28.479
Faculty (Olympus): There are multiple ways to handle the errors. So if you look at this, it'll tell you errors, there are multiple options. If you say raise, it'll raise an exception. You'll say, oh, I got this error problem, okay? If you say course, then invalid parsing will be set as NAND, which is actually very useful for us. So the TMD will actually be handled. In fact, even this DMB would have been handled.

524
01:11:28.630 --> 01:11:34.519
Faculty (Olympus): However, I cannot do that for star, right? Because star is actually a valid score, I don't want to replace that with NAN.

525
01:11:34.640 --> 01:11:38.180
Faculty (Olympus): Only TMB, DMB, and those kind of things I want to wipe down, okay?

526
01:11:39.210 --> 01:11:44.220
Faculty (Olympus): Third option is, if you put ignore, the invalid parsing will return input. I don't want that, because

527
01:11:44.330 --> 01:11:52.009
Faculty (Olympus): it'll give you a string, and then you'll again be back to square one. Okay, so we don't want to do that. So here I just say I coerce it, I'll run this.

528
01:11:53.110 --> 01:11:54.979
Faculty (Olympus): What did I do now?

529
01:12:06.070 --> 01:12:09.220
Faculty (Olympus): Okay, okay, okay.

530
01:12:09.390 --> 01:12:16.659
Faculty (Olympus): Soâ€¦ Okay, we can't replace it with NAM, so let me just replace it with empty.

531
01:12:17.380 --> 01:12:18.600
Faculty (Olympus): Okay, there, look.

532
01:12:18.770 --> 01:12:19.889
Faculty (Olympus): Okay, great.

533
01:12:20.770 --> 01:12:23.030
Faculty (Olympus): Now, notice, run this float64.

534
01:12:23.930 --> 01:12:28.469
Faculty (Olympus): Okay, so now let's look at the runs once to make sure that this isâ€¦

535
01:12:28.710 --> 01:12:44.449
Faculty (Olympus): Okayâ€¦ and please note, you are going to have to do this sort of work with aâ€¦ first time it's a raw data frame, you have to do this kind of munging around with the data. Otherwise, you'll parse it into something which is a mess. So, it runsâ€¦

536
01:12:45.590 --> 01:12:50.399
Faculty (Olympus): So, if I want toâ€¦ You know, so all of these are float 64 data.

537
01:12:50.960 --> 01:12:52.840
Faculty (Olympus): So, all is good so far.

538
01:12:53.080 --> 01:12:53.740
Faculty (Olympus): Nope.

539
01:12:57.490 --> 01:13:06.120
Faculty (Olympus): All right, and this will have some NANs, because he did not bat at some time, so let me look at the first 20 values, and let's see if that is true. Yeah, so notice that

540
01:13:06.310 --> 01:13:10.730
Faculty (Olympus): All the ones where we couldn't parse, you know, are treated as NANs.

541
01:13:12.570 --> 01:13:13.590
Faculty (Olympus): Siddharth?

542
01:13:14.340 --> 01:13:20.739
Siddharth Digambar Kulkarni .: So the TDNBs got converted to NAN, and the DNBs got converted to space, right?

543
01:13:21.770 --> 01:13:22.320
Faculty (Olympus): No.

544
01:13:22.700 --> 01:13:24.820
Faculty (Olympus): Well, that will also be parsed as an amp.

545
01:13:25.490 --> 01:13:27.329
Faculty (Olympus): In principle, I could remove this.

546
01:13:28.330 --> 01:13:28.970
Siddharth Digambar Kulkarni .: Okay.

547
01:13:29.190 --> 01:13:31.569
Faculty (Olympus): Check it. If it worst case, it doesn't work.

548
01:13:32.110 --> 01:13:34.429
Faculty (Olympus): Parse it, or we can maybe even replace a book.

549
01:13:34.740 --> 01:13:35.910
Faculty (Olympus): In the athletics.

550
01:13:37.340 --> 01:13:39.610
Faculty (Olympus): It doesn't matter, because anyway, the errorâ€¦

551
01:13:39.620 --> 01:13:43.110
Siddharth Digambar Kulkarni .: Why not NP.NET? Why not NP.net?

552
01:13:43.110 --> 01:13:47.129
Faculty (Olympus): you try it. You got an exception basically saying you must replace it with

553
01:13:47.260 --> 01:13:52.769
Faculty (Olympus): some other type, right? You cannot replace it, you must replace it back with a string, okay? Not with aâ€¦

554
01:13:53.080 --> 01:13:54.280
Faculty (Olympus): Nonstick.

555
01:13:56.140 --> 01:13:56.940
Faculty (Olympus): Okay?

556
01:13:57.040 --> 01:14:06.019
Faculty (Olympus): So now, next thing is, we need to convert the dates, right? So if you notice that this had a dates column, the dates.

557
01:14:06.950 --> 01:14:12.970
Faculty (Olympus): Did I look at info in this case? Yeah, so notice we have,

558
01:14:16.320 --> 01:14:19.820
Faculty (Olympus): Startâ€¦ start date ascending.

559
01:14:20.020 --> 01:14:20.900
Faculty (Olympus): Right?

560
01:14:21.120 --> 01:14:26.679
Faculty (Olympus): start date ascending, so God knows what that start date ascending is, so I have no, you know,

561
01:14:27.450 --> 01:14:43.060
Faculty (Olympus): So the start date ascending is actually the date of that match, okay? Soâ€¦ or start date, right? Assuming that sometimes the match ended because of rain and was replayed on the next day, God knows what, but it's start date in this case. So what I'm doing is I'm creating a new column called date.

562
01:14:43.090 --> 01:14:59.260
Faculty (Olympus): And then I'm saying pandas to datetime. Again, this is useful, just like we did to numeric, to date time. So what this will do is, datetime is a built-in Python, part of the standard library, which allows you to represent a date and a time together as one object.

563
01:14:59.470 --> 01:15:02.150
Faculty (Olympus): So what this will do is it'll parse

564
01:15:02.740 --> 01:15:06.619
Faculty (Olympus): This column of strings. Again, do a coercion.

565
01:15:06.930 --> 01:15:10.839
Faculty (Olympus): Wherever it fails, and it'll represent it as a data.

566
01:15:11.800 --> 01:15:18.259
Faculty (Olympus): And here, what I do is, I get the date, and then I also yank out the year by saying data.

567
01:15:18.440 --> 01:15:34.500
Faculty (Olympus): dt.year. So this is notice, just like .str.dt will give you the datetime object, on which there are different methods, onâ€¦ sorry, on different attributes. So you can get year, you can get month, you can get day, right? Those kind of things are available. So again, this is another kind of an accessor. So the reason I've

568
01:15:34.570 --> 01:15:39.580
Faculty (Olympus): Sort of walk through this demo, was to show you many features, sort of, as we go down.

569
01:15:40.520 --> 01:15:47.310
Faculty (Olympus): And then, I don't want this original fellow, so I'm wiping out the start dataset. That fellow is gone, okay?

570
01:15:47.840 --> 01:15:54.970
Faculty (Olympus): Then, in the opposition, if you look at the data, you'll actually find it says V Best Indies.

571
01:15:55.130 --> 01:16:07.139
Faculty (Olympus): V bangladesh, okay? So that V space prefix will be removed. So again, we replace data opposition is dataopposition.str.replaceV with empty string against this fonts. So run that.

572
01:16:07.420 --> 01:16:08.570
Faculty (Olympus): everything, right?

573
01:16:08.820 --> 01:16:21.979
Faculty (Olympus): Okay? Then we want to do a little more. We want to clean up the text columns and create a binary not-out column, and we also want to clean up the dismissal, right? So we look at the dismissal, whenever,

574
01:16:22.800 --> 01:16:26.860
Faculty (Olympus): We fillâ€¦ Any NANs with DNB?

575
01:16:27.100 --> 01:16:32.730
Faculty (Olympus): And thenâ€¦ We cast this as a string, and then we do string.strip.

576
01:16:33.290 --> 01:16:37.310
Faculty (Olympus): fill that again with TMB, okay? And again.

577
01:16:37.710 --> 01:16:40.150
Faculty (Olympus): It cleans up this dismissal column.

578
01:16:40.840 --> 01:16:55.260
Faculty (Olympus): And then, again, same thing. For ground, it says data.ground, strcript. So again, I would urge you, this notebook is with you, explore all of these different methods. This will sort of teach you different methods that are available for Panda's data frames, as well as for series objects.

579
01:16:55.800 --> 01:16:58.470
Faculty (Olympus): Remember, data of dismissal gives you a series object.

580
01:17:02.060 --> 01:17:13.740
Faculty (Olympus): Same way for ground, we are replaced, we're stripping the ground because they may be leading and drinking spaces. Same thing for opposition. And then we are constructing this not-out column by saying data dismissal.eq.

581
01:17:14.120 --> 01:17:16.760
Faculty (Olympus): Okay, not out. If it is equal to not out.

582
01:17:17.670 --> 01:17:27.079
Faculty (Olympus): You check whether it is equal to this, and then replace this as some type int. Instead of giving a Boolean value, it'll be either 0 or 1. So it's a binary representation.

583
01:17:28.040 --> 01:17:42.729
Faculty (Olympus): Then there are several other columns, like BF, ball space, 4, 6s, position, innings, position is when he came out the bat, strike rate, minutes, and so on and so forth. So now, for each of these columns, we just write a for loop, and say forâ€¦

584
01:17:42.730 --> 01:17:43.320
Advait Ketkar .: Oh my god.

585
01:17:43.320 --> 01:17:52.829
Faculty (Olympus): comes inâ€¦ Columns in, columns to numeric, redo data of column, and then again, coerce this.

586
01:17:54.610 --> 01:17:55.830
Faculty (Olympus): Now, please note.

587
01:17:56.180 --> 01:18:13.829
Faculty (Olympus): If you have valuable data, when you do such processing, please test and make sure that everything is as per requirements. This is just some toy data as far as you and I are concerned for this class, but if it's valuable data, when you coerce things and things disappear, if the parsing fails, you may actually lose valuable data.

588
01:18:14.110 --> 01:18:23.939
Faculty (Olympus): So always, once you do all of this processing, check and make sure that it is consistent, and probably write test cases as well for this, if you're going to do this in production.

589
01:18:25.410 --> 01:18:30.549
Faculty (Olympus): Alright, so then we want a final column order. Okay, so notice.

590
01:18:30.700 --> 01:18:32.030
Faculty (Olympus): What we're doing isâ€¦

591
01:18:32.250 --> 01:18:48.060
Faculty (Olympus): Somebody asked me this question last time. You had, some sine, cosine, this, that, I want to change around the order. This is how you do the changing of order. Okay, so you say data is equal toâ€¦ you simply re-index into this fellow using whatever column order you want.

592
01:18:48.410 --> 01:18:53.280
Faculty (Olympus): So if I want this as my order, date, year, ground, opposition, innings, position, blah blah blah blah.

593
01:18:53.850 --> 01:18:57.350
Faculty (Olympus): It's just reordering it, and then we're looking at data.inform.

594
01:18:58.200 --> 01:18:59.660
Faculty (Olympus): plug shift minus.

595
01:18:59.740 --> 01:19:11.769
Faculty (Olympus): And I'm gonna run this, and I hope and pray everything works. Aha! Now it's great! So now date is a date time, year is an integer, ground is an object, which is a string, opposition isâ€¦

596
01:19:11.820 --> 01:19:31.749
Faculty (Olympus): an object, everything else is nice float64 quantities, dismissal, because this is multiple possibility, right? Again, it's an object, not out as an integer, okay? So all of these have nicely been parsed, and now we have a useful data frame to play with, okay? And now that we do have this, I don't want to repeat this stupid code every time.

597
01:19:31.800 --> 01:19:38.450
Faculty (Olympus): I can now save this into coliecleanedBatting.csv. I do not want the index, okay?

598
01:19:39.470 --> 01:19:40.909
Faculty (Olympus): And now I can say it off.

599
01:19:41.220 --> 01:19:48.080
Faculty (Olympus): Okay, and in fact, this is the file that is available for you. This is how it was generated for different batchmen that is already available in the data file.

600
01:19:48.560 --> 01:19:51.479
Faculty (Olympus): Is this clear? So, we spent a lot of time on this.

601
01:19:51.580 --> 01:20:01.560
Faculty (Olympus): Now, what I'm going to do is just show you some cool features, okay? That we can do some nice analysis using Pandas, and again, this is very useful.

602
01:20:02.100 --> 01:20:13.129
Faculty (Olympus): This kind of processing. So please take your time, go through this notebook carefully, and try it, experiment, try it with your own dataset, and play with this to get some feel for this.

603
01:20:13.490 --> 01:20:19.920
Faculty (Olympus): So now that we have the data frame, it's really nice, because now we can do some fun things with the Panda Spot.

604
01:20:20.230 --> 01:20:25.629
Faculty (Olympus): So the first is, I want to see how many, times did he cross 100.

605
01:20:26.330 --> 01:20:29.329
Faculty (Olympus): So I'm kind of showing you things that I found useful.

606
01:20:29.880 --> 01:20:45.709
Faculty (Olympus): And some of these, again, I have not shown you before. So, whenever you have something which is, you have a series object, so for example, let us say we have different categories of students here, okay? Of learners in this course.

607
01:20:45.780 --> 01:20:56.970
Faculty (Olympus): Some of you may be, in IT industry, some of you may be in the finance industry, some of you may be academics in engineering, or whatever. So let's say we have categories for each. I have

608
01:20:56.970 --> 01:21:09.279
Faculty (Olympus): I have a column which says engineering, finance, you know, Computer Science, IT, whatever it is, okay? Now, I would like to get a sense of how many fellows are, or how many people, sorry, areâ€¦

609
01:21:09.720 --> 01:21:15.779
Faculty (Olympus): In this category of that. In all of these cases, if you just do the value counts, it will do a

610
01:21:15.800 --> 01:21:33.769
Faculty (Olympus): it will look at the values, kind of like a histogram, right, for these kind of quantities. So here, what I'm saying is, give me all the data runs greater than 100, so there's only two possibilities, right? It's either greater than 100 or not 2, so there's only two things that are going to come out. So this will actually tell me false is 263, which means

611
01:21:34.500 --> 01:21:38.430
Faculty (Olympus): Most of them, 263, Less than 100.

612
01:21:38.870 --> 01:21:46.999
Faculty (Olympus): Less than equal to 100, andâ€¦ so maybe I should do this. Maybe we got out sometimes. Yeah, okay, at 100.

613
01:21:47.350 --> 01:21:58.869
Faculty (Olympus): Okay, so less than 100 will be 260, and he has 54 centuries. Is that clear? Similarly, data.not out value counts

614
01:21:59.220 --> 01:22:00.340
Faculty (Olympus): he wasâ€¦

615
01:22:01.890 --> 01:22:06.960
Faculty (Olympus): Okay, so of course, you can do np.sumdata.notorg, that will also give you the same answer for TISA.

616
01:22:07.370 --> 01:22:08.180
Faculty (Olympus): It's okay.

617
01:22:10.260 --> 01:22:22.719
Faculty (Olympus): Data.opposition value counts is very nice, because now I can tell you, in one shot, how many matches he's played against Pakistan, so on and so forth, right? So you can see that most of his matches are against Sri Lanka, amazingly so.

618
01:22:22.770 --> 01:22:33.670
Faculty (Olympus): many against Australia, 53, right? You can say this, and it's played against UAE, Nepal, andâ€¦ Okay, so value cons, I find, is very useful at a glance to get, like, a summary of, you know.

619
01:22:33.790 --> 01:22:35.310
Faculty (Olympus): Something like this.

620
01:22:35.690 --> 01:22:40.289
Faculty (Olympus): Same way, dismissal. So you want to quickly say, okay, what is the most frequent way that he gets out?

621
01:22:40.420 --> 01:22:41.260
Faculty (Olympus): caught.

622
01:22:41.450 --> 01:22:46.819
Faculty (Olympus): It's 180 times this. So a lot of nice statistical information you can just get by

623
01:22:47.190 --> 01:22:51.229
Faculty (Olympus): You have a data frame, now you can do all of these important things very nicely.

624
01:22:51.720 --> 01:22:55.060
Faculty (Olympus): But then, you can do some very interesting things, like the following.

625
01:22:55.640 --> 01:23:03.650
Faculty (Olympus): So, there's an operation in Pandas called GroupByte. What this does is, it will say, group that data frame.

626
01:23:03.810 --> 01:23:19.540
Faculty (Olympus): by the opposition, which means it'll look at all of the oppositions and group all of them by this. So if I just did group by, you'll get an object. It's called a group by object, and that fellow will allow you to do all of these things. So you say group by objects, fetch the runs column.

627
01:23:20.530 --> 01:23:21.919
Faculty (Olympus): And then give me a sum.

628
01:23:22.140 --> 01:23:26.260
Faculty (Olympus): So if I did this, it'll tell meâ€¦ for opposition.

629
01:23:26.710 --> 01:23:30.219
Faculty (Olympus): What is the total number of runs against each country?

630
01:23:30.490 --> 01:23:36.500
Faculty (Olympus): Okay, so it looks like Sri Lanka is the highest number of runs he scored against, is 265242.

631
01:23:36.920 --> 01:23:45.960
Faculty (Olympus): Now, of course, this may not be very useful, you may want to do mean, so you do, you know, mean. Same thing. Group by opposition runs off mean.

632
01:23:47.110 --> 01:24:03.140
Faculty (Olympus): Nepal, it looks like he didn't actually play, soâ€¦ man. Again, now, same way, data.strike rate.mean, now you can get his total strike rate, and then you can get the average, no, sorry, strike rate across different teams, and then tell you which team he's, you know, highest scorer.

633
01:24:03.270 --> 01:24:08.609
Faculty (Olympus): strike rate is highest. So, once again, you can see just one line of code,

634
01:24:08.830 --> 01:24:15.070
Faculty (Olympus): You can sort of get a lot of insightful statistical information about your, whatever, cricket scores in this case.

635
01:24:15.290 --> 01:24:29.890
Faculty (Olympus): All right, so I hope this is, so far useful. I have given you an exercise here, but that's okay. Before that, I'll just wrap this up. One very small aside. Supposing I give you a data set.

636
01:24:30.070 --> 01:24:43.200
Faculty (Olympus): And I want to do probabilistic programming. So the same thing. Remember, we played this game with Kohli and Sachin, and we said, look, he's gonna play a 3-match series. I want to generate, you know, a set of numbers. You can do the same thing with a data frame also.

637
01:24:43.340 --> 01:24:51.829
Faculty (Olympus): So, data.sampleâ€¦ Okay, with replacement, if I did 5, it'll basically give me a data frame with 5 scores.

638
01:24:52.840 --> 01:24:54.399
Faculty (Olympus): generated. So if Iâ€¦

639
01:24:56.820 --> 01:25:13.609
Faculty (Olympus): All right? So if you want to do things like this, so you want to do statistical, you know, bootstrapping kind of probabilistic programming with a data frame, you can. A data frame will give you methods so that you can generate these, you can do bootstrapping, find averages, ask him to play 3 more matches.

640
01:25:13.610 --> 01:25:24.259
Faculty (Olympus): Now, of course, the date is no meaning in this case, because obviously that match is finished, right? But what is more useful is if you're looking at things like distribution of the runs.

641
01:25:24.350 --> 01:25:31.870
Faculty (Olympus): You know, because you're doing sampling with replacement and using a random number generator to do it, it will be representative of the original distribution of the data.

642
01:25:33.300 --> 01:25:34.150
Siddharth Digambar Kulkarni .: Replacementâ€¦

643
01:25:34.150 --> 01:25:34.510
Faculty (Olympus): Soyh.

644
01:25:34.510 --> 01:25:39.789
Siddharth Digambar Kulkarni .: The same column can be, can come twice, right? Replacement through meansâ€¦

645
01:25:39.790 --> 01:25:41.180
Faculty (Olympus): Yeah. Yeah.

646
01:25:42.020 --> 01:25:42.640
Faculty (Olympus): Yes.

647
01:25:42.640 --> 01:25:48.279
Siddharth Digambar Kulkarni .: But ideally, if you want all the 5 are different, you should put replace as false, right?

648
01:25:48.890 --> 01:25:49.460
Faculty (Olympus): No.

649
01:25:49.590 --> 01:25:53.540
Faculty (Olympus): Again, go back to what we discussed in the previousâ€¦ when we did probabilistic program.

650
01:25:54.810 --> 01:26:01.129
Faculty (Olympus): If I want to generate 50,000 scores, I cannot do replace is false. I cannot generate 50,000 unique scores.

651
01:26:01.450 --> 01:26:07.849
Faculty (Olympus): Okay, the idea is that the distribution of this is reproduced, and if it gets two values of the same kind, that's okay.

652
01:26:08.220 --> 01:26:09.060
Faculty (Olympus): It's fine.

653
01:26:09.920 --> 01:26:10.780
Faculty (Olympus): Okay.

654
01:26:11.470 --> 01:26:17.450
Faculty (Olympus): Okay, so here's a small exercise, you can do this. It's a small data file that's available here.

655
01:26:17.700 --> 01:26:27.350
Faculty (Olympus): You can rate this, okay? And notice, so this is just, again, maybe I'll show you this. So when I did this, notice it produced a horrible-looking data frame.

656
01:26:28.850 --> 01:26:44.599
Faculty (Olympus): if I did dot data types, it says this is one column with this horrible name and its type of object, okay? This is not what we want, right? So clearly, looks like the separator is semicolon. The default separator Pandas uses is semicolon. So if I did this.

657
01:26:45.080 --> 01:26:50.520
Faculty (Olympus): And now it looks much better, okay? So now, you know,

658
01:26:51.190 --> 01:26:57.589
Faculty (Olympus): When you read the CSV file, the original file actually had some MAs or some missing ones, absent or something.

659
01:26:57.770 --> 01:27:03.709
Faculty (Olympus): So you can then supply NA values, and then make sure that is also it. So please, when you always do these things.

660
01:27:04.020 --> 01:27:11.809
Faculty (Olympus): Always make sure that these data types are as expected, or either look at info, or look at D types, and do it.

661
01:27:12.760 --> 01:27:19.409
Faculty (Olympus): Again, this is all the same, similar things, so it's okay. I don't think this is really an exercise, this is just a small,

662
01:27:20.060 --> 01:27:23.870
Faculty (Olympus): exercise that we're looking at. Now, one of the things that,

663
01:27:25.260 --> 01:27:30.349
Faculty (Olympus): I didn't show you is, when you do this group by operation, right, you can also do plots.

664
01:27:30.800 --> 01:27:37.740
Faculty (Olympus): So, for example, I can say data.groupByOppositionRuns.mean.plot.bar. Okay, so let me just show this.

665
01:27:38.020 --> 01:27:42.419
Faculty (Olympus): So this shows you Afghanistan, Australia, right? One line of code.

666
01:27:42.630 --> 01:27:44.869
Faculty (Olympus): You can do stuff like this.

667
01:27:46.290 --> 01:27:52.360
Faculty (Olympus): Alright, so again, even though I've done quite a bit, I've only scratched the surface, okay?

668
01:27:52.670 --> 01:28:00.109
Faculty (Olympus): You can definitely check out the documentation. Again, this should be HTTPS.

669
01:28:00.540 --> 01:28:09.220
Faculty (Olympus): You can also go to this chapter, really nice chapter, and there are also some nice cookbook, examples that are available.

670
01:28:10.220 --> 01:28:16.340
Faculty (Olympus): That you can check out, okay? So there are lots ofâ€¦ there's a lot of material online available, and I know,

671
01:28:16.360 --> 01:28:33.959
Faculty (Olympus): This hand does itself is, like, a massive amount of information, but I thought, you know, Jake's book is very nice. Data Science Handbook actually walks through a lot of these things that I've covered. So if you want, like, more textbook exposition of this, please check out, that chapter from this book.

672
01:28:34.170 --> 01:28:43.730
Faculty (Olympus): But with that, I will wrap up Pandas. It's an extremely powerful tool. There are many other libraries that sort of behave like Pandas. For example, Polars.

673
01:28:44.390 --> 01:28:47.719
Faculty (Olympus): There's a library written in Rust, it's extremely performant.

674
01:28:47.910 --> 01:28:52.220
Faculty (Olympus): But you know, there are many such tools that you can use.

675
01:28:52.570 --> 01:28:53.930
Faculty (Olympus): We'll perform your analysis.

676
01:28:54.410 --> 01:28:57.270
Faculty (Olympus): So, I will stop the Panda's discussion here.

677
01:28:59.650 --> 01:29:10.029
Faculty (Olympus): I have 10 minutes, so if you don't mind, I will start the next session on regression today, and anywhere in 10 minutes, we'll stop for Q&A, and I will answer the question. Is that alright?

678
01:29:10.230 --> 01:29:11.500
Faculty (Olympus): Is that okay, everyone?

679
01:29:12.340 --> 01:29:13.740
Faculty (Olympus): I don't see anyâ€¦

680
01:29:14.220 --> 01:29:20.320
Faculty (Olympus): urgent questions people are asking here, so I'm hoping that this is okay, so let meâ€¦

681
01:29:23.630 --> 01:29:25.130
Faculty (Olympus): Singhal should be rolling.

682
01:29:42.380 --> 01:29:44.409
Faculty (Olympus): Okay, so 10 minutes.

683
01:29:45.340 --> 01:30:00.830
Faculty (Olympus): We don't know if I should really jump in. Okay, anyway, I'll repeat myself for the next class. So, our next section is going to be on regression, and here I will spend a bit of time on the theory. I don't believe you would have completed or even gotten close to regression so far in your stats course, is that correct?

684
01:30:01.500 --> 01:30:02.030
Swapnil Sankla .: Yeah.

685
01:30:02.910 --> 01:30:03.949
Soumen Deb .: And, you know.

686
01:30:03.970 --> 01:30:17.549
Faculty (Olympus): So it's okay, don't worry, even if you don't fully understand everything that I'm doing here, you will eventually understand when we do statistics. But my goal here is to sort of walk you through the big picture of what regression is about.

687
01:30:18.310 --> 01:30:20.720
Faculty (Olympus): Okay, so there are some definitions.

688
01:30:22.270 --> 01:30:24.530
Faculty (Olympus): So, we'll just look at some theory here.

689
01:30:25.370 --> 01:30:27.890
Faculty (Olympus): A bunch of theory here.

690
01:30:29.410 --> 01:30:31.359
Faculty (Olympus): And maybe I'll try to cover this quickly.

691
01:30:31.790 --> 01:30:36.720
Faculty (Olympus): So, typically, in a regression problem, you have two kinds of quantities.

692
01:30:36.980 --> 01:30:41.180
Faculty (Olympus): You have what are called dependent variable. You have the dependent variable.

693
01:30:41.320 --> 01:30:46.379
Faculty (Olympus): Okay, it's also called a response variable, which means, so if you remember.

694
01:30:46.550 --> 01:30:49.189
Faculty (Olympus): The L versus T squared example, pendulum.

695
01:30:49.600 --> 01:30:55.310
Faculty (Olympus): Okay? You can think of the time period being proportional to length.

696
01:30:56.000 --> 01:30:57.359
Faculty (Olympus): So your length?

697
01:30:57.530 --> 01:30:58.380
Faculty (Olympus): Late?

698
01:30:58.660 --> 01:31:09.490
Faculty (Olympus): will be the independent variable, and your dependent variable will be your time period. Now, in this particular example, it may be flipped around, okay? This really depends on the dataset you're talking about.

699
01:31:09.630 --> 01:31:21.979
Faculty (Olympus): Right? Because if I give you a linear function, I can always rewrite one in terms of the other, right? So this really depends on the specific problem that you have, but you can think of it as, I have some known quantity, for example,

700
01:31:22.140 --> 01:31:26.480
Faculty (Olympus): Let's say I give you a new length of the pendulum, and I want you to predict for me what the time period should be.

701
01:31:27.130 --> 01:31:40.289
Faculty (Olympus): Right, so in this case, which means I know a new length, the question I'm going to ask is, what is the time period given a length? So, which means I know this quantity, so it's an independent variable. The dependent quantity is, when I give you this fellow, this fellow is entirely dependent upon this quantity.

702
01:31:40.590 --> 01:31:54.250
Faculty (Olympus): Okay, so the response variable is the dependent variable, there are a set of independence, okay? And the process of doing regression is to find the relationship based on the data that's given, or the meta that's measured.

703
01:31:58.130 --> 01:32:04.580
Faculty (Olympus): Find the relationship, based on the data between the dependent variable and the independent.

704
01:32:05.000 --> 01:32:06.150
Faculty (Olympus): That's the need.

705
01:32:06.680 --> 01:32:16.009
Faculty (Olympus): So what we will look at today is linear regression, although it's very easy to expand this to polynomial and other kinds of diffusion, right? But the idea is.

706
01:32:16.320 --> 01:32:20.400
Faculty (Olympus): Y here is your dependent variable, or the response variable.

707
01:32:20.550 --> 01:32:26.270
Faculty (Olympus): X1 dot dot dot dot to XR are your independent variables.

708
01:32:26.410 --> 01:32:30.850
Faculty (Olympus): The betas that you have here are your coefficients, okay?

709
01:32:31.510 --> 01:32:34.139
Faculty (Olympus): So, this sort of a linear relationship

710
01:32:34.270 --> 01:32:53.840
Faculty (Olympus): The goal is, we will typically be given the Y values and a set of X dot dot dot XR values. Please remember, this is for one measurement, so this is a multilinear regression, which means I have multiple variables, and Y is linearly proportional to all of these. The goal of regression is to be able to find these beta elements.

711
01:32:53.960 --> 01:32:55.719
Faculty (Olympus): That's the rule of edition.

712
01:32:56.610 --> 01:33:01.400
Faculty (Olympus): So, formally, when you're doing your statistics, what you'll basically say is.

713
01:33:01.660 --> 01:33:08.320
Faculty (Olympus): The real model is basically going to be Y is beta naught plus beta 1x1 dot dot dot, plus some error.

714
01:33:08.660 --> 01:33:17.379
Faculty (Olympus): Right? Because there's always going to be some noise, and whatever be your model, your model is not going to fit everything exactly, okay? It is going to have

715
01:33:17.630 --> 01:33:20.740
Faculty (Olympus): Some degree of noise when it's making a prediction.

716
01:33:21.180 --> 01:33:27.930
Faculty (Olympus): So you account for that by adding this noise, and in your stat scores, you will assume that this

717
01:33:28.070 --> 01:33:34.029
Faculty (Olympus): E is usually normally distributed, okay? But as far as we are concerned, we're going to assume that

718
01:33:34.330 --> 01:33:37.650
Faculty (Olympus): E is a random variable with zero mean.

719
01:33:38.900 --> 01:33:43.690
Faculty (Olympus): If it was not zero mean, please note, if I take the expectation of this whole fellow.

720
01:33:44.090 --> 01:33:48.839
Faculty (Olympus): If it is not zero mean, that constant would be absorbed and beaten up. Am I making sense?

721
01:33:49.430 --> 01:33:54.000
Faculty (Olympus): So you're saying there's some scatter about someâ€¦ model.

722
01:33:54.190 --> 01:33:58.989
Faculty (Olympus): And I'm making it in such a way that this error that you're adding is not a bias, right? It'sâ€¦

723
01:33:59.320 --> 01:34:02.610
Faculty (Olympus): This has zero bytes. The bias is already accommodated by your beta number.

724
01:34:03.610 --> 01:34:05.289
Faculty (Olympus): So now what you're saying is.

725
01:34:05.700 --> 01:34:11.950
Faculty (Olympus): This, what we are trying to solve is basically saying the expected value of Y

726
01:34:12.280 --> 01:34:16.280
Faculty (Olympus): given an X array, array of X values.

727
01:34:16.470 --> 01:34:25.040
Faculty (Olympus): is given by this model, beta naught plus beta 1x1 plus dot r dot plus beta RXI. Remember, because this fellow's mean is 0, the expectation of this fellow is

728
01:34:25.730 --> 01:34:37.560
Faculty (Olympus): All right, so that is the linear model that we are trying to get. And our goal is, we want to find these regression coefficients. So the beta I's are called regression coefficients, and this particular equation is called the linear regression equation.

729
01:34:38.770 --> 01:34:49.019
Faculty (Olympus): So, in linear regression, we have two variants, if r is 1, which means I have just beta naught plus beta on X1. This is the example that we had for our simple print one. It has only two

730
01:34:49.420 --> 01:34:52.119
Faculty (Olympus): constants, C and the slope, right?

731
01:34:52.380 --> 01:34:59.890
Faculty (Olympus): In that case, you getâ€¦ this is called simple linearâ€¦ simple regression equation. If r is greater than 1, it's called multiple regression.

732
01:35:02.210 --> 01:35:06.219
Faculty (Olympus): So now, I'll just take a small detour, you know, 5 minutes, soâ€¦

733
01:35:06.970 --> 01:35:10.369
Faculty (Olympus): So, have you looked at estimators so far in your stats course?

734
01:35:13.780 --> 01:35:15.979
Faculty (Olympus): Have you seen Aseem? Sorry?

735
01:35:16.330 --> 01:35:17.330
Abhineet Bansal: No, no.

736
01:35:17.450 --> 01:35:18.560
Faculty (Olympus): Okay, fine.

737
01:35:18.750 --> 01:35:23.260
Faculty (Olympus): So, an estimator is basically, you can think of it as some formula.

738
01:35:23.680 --> 01:35:31.350
Faculty (Olympus): that is used to estimate some unknown parameters. So, for example, let me say, let's take the weight of all learners in this class, okay?

739
01:35:31.940 --> 01:35:41.849
Faculty (Olympus): If I pick randomly a learner from TPGDP, MLITM, I pick some student, I will get some weight. If I correct all the weights, and then give you a

740
01:35:42.430 --> 01:35:47.509
Faculty (Olympus): density plot, I will get an approximate probability density function.

741
01:35:47.760 --> 01:35:49.650
Faculty (Olympus): Correct? No.

742
01:35:49.870 --> 01:35:53.159
Faculty (Olympus): Let us say I want to find the mean.

743
01:35:53.380 --> 01:35:57.610
Faculty (Olympus): The true mean of the population.

744
01:35:57.820 --> 01:36:00.499
Faculty (Olympus): The true mean of the population. How can I find it?

745
01:36:04.770 --> 01:36:08.900
Faculty (Olympus): So I'll rephrase the question. All the learners of EPGD PML

746
01:36:09.540 --> 01:36:11.430
Faculty (Olympus): I want to find the true mean.

747
01:36:11.810 --> 01:36:14.129
Faculty (Olympus): Of the weight of this population.

748
01:36:14.380 --> 01:36:15.500
Faculty (Olympus): How do I do that?

749
01:36:18.470 --> 01:36:19.030
Faculty (Olympus): Anyone?

750
01:36:19.030 --> 01:36:20.150
Abhishek Raghuvanshi .: the details.

751
01:36:20.260 --> 01:36:23.790
Abhishek Raghuvanshi .: Data for each and every one in the population.

752
01:36:23.930 --> 01:36:24.860
Abhishek Raghuvanshi .: Calculate them.

753
01:36:25.580 --> 01:36:30.840
Faculty (Olympus): Okay, so your answer is, take all the population that you have, Find the meme.

754
01:36:31.420 --> 01:36:34.820
Faculty (Olympus): Right? Sum everything, divide by total number, done.

755
01:36:35.240 --> 01:36:38.820
Faculty (Olympus): Now, what you have come up with is called an estimator.

756
01:36:39.400 --> 01:36:42.610
Faculty (Olympus): This is a formula. You said, take some sample of fellows.

757
01:36:42.950 --> 01:36:48.759
Faculty (Olympus): X1 plus X2, W1, W2, W3, W4, add all of them, divide by N, give you the mean, right?

758
01:36:49.070 --> 01:37:01.480
Faculty (Olympus): This is an estimate. But please remember, this is not the true mean of the population. Why? Because the true mean is actually a very abstract thing. There is no true population. You'll need to do infinite sample size in order to obtain the true mean.

759
01:37:02.340 --> 01:37:11.270
Faculty (Olympus): All you will be able to do is to give me a finite sample, which means you're going to give me a sample, and from that sample, you're going to estimate the me. Is this clear?

760
01:37:11.750 --> 01:37:12.260
Soumen Deb .: Yep.

761
01:37:13.030 --> 01:37:17.080
Faculty (Olympus): Okay? So remember that the true distribution is this abstract quantity.

762
01:37:17.280 --> 01:37:31.470
Faculty (Olympus): We don't have access to that. All we have is a sample, which is 2026 batch of students, and Rak 2 today. If I take your weights today, it'll be something, tomorrow it will be something else, you know, 10 days later, it'll be something else, right? So I can't say this is the true value.

763
01:37:31.770 --> 01:37:34.230
Faculty (Olympus): So, it's an estimate, so I will give you an estimate.

764
01:37:34.370 --> 01:37:46.110
Faculty (Olympus): from this estimate, how doâ€¦ sorry, sorry, I'll give you a sample. From that sample, I can come up with an estimate, and that estimate, in our case, is going to be sigma Xi divided, or sigma Wi divided by N. That's going to begin the name. That's the sample name.

765
01:37:46.240 --> 01:37:47.359
Faculty (Olympus): Okay, Abhineet.

766
01:37:48.960 --> 01:37:52.910
Abhineet Bansal: But for a finite population, Infinite.

767
01:37:53.290 --> 01:38:01.580
Abhineet Bansal: samplesâ€¦ how is that possible? If I have a population of 100 students, I can actually find the true mean, right? Just for those 100 students.

768
01:38:01.580 --> 01:38:03.060
Faculty (Olympus): No, that is not the true name.

769
01:38:03.280 --> 01:38:05.330
Faculty (Olympus): Then it's not a random variable anymore, right?

770
01:38:05.570 --> 01:38:09.340
Faculty (Olympus): If there are only 100, Then it's fixed dataset.

771
01:38:10.210 --> 01:38:11.540
Faculty (Olympus): Everything is normal.

772
01:38:13.470 --> 01:38:14.150
Abhineet Bansal: But it'sâ€¦

773
01:38:14.320 --> 01:38:19.350
Faculty (Olympus): Right? The idea is, when you say population, it means everything, at every instant.

774
01:38:21.010 --> 01:38:27.270
Faculty (Olympus): So in that case, you know, there is a variation, and what all you get is a sample.

775
01:38:27.750 --> 01:38:29.820
Faculty (Olympus): Right, soâ€¦

776
01:38:30.380 --> 01:38:38.970
Faculty (Olympus): In statistics, that's the idea, right? The true distribution is this abstract quantity, and everything else is sort of an approximation to that. In the limit of infinite sample size, you get to that.

777
01:38:39.340 --> 01:38:54.820
Faculty (Olympus): Alright, so an estimator is very simple. The concept is some formula that is an estimate of some parameter. So, if you take mu and sigma of a normal distribution, right, or the probability of success in aâ€¦ so, for example, I did coin toss, right? Heads and tails. How do I find the total probability of

778
01:38:55.410 --> 01:38:56.529
Faculty (Olympus): You know, headsâ€¦

779
01:38:57.190 --> 01:39:13.820
Faculty (Olympus): I'll basically count the number of heads, divide by the total number of coin tosses, right? So I'll say 0 or 1, some of these fellows. So the estimator for P is simply P is equal to sigma Xi by N. So this is also a formula, because I'm estimating this probability by doing some experiment, okay? So these are all called estimators, okay?

780
01:39:14.130 --> 01:39:22.400
Faculty (Olympus): So, when we do least squares process, okay, which is the regression process, Okay,

781
01:39:22.790 --> 01:39:29.480
Faculty (Olympus): you can come up with what's called a least squares estimator for any one of these parameters. So remember, these are all parameters.

782
01:39:29.770 --> 01:39:30.929
Faculty (Olympus): In your model.

783
01:39:31.600 --> 01:39:35.870
Faculty (Olympus): So if you consider, say, Y is equal to alpha plus beta X, Okay?

784
01:39:36.310 --> 01:39:43.850
Faculty (Olympus): What you're doing is, you're only going to get some finite set of measurements. So when we did the pendulum experiment, we had, you know, 90 values per measure.

785
01:39:43.980 --> 01:40:00.059
Faculty (Olympus): That's not every single possible measurement, right? So what you basically are doing is, you are coming up with an estimate for alpha and an estimate for beta. And this makes sense, because if I did 90 more experiments, I'll get different numbers. So, obviously, it's not the true parameter, right? So it's only an estimate.

786
01:40:00.250 --> 01:40:06.710
Faculty (Olympus): So what you're doing is, you're constructing estimators A and B, capital A and B, for these parameters, alphiling it up.

787
01:40:06.950 --> 01:40:07.880
Faculty (Olympus): Okay?

788
01:40:07.990 --> 01:40:13.650
Faculty (Olympus): And the idea is, the expectation of these estimators will be the true parameter.

789
01:40:13.820 --> 01:40:18.109
Faculty (Olympus): Okay, which means the expectation of A should be alpha, expectation of B should be beta.

790
01:40:18.920 --> 01:40:23.379
Faculty (Olympus): I hope I'm making sense, because this, again, A and B is only evaluated for a given set of data.

791
01:40:24.230 --> 01:40:28.670
Faculty (Olympus): And the limit of bazillion experiments, it'll go towards alpha.

792
01:40:29.740 --> 01:40:41.019
Faculty (Olympus): Alright, so here, what we have is, we have actual measurements by i and Xi, right? And when we say least squares, what we're doing is, we are minimizing the sum of the squared differences.

793
01:40:41.390 --> 01:40:45.929
Faculty (Olympus): So what do we have? We have a model. The model is A plus BX, i.e.

794
01:40:46.240 --> 01:40:57.349
Faculty (Olympus): And the actual value is ya. So now you look at the difference between these two, take the square, sum all of them, and this is called the sum of the squares of the residuals.

795
01:40:57.620 --> 01:41:00.890
Faculty (Olympus): This fellow is called a residual, taking a square, summing it up.

796
01:41:01.640 --> 01:41:06.810
Faculty (Olympus): So what is done in these squares is, you minimize the sum of the squares of the differences.

797
01:41:07.140 --> 01:41:09.100
Faculty (Olympus): you minimize SSR,

798
01:41:09.750 --> 01:41:16.410
Faculty (Olympus): And that's how you get least squares. And it's again called least squares because you're actually taking square of this film.

799
01:41:17.440 --> 01:41:19.690
Faculty (Olympus): Yeah, and then you're taking the minimize elements.

800
01:41:21.210 --> 01:41:22.110
Faculty (Olympus): All right?

801
01:41:22.350 --> 01:41:24.779
Faculty (Olympus): Let usâ€¦

802
01:41:25.600 --> 01:41:31.889
Faculty (Olympus): resume this in the next class. We will now set up the normal equations, solve this, you know, and then get intoâ€¦

803
01:41:32.460 --> 01:41:41.510
Faculty (Olympus): some other details, basic details, and then we'll get into code, okay? Just revise this next class. So I'll stop here, open for any questions.

804
01:41:45.370 --> 01:41:48.140
Faculty (Olympus): Sorry, one secondâ€¦ yes, varun?

805
01:41:49.180 --> 01:41:54.580
varun kumar .: Yeah, so here itself, if you go to the top, the first thingâ€¦ In regression.

806
01:41:54.870 --> 01:41:56.270
Faculty (Olympus): Yeah, this is the top thing.

807
01:41:56.920 --> 01:42:07.610
varun kumar .: So, here you introduce that, E, and, expectations of Y even given X. At that point, you explained something. I guess I understood, but I just wanted to.

808
01:42:07.610 --> 01:42:13.010
Faculty (Olympus): So, see, supposing I want to say there's a true model that is able to explain all the noise.

809
01:42:14.360 --> 01:42:21.980
Faculty (Olympus): So, every YI, I cannot predict with just this linear model. There's going to be some noise, so you're putting that into this random variable, which has zero mean, that's all.

810
01:42:24.180 --> 01:42:27.880
varun kumar .: Yeah, but then you said that, that expectations of eachâ€¦

811
01:42:27.880 --> 01:42:31.730
Faculty (Olympus): Because it has zeroâ€¦ yeah, because E has zero mean, expectation of E should be zero.

812
01:42:33.510 --> 01:42:40.380
Faculty (Olympus): E is a random variable, right? If it's noise, I don't know what the value is. It's gonna be some noise here, some noise here, some noise here, it's gonna change.

813
01:42:41.640 --> 01:42:44.890
Faculty (Olympus): I'm just saying that the noise is such that it has zero mean.

814
01:42:45.640 --> 01:42:46.300
varun kumar .: Okay.

815
01:42:46.300 --> 01:42:50.370
Faculty (Olympus): Because if it were not zero mean, then I would have actually captured it in my beta note.

816
01:42:51.020 --> 01:42:52.119
Faculty (Olympus): Which is a construct.

817
01:42:57.250 --> 01:42:59.200
Faculty (Olympus): Okay. Okay? Yeah, that sucks.

818
01:42:59.400 --> 01:43:03.120
Faculty (Olympus): You know, you'll probably do this more formally in your stats course.

819
01:43:03.380 --> 01:43:04.330
Faculty (Olympus): Ashish?

820
01:43:04.810 --> 01:43:07.449
Ashish Kumar .: After this SSR is basically the error.

821
01:43:08.310 --> 01:43:10.789
Faculty (Olympus): Some of the squares are theâ€¦ errors, yes.

822
01:43:12.130 --> 01:43:15.059
Ashish Kumar .: Okay, so we should not relate this with the noise.

823
01:43:17.660 --> 01:43:21.959
Faculty (Olympus): Good question. Where is this error coming? Supposing the model is perfect.

824
01:43:23.490 --> 01:43:25.849
Faculty (Olympus): I give you a straight line where there's no noise.

825
01:43:26.050 --> 01:43:27.730
Faculty (Olympus): What'll SSRB?

826
01:43:28.570 --> 01:43:29.400
Faculty (Olympus): We zeroed.

827
01:43:29.400 --> 01:43:30.230
Ashish Kumar .: to zero.

828
01:43:30.230 --> 01:43:38.840
Faculty (Olympus): perfect model, right? But hopefully, we are in this whole course because it's a not-perfect model, right? No model is perfect. Every model is an approximation.

829
01:43:39.070 --> 01:43:41.150
Siddharth Digambar Kulkarni .: So, these are the squareâ€¦

830
01:43:41.150 --> 01:43:48.929
Faculty (Olympus): There's a famousâ€¦ there's a famous stats quote. There's aâ€¦ hang on, Siddharth one second. There's a famous statistics quote called, all models are wrong, some are useful.

831
01:43:49.280 --> 01:43:51.890
Faculty (Olympus): It's a worthwhile code to remember.

832
01:43:52.440 --> 01:43:54.909
Faculty (Olympus): All right, Siddharth, what are you saying?

833
01:43:54.910 --> 01:43:59.650
Siddharth Digambar Kulkarni .: So, you are, squaring the errors only, here. You're squaring the errors only, yes.

834
01:44:00.140 --> 01:44:01.120
Faculty (Olympus): That's what I said.

835
01:44:01.120 --> 01:44:01.919
Siddharth Digambar Kulkarni .: Yes, yes, yes.

836
01:44:01.920 --> 01:44:02.780
Faculty (Olympus): Ashish?

837
01:44:03.880 --> 01:44:05.580
Faculty (Olympus): I don't answer the question.

838
01:44:05.580 --> 01:44:06.750
Ashish Kumar .: Yes, sir, yes, sir, Ankit.

839
01:44:06.750 --> 01:44:08.950
Faculty (Olympus): Okay, got it, fine. Soumen?

840
01:44:10.050 --> 01:44:23.620
Soumen Deb .: Yeah, sorry, I've got a Pandas question, though. Sure. So, so, looking at it, it's a lot of code. So, does internally Pandas default using NumPy, or is it, like, general Python data structures.

841
01:44:23.620 --> 01:44:28.280
Faculty (Olympus): No, no. So, well, it uses a combination. I mean, NumPy doesn't do everything Pandas requires.

842
01:44:28.520 --> 01:44:37.500
Faculty (Olympus): So, NumPy is, I think, so earlier in the past, Pandas used to be written, implemented with Cython. I don't know what it is currently, many years ago.

843
01:44:37.650 --> 01:44:42.869
Faculty (Olympus): But it does use NumPy as a core. I mean, if you look at any series, dot value is a NumPy.

844
01:44:43.320 --> 01:44:53.990
Faculty (Olympus): So yeah, NumPy array is an extremely efficient, well-designed data structure that everybody in the Python community who does any numerics is familiar with. So it kind of makes sense to use that.

845
01:44:56.240 --> 01:44:57.440
Soumen Deb .: Makes sense, thank you.

846
01:44:58.860 --> 01:44:59.690
Faculty (Olympus): Rahul?

847
01:45:00.200 --> 01:45:02.640
Rahul Joshi .: So if you go to that integration formula.

848
01:45:02.640 --> 01:45:03.880
Faculty (Olympus): Regulation, okay.

849
01:45:03.880 --> 01:45:04.420
Rahul Joshi .: Yep.

850
01:45:04.600 --> 01:45:21.630
Rahul Joshi .: So, where it is, multiple variables are, means X1 to XR are somehow driving the value of Y. Yes. So, in calculation of these constants, V, beta, is it like a one-on-one calculation? Like, first calculate B1 against Y? Sorry. No.

851
01:45:21.630 --> 01:45:27.680
Faculty (Olympus): No, no, no, no. So that's whatâ€¦ so this is what I'mâ€¦ I didn't finish that material. So the next step here is you minimize this.

852
01:45:29.070 --> 01:45:39.829
Faculty (Olympus): Okay? You minimize this. When you minimize it, you'll end up getting a set of equations for A and B. Simultaneous set of equations, you solve it. You end up getting a linear system, in this case.

853
01:45:42.060 --> 01:45:44.889
Rahul Joshi .: Because, sir, the question is,

854
01:45:45.220 --> 01:45:55.959
Rahul Joshi .: Y and, let's say, X1, you find out a constant. But whenever you add X2 variable, again, X1 and X2 also are driving each other, right? They might be also having some connection between the two.

855
01:45:56.540 --> 01:45:57.590
Rahul Joshi .: There's a constant.

856
01:45:57.590 --> 01:46:02.030
Faculty (Olympus): No, no, no, no, no, no, they're independent variables. Xon and X2 are not related, in this case.

857
01:46:05.660 --> 01:46:08.779
Faculty (Olympus): They're supposed to be independent limits, so they're not responses.

858
01:46:09.020 --> 01:46:10.569
Siddharth Digambar Kulkarni .: We try to choose them.

859
01:46:10.570 --> 01:46:15.809
Faculty (Olympus): They may be, they may be related, but, you know, you'll startâ€¦ there may be correlated variables, but yeah.

860
01:46:15.990 --> 01:46:20.680
Faculty (Olympus): Ideally, you'd want them to may not correlate, but it's okay. You canâ€¦ you can still come up with this.

861
01:46:21.930 --> 01:46:26.050
Rahul Joshi .: Anyway, probably after the next class, I will understand that.

862
01:46:26.050 --> 01:46:26.470
Faculty (Olympus): Sure.

863
01:46:27.910 --> 01:46:32.269
Faculty (Olympus): Sorry, I have to just step out, I'll be right back. Just give me one second, I'll be right back.

864
01:46:35.000 --> 01:46:36.510
Faculty (Olympus): I'llâ€¦ as soon as I'm backâ€¦

865
01:47:41.060 --> 01:47:42.120
Amod Kulkarni: Pura tomolar.

866
01:48:09.040 --> 01:48:10.799
Faculty (Olympus): Sorry about that. Please tell me.

867
01:48:12.260 --> 01:48:13.250
Faculty (Olympus): Rahul?

868
01:48:14.300 --> 01:48:15.880
Rahul Joshi .: No, sir, you answered my question.

869
01:48:15.880 --> 01:48:17.549
Faculty (Olympus): Okay, great. Siddharth?

870
01:48:18.600 --> 01:48:30.060
Siddharth Digambar Kulkarni .: So, sir, this, the first coefficient, that is B0, essentially when all Xs are 0, then Y will be equal to B0, right?

871
01:48:30.060 --> 01:48:30.600
Faculty (Olympus): Yup.

872
01:48:30.880 --> 01:48:42.379
Siddharth Digambar Kulkarni .: Right, so, like, this is a, is it notâ€¦ is this not a very oversimplification because, or this is a linear,

873
01:48:42.780 --> 01:48:46.039
Siddharth Digambar Kulkarni .: What do you say, relation that we are trying to see?

874
01:48:46.040 --> 01:48:47.620
Faculty (Olympus): That's a linear model.

875
01:48:47.620 --> 01:48:52.179
Siddharth Digambar Kulkarni .: Y may not be linearly correlated with all these,

876
01:48:53.020 --> 01:48:55.599
Faculty (Olympus): not have a linear relationship with other animals. Yes, true.

877
01:48:55.910 --> 01:48:57.360
Siddharth Digambar Kulkarni .: Yes. So,

878
01:48:57.360 --> 01:48:58.440
Faculty (Olympus): We have to start somewhere.

879
01:48:58.440 --> 01:49:01.930
Siddharth Digambar Kulkarni .: Here, we are trying to find the, line which is.

880
01:49:01.930 --> 01:49:12.610
Faculty (Olympus): We are starting with theâ€¦ we are starting with the simplest possible thing, which is a linear model. It's actually not so simple when it becomes multilinear, but okay, you can do a lot with linear models, but yeah, this is a starting point.

881
01:49:12.730 --> 01:49:18.010
Faculty (Olympus): We'll slowly see that you can do slightly more sophisticated things with this. You can do polynomial models, you can have

882
01:49:18.120 --> 01:49:24.860
Faculty (Olympus): Full-on nonlinear models. But you still need to know something between, you know, what are the variables and what are the functional forms.

883
01:49:25.140 --> 01:49:28.549
Faculty (Olympus): When you're doing something like this, you needâ€¦ You need to know that.

884
01:49:28.800 --> 01:49:34.059
Siddharth Digambar Kulkarni .: So even if it is, not linear, we'll still try to find a line,

885
01:49:34.060 --> 01:49:34.390
Faculty (Olympus): Yes.

886
01:49:34.480 --> 01:49:36.930
Siddharth Digambar Kulkarni .: Apart from, whoâ€¦

887
01:49:36.930 --> 01:49:43.059
Faculty (Olympus): This is a linear model, so you're gonna try to fit a line somehow or the other for the data, and it'll give you the best possible line.

888
01:49:43.800 --> 01:49:46.920
Faculty (Olympus): By best, we mean minimizing the sum of the squares of differences.

889
01:49:46.920 --> 01:49:52.410
Siddharth Digambar Kulkarni .: And that error is having a zero, beam.

890
01:49:53.270 --> 01:49:57.300
Siddharth Digambar Kulkarni .: So if you sum these all errors without squaring them, you'll get 0.

891
01:49:58.420 --> 01:49:59.420
Faculty (Olympus): No, you may not.

892
01:49:59.620 --> 01:50:04.550
Siddharth Digambar Kulkarni .: If you sum these all at YI minus A minus BXI.

893
01:50:04.550 --> 01:50:07.860
Faculty (Olympus): You're not guaranteed. You're not guaranteed. Remember, this is statistical.

894
01:50:08.160 --> 01:50:13.780
Faculty (Olympus): Expectation means over lots and lots and not infinite amount of data. May not actually get zero.

895
01:50:15.750 --> 01:50:17.630
Siddharth Digambar Kulkarni .: Because, like,

896
01:50:17.630 --> 01:50:21.419
Faculty (Olympus): What is the expectation of this? Just saying that there's no bias in this, that's all.

897
01:50:21.700 --> 01:50:22.720
Siddharth Digambar Kulkarni .: Okay, okay.

898
01:50:23.700 --> 01:50:30.179
Siddharth Digambar Kulkarni .: So, that is the reason why we are squaring them, we want to find the difference. If we just add them up, then we'll get zero only.

899
01:50:30.180 --> 01:50:31.219
Faculty (Olympus): No, he won't get zero.

900
01:50:31.530 --> 01:50:32.840
Faculty (Olympus): You won't get zero.

901
01:50:33.040 --> 01:50:33.560
Siddharth Digambar Kulkarni .: Okay.

902
01:50:33.560 --> 01:50:38.200
Faculty (Olympus): There are many things you can do. You can take absolute value of this and take it, but then it will not be R-squares.

903
01:50:38.630 --> 01:50:39.850
Siddharth Digambar Kulkarni .: Okay, okay, okay.

904
01:50:39.850 --> 01:50:44.540
Faculty (Olympus): the statistics of what you will get will change. It will no longer be lease price system, will be something else.

905
01:50:44.770 --> 01:50:45.810
Siddharth Digambar Kulkarni .: Very practical.

906
01:50:46.180 --> 01:50:51.780
Faculty (Olympus): But it'll be related more to the median, if you're looking at absorbes. It will not be the mean.

907
01:50:53.110 --> 01:50:53.890
Siddharth Digambar Kulkarni .: Welcome.

908
01:50:56.880 --> 01:50:58.820
Faculty (Olympus): Savalo? Sorry, Suresh?

909
01:51:01.070 --> 01:51:07.900
Savalo Suresh Naroji .: It's Savo only. My question is regarding, will we have any TA sessions?

910
01:51:08.480 --> 01:51:08.970
Savalo Suresh Naroji .: Yes.

911
01:51:08.970 --> 01:51:09.610
Faculty (Olympus): You will have TSA.

912
01:51:09.610 --> 01:51:13.549
Savalo Suresh Naroji .: Will we have anyâ€¦ PA Session this weekend, becauseâ€¦

913
01:51:13.710 --> 01:51:14.849
Faculty (Olympus): It is not yet.

914
01:51:14.850 --> 01:51:15.540
Savalo Suresh Naroji .: headache.

915
01:51:15.540 --> 01:51:24.160
Faculty (Olympus): So we will, so we will meet again, so this Friday we're not meeting, but we will meet again on Saturday and Sunday. That's the plan.

916
01:51:24.410 --> 01:51:33.219
Faculty (Olympus): And we will have a TA session, and I've also asked the TAs to give you another TA session next week, before your mid-sum, so if there are doubts and things like that, you can be answered there.

917
01:51:35.870 --> 01:51:37.080
Savalo Suresh Naroji .: Okay, on Friday we haveâ€¦

918
01:51:37.080 --> 01:51:37.420
Faculty (Olympus): Emerson?

919
01:51:37.740 --> 01:51:45.019
Faculty (Olympus): So before that, in that week, again, I've requested the TAs to have aâ€¦ conduct a TA session.

920
01:51:46.510 --> 01:51:49.179
Savalo Suresh Naroji .: Okay, but this Friday we have a session, right? 25th.

921
01:51:49.180 --> 01:51:53.420
Faculty (Olympus): No, this Friday I'm traveling, so there will be no session this third.

922
01:51:54.920 --> 01:51:56.869
Savalo Suresh Naroji .: Oh, okay, okay, it is not yet canceled.

923
01:51:56.870 --> 01:52:01.670
Faculty (Olympus): yeah, I'll be on a flight at that time, so I can't take the class, soâ€¦

924
01:52:02.790 --> 01:52:09.569
Faculty (Olympus): Saturday morning, we will have the class, and Sunday morning also, I'm hoping to have the class. And then I will wrap up, no more extra classes.

925
01:52:11.270 --> 01:52:12.399
Savalo Suresh Naroji .: Okay, yeah, that's fantastic.

926
01:52:13.050 --> 01:52:14.840
Rahul Joshi .: Part of the exam, right?

927
01:52:15.060 --> 01:52:17.630
Faculty (Olympus): Sorry, I didn't hear, can you please repeat?

928
01:52:18.930 --> 01:52:20.989
Rahul Joshi .: screen. Panda is part of the exam.

929
01:52:20.990 --> 01:52:25.029
Faculty (Olympus): Yeah, yeah, everything I do till the Sunday class is part of the exam.

930
01:52:26.660 --> 01:52:28.520
Siddharth Digambar Kulkarni .: It's a programming exam, right?

931
01:52:32.260 --> 01:52:33.160
Siddharth Digambar Kulkarni .: Hello?

932
01:52:33.160 --> 01:52:45.170
Faculty (Olympus): Yeah, it'll be programming, as in you'll have to submit code. Now, whether it is on Yux or not on Yux, we will see. I think you'll have some part on Yux, some part will be, you know, just a notebook that you upload onto.

933
01:52:46.400 --> 01:52:48.130
Anurag Singh: And when is the exam?

934
01:52:49.280 --> 01:52:51.430
Faculty (Olympus): I don't know that, I think GL team will tell you.

935
01:52:52.390 --> 01:52:55.510
Faculty (Olympus): I think third or fourth is the dates that have been already

936
01:52:55.620 --> 01:52:59.499
Faculty (Olympus): told to you, but the exact date and time, I don't know yet.

937
01:53:00.580 --> 01:53:01.690
Anurag Singh: Thank you, thank you.

938
01:53:03.230 --> 01:53:07.249
Faculty (Olympus): Okay, there don't seem to be any more questions, I need to go, I have to have dinner, soâ€¦

939
01:53:07.420 --> 01:53:12.069
Faculty (Olympus): Have a good rest of the week. I will catch up with you on Saturday.

940
01:53:15.180 --> 01:53:16.360
Faculty (Olympus): Have a good night.

941
01:53:16.360 --> 01:53:18.760
Kedar Digambar Gokhale .: Thank you, Seth.

