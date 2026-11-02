WEBVTT

1
00:11:24.340 --> 00:11:27.780
Abhineet Bansal: Hello, I'm just checking, is the professor online?

2
00:11:33.250 --> 00:11:34.539
Faculty (Olympus): No, no kidding.

3
00:11:34.950 --> 00:11:36.559
Faculty (Olympus): In the United States.

4
00:11:37.680 --> 00:11:38.450
Abhineet Bansal: Thank you.

5
00:12:14.010 --> 00:12:14.730
varun kumar .: Bye.

6
00:13:08.510 --> 00:13:09.640
Faculty (Olympus): Morning, everyone.

7
00:13:09.960 --> 00:13:11.899
Faculty (Olympus): Sorry, I'm a few minutes late.

8
00:13:12.260 --> 00:13:13.260
Faculty (Olympus): Set up.

9
00:13:15.980 --> 00:13:16.800
Apurva Jain .: Morning, sir.

10
00:13:16.800 --> 00:13:17.740
Dinesh Devnath Yadav .: Good morning, Phil.

11
00:13:17.740 --> 00:13:18.550
Abhishek Agrawal .: Good morning, sir.

12
00:13:19.450 --> 00:13:20.840
Amlan Sarkar .: Look, Ronnie, sir.

13
00:13:23.520 --> 00:13:24.329
Faculty (Olympus): Good morning.

14
00:13:38.790 --> 00:13:40.349
Faculty (Olympus): In the schoolâ€¦

15
00:13:45.430 --> 00:13:47.500
Faculty (Olympus): I hope my screen is visible.

16
00:13:48.580 --> 00:13:49.539
Faculty (Olympus): Sleep at this.

17
00:13:49.540 --> 00:13:50.630
Amlan Sarkar .: Yes, sir. Yes, sir.

18
00:13:51.320 --> 00:13:58.580
Faculty (Olympus): Alright, so very quickly, anyâ€¦ Questions, or there's some emergency questions?

19
00:14:01.000 --> 00:14:06.640
Faculty (Olympus): But if it's something not related to the content, we canâ€¦ Have them at the end.

20
00:14:09.510 --> 00:14:15.460
Faculty (Olympus): I don't see any hand raises, so I'm gonna assume there's noâ€¦ Questions?

21
00:14:23.620 --> 00:14:28.670
Faculty (Olympus): All right, so let's get on with this. I think you must also be a little anxious with yourâ€¦

22
00:14:29.450 --> 00:14:31.839
Faculty (Olympus): upcoming quiz,

23
00:14:32.690 --> 00:14:39.449
Faculty (Olympus): So we were looking at text processing with Python, and just do a quick recap of what we covered in the last class.

24
00:14:39.680 --> 00:14:44.030
Faculty (Olympus): We looked at strings, we looked at various string operations and string methods.

25
00:14:44.460 --> 00:14:50.630
Faculty (Olympus): And then, we've mentioned that strings are immutable,

26
00:14:51.150 --> 00:14:58.210
Faculty (Olympus): Whole bunch of different methods. Some of these are extremely useful, especially when you're doing string processing, which we will be doing shortly.

27
00:14:58.630 --> 00:15:01.839
Faculty (Olympus): Then we looked at string formatting, which is a bit of aâ€¦

28
00:15:05.020 --> 00:15:14.999
Faculty (Olympus): sort of arcane syntax, but a lot of this has come from, you know, C lineage. So, those of you who are familiar with C programming, you can use this, continue to use it.

29
00:15:15.110 --> 00:15:19.310
Faculty (Olympus): What are thoseâ€¦ would much prefer to use F-strings.

30
00:15:19.390 --> 00:15:38.019
Faculty (Olympus): And with F-strings, it's a lot easier to, you know, make these kind of strings. One thing I want to point out, in case it's not obvious to everybody so far, is that when you construct an F string, the result is actually a string. So, for example, when we looked at this here, if I evaluate the stringâ€¦ sorry, I didn'tâ€¦

31
00:15:38.300 --> 00:15:46.430
Faculty (Olympus): this one. So now you see that the result here is a string. So if I were to look at, you know, X is equal to this, and then say type of STR,

32
00:15:47.690 --> 00:15:49.499
Faculty (Olympus): Thanks, it'll be a steal.

33
00:15:49.850 --> 00:15:54.219
Faculty (Olympus): Okay, so F-strings are just a syntactic convenience.

34
00:15:54.330 --> 00:15:58.510
Faculty (Olympus): Where this thing is interpolated into theâ€¦

35
00:15:59.450 --> 00:16:01.339
Faculty (Olympus): String, and the result is a string.

36
00:16:01.690 --> 00:16:09.899
Faculty (Olympus): All right, the same applies even for raw strings. I had mentioned raw strings earlier, but that'sâ€¦ you don't recall that, that's all right.

37
00:16:10.280 --> 00:16:14.810
Faculty (Olympus): And then I said, you know, you can add additional format specifiers to these,

38
00:16:15.290 --> 00:16:17.930
Faculty (Olympus): Variables that are interpolated into your string.

39
00:16:18.600 --> 00:16:37.529
Faculty (Olympus): And I kind of left you with this, with this documentation you can read and, you know, figure out more in case you have to do more kind of formatting. It's unlikely that in this course we'll be asking you, you know, all kinds of funny formatting requirements, but if you're never needing to build something like a console tool or things like that, and you want to write

40
00:16:38.050 --> 00:16:43.889
Faculty (Olympus): pretty printing, you know, and use F-strings for that, you can use this. But if you really want to do, you know.

41
00:16:44.140 --> 00:16:47.569
Faculty (Olympus): console tools, there are other libraries in Python which willâ€¦

42
00:16:48.330 --> 00:16:53.029
Faculty (Olympus): Make it very easy to render color, text, and things like that on a console.

43
00:16:53.400 --> 00:16:54.939
Faculty (Olympus): But we won't get into that.

44
00:16:56.740 --> 00:17:00.159
Faculty (Olympus): The last thing I stopped was with, you know, string container ship.

45
00:17:00.230 --> 00:17:19.210
Faculty (Olympus): And then we looked at some sneaky solutions that you can do with using strings. So, the nice thing about having these data structures and the ability to convert from strings to integers is that sometimes you can solve problems in an alternative way by, you know, converting from one data type to another, and then slider.

46
00:17:20.290 --> 00:17:35.120
Faculty (Olympus): Then we looked at reading and writing data files, and I started off with this approach of opening a file and then formally closing it. This is generally not a good idea, and it's always a better idea to use this form, which is a context manager, where you basically say, with

47
00:17:35.120 --> 00:17:44.119
Faculty (Olympus): you know, data file asâ€¦ open this file as F, and then youâ€¦ inside the scope of this, the fileâ€¦ this F file object is available.

48
00:17:44.120 --> 00:17:56.869
Faculty (Olympus): is open, and as soon as this block ends, this file object is closed, okay? So just keep that in mind, that once this is done, this file is actually closed. You cannot do f.read and things like that in this section, okay?

49
00:17:56.870 --> 00:18:06.029
Faculty (Olympus): the ZEF becomes automatically closed. This is useful because even if you had an exception arise here, some error, right, something you're passing, you're doing some code, and there's an

50
00:18:06.100 --> 00:18:17.739
Faculty (Olympus): error, this file object will still be closed, which is not the case, and doing this carefully in this particular form is a lot more tricky. So, in general, use this form.

51
00:18:18.130 --> 00:18:21.749
Faculty (Olympus): When you looked at writing files, probablyâ€¦

52
00:18:21.950 --> 00:18:29.420
Faculty (Olympus): Just beware that it will clobber any file that you want to write. So if youâ€¦ if you have an existing file, you're finished. It's going to overwrite that file.

53
00:18:30.930 --> 00:18:43.290
Faculty (Olympus): Then we looked at a simple exercise, and then I sort of, introduced the motivation for dictionaries by considering this little problem where we have Alice in Wonderland's first paragraph.

54
00:18:43.330 --> 00:18:54.960
Faculty (Olympus): And we wanted to count the number of occurrences of Alice. So the first trick here is to reduce, to sort of convert this paragraph into lowercase text, and then use the count built-in method to count the number of occurrences of Alice.

55
00:18:54.960 --> 00:19:08.449
Faculty (Olympus): We did the same thing for the, but then the question was, I want to look at all the words that are there in that text, and I want to find out their number of occurrences. So, how would we do something like this? Here, I know that I want to look at Alice, which I don't knowâ€¦

56
00:19:08.510 --> 00:19:19.479
Faculty (Olympus): You know, so there are many ways to do this, but once we introduce dictionaries, a lot of these kind of problems become very easy to solve, and this is also a nice point to introduce dictionaries.

57
00:19:19.620 --> 00:19:22.539
Faculty (Olympus): So, Rahul, you have a quick question, I'll answer your question.

58
00:19:22.940 --> 00:19:36.390
Rahul Joshi .: Thank you, Sauria. In the previous class, you mentioned that f.read and if.readLines both read the complete file in one go anyway. But then, what is the exact difference between the two if the file is completely red?

59
00:19:36.390 --> 00:19:39.179
Faculty (Olympus): One returns a list, the other returns a string.

60
00:19:39.730 --> 00:19:45.470
Faculty (Olympus): RAID returns a string, the other one returns a, you know, RAID lines returns a list of strings.

61
00:19:46.110 --> 00:19:47.140
Rahul Joshi .: Okay, thank you, sir.

62
00:19:47.660 --> 00:19:56.450
Faculty (Olympus): Yeah, and of course, please note, read takes an argument which will allow you to read only small chunks of the file, so it's not like you have to read everything in one go.

63
00:19:56.870 --> 00:19:59.520
Faculty (Olympus): But sometimes for small files, it doesn't make a difference.

64
00:19:59.660 --> 00:20:00.639
Faculty (Olympus): That'd be neat?

65
00:20:01.140 --> 00:20:03.920
Abhineet Bansal: So, why do we need to convert it to a lowercase?

66
00:20:04.340 --> 00:20:09.249
Faculty (Olympus): So, supposing you have Alice, and somehow, for whatever reason, Alice was misspelled here as smalling.

67
00:20:11.070 --> 00:20:12.559
Faculty (Olympus): We don't know, right?

68
00:20:12.830 --> 00:20:15.689
Abhineet Bansal: Got it. So this is case sensitive, what you're writing inside count.

69
00:20:15.850 --> 00:20:18.370
Faculty (Olympus): Everything is case sensitive, right? Yes.

70
00:20:18.780 --> 00:20:19.400
Abhineet Bansal: Thanks.

71
00:20:20.590 --> 00:20:30.579
Faculty (Olympus): So, good point. Please remember, everything is case sensitive. So, Alice, the little string, ALICE is not equal to capital ALIC, okay? So, for example, if I were toâ€¦

72
00:20:37.520 --> 00:20:40.819
Faculty (Olympus): It's false, yeah? As, of course, we started.

73
00:20:44.220 --> 00:20:45.060
Faculty (Olympus): Okay.

74
00:20:46.160 --> 00:20:48.979
Faculty (Olympus): Vinet, I think I've answered your question.

75
00:20:50.010 --> 00:21:02.709
Faculty (Olympus): Great. So, let us now introduce dictionaries. So, dictionaries are a nice, very powerful data structure that are used in many places all over Python.

76
00:21:03.010 --> 00:21:08.629
Faculty (Olympus): And we will soon find that it's a very convenient data structure to do a variety of things.

77
00:21:08.920 --> 00:21:13.320
Faculty (Olympus): So, one general way of thinking of a dictionary is think of it as a container, like a list.

78
00:21:13.530 --> 00:21:20.259
Faculty (Olympus): But instead of having, you know, indices which are constrained to be 0, 1, 2, 3, 4, and so on.

79
00:21:20.410 --> 00:21:25.720
Faculty (Olympus): You can useâ€¦ you can think of the index being a generalized object called a key.

80
00:21:25.860 --> 00:21:28.079
Faculty (Olympus): Okay, so you can use a key and a value.

81
00:21:28.610 --> 00:21:37.209
Faculty (Olympus): And so these keys can be strings, integers, floats, tuples, basically any mutable quantity.

82
00:21:37.320 --> 00:21:41.780
Faculty (Olympus): technicâ€¦ there is a technicality here. There'sâ€¦ it basically says anything that can be

83
00:21:42.110 --> 00:21:51.759
Faculty (Olympus): That can be made into a hash. So if it does not make sense, forget about it. But basically, any immutable quantity in general is a good idea you can use as a key.

84
00:21:52.040 --> 00:21:58.710
Faculty (Olympus): And the values can also be anything. So values can be anything at all. That is the keys, there is some constraints.

85
00:22:00.440 --> 00:22:13.710
Faculty (Olympus): And the keys don't have to be of the same type, neither do the values. Just like in a list, you can put a string, an integer, a floating point, another list, a dictionary, whatever. Same way, the values can be anything, and the keys also don't necessarily have to be all of the same type.

86
00:22:13.920 --> 00:22:16.920
Faculty (Olympus): So let's look at some simple examples to get used to this.

87
00:22:17.050 --> 00:22:21.959
Faculty (Olympus): First thing is, I'm going to show you the literal syntax, which means how you just construct a dictionary

88
00:22:22.320 --> 00:22:27.059
Faculty (Olympus): Directly, you know, usingâ€¦ literally typing the values.

89
00:22:27.180 --> 00:22:37.089
Faculty (Olympus): So here we have a small phone book, which says mom's number, so notice the syntax, it's a curly bracket, and here my key is a string. So it's going to be mom is string.

90
00:22:37.320 --> 00:22:38.040
Faculty (Olympus): Nope.

91
00:22:38.290 --> 00:22:54.029
Faculty (Olympus): And then followed by a colon, and then the value. The value is 1234 in this case, it could be anything. Dad, so in this case, it's a phone book, so it's like a phone number, 4-digit phone. Oops, dad is. And then all different key-value pairs are separated by commas, so you can have as many of these as you want.

92
00:22:54.140 --> 00:23:00.659
Faculty (Olympus): Right, so I've just taken two here. So now, if I were to execute this, you'd see that I get back, you know, what I have typed here.

93
00:23:00.660 --> 00:23:14.929
Faculty (Olympus): mom is 1234, dad is 5, 6, right? And notice here that, you know, as I said before, strings are strings, right? The way you construct them in literal strings can be either with single quotes or double quotes, so, you know, don't let these things bother you. It's just a string, okay?

94
00:23:15.730 --> 00:23:18.130
Faculty (Olympus): Now, if you look at the type of the phone book.

95
00:23:18.560 --> 00:23:27.959
Faculty (Olympus): Okay, so dict is also a constructor, you can use it to construct, right, just like LIST, small LIST, is the type of the list, but you can also use it as a constructor.

96
00:23:28.180 --> 00:23:46.580
Faculty (Olympus): Now, how do you get thisâ€¦ how do you get mom's phone number? Well, you just say phone book, and give it the string as the key, unlike a list where it's an index, and implicitly it's 0, 1, 2, 3, so on and so forth. Here, the keys are what determine theâ€¦ you can use the keys to extract the values. So, phone book of mom will be 1234, okay?

97
00:23:46.580 --> 00:23:49.110
Faculty (Olympus): Now, setting values is straightforward. Again, you can set

98
00:23:49.110 --> 00:23:55.239
Faculty (Olympus): Phone book mom equal to 4567, right? That's right. So now notice this mom's number has changed, okay?

99
00:23:55.630 --> 00:24:03.099
Faculty (Olympus): And then you can add new keys also. You can say phone book of work, okay, is 1024, right? So now we have 3 entries.

100
00:24:03.190 --> 00:24:15.860
Faculty (Olympus): Okay? And now, just a quick illustration to show that you don't need all of them to be fixed type. So here I have a key as an integer, and a value as an integer. Key as a string, value as a floating point. Key as a string, andâ€¦

101
00:24:15.990 --> 00:24:27.799
Faculty (Olympus): then, you know, value as a string, and then key as a floating point number, and value as a string. Okay, so it isâ€¦ there's no restriction on what types it is, just that the keys have to be generally immutable objects.

102
00:24:28.700 --> 00:24:47.299
Faculty (Olympus): Now, another thing that's useful, just like empty lists, we create an empty list and then appended elements into it in many of our code, exercises. You can create an empty list, sorry, an empty dictionary by just using curly bracket open close. Okay, so empty dict, you can use this, or you can just use the constructor, just DICT, okay?

103
00:24:47.600 --> 00:24:49.730
Faculty (Olympus): And that will also give you a dictionary.

104
00:24:51.540 --> 00:25:00.720
Faculty (Olympus): So now that you have this dictionary, if I look at tab here, you'll see this, you'd say dict self, so ignore the self, slash. You remember what slash is?

105
00:25:04.120 --> 00:25:05.449
Roshan Mathane .: Everything beforeâ€¦

106
00:25:05.770 --> 00:25:07.030
Siddharth Digambar Kulkarni .: After that, dude.

107
00:25:07.030 --> 00:25:07.950
Abhineet Bansal: positional.

108
00:25:07.950 --> 00:25:08.430
Soumen Deb .: Bozyâ€¦

109
00:25:08.430 --> 00:25:09.750
Roshan Mathane .: Solution, yeah.

110
00:25:09.750 --> 00:25:22.220
Faculty (Olympus): So there's noâ€¦ none of these are either positional or, you know, so you have to be careful with this. But anyway, the point here is, any arguments you give here, this is variable arguments, this is variable keyword arguments.

111
00:25:22.230 --> 00:25:41.750
Faculty (Olympus): Okay, so you can call it in multiple different ways. So here, what I'm doing is I'm calling it with keyword arguments. Okay, so keyword arguments here areâ€¦ I'm saying X is equal to 1, Y is equal to 2.1, Z is equal to hello. So what is this? This basically maps into the star star keyword argument form. So what'll happen here is.

112
00:25:41.830 --> 00:25:49.200
Faculty (Olympus): This will be equivalent to meâ€¦ so let'sâ€¦ if I run this, you'll see what happens. It will create a dictionary with X being the key.

113
00:25:49.330 --> 00:25:50.910
Faculty (Olympus): And the value being 1.

114
00:25:50.940 --> 00:25:59.540
Faculty (Olympus): Y being the key, value being 2.1. So this is sometimesâ€¦ I find this convenient to type, because for every key, I don't have to put quote marks.

115
00:25:59.540 --> 00:26:17.780
Faculty (Olympus): I can just say dict X equal to 1, Y equal to 2, Z equal to 3, blah blah blah, and then it'll construct that, right? On the other hand here, I have to put quotes, colon, and all of that. It's much faster to type this sometimes, so you'll see this kind of a construction also. Just note that, it's no different from creating a dictionary, okay?

116
00:26:18.290 --> 00:26:21.089
Faculty (Olympus): Now, iteration across a dictionary.

117
00:26:21.240 --> 00:26:37.780
Faculty (Olympus): is also very easy, and it's very similar to everything you have learned so far. So you can do iteration in the following fashion for key in dictionary. And please note, when you iterate in this form, it is always going to iterate across the keys, not across the values, or not across key-value pairs.

118
00:26:37.890 --> 00:26:52.380
Faculty (Olympus): And if you want to extract the value, you must ask the dictionary for that value, okay? So, if you run this, it will basically say oneâ€¦ this is the key, this is the value, so 125, K is 1.23, so on and so forth. This is for this dictionary.

119
00:26:54.080 --> 00:26:56.560
Faculty (Olympus): Of course, if I try it for phone book, I'll getâ€¦

120
00:27:01.960 --> 00:27:03.570
Faculty (Olympus): Just help him out, sort of.

121
00:27:04.130 --> 00:27:04.820
Faculty (Olympus): Huh.

122
00:27:05.730 --> 00:27:16.430
Faculty (Olympus): Okay, so this tells you something, right? I used the wrong dictionary here. It says key error. So if you give me aâ€¦ take a dictionary and give it a key which doesn't exist, you will get an exception, and the exception will be called key error.

123
00:27:16.430 --> 00:27:27.530
Faculty (Olympus): So, remember, this key error means it tells you something, right? Tells you that there is no key for this. And notice that nicely it has highlighted this block as well, to tell you where the error is. If I run this, I would get this.

124
00:27:27.550 --> 00:27:29.650
Faculty (Olympus): Let me go back to the original board.

125
00:27:32.150 --> 00:27:37.660
Faculty (Olympus): All right. Now, very often, right, just like we had, things like

126
00:27:38.030 --> 00:27:42.540
Faculty (Olympus): Zip and things like that, so there are some conveniences that you'll find are useful.

127
00:27:43.670 --> 00:27:49.600
Faculty (Olympus): When you're iterating across a dictionary, very often you'll have a pattern where you want the key and you also want the value, okay?

128
00:27:49.600 --> 00:28:04.820
Faculty (Olympus): And then you have to unnecessarily do key, then find D of key, and things like that. Instead, you can do something like this. You can say for key comma value in d.items, okay? So let's just quickly see what D.Items is. D.Items.

129
00:28:05.810 --> 00:28:12.099
Faculty (Olympus): Well, give me dict items, which is an iterator, so, but anyway, I can make this into a list, or a tuple, or whatever.

130
00:28:13.310 --> 00:28:17.989
Faculty (Olympus): be the same thing, but for now, it's alright. Dict items, let it be as it is.

131
00:28:18.520 --> 00:28:25.510
Faculty (Olympus): Notice that this is basically a list, or a, you know, a container, a sequence of Key value pairs.

132
00:28:25.780 --> 00:28:40.519
Faculty (Olympus): So it has taken this dictionary, converted into a set of key-value pairs. So items will convert this into some sort of an iterable, which you can iterate over, right? So it means the first will be 125, second will be A1.23, so on and so forth. And this will beâ€¦

133
00:28:40.630 --> 00:28:47.600
Faculty (Olympus): expanded out into key and values. So if I were to run this, I can immediately get this. So this form is also very useful.

134
00:28:48.130 --> 00:28:56.150
Faculty (Olympus): There's another form as well, which is, opt Do you, Doc?

135
00:28:57.180 --> 00:29:09.650
Faculty (Olympus): So, okay, there used to be something else, but okay, this item is sufficient as far as you're concerned at this point. I don't think you need anything else. So you useâ€¦ if you want just the keys, you do for key in dictionary.

136
00:29:09.650 --> 00:29:20.609
Faculty (Olympus): If you want keys and values, it's ideal to use key comma value in D.O.items, okay? And of course, as before, you can also put this in a tuple that is also perfectly legal syntax.

137
00:29:23.350 --> 00:29:24.290
Faculty (Olympus): Alright.

138
00:29:24.410 --> 00:29:28.650
Faculty (Olympus): If you want all of the keys, dictionaries have a method called keys.

139
00:29:28.790 --> 00:29:45.029
Faculty (Olympus): which will again give you a dict keys, which is, again, an iterable, which means it's not a list, it's not a tuple, it's some other thing, but it can be iterated over. And you can convert this freely to a list, or a tuple, or whatever. So if I say a tuple of this, so it behaves like a sequence, is what I'm trying to say.

140
00:29:47.230 --> 00:29:53.780
Faculty (Olympus): Okay, so this will give me all the dictionary keys. If I did values, I will similarly get dict values, and this will all be the values.

141
00:29:54.230 --> 00:29:54.950
Faculty (Olympus): Okay.

142
00:29:55.180 --> 00:29:58.610
Faculty (Olympus): The last thing we need to use is, Dell.

143
00:29:58.780 --> 00:30:15.710
Faculty (Olympus): So if I want to remove an element from this, for example, in D, if I want to remove the B, right, remember what D was? D was this fellow, 125, B was hello, right? So if I want to remove the B fellow, I can do del D of B, like this.

144
00:30:16.090 --> 00:30:18.329
Faculty (Olympus): I run this, now hello is gone.

145
00:30:18.450 --> 00:30:20.419
Faculty (Olympus): The Dâ€¦ the B key is gone.

146
00:30:21.070 --> 00:30:27.270
Faculty (Olympus): All right, so very quickly, Create dictionaries like this, or you can use this sort of a constructor.

147
00:30:27.550 --> 00:30:37.330
Faculty (Olympus): You can iterate over dictionaries using either the keys or the key values using the d.items method. You can extract all the keys, all the values, and then delete.

148
00:30:38.510 --> 00:30:43.899
Faculty (Olympus): Now, there are several other methods dictionaries have. I urge you to go back.

149
00:30:44.010 --> 00:30:48.200
Faculty (Olympus): There's homework, look at each of these methods, and look at what theyâ€¦

150
00:30:48.570 --> 00:31:00.500
Faculty (Olympus): what the doc string says, okay? So, obviously, clear will clear the entire dictionary. So, if you have a dictionary with many elements, it will completely wipe out the keys, everything, clear it out. Copy will create a copy.

151
00:31:00.500 --> 00:31:09.379
Faculty (Olympus): From keys, I'm going to show you a quick example, but from keys is very useful to quickly create a key dictionary with some default key and value pairs.

152
00:31:09.380 --> 00:31:23.449
Faculty (Olympus): So, for example, if I have some iterable, any iterable, so which means it could be a tuple, list, string, some container, okay, numpy array, whatever it is, anything that can be iterated over, it will treat every value in that sequence, in that iterable, as a key.

153
00:31:23.830 --> 00:31:33.869
Faculty (Olympus): And it'll put a default value to whatever you give it, and the default is none, which means we'll just create key, none, key, none, key, none, so on and so forth, okay?

154
00:31:34.220 --> 00:31:52.469
Faculty (Olympus): I'll show you a quick example here. So if I did dick.frontKeys, range file. Remember, range is not going to give me a tuple or a list, it's actually going to give me some iterable, which means you can iterate over it. And if I were to run this, I will get 0, none, one, none, 2, none, 3, none, right? On the other hand, if I said value is 0, I will get all of the values to be 0.

155
00:31:53.450 --> 00:31:59.320
Faculty (Olympus): Alright? The only thing you have to be careful here is, if I did this, and made this a list.

156
00:31:59.600 --> 00:32:03.330
Faculty (Olympus): And now, if I said D of 0 dot append.

157
00:32:03.560 --> 00:32:05.889
Faculty (Olympus): 1, and then looked at D.

158
00:32:07.070 --> 00:32:07.980
Faculty (Olympus): Bingo.

159
00:32:10.370 --> 00:32:13.420
Faculty (Olympus): Oh, sorry, I didn't save this. So, X is this.

160
00:32:13.700 --> 00:32:15.410
Faculty (Olympus): That's our technology B.

161
00:32:15.870 --> 00:32:17.220
Faculty (Olympus): Thanks to thisâ€¦

162
00:32:21.780 --> 00:32:23.419
Faculty (Olympus): What did I just do?

163
00:32:29.510 --> 00:32:31.670
Bhavin Desai .: Sir, X.append.

164
00:32:36.090 --> 00:32:36.690
Faculty (Olympus): Wait a minute.

165
00:32:36.690 --> 00:32:37.259
Anuj Kumar Gupta .: I thinkâ€¦

166
00:32:37.260 --> 00:32:46.609
Faculty (Olympus): I didn't run it. I didn't run it. That's what I want. Okay, early morning. Okay, so if I did one here, and then look at X,

167
00:32:47.370 --> 00:32:49.520
Faculty (Olympus): I'll run these both once again.

168
00:32:51.220 --> 00:32:56.020
Faculty (Olympus): So beware of this, okay? So when you use a mutable object like this.

169
00:32:56.180 --> 00:33:10.269
Faculty (Olympus): super careful you have to be, simply becauseâ€¦ now, notice, I just added it to 0 fellow, all of them now have this one. Why? Because this is an object that's been created, and it's been added as the default, so be very careful when you do things like this, okay?

170
00:33:13.550 --> 00:33:21.209
Faculty (Olympus): On the other hand, if it's immutable, it doesn't matter, right? So, of course, this will not work anymore. So I just wanted to warn you of this little,

171
00:33:23.210 --> 00:33:30.729
Faculty (Olympus): thing that you might run into, okay? If you want the value to be 1 or whatever, you can. So, I want to save this now, soâ€¦

172
00:33:32.210 --> 00:33:36.619
Faculty (Olympus): Okay? So this is what From Keys does. So it's very convenient when you want to say, I want toâ€¦

173
00:33:37.080 --> 00:33:39.869
Faculty (Olympus): Generate something with some default values, and then iterate.

174
00:33:40.140 --> 00:33:49.839
Faculty (Olympus): d.get will give you the key, give you the value for the key, but if the key does not exist, it will return, it will basically return none.

175
00:33:49.840 --> 00:34:04.149
Faculty (Olympus): Okay, whereas if you did D square bracket and give it a key, you will get an exception if the key doesn't exist. So this is very useful sometimes when you want to say, look, I want to find if it's there or not there, and I don't want to do it, you know, I don't want to catch an exception and things like that, so it's useful in that case.

176
00:34:04.350 --> 00:34:08.840
Faculty (Olympus): d.pop and dot pop item will do kind of what they'll say, it'll remove that

177
00:34:09.170 --> 00:34:11.929
Faculty (Olympus): The last element of, you know, pop a specific element.

178
00:34:12.760 --> 00:34:19.260
Faculty (Olympus): D.setdefault is a little more involved. Again, I urge you to look at the,

179
00:34:20.750 --> 00:34:25.280
Faculty (Olympus): I urge you toâ€¦ Let me show you this.

180
00:34:28.090 --> 00:34:34.350
Roshan Mathane .: Sir, can you please repeat for D.Getkey? What happens in case of null?

181
00:34:35.449 --> 00:34:39.249
Faculty (Olympus): So, if I did X dot X off, say, 10.

182
00:34:39.749 --> 00:34:45.119
Faculty (Olympus): it'll give me a key error, right? On the other hand, if I said GET, and say 10,

183
00:34:46.149 --> 00:34:47.599
Faculty (Olympus): It'll say, it'll return none.

184
00:34:48.580 --> 00:34:49.250
Roshan Mathane .: Okay.

185
00:34:49.250 --> 00:34:51.679
Faculty (Olympus): So it does not give me an error, right?

186
00:34:52.730 --> 00:34:54.489
Faculty (Olympus): And you can also do this.

187
00:34:54.969 --> 00:34:56.400
Faculty (Olympus): You can see it.

188
00:35:07.390 --> 00:35:08.300
Faculty (Olympus): Okay?

189
00:35:08.430 --> 00:35:10.249
Faculty (Olympus): So you can get default values.

190
00:35:10.630 --> 00:35:11.200
Roshan Mathane .: Yeah.

191
00:35:11.870 --> 00:35:16.590
Faculty (Olympus): Similarly, if you have X.setDefault, so let's look at X.setDefault.

192
00:35:18.950 --> 00:35:29.120
Faculty (Olympus): Okay, let's look at what it says. It says, set default. Insert key with a value of default if key is not in the dictionary. So if I said set default, and I said zero.

193
00:35:29.370 --> 00:35:34.769
Faculty (Olympus): And, you know, you have to give it a value, right? So give it aâ€¦ or a default value. If I said set default.

194
00:35:35.110 --> 00:35:37.750
Faculty (Olympus): And I give it a default of, say.

195
00:35:41.400 --> 00:35:45.520
Faculty (Olympus): Okay, sorry, you shouldn't use keyword arguments here, so if I did thisâ€¦

196
00:35:45.660 --> 00:35:52.480
Faculty (Olympus): Now, let's look at X when I did this. It won't set it to anything, because 0 exists. But if it doesn't exist.

197
00:35:52.660 --> 00:35:56.889
Faculty (Olympus): it will set this to 10. So this is sometimes useful whenâ€¦

198
00:35:57.540 --> 00:36:13.989
Faculty (Olympus): You want some sort of a default, but you don't know if the key exists, right? So this is useful when you're writing code, when you're, you know, working with dictionaries. So just keep this in mind. So this is a bit advanced at this point, so you can just look at the documentation, try some examples. When you look at the exercises, maybe the same.

199
00:36:15.110 --> 00:36:32.729
Faculty (Olympus): The final one is d.update, and what this will do is, given a dictionary or a, you know, an iterable, it will update the key-value pairs using those, okay? So if I give you one dictionary and I say, update this dictionary using another dictionary, it will take the key-value pairs from this and update it.

200
00:36:32.760 --> 00:36:36.459
Faculty (Olympus): Okay, soâ€¦ so let's look at the top string. Itâ€¦

201
00:36:37.370 --> 00:36:39.789
Faculty (Olympus): See, if you give meâ€¦ give me this?

202
00:36:39.950 --> 00:36:53.929
Faculty (Olympus): Okay, optionally give it keyword arguments. So either you give it a set of keys, right, so either a dictionary or an iterable. If E is present and has dot keys, then it does this. If E is present and lacks a dot keys, then it does this. Okay, equal to some.

203
00:36:55.080 --> 00:36:56.100
Faculty (Olympus): Victor.

204
00:36:56.600 --> 00:37:04.830
Faculty (Olympus): Right? So, basically, this is, it's gonna iterate over either a set, a tuple of elements.

205
00:37:05.840 --> 00:37:09.630
Faculty (Olympus): And then set the key-value pairs. So it's,

206
00:37:10.060 --> 00:37:14.110
Faculty (Olympus): It's a useful way to update a dictionary from some additional data.

207
00:37:15.660 --> 00:37:16.550
Faculty (Olympus): conduct.

208
00:37:22.060 --> 00:37:32.869
Faculty (Olympus): Okay, so now let us get back to something useful. So you can always go back and, you know, look at these methods later, when you have some time. So there were some questions, I will quickly take a look. Mayank?

209
00:37:33.590 --> 00:37:42.339
Mayank Johri .: Morning, Broff. So, suppose, I want to iterate through my dictionary, and simultaneously, I also want to delete a key value pair.

210
00:37:42.530 --> 00:37:48.640
Mayank Johri .: Now, what would happen? Would not it throw, like, some kind of a concurrent modification exception?

211
00:37:48.640 --> 00:38:02.430
Faculty (Olympus): It's not concurrency in this case, because if you notice, if you remember my first few classes, everything is sequentially executed. Unless you're doing something in threads, or using a sync, or something like that, there's no concurrency business happening.

212
00:38:02.480 --> 00:38:08.790
Faculty (Olympus): What will happen, though, is if you're iterating and you're modifying the dictionary in place, you're going to run into trouble.

213
00:38:09.000 --> 00:38:16.639
Faculty (Olympus): So, in such cases, you should never modify the original. You always iterate over a copy, and then you modify theâ€¦

214
00:38:16.820 --> 00:38:18.170
Faculty (Olympus): No, whichever one you want.

215
00:38:18.910 --> 00:38:21.529
Faculty (Olympus): Oh, just a standard programming problem, yeah.

216
00:38:21.670 --> 00:38:34.930
Faculty (Olympus): But there's no concurrency issue in this case. It's just that you'll have a dictionary you're iterating, and as you're iterating, you'll start running into problems. So one way to do this, for example, is you yank out all the keys, right? And you say forâ€¦

217
00:38:35.070 --> 00:38:38.190
Faculty (Olympus): You know, for key in dictionary.

218
00:38:38.530 --> 00:38:55.310
Faculty (Olympus): Right? Be careful with something like that. If that thing is a generator, and it's doing it dynamically, you might turn into trouble. But if you yank out the keys, and say, okay, give me the keys at this instant, and then iterate over it, and then inject elements, then it may be safe. But you have to be a little careful, test your code before you do something like that.

219
00:38:57.110 --> 00:38:57.450
Mayank Johri .: Okay.

220
00:38:57.450 --> 00:38:59.849
Faculty (Olympus): Okay, yeah. So,

221
00:39:01.520 --> 00:39:08.970
Faculty (Olympus): Fine. So, your task is to now count the words in the string. I've, of course, given you the solution, given that we're running short of time.

222
00:39:09.090 --> 00:39:15.360
Faculty (Olympus): Now I'm going to march ahead. So our task is what our task is, given this text here, this para that we have.

223
00:39:15.820 --> 00:39:23.900
Faculty (Olympus): This isâ€¦ Right, so given this paragraph, It's fixed.

224
00:39:24.100 --> 00:39:27.169
Faculty (Olympus): I want to count the occurrence of every word in this.

225
00:39:27.300 --> 00:39:28.540
Faculty (Olympus): That's the task.

226
00:39:28.820 --> 00:39:34.900
Faculty (Olympus): I'll give you a minute if you want to try this without looking at the solution, the solution is right there.

227
00:39:35.160 --> 00:39:39.429
Faculty (Olympus): So, but I'll quickly answer some questions if you want to take a stab at doing this. Vallabh?

228
00:39:40.820 --> 00:39:43.739
Vallabh M: Yeah, good morning, sir. Do the keys have to be unique?

229
00:39:45.100 --> 00:39:46.649
Faculty (Olympus): Yes, they do have to be.

230
00:39:48.330 --> 00:39:52.570
Faculty (Olympus): So you can't have two values, two keys with the same key.

231
00:39:52.960 --> 00:39:54.759
Faculty (Olympus): That's the whole point of a dictionary.

232
00:39:56.200 --> 00:39:59.030
Faculty (Olympus): I can't have two ones, then what do you mean? Which one do you mean?

233
00:40:02.080 --> 00:40:05.519
Vallabh M: Jawah forms a list of, keys, actually.

234
00:40:05.520 --> 00:40:06.330
Faculty (Olympus): Yeah, that's magic.

235
00:40:06.330 --> 00:40:07.820
Vallabh M: formatting with this.

236
00:40:08.530 --> 00:40:19.959
Faculty (Olympus): That is magic. That shouldn't be done. So in this case, it's like, no, you set it to a list, and then, yeah, you can append to that list. Otherwise, it's not going to magically change some value into a list just because somebody added price.

237
00:40:20.630 --> 00:40:22.440
Faculty (Olympus): Right? That's very surprising behavior.

238
00:40:22.440 --> 00:40:23.090
Vallabh M: Yep.

239
00:40:23.090 --> 00:40:25.660
Faculty (Olympus): Yeah, so it doesn't do things like that.

240
00:40:27.100 --> 00:40:27.980
Faculty (Olympus): Thanks.

241
00:40:28.110 --> 00:40:29.100
Faculty (Olympus): Ashish?

242
00:40:29.930 --> 00:40:36.879
Ashish Kumar .: Sir, in case of the key being a floating point number, how do you follow it? Like, in case of strain, we are giving it in quotations.

243
00:40:37.000 --> 00:40:39.850
Ashish Kumar .: So, if you want to call D1.23.

244
00:40:40.610 --> 00:40:44.820
Faculty (Olympus): Yeah, you can justâ€¦ huh, so you can just do D1.23. Again, you can try this yourself.

245
00:40:45.290 --> 00:40:45.939
Ashish Kumar .: It's aâ€¦

246
00:40:45.940 --> 00:40:50.730
Faculty (Olympus): Right here, you can just try this, it's not aâ€¦ Nothing will happen.

247
00:40:53.080 --> 00:40:54.430
Faculty (Olympus): BF1?

248
00:40:55.440 --> 00:40:57.780
Faculty (Olympus): Day of 1.23â€¦

249
00:40:59.680 --> 00:41:10.859
Faculty (Olympus): Right? But here, you have to be a little careful, supposing it's some complicated thing like pi, right? You can't be saying 3.14, you'll have to be exactly that value. You'll have to be exactly that value.

250
00:41:10.860 --> 00:41:11.780
Ashish Kumar .: Nate'sâ€¦

251
00:41:12.000 --> 00:41:17.080
Faculty (Olympus): So be careful when you have someâ€¦ Some irrational, transcendental number.

252
00:41:17.980 --> 00:41:18.780
Faculty (Olympus): Careful.

253
00:41:21.100 --> 00:41:24.919
Faculty (Olympus): It will not do an approximate key and all things like that. It has to be exact.

254
00:41:25.740 --> 00:41:30.620
Faculty (Olympus): Alright, so I hope you have at least thought about how to do this.

255
00:41:31.290 --> 00:41:34.219
Faculty (Olympus): So, Sneh, I'll walk through the solution.

256
00:41:34.750 --> 00:41:40.049
Faculty (Olympus): And what we do is, we say data is an empty dictionary, okay?

257
00:41:40.220 --> 00:41:48.520
Faculty (Olympus): Then, they iterate over time All the lowercased words in this, and we split it.

258
00:41:48.960 --> 00:41:58.190
Faculty (Olympus): Remember what split does? Split will split on boundaries which have spaces, right? So wherever there's a space, it will cut the fellow into

259
00:41:58.440 --> 00:42:05.950
Faculty (Olympus): you know, two parts, and then return a list, okay? And then it iterates over each of these words, okay?

260
00:42:06.840 --> 00:42:11.190
Faculty (Olympus): You know, for if word in data, right, if this word is in data.

261
00:42:12.040 --> 00:42:14.209
Faculty (Olympus): Or why is thisâ€¦ why is this being done?

262
00:42:17.180 --> 00:42:19.330
Siddharth Digambar Kulkarni .: To check if the key is there in the data.

263
00:42:19.330 --> 00:42:32.779
Faculty (Olympus): Exactly, because I started with an empty data, right? So now what it does is it checks, oh, is this already there in data? And this operation with dictionaries is cheap. It is not an order of M, it's an order of 1 operation. It's a very quick operation.

264
00:42:33.810 --> 00:42:38.869
Faculty (Olympus): So now, if the key exists, just increment the key. If the key does not exist.

265
00:42:39.660 --> 00:42:42.300
Faculty (Olympus): Set it to 1. That means it's the first time you're fighting.

266
00:42:42.890 --> 00:42:43.380
Siddharth Digambar Kulkarni .: Fantastic.

267
00:42:43.380 --> 00:42:49.060
Faculty (Olympus): Simple as that, okay? So if you were to run this, Nope.

268
00:42:50.780 --> 00:42:55.360
Faculty (Olympus): Okay, so this is what the answer is. It basically says there are two Alices, there's WAS,

269
00:42:55.780 --> 00:42:59.630
Faculty (Olympus): Blah blah blah, there were 3 does, three R'sâ€¦

270
00:42:59.950 --> 00:43:04.650
Faculty (Olympus): Right? But notice there's some crazy things. There is a quotation

271
00:43:05.080 --> 00:43:16.520
Faculty (Olympus): Okay? There is comma, right? There are all of these things which, you know, are a little surprising, right? So there's a problem with punctuation marks, and I'm not interested. So suppose you put Alice, comma.

272
00:43:16.650 --> 00:43:22.899
Faculty (Olympus): I just did a split, and the split is basically going to not care whether it's a comma or whatever, it's only going to look at spaces.

273
00:43:23.090 --> 00:43:24.839
Faculty (Olympus): Right? So there's a problem.

274
00:43:25.080 --> 00:43:30.480
Faculty (Olympus): So what we want to do is we want to delete any punctures, okay, and we want to remove any additional spaces.

275
00:43:31.710 --> 00:43:39.239
Faculty (Olympus): So you can useâ€¦ there are some string methods that'll do this nicely, okay? I've not shown you all the string methods, we only looked at some specific ones.

276
00:43:39.500 --> 00:43:51.960
Faculty (Olympus): So, there is this one method called translate, okay? But using translate is a bit tricky, so I'm going to walk you through how you can use translate. It's very simple, but you need to know dictionaries to do translate, okay?

277
00:43:52.250 --> 00:43:55.969
Faculty (Olympus): So, let us first look at, the translate documentation.

278
00:43:56.490 --> 00:44:09.540
Faculty (Olympus): So it says para, or whatever, this object, translate, table, okay? Where table is a translation table, which must be a mapping of Unicode ordinals to Unicode table.

279
00:44:11.170 --> 00:44:19.849
Faculty (Olympus): Ordinals, strings, or none. So, if it is none, it will delete. If it is some other Unicode ordinal or a string, it will replace it.

280
00:44:20.080 --> 00:44:29.429
Faculty (Olympus): Okay? So here is a simple example, so that you understand this with code rather than reading the documentation. We are constructing this table, which is a translation table.

281
00:44:30.400 --> 00:44:36.809
Faculty (Olympus): Okay? And this table isâ€¦ I say, colon, none.

282
00:44:37.890 --> 00:44:39.470
Faculty (Olympus): Kumar Nun.

283
00:44:39.660 --> 00:44:51.529
Faculty (Olympus): And question mark now, which means 3 keys, and the value is none, okay? Now, of course, I could have used dict.from keys, and just put colon, comma, question mark, okay, butâ€¦

284
00:44:51.810 --> 00:44:54.920
Faculty (Olympus): I hope this is at least easy for you to immediately understand.

285
00:44:55.530 --> 00:45:09.339
Faculty (Olympus): Now, the second thing is, I take this dictionary and generate what para.translate requires using a maketrans. So, let's look at maketrans. Return a translation table useful for str.translate.

286
00:45:09.500 --> 00:45:15.169
Faculty (Olympus): There's only one argument, it must be a dictionary mapping, blah blah blah. Okay, so what it says isâ€¦

287
00:45:15.310 --> 00:45:17.529
Faculty (Olympus): It will convert all of them intoâ€¦

288
00:45:17.740 --> 00:45:24.050
Faculty (Olympus): Unicode ordinal. So what is this ordinal? So let us now, let me maybe split this cell into two.

289
00:45:24.170 --> 00:45:28.490
Faculty (Olympus): And then we will start looking at quantities. So, save table.

290
00:45:28.800 --> 00:45:33.370
Faculty (Olympus): And I do this, this is our table, this is a dictionary that we created. Now let's see what D has become.

291
00:45:34.240 --> 00:45:48.000
Faculty (Olympus): So notice what it says, 58 none, 44 none, 63. What are this? 54, 48, and all? These are the integers corresponding to these Unicodes characters that we have supplied here.

292
00:45:48.870 --> 00:45:58.230
Faculty (Olympus): So what this Ara.makeTrans does is, it takes these things in the form of what is convenient to us in the form of strings, or Unicode characters.

293
00:45:58.400 --> 00:46:05.480
Faculty (Olympus): converts them to the appropriate integer, that is what is needed by this translate. The translate, if you remember the documentation, it says.

294
00:46:06.220 --> 00:46:12.969
Faculty (Olympus): mapping of Unicode ordinals. So the ordinals are these integers which are corresponding to theâ€¦

295
00:46:13.960 --> 00:46:31.110
Faculty (Olympus): the character that you have, okay? So, MakeTrial simply takes all of these keys, makes them into the ordinals, and then, does this. So, for example, howâ€¦ what is this ordinal, if you're still worried? Let me show you. There's a built-in called ORD.

296
00:46:31.470 --> 00:46:35.490
Faculty (Olympus): ORD of colon. So I did, it's gonna give me 58.

297
00:46:36.810 --> 00:46:37.980
Siddharth Digambar Kulkarni .: Which is a quote.

298
00:46:37.980 --> 00:46:40.670
Faculty (Olympus): which is exactlyâ€¦ yeah, it is like an ASCII code.

299
00:46:40.920 --> 00:46:47.919
Faculty (Olympus): And in this case, since this is the same as ASCII and we're using default encoding of UTF-8, it corresponds to the ASCII character.

300
00:46:48.060 --> 00:46:54.460
Faculty (Olympus): But if it is some crazy thing which is, you know, some Unicode character in UTF8, it'll give you that integer.

301
00:46:54.750 --> 00:46:56.000
Faculty (Olympus): Does it make sense?

302
00:46:57.060 --> 00:47:02.699
Faculty (Olympus): Alright, so now that we have this ordinal to mapping whatever we want.

303
00:47:02.840 --> 00:47:14.770
Faculty (Olympus): Okay? If I ran para.translate, it will give me the string. It says Alice was beginning to get very tired. Notice that all of the colon question marks are all gone. They're all wiped out.

304
00:47:14.970 --> 00:47:24.650
Faculty (Olympus): So, when you put none, then this fellow will remove it, okay? On the other hand, let me, do another example.

305
00:47:26.490 --> 00:47:32.309
Faculty (Olympus): So let me now make another table, that's a table. I'll copy-paste this code so that

306
00:47:33.540 --> 00:47:35.109
Faculty (Olympus): is equal in A.

307
00:47:35.660 --> 00:47:37.889
Faculty (Olympus): Set that out, I'll translate.

308
00:47:40.280 --> 00:47:41.190
Faculty (Olympus): Do you?

309
00:47:41.900 --> 00:47:49.560
Faculty (Olympus): So now, instead of doing none, let me make itâ€¦ Let me make stop, yeah?

310
00:47:56.730 --> 00:48:00.730
Faculty (Olympus): Notice, it's put stars wherever this thing comes. Does it make sense?

311
00:48:00.960 --> 00:48:04.859
Faculty (Olympus): So, when you make it none, it will actually remove that character.

312
00:48:06.020 --> 00:48:07.579
Faculty (Olympus): Yes, I removed this.

313
00:48:09.340 --> 00:48:13.680
Faculty (Olympus): Now comes the next problem. I've only done this for colon

314
00:48:13.910 --> 00:48:21.740
Faculty (Olympus): So, colon, comma, and question mark. But there are a whole bunch of other punctuation marks, and I don't remember all of them.

315
00:48:22.000 --> 00:48:33.520
Faculty (Olympus): So there's a string module, right? The string module is very convenient because it has a lot of these things that you may want. For example, if I want all the ASCII letters, you don't have to type ABCD, F, G. Ajit.

316
00:48:33.520 --> 00:48:42.240
Faculty (Olympus): You can just do string.asci letters, it'll tell you all of the lowercase, all of the uppercase. So this is convenient, because if I want to say, hey, is this character an ASCII letter? You can say.

317
00:48:42.450 --> 00:48:43.580
Faculty (Olympus): character.

318
00:48:43.750 --> 00:48:47.219
Faculty (Olympus): in string.asky letters, and it will tell you 12 forms, okay?

319
00:48:47.260 --> 00:49:04.889
Faculty (Olympus): Same way, if you want to say string.punctuation, you can simply say string.punctuation, it gives you all the punctuations. Similarly, string.whitespace, it'll give you all of the whitespace gaps, okay? So now we are all set, right? I can simply do the following, I can say table is dict.from keys, string.punctuation. One shot.

320
00:49:04.960 --> 00:49:12.540
Faculty (Olympus): Right? What I have done here with this, you know, I'm simply using multiple things that we have learned today. Dick.farm keys takes

321
00:49:13.720 --> 00:49:21.659
Faculty (Olympus): some iterable, and it will set by default the default value for the dictionary to be none. So when I do this table, I will get all the string character

322
00:49:21.900 --> 00:49:25.830
Faculty (Olympus): you know, string punctuation follows. Each one of these will be mapped

323
00:49:26.370 --> 00:49:39.240
Faculty (Olympus): Right? Into a key, so I'll get key for each of these characters. Any sequence here will work, and in particular, this is a string, and so it is also a sequence, and when you iterate over a string, it'll iterate over every character in the string.

324
00:49:39.300 --> 00:49:49.399
Faculty (Olympus): Okay, so this will give me a table with every element being the punctuation. So let me, again, split this, since many of you may be a bit confused.

325
00:49:49.650 --> 00:49:51.849
Faculty (Olympus): So if I run this, this is what I get.

326
00:49:53.850 --> 00:50:05.479
Faculty (Olympus): So notice this is much simpler for me to type. I don't have to do all of this, you know. Remember, all of this I had to type? It's annoying to type all this. I can make mistakes. This is so much easier.

327
00:50:10.300 --> 00:50:18.620
Kapil Shailesh Inamdar .: Okay. Sir, one question, where have you mentioned that its output would be none, or is it default behavior?

328
00:50:18.620 --> 00:50:21.710
Faculty (Olympus): From case. From case, default value is none.

329
00:50:21.710 --> 00:50:23.160
Kapil Shailesh Inamdar .: Okay, okay, thank you, sir.

330
00:50:23.710 --> 00:50:24.420
Faculty (Olympus): Okay?

331
00:50:24.530 --> 00:50:38.790
Faculty (Olympus): Now I do para.translate, para.maketrans. I don't need to put this in a separate line, I just say maketrans of this table, and pass it on to para.translate, and now I'm done. Now all punctuation has been written, okay? And notice it's just, like.

332
00:50:39.270 --> 00:50:42.230
Faculty (Olympus): Three lines of code, right? If you know what you're doing.

333
00:50:43.670 --> 00:50:49.510
Faculty (Olympus): Okay, so now I'm going to give you an exercise, which I would like you to do now, and I'll answer any questions.

334
00:50:49.660 --> 00:50:59.120
Faculty (Olympus): take the text file provided in, Alistar takes it. This is a fullâ€¦ this is a full novel, okay? This is the full novel by Lewis Carroll, Alice in Wonderland.

335
00:50:59.450 --> 00:51:06.510
Faculty (Olympus): Cleanâ€¦ read the entire novel, clean up the data of punctuation, normalize the white space to a single space.

336
00:51:06.620 --> 00:51:08.510
Faculty (Olympus): Do a full word count.

337
00:51:08.690 --> 00:51:10.910
Faculty (Olympus): Show the top 10 words in the text.

338
00:51:11.040 --> 00:51:20.809
Faculty (Olympus): Okay, and ideally, you can also show a histogram of the top words, and you can also answer the question immediately, what is the longest word in the book? Okay? So, please try this.

339
00:51:21.120 --> 00:51:27.590
Faculty (Olympus): You may notâ€¦ at least first 3 items, sorry, 1, 2, 3, 4.

340
00:51:28.600 --> 00:51:35.609
Faculty (Olympus): Right? Try these. I've already given you the code, it's just putting them together, okay? So try this now, and I'll answer any questions.

341
00:51:40.490 --> 00:51:41.680
Faculty (Olympus): No questions?

342
00:51:43.570 --> 00:51:50.509
Siddharth Digambar Kulkarni .: Do we have to import that para, para, or it is already available? Do you have to import it? No.

343
00:51:50.510 --> 00:51:52.230
Faculty (Olympus): What is important? I don't understand.

344
00:51:52.230 --> 00:51:56.239
Siddharth Digambar Kulkarni .: No, the Para is already available, this para.

345
00:51:56.240 --> 00:52:00.759
Faculty (Olympus): is just a single paragraph. I'm asking you to read the entire novel. I don't want you to just do the paragraph.

346
00:52:00.760 --> 00:52:05.530
Siddharth Digambar Kulkarni .: Okay, para is the, you have, saved it as para.

347
00:52:05.790 --> 00:52:07.519
Faculty (Olympus): It's there in your notebook. Are you using the notebook?

348
00:52:07.520 --> 00:52:08.770
Siddharth Digambar Kulkarni .: Exactly. Okay, pill, pill, pill.

349
00:52:08.770 --> 00:52:13.800
Faculty (Olympus): Right? I've literally cut this out from that and put it here in triple quotes.

350
00:52:15.740 --> 00:52:18.970
Faculty (Olympus): I don't want you to operate on Thaa, I want you to operate on the full novel.

351
00:52:19.640 --> 00:52:26.149
Faculty (Olympus): And I want toâ€¦ the power of this is that when you do this, you'll realize that, oh, reading a full novel in Python is, like.

352
00:52:26.990 --> 00:52:29.450
Faculty (Olympus): Not even a second Done.

353
00:52:30.040 --> 00:52:32.569
Faculty (Olympus): And then you can do statistical analysis of these.

354
00:52:33.050 --> 00:52:35.890
Faculty (Olympus): We can do lots of interesting things with this exercise.

355
00:52:48.660 --> 00:52:55.540
Faculty (Olympus): Okay, you want me to give you a few minutes to do this exercise now, or you want to do this as homework, and then I just move on?

356
00:52:58.350 --> 00:52:59.460
Faculty (Olympus): Dr. Nayak?

357
00:53:00.770 --> 00:53:03.759
Siddharth Digambar Kulkarni .: Part of the homework, sir? Is it part of the homework, orâ€¦

358
00:53:03.760 --> 00:53:18.259
Faculty (Olympus): Not yet. I mean, we've not shared any homework yet, right? So, if you want it, we'll put it as real anyway, make it part of homework, but if you want to try it now, you know, maybe it will help you understand, or you're confused, you can ask me some questions. That's the reason we want you to do exercises.

359
00:53:31.350 --> 00:53:40.280
Faculty (Olympus): But do you at least understand how you can do this? This one notebook has covered a lot of ground, but I think you should at least be able toâ€¦ each of these steps is easy, right?

360
00:53:40.510 --> 00:53:46.220
Soumen Deb .: So, one question, though. So, what do you mean by normalize the white texture?

361
00:53:46.220 --> 00:53:49.409
Faculty (Olympus): I mean, convert all white space to a single space.

362
00:53:49.700 --> 00:53:50.860
Soumen Deb .: Okay, fine, thanks.

363
00:53:50.860 --> 00:53:55.950
Faculty (Olympus): Right? Remove all the punctuation. Then, if you see any white space, make it into a single space.

364
00:54:01.870 --> 00:54:09.529
Faculty (Olympus): As in, see, there may be new line, there might be, tab, there will be, you know, just make it into a single space.

365
00:54:11.280 --> 00:54:17.980
Faculty (Olympus): And anyway, when you do split of the words, even if you have multiple spaces, that's gone, right?

366
00:54:18.330 --> 00:54:20.280
Faculty (Olympus): In principle, you don't even have to do

367
00:54:20.550 --> 00:54:26.439
Faculty (Olympus): You canâ€¦ if you don't want to do three, don't do 3, it's fine. Doesn't hurt, because you're going to split the words anyway.

368
00:54:27.290 --> 00:54:29.660
Faculty (Olympus): And when you split, it's going to remove whitespace.

369
00:54:35.090 --> 00:54:38.299
Faculty (Olympus): But I put it in here for a reason, because when you do this.

370
00:54:38.750 --> 00:54:41.460
Faculty (Olympus): I want you to finish this, and then do this.

371
00:54:41.900 --> 00:54:46.149
Faculty (Olympus): Right, so you understand that you can do multiple levels of processing.

372
00:55:04.370 --> 00:55:13.429
Gaurav Singh .: Professor Lick, the white space, you are expecting that after splitting, we will do this, strip, or, in the actual.

373
00:55:13.430 --> 00:55:14.210
Faculty (Olympus): No.

374
00:55:15.060 --> 00:55:19.760
Faculty (Olympus): See, if you split with multiple lines, for example.

375
00:55:27.210 --> 00:55:29.769
Faculty (Olympus): It'll still split it, so you don'tâ€¦ don't worry about them.

376
00:55:31.350 --> 00:55:37.530
Faculty (Olympus): Basically, what I'm saying is, if you have any white space character, replace it with a single space, so you don't need to have

377
00:55:37.640 --> 00:55:43.229
Faculty (Olympus): You know, there are all kinds of other whitespace characters, slash slash R, slash N, slashâ€¦

378
00:55:43.230 --> 00:55:43.780
Gaurav Singh .: Oh, God.

379
00:55:43.780 --> 00:55:47.960
Faculty (Olympus): T, all of those, right, really convert into one single space.

380
00:55:49.390 --> 00:55:55.690
Faculty (Olympus): You don't need it, I'm just forcing you to do this so that you understand you can do multiple levels of

381
00:55:55.970 --> 00:55:57.679
Faculty (Olympus): These kind of changes.

382
00:55:58.200 --> 00:56:06.350
Faculty (Olympus): And please don't delete the white space, so they are two different things. I'm asking you to delete the punctuation, right? And here, I'm asking you toâ€¦

383
00:56:06.800 --> 00:56:08.010
Faculty (Olympus): Replaceâ€¦

384
00:56:08.920 --> 00:56:18.560
Faculty (Olympus): Any white space? By single space. If you remove the white space, then you will not be able to split anything at all. You'll get one giganticâ€¦ the whole novel will be one word. You don't want that.

385
00:56:47.780 --> 00:56:51.380
Faculty (Olympus): Okay, is anyone done? If you have done, can you raise your thumb?

386
00:56:53.570 --> 00:57:00.409
Faculty (Olympus): I mean, I don't mean the whole list, at least 1, 2, 3, 4, and 5.

387
00:57:00.950 --> 00:57:03.109
Faculty (Olympus): Okay, great. Very good.

388
00:57:05.340 --> 00:57:10.299
Rahul Joshi .: So, just one question. Whenever we are replacing the punctuations, it is adding a skip end.

389
00:57:12.110 --> 00:57:12.860
Faculty (Olympus): No.

390
00:57:14.010 --> 00:57:17.489
Rahul Joshi .: is what, They skip and, like.

391
00:57:17.660 --> 00:57:19.319
Rahul Joshi .: Anwar did, if you don't mind, yeah.

392
00:57:20.200 --> 00:57:22.740
Faculty (Olympus): Where? Where did it replace anything with escape?

393
00:57:25.750 --> 00:57:27.230
Rahul Joshi .: You can just stay here, this one.

394
00:57:28.750 --> 00:57:29.700
Faculty (Olympus): No.

395
00:57:29.810 --> 00:57:31.620
Faculty (Olympus): That is already there in the original.

396
00:57:31.940 --> 00:57:34.249
Rahul Joshi .: Oh, that is already there in the final PK, sorry.

397
00:57:34.990 --> 00:57:41.810
Faculty (Olympus): Yeah, so you notice there's a new line here, there's a new line here, you knowâ€¦ Yep.

398
00:57:53.680 --> 00:57:58.710
Faculty (Olympus): Okay, soâ€¦ is everybody at least comfortable with this solving problems like this?

399
00:58:00.420 --> 00:58:03.100
Faculty (Olympus): Should I quickly do the solution, and then we can move on?

400
00:58:05.020 --> 00:58:05.870
Abhineet Bansal: Yes, sir.

401
00:58:05.870 --> 00:58:12.080
Faculty (Olympus): Okay, great. So, I'll just quickly type something out. So, withâ€¦ Hopangâ€¦

402
00:58:23.260 --> 00:58:24.659
Faculty (Olympus): Right, so now I'm done.

403
00:58:24.820 --> 00:58:28.389
Faculty (Olympus): Now, I can just doâ€¦ The same thing.

404
00:58:28.560 --> 00:58:38.819
Faculty (Olympus): The airport isâ€¦ stolenâ€¦ Fituation in that.

405
00:58:40.280 --> 00:58:42.290
Faculty (Olympus): Dick.front, please.

406
00:58:44.270 --> 00:58:55.360
Faculty (Olympus): string dot punctuationâ€¦ It's moved.

407
00:58:59.970 --> 00:59:04.370
Faculty (Olympus): Opening balanceâ€¦ Boom.

408
00:59:06.480 --> 00:59:12.820
Faculty (Olympus): Then, the next step would beâ€¦ Ohâ€¦ Another table.

409
00:59:13.610 --> 00:59:17.389
Faculty (Olympus): White space table will be dictored from this.

410
00:59:19.350 --> 00:59:23.630
Faculty (Olympus): It's been botâ€¦ It's news.

411
00:59:24.190 --> 00:59:31.859
Faculty (Olympus): Singhal in spaceâ€¦ Text is, text, translate, so notice I'm clobbering the same text.

412
00:59:32.270 --> 00:59:43.970
Faculty (Olympus): So every time I do text.translate, it's going to give me a new text, a new bunch ofâ€¦ a new string, which I'm assigning back to text. So that old string is gone, there's a new string that's going to be created.

413
00:59:44.290 --> 00:59:48.510
Faculty (Olympus): So, L, W, S Tâ€¦

414
00:59:55.240 --> 00:59:56.060
Faculty (Olympus): suck.

415
01:00:04.890 --> 01:00:07.220
Faculty (Olympus): Okay, I didn't make a mistake, that is amazing.

416
01:00:07.700 --> 01:00:08.520
Faculty (Olympus): Oops.

417
01:00:10.500 --> 01:00:12.139
Faculty (Olympus): No.

418
01:00:12.350 --> 01:00:14.089
Faculty (Olympus): Let's do a full word count.

419
01:00:15.570 --> 01:00:20.239
Faculty (Olympus): How do you do a film card count? So, text. How do you do a film card count?

420
01:00:20.810 --> 01:00:23.690
Siddharth Digambar Kulkarni .: Length of, no, radio gun.

421
01:00:23.690 --> 01:00:27.510
Faculty (Olympus): So can't you land.

422
01:00:35.770 --> 01:00:49.049
Faculty (Olympus): Right? Now, how do I look at the first top 10 words? It's a bit tricky, okay? So I've not told you how you can do this, but if you were to just look atâ€¦ so letâ€¦ oh, I now have to run the actual analysis, which is our same old thing that we did here.

423
01:00:49.740 --> 01:01:05.089
Faculty (Olympus): So I can say data isâ€¦ Day 4â€¦ Word in text.splitâ€¦ Word and data, data, wordâ€¦

424
01:01:05.930 --> 01:01:11.960
Faculty (Olympus): Let's take a long spaceâ€¦ Wait a lotâ€¦

425
01:01:13.900 --> 01:01:15.449
Faculty (Olympus): Okay, so now this is allâ€¦

426
01:01:18.060 --> 01:01:21.900
Savalo Naroji: The other thingâ€¦ Instead of it, we can use that default as well, right?

427
01:01:21.900 --> 01:01:22.670
Faculty (Olympus): Sonu?

428
01:01:22.830 --> 01:01:25.899
Savalo Naroji: The diffâ€¦ set default to 0, and thenâ€¦

429
01:01:26.270 --> 01:01:27.050
Faculty (Olympus): Yes.

430
01:01:27.500 --> 01:01:31.240
Faculty (Olympus): Yeah, there are hundreds of ways of doing this. The simple thing I'm doing.

431
01:01:31.470 --> 01:01:32.960
Faculty (Olympus): Want to keep it simple.

432
01:01:33.270 --> 01:01:35.099
Faculty (Olympus): There are many ways of doing this.

433
01:01:36.550 --> 01:01:38.160
Faculty (Olympus): Can you set default option?

434
01:01:38.590 --> 01:01:46.389
Faculty (Olympus): Okay, soâ€¦ Now, notice, this tells meâ€¦ Full word count.

435
01:01:46.670 --> 01:01:49.779
Faculty (Olympus): This actually tells me the number of unique words there are in this.

436
01:01:50.510 --> 01:01:52.080
Faculty (Olympus): 315.

437
01:01:53.840 --> 01:01:54.819
Faculty (Olympus): Oh, God.

438
01:01:57.050 --> 01:02:00.880
Faculty (Olympus): Yeah, now if I were to look at all the keys, it'll tell me this, yeah?

439
01:02:05.640 --> 01:02:08.429
Faculty (Olympus): Now, this is a mess, right? How do I offend the top 10?

440
01:02:11.800 --> 01:02:13.179
Gaurav Singh .: Choprape value.

441
01:02:13.180 --> 01:02:15.340
Abhineet Bansal: We can sort them and then take the document.

442
01:02:15.340 --> 01:02:17.520
Faculty (Olympus): Okay, so how do you do sorting?

443
01:02:19.240 --> 01:02:22.680
varun kumar .: If we get the values of each keys, and thenâ€¦

444
01:02:22.680 --> 01:02:23.400
Faculty (Olympus): Boom.

445
01:02:23.910 --> 01:02:24.830
varun kumar .: Sort it and get.

446
01:02:24.830 --> 01:02:27.080
Faculty (Olympus): So there's a built-in called Sorted.

447
01:02:27.750 --> 01:02:32.539
Faculty (Olympus): Yeah, we shouldn't do this. Oh boy, this is a mess, right? So, how do you do this?

448
01:02:32.730 --> 01:02:34.089
Faculty (Olympus): How do you tell me?

449
01:02:34.620 --> 01:02:37.550
Faculty (Olympus): Ohâ€¦ Chopravendous.

450
01:02:38.750 --> 01:02:40.870
Faculty (Olympus): 3,001 values would be printed.

451
01:02:41.290 --> 01:02:46.159
Faculty (Olympus): How do you tell meâ€¦ how do youâ€¦ how do you tell me the topâ€¦ top 10 words?

452
01:02:46.360 --> 01:02:48.029
Gaurav Singh .: In the spot, there is aâ€¦

453
01:02:48.030 --> 01:02:50.000
Apurva Jain .: When it comes to the argument.

454
01:02:50.050 --> 01:02:52.370
Gaurav Singh .: Where we can pass a function.

455
01:02:52.370 --> 01:02:54.539
Faculty (Olympus): Yeah, yeah. So, Gaurav is an expert.

456
01:03:00.000 --> 01:03:01.820
Faculty (Olympus): Without sorting, how would you do this?

457
01:03:08.220 --> 01:03:10.880
Soumen Deb .: Iterate and then create another dictionary.

458
01:03:11.210 --> 01:03:13.819
Faculty (Olympus): You can. Okay, that's one way of doing it.

459
01:03:14.120 --> 01:03:15.400
Faculty (Olympus): Any other ways?

460
01:03:20.620 --> 01:03:24.420
Faculty (Olympus): So, first thing is, say theâ€¦ Sorry? Sorry?

461
01:03:24.420 --> 01:03:25.700
Apurva Jain .: Dota histogram.

462
01:03:25.950 --> 01:03:28.439
Faculty (Olympus): You can plot a histogram, sure, you can do that.

463
01:03:30.660 --> 01:03:33.570
Siddharth Digambar Kulkarni .: Read the dictionary according to the values.

464
01:03:34.930 --> 01:03:38.389
Rahul Joshi .: Do the PMF and say, the cumulative?

465
01:03:38.530 --> 01:03:46.160
Faculty (Olympus): Oh, both complicated. So you canâ€¦ so there are multiple ways to do this. So one way is, you look at all the words.

466
01:03:46.400 --> 01:03:51.420
Faculty (Olympus): You can create a dictionary, Having, you know, keys as a list.

467
01:03:52.120 --> 01:03:56.500
Faculty (Olympus): And then, for every value that you find, you iterate over the dictionary.

468
01:03:56.930 --> 01:03:59.689
Faculty (Olympus): So then you create a reverse dictionary.

469
01:03:59.860 --> 01:04:02.509
Faculty (Olympus): It has values and a list of possible keys.

470
01:04:04.120 --> 01:04:06.169
Gaurav Singh .: But values can match, right?

471
01:04:06.170 --> 01:04:07.920
Faculty (Olympus): Yeah, so you'll add them to a list.

472
01:04:08.110 --> 01:04:27.699
Faculty (Olympus): So you can basically have a list, and then you can have that. So there are many ways to do this, right? But sorted is actually very powerful, and so now that Gaurav has mentioned it, I might as well tell you how to do this. So sorted will sort any iterable, which means anything you can do a for loop over, it can iterate over, okay?

473
01:04:28.040 --> 01:04:40.769
Faculty (Olympus): And then, it has this special argument called key, okay? So, what this does is it always returns a new risk containing all items from the iterable in ascending order, okay? If you say reverse is true, it will do it in descending order.

474
01:04:40.770 --> 01:04:51.090
Faculty (Olympus): Okay, so this is the first simple thing that you can keep in mind, okay? So if I give it sorted, and say 10, 1, 2, 3, 5â€¦

475
01:04:52.630 --> 01:04:54.539
Faculty (Olympus): So I shouldn't have on this side.

476
01:04:57.300 --> 01:05:00.290
Faculty (Olympus): It'll give me a nice sorted list. If I say reverse is true.

477
01:05:03.630 --> 01:05:07.419
Faculty (Olympus): It'll give me the opposite problem, okay? That's the first easy thing.

478
01:05:07.590 --> 01:05:11.069
Faculty (Olympus): The second one is a tricky one. This is a key, okay?

479
01:05:11.720 --> 01:05:16.900
Faculty (Olympus): A custom key function can be supplied to customize the sort order

480
01:05:17.130 --> 01:05:25.919
Faculty (Olympus): Okay? So what does this mean? So how do you decide how to sort? You have to supply a key, and you need to know what is to be passed to the

481
01:05:26.100 --> 01:05:32.559
Faculty (Olympus): To the key, okay? So, how would youâ€¦ what should the customized key be?

482
01:05:33.180 --> 01:05:34.229
Siddharth Digambar Kulkarni .: The values of theâ€¦

483
01:05:34.230 --> 01:05:35.140
Gaurav Singh .: value.

484
01:05:36.730 --> 01:05:37.620
Siddharth Digambar Kulkarni .: Values of the.

485
01:05:38.790 --> 01:05:50.650
Faculty (Olympus): Correct. So, all you need to do is, you need to say, okay, sort this usingâ€¦ so you don't have to do any major complicated logic. Your key function will have to be a function. The function will be given the value.

486
01:05:50.840 --> 01:05:55.620
Faculty (Olympus): Okay? And then once you give it the value, you need to,

487
01:05:55.830 --> 01:06:00.110
Faculty (Olympus): The function will take a value, and it should return something with which that fellow can do the sorting.

488
01:06:01.140 --> 01:06:06.769
Faculty (Olympus): Is that clear? So here, in our case, it's not so straightforward, right? Because we have a dictionary.

489
01:06:07.420 --> 01:06:09.990
Faculty (Olympus): Right? Our data is a dictionary.

490
01:06:10.180 --> 01:06:12.359
Faculty (Olympus): How do you sort a dictionary in this case?

491
01:06:12.560 --> 01:06:19.659
Faculty (Olympus): So what you can do is, very simply, you can say, sorted, Let's say data.items.

492
01:06:21.330 --> 01:06:27.159
Faculty (Olympus): what do data.items be? It'll be key-value pairs, and I want the key-value pairs because I want to associate which is what.

493
01:06:27.640 --> 01:06:28.750
Faculty (Olympus): Does that make sense?

494
01:06:29.430 --> 01:06:42.939
Faculty (Olympus): So I want to know what key and what the values, and I want to keep them together. If I now take the keys separately and the values separately, I lose that association between them. By making them into items, I basically have them as pairs, always as pairs, okay?

495
01:06:42.960 --> 01:06:52.889
Faculty (Olympus): But now there's a tricky problem. How do I sort a tuple containing two elements? One is a string, the other fellow is this. In fact, I don't want to sort on the string. I want to sort only on the value.

496
01:06:53.230 --> 01:06:54.030
Faculty (Olympus): Nate?

497
01:06:56.090 --> 01:07:01.079
Faculty (Olympus): Does that make sense? And I want to reverse sorting. I want the top 10 elements, the most frequently used words.

498
01:07:01.180 --> 01:07:18.570
Faculty (Olympus): So now you can say, passkey. Key has to be a keyword argument in this case, because it follows a star, and now I can give it a lambda function. I don't need to give a lambda, but I can do a lambda. Now, you must have studied well for the exam, so you know lambdas. So now I will give you an item.

499
01:07:19.580 --> 01:07:25.510
Faculty (Olympus): So, this lambda is going to take an item. I simply need to return what you want to sort by. So, I can simply say.

500
01:07:26.080 --> 01:07:26.690
Faculty (Olympus): off.

501
01:07:26.690 --> 01:07:27.380
Siddharth Digambar Kulkarni .: Item 1.

502
01:07:27.380 --> 01:07:28.000
Faculty (Olympus): One.

503
01:07:28.340 --> 01:07:33.379
Faculty (Olympus): What does this mean? So, every value that is going to come to the sorted fellow is going to be a tuple.

504
01:07:33.540 --> 01:07:37.299
Faculty (Olympus): In that tuple, the first element is the key, the second element is the

505
01:07:37.690 --> 01:07:42.089
Faculty (Olympus): Value. I simply want to sort on the value. So that's all it takes.

506
01:07:42.720 --> 01:07:44.860
Faculty (Olympus): And of course, I must say reverse is true.

507
01:07:47.560 --> 01:07:54.869
Faculty (Olympus): Done. Job done. Okay? And now if I read theâ€¦ okay, scroll up a lot. Those are 3,000 fellows.

508
01:07:55.110 --> 01:07:59.559
Faculty (Olympus): Right? I getâ€¦ The is the most commonly used.

509
01:07:59.990 --> 01:08:01.139
Faculty (Olympus): By a long way.

510
01:08:02.250 --> 01:08:12.749
Faculty (Olympus): Right? But notice this is just one single line. Oh, and I can just say, show me the top 10. I will simply say, how do I show the first top 10 of elements of the result?

511
01:08:13.520 --> 01:08:14.450
Siddharth Digambar Kulkarni .: One, two, two.

512
01:08:14.450 --> 01:08:15.380
Soumen Deb .: We're split.

513
01:08:15.380 --> 01:08:16.790
Siddharth Digambar Kulkarni .: Yeah, yeah.

514
01:08:16.790 --> 01:08:17.330
Soumen Deb .: Got it, yeah.

515
01:08:17.330 --> 01:08:17.640
Gaurav Singh .: Yeah.

516
01:08:17.649 --> 01:08:27.959
Faculty (Olympus): So notice how the building blocks that we have introduced so far, simple, simple things, together when you put them, you can do a lot of very powerful things. Just simple slicing is all we've done.

517
01:08:28.769 --> 01:08:35.279
Faculty (Olympus): Okay, and it's just very few lines of code, and we've basically looked at the entire Alice in Wonderland, cleaned it up.

518
01:08:35.749 --> 01:08:42.799
Faculty (Olympus): you know, look through the whole things, figure this out. In fact, there's an easier, even easier way to do this, but I wanted to show you this withâ€¦

519
01:08:42.929 --> 01:08:51.859
Faculty (Olympus): the basic building blocks that we've introduced so far. Okay, so these are the top 10 words, and Alice is among them, apart from all these,

520
01:08:52.089 --> 01:08:53.659
Faculty (Olympus): Prepositions, you know?

521
01:08:53.929 --> 01:08:59.649
Faculty (Olympus): IE and Dallas is very high up. Even if you want to look at the top 20, It's nice.

522
01:09:00.729 --> 01:09:01.489
Faculty (Olympus): Good.

523
01:09:02.109 --> 01:09:07.629
Faculty (Olympus): Alright, so Rahul, now you can do histogram and other things, it's all easy stuff, right? Okay.

524
01:09:08.529 --> 01:09:13.240
Rahul Joshi .: So, just one quick question. In that, sorting function which you passed.

525
01:09:13.240 --> 01:09:13.590
Faculty (Olympus): Yes.

526
01:09:13.810 --> 01:09:20.579
Rahul Joshi .: You, you sorted, you passed a function, with the item 1, but how theâ€¦

527
01:09:20.580 --> 01:09:29.729
Faculty (Olympus): No, no, no, no, no, no, I passed. So key is a function. So in this case, I've created a lambda function, which takes a single argument, which is the item that is being looked at.

528
01:09:30.090 --> 01:09:35.119
Faculty (Olympus): That items, I simply look at the expression item of 1, which means this is the

529
01:09:35.470 --> 01:09:37.930
Faculty (Olympus): This is the thing that I wanted to sort on.

530
01:09:38.540 --> 01:09:41.060
Faculty (Olympus): So it looks at the second element of the tuple and sorts.

531
01:09:41.220 --> 01:09:48.450
Rahul Joshi .: Sorry, justâ€¦ so this item which is passed to the function, how it is associated with the items which are in the first argument?

532
01:09:49.120 --> 01:09:55.689
Faculty (Olympus): There's no association. So, basically, every item, so sorted basically takes everything in this sequence. Each element is a two-tuple.

533
01:09:56.220 --> 01:10:15.279
Faculty (Olympus): So it retains those two tuples as they are, and it's going to sort those. How does it sort those? By giving the key. So the key will be the second element. So basically, what you're saying is, sort this set of tuples, I have this set of tuples, sort them based on the second value. And now you're telling the sorted function, hey, don't sort based on this tuple itself.

534
01:10:16.280 --> 01:10:22.500
Faculty (Olympus): Take each element of the tuple, but only sort on the Second element of this talk.

535
01:10:22.670 --> 01:10:30.050
Faculty (Olympus): That's what this function is doing. So, given the item that is being sorted, considered, look at the second element and use that to do the sorting.

536
01:10:31.130 --> 01:10:32.569
Faculty (Olympus): That's why it's called key.

537
01:10:32.720 --> 01:10:35.670
Faculty (Olympus): It tells you the key on which the sorting is performed.

538
01:10:36.400 --> 01:10:41.090
Faculty (Olympus): And by the way, this key is not the same as your dictionary key. Don't get confused by that key.

539
01:10:41.530 --> 01:10:46.810
Faculty (Olympus): The key argument here to sort it is nothing to do with dictionaries, okay? It's a custom key function.

540
01:10:47.410 --> 01:10:49.969
Faculty (Olympus): Okay, which customizes the sorting order.

541
01:10:50.580 --> 01:10:53.989
Faculty (Olympus): So, for example, if you wanted to say, no, no, no, I don't want to sort like this.

542
01:10:54.530 --> 01:10:56.889
Faculty (Olympus): I want to sort on the length of the key.

543
01:10:58.340 --> 01:10:59.470
Faculty (Olympus): I can do this.

544
01:11:00.760 --> 01:11:03.039
Faculty (Olympus): And make this stand, so you can click this.

545
01:11:05.380 --> 01:11:08.039
Faculty (Olympus): So this is the longest word in the book.

546
01:11:08.270 --> 01:11:09.549
Faculty (Olympus): Does this make sense?

547
01:11:10.130 --> 01:11:14.089
Faculty (Olympus): And notice this is extremely powerful, because I don't need to do much.

548
01:11:17.380 --> 01:11:22.249
Siddharth Digambar Kulkarni .: So you can even write lambda XY and colon Y, right?

549
01:11:22.250 --> 01:11:22.800
Faculty (Olympus): Yep.

550
01:11:24.090 --> 01:11:26.439
Faculty (Olympus): No.

551
01:11:28.070 --> 01:11:33.140
Faculty (Olympus): Nambda XY colon Y. I don't know if it will expand it out. No, it won't do that.

552
01:11:33.140 --> 01:11:34.010
Gaurav Singh .: oneâ€¦ oneâ€¦

553
01:11:34.010 --> 01:11:35.820
Faculty (Olympus): It expects only one argument, so you.

554
01:11:35.820 --> 01:11:36.730
Gaurav Singh .: argument.

555
01:11:36.730 --> 01:11:40.760
Faculty (Olympus): Yeah, you can't do that then. You'll only get that single element.

556
01:11:42.960 --> 01:11:49.289
Faculty (Olympus): And you can't do assignments here, so you have to do explicitly whatâ€¦ you can't do an assignment statement inside a Lambda function.

557
01:11:49.450 --> 01:11:52.309
Siddharth Digambar Kulkarni .: So, lambda takes just one argument.

558
01:11:54.750 --> 01:11:59.700
Faculty (Olympus): The key function takes only one argument. The lambda can take anything. Lambda is just a way to create the function.

559
01:12:00.270 --> 01:12:01.469
Siddharth Digambar Kulkarni .: Okay, okay, okay.

560
01:12:01.470 --> 01:12:06.390
Faculty (Olympus): The key function takes a single argument of the element that isâ€¦ they're trying to consider, or sort.

561
01:12:06.900 --> 01:12:07.719
Siddharth Digambar Kulkarni .: Okay, okay.

562
01:12:09.920 --> 01:12:11.100
Yashi Agarwal .: Ramon?

563
01:12:11.100 --> 01:12:12.390
varun kumar .: It's always a function.

564
01:12:13.430 --> 01:12:20.239
Rahul Joshi .: Yeah, so, keep in mind, I'm a little confused, sir. This, data.items returns theâ€¦ all the tuples, right?

565
01:12:20.240 --> 01:12:20.950
Faculty (Olympus): Yes.

566
01:12:21.180 --> 01:12:21.770
Faculty (Olympus): Yes.

567
01:12:21.960 --> 01:12:24.560
Rahul Joshi .: So, so this data.items,

568
01:12:24.560 --> 01:12:27.090
Faculty (Olympus): Show your items. We had items somewhere here, yeah.

569
01:12:29.110 --> 01:12:29.850
Faculty (Olympus): Yup.

570
01:12:31.240 --> 01:12:36.840
Rahul Joshi .: Yeah, so this data.items returns a tuple, and then in the function, you are passing item.

571
01:12:38.090 --> 01:12:47.390
Faculty (Olympus): I am not passing. It is, it is calling a function. Key function is given the value. So, if I give you a set of values, I give you a set of values, and I say, sort these elements.

572
01:12:47.590 --> 01:12:51.869
Faculty (Olympus): These elements can be anything, right? It could be a dictionary, it could beâ€¦ in this case, it's a tuple.

573
01:12:52.050 --> 01:12:52.730
Rahul Joshi .: Yep.

574
01:12:52.950 --> 01:12:54.189
Faculty (Olympus): How do you sort them?

575
01:12:54.400 --> 01:12:56.249
Faculty (Olympus): If I just give you numbers, it's easy.

576
01:12:56.430 --> 01:13:09.330
Faculty (Olympus): But it may not be a number. So the key is something that allows you to generalize the sorting. That basically says, hey, you can supply some function, that function you do whatever, you return whatever you want to sort by in that function. So this function

577
01:13:09.830 --> 01:13:15.579
Faculty (Olympus): is given, each item Each item here is pulled out from this.

578
01:13:17.150 --> 01:13:19.829
Faculty (Olympus): Maybe I shouldn't call this item. Let me call this X.

579
01:13:20.210 --> 01:13:21.829
Rahul Joshi .: Okay, now I got it here.

580
01:13:22.500 --> 01:13:23.959
Faculty (Olympus): Is that even easier for you to understand?

581
01:13:23.960 --> 01:13:25.979
Rahul Joshi .: Yeah, yeah, yeah, it's a variable name, actually.

582
01:13:25.980 --> 01:13:26.680
Faculty (Olympus): Yes.

583
01:13:26.820 --> 01:13:29.889
Faculty (Olympus): It is. I thought that'sâ€¦ I thought that's obvious, but okay.

584
01:13:29.890 --> 01:13:30.350
Rahul Joshi .: Yeah, yeah, soâ€¦

585
01:13:30.350 --> 01:13:34.079
Faculty (Olympus): Because items is just a method, right? This is just some number.

586
01:13:34.620 --> 01:13:35.990
Faculty (Olympus): We have the Samus up.

587
01:13:36.200 --> 01:13:37.210
Faculty (Olympus): Is that okay?

588
01:13:37.390 --> 01:13:38.449
Rahul Joshi .: Perfect, sir, thank you.

589
01:13:39.330 --> 01:13:40.879
Faculty (Olympus): Anybody else with questions?

590
01:13:44.030 --> 01:13:46.699
Faculty (Olympus): Alright, so I didn't want to do sorted, but it'sâ€¦

591
01:13:46.850 --> 01:14:03.750
Faculty (Olympus): Nice, that it ended up being cited. So, I'll stop here with this, text processing material, with just this one comment. So, we have done extremely simple stuff here, okay? If you really want to do very fancy kind of processing with text, the way that we have taken is not the best way. For simple things like this, it works.

592
01:14:03.750 --> 01:14:11.139
Faculty (Olympus): But for other things, you may want to use something called regular expressions, and this is well beyond what we want to cover. We don't want to do regular expressions in this course.

593
01:14:11.140 --> 01:14:26.160
Faculty (Olympus): But if you are really interested in doing this, and you need to do it for your work or something like that, there are some really nice guides. This how-to that is part of Python documentation is very well written, so it has lots of examples, and it walks you through how to use the built-in standard library RE.

594
01:14:26.170 --> 01:14:41.510
Faculty (Olympus): For regular expressions in Python. It sort of shows you examples of various things you can do with it. So you can read this and learn for yourselves if you want to do this. And when you're learning, there's this other website called Pythex, which allows you to, you know, type the regular expression. The regular expression syntax can be a little

595
01:14:41.680 --> 01:14:54.840
Faculty (Olympus): scary, especially when you start doing very complicated regulates. So what this one lets you do is it lets you, you know, write, learn, and debug these verbal expressions very well. So if you're gonna, you know, learn with this, use this website to help people.

596
01:14:54.840 --> 01:15:10.789
Faculty (Olympus): And with that, we stop text processing. This should be enough for doing, you know, feature engineering and whatever small things you need to do. We've now looked at dictionaries, we've looked at sorted, which I didn't plan to do, but it's a very powerful single little function that you can do lots of nice things with.

597
01:15:11.820 --> 01:15:23.130
Faculty (Olympus): Now we will move to Pandas. We have about 20 minutes, 25 minutes. I don't see any questions, so I'm gonna move on to Pandas. This notebook has already been uploaded on the

598
01:15:26.160 --> 01:15:26.889
Faculty (Olympus): Just listen.

599
01:15:27.940 --> 01:15:30.139
Siddharth Digambar Kulkarni .: There'll be homework for this, right, text person.

600
01:15:30.140 --> 01:15:34.490
Faculty (Olympus): But not today. I mean, you have enough stressful things today.

601
01:15:34.590 --> 01:15:40.619
Faculty (Olympus): So, next week, we will give youâ€¦ next week, actually, is very packed, because I have a lot of material to cover.

602
01:15:40.880 --> 01:15:47.489
Faculty (Olympus): So, today we'll start off with pandas, and hopefully by tomorrow I'll finish Pandas. So, what we have left is, we have Pandas.

603
01:15:47.620 --> 01:15:50.929
Faculty (Olympus): And then I have to talk to you about regression, and thenâ€¦

604
01:15:51.260 --> 01:16:09.980
Faculty (Olympus): Yeah, so Pandas, regression, and then we'll discuss scikit-learn in the context of regression, and then start introducing machine learning. So we're basically coming to the end of your, you know, programming stuff, and now we'll start doingâ€¦ once you finish Pandas, you'll be using this to do, you know, look at things like regression.

605
01:16:10.530 --> 01:16:23.429
Faculty (Olympus): So, our first approach to regression is going to be very straightforward. We're not going to look at it from machine learning. I'm going to maybe jump ahead of your stats course, as I've done so far, but don't worry, we'll be covering it in greater detail in stats course.

606
01:16:23.430 --> 01:16:32.529
Faculty (Olympus): But I want to show you the connections between what we have learned with our sampling and probabilistic programming and things like that, with repression, so that we'll do after we finish Piyans.

607
01:16:32.530 --> 01:16:46.519
Faculty (Olympus): So that's why I've asked for a few extra classes. If I finish earlier, I will not have three, but if I require it, I will take all three, okay? And my hope is, I'd rather do the material with you having a few extra classes, rather than, you know, rush through the material and

608
01:16:47.220 --> 01:16:53.180
Faculty (Olympus): leave you uncomfortable. Okay, very quickly, before we start this, Rahul, you have a question?

609
01:16:53.180 --> 01:16:58.949
Rahul Joshi .: Yes, sir. In the dictionary, the keys, can the key be a list itself, or that's not.

610
01:16:58.950 --> 01:17:04.389
Faculty (Olympus): No, it should not be a list, because a list is not what's called a hashable thing, because it's mutable.

611
01:17:04.880 --> 01:17:08.340
Faculty (Olympus): Basically, a key has to be something that's fixed.

612
01:17:08.600 --> 01:17:13.470
Faculty (Olympus): In some sense, fixed. That's why it means it should be able to hash into one unique thing.

613
01:17:13.650 --> 01:17:16.600
Faculty (Olympus): Which means you should be able to convert that into a number.

614
01:17:16.880 --> 01:17:27.970
Faculty (Olympus): So if you have a list, for example, the list can perhaps change and move around, so the hash will change, you know, so you have a problem. So don't use, say, dictionaries or lists. Generally, don't use a mutable object for a key.

615
01:17:28.300 --> 01:17:30.240
Faculty (Olympus): Because anything that's immutable is okay.

616
01:17:30.880 --> 01:17:35.869
Faculty (Olympus): You can try it and see, right? But it's dangerous to do it, even if it does work. I don't think it will work.

617
01:17:38.150 --> 01:17:39.339
Faculty (Olympus): Tuples are okay.

618
01:17:41.510 --> 01:17:42.430
Faculty (Olympus): Soumen?

619
01:17:44.780 --> 01:17:51.510
Soumen Deb .: Sorry, just diagnosing. So, you mentioned a couple of extra classes, right? Will it be tomorrow or something? Just wanted to ask.

620
01:17:51.510 --> 01:17:56.740
Faculty (Olympus): Oh, I thought they've already been announced. Okay, so it's only next week. I will notâ€¦ I will not disturb you.

621
01:17:56.740 --> 01:17:57.280
Soumen Deb .: Oops.

622
01:17:57.280 --> 01:18:00.859
Faculty (Olympus): So after that, you have a one-week break for yourâ€¦ for your mid-sum, right?

623
01:18:01.620 --> 01:18:05.879
Faculty (Olympus): It'll all be finished next week. By next Saturday, we're done. I'll finish everything.

624
01:18:07.080 --> 01:18:10.979
Soumen Deb .: And then thoseâ€¦ those will be part of the mid-Sem, career.

625
01:18:10.980 --> 01:18:14.059
Faculty (Olympus): Oh, yes, that is the idea.

626
01:18:14.060 --> 01:18:21.659
Soumen Deb .: Okay, which means we'll have to rush to get those things done. Because what is happening is the curve is getting, you knowâ€¦ It is getting stiffer.

627
01:18:21.970 --> 01:18:34.689
Faculty (Olympus): It is going to get steeper now, it is going to get very rapidly steep, and then, essentially, I will leave you off at a point when you're, like, saying, okay, I know pandas, I know this, I know that, I know this, and then Profavinay will just say, okay, I assume you know all of this.

628
01:18:34.950 --> 01:18:45.649
Faculty (Olympus): And then he'sâ€¦ he may even askâ€¦ he will definitely ask you to use AI, but the idea is, he will say, when you use AI to generate your code, you own that code, which means you should be able to explain every line of code then.

629
01:18:45.970 --> 01:18:57.609
Faculty (Olympus): Which is why I've been sort of, you know, pushing you guys to learn programming well, so you canâ€¦ if AI spits out code, you're like, it's doing this, it's doing this, it's doing this. That's why we're pushing you to program, okay? Sonu?

630
01:18:59.050 --> 01:19:01.600
varun kumar .: Before that, we have to pass the exam also, sir.

631
01:19:02.070 --> 01:19:13.280
Faculty (Olympus): No, no, you don't have to passâ€¦ I mean, you have to passâ€¦ you have to pass in the final exam, this is intermediate. Okay, can we skip questions that are not related to the text processing material? Can we ask other questions at the end, please?

632
01:19:13.280 --> 01:19:15.969
Sonu Kumar .: Hi, Professor, this is related to dictionary.

633
01:19:16.910 --> 01:19:18.180
Sonu Kumar .: Can I go ahead?

634
01:19:18.180 --> 01:19:18.780
Faculty (Olympus): Yeah.

635
01:19:19.590 --> 01:19:30.019
Sonu Kumar .: Yes, yes, Professor. So, let's say if, we are storing an object in the dictionary, and then we want to do a sorted, that object is sorted, automatically we need to write.

636
01:19:30.020 --> 01:19:37.100
Faculty (Olympus): Yeah, so theâ€¦ so the key here, again, do whatever you want in this key. So the key can be, like, object.method.whatever.

637
01:19:37.280 --> 01:19:39.580
Faculty (Olympus): But that should be legal on this object.

638
01:19:40.600 --> 01:19:43.049
Sonu Kumar .: Okay, so basically we'll have to write some compare logic inside.

639
01:19:43.050 --> 01:19:56.370
Faculty (Olympus): So, for example, here it'sâ€¦ here it'sâ€¦ I have a list, I have a dictionary. Dictionary items will give me tuples, so then you find out whichever element you want to look at, and then do whatever method. You can call methods here. It's any expression here will work.

640
01:19:57.540 --> 01:20:02.799
Faculty (Olympus): Right? I even looked at length. I just said, like, give me the length of the key and sort on the length of the key. Lots of work.

641
01:20:03.490 --> 01:20:04.199
Sonu Kumar .: Okay, yep.

642
01:20:04.540 --> 01:20:09.970
Faculty (Olympus): So it's extremely powerful, that's the thing. The remarkable thing about this sorted is, like, just this one thing.

643
01:20:10.120 --> 01:20:12.649
Faculty (Olympus): You can do all kinds of sorting problems, it's easy.

644
01:20:13.240 --> 01:20:14.130
Faculty (Olympus): And?

645
01:20:14.920 --> 01:20:21.450
Ann G. .: Sir, this may be a knife question, but can we use, NumPy processing with text, processing?

646
01:20:23.620 --> 01:20:31.549
Faculty (Olympus): So, for these sort of things, NumPy, not so much. I mean, NumPy, if you have a pure text file, for example, Alice, you will not be able to read Alice with load text.

647
01:20:32.790 --> 01:20:34.769
Faculty (Olympus): They don't do what you expect.

648
01:20:34.910 --> 01:20:39.220
Faculty (Olympus): NumPy is meant for more structured data that you already know there's a structure to.

649
01:20:40.040 --> 01:20:43.179
Ann G. .: So, structure is difficult with random text.

650
01:20:43.180 --> 01:20:50.970
Faculty (Olympus): Yes, for example, punctuation, how will you remove it? I mean, you'll have to do actual processing. So, in fact, NumPy's own load text is doing all this dirty work for you.

651
01:20:51.370 --> 01:21:03.989
Faculty (Olympus): But Pandas, when you use Pandas to read something, it is actually passing those files, or it's using a library where somebody else has written this form, right? End of the day, so I've shown you building blocks, elementary Python operations, using which you can do something like this.

652
01:21:05.740 --> 01:21:13.639
Ann G. .: So, just toâ€¦ so in the lambda, function that you passed, I wasâ€¦ so I was just wondering, like.

653
01:21:13.930 --> 01:21:19.230
Ann G. .: If we had used Numbai instead, it would just happen in one go instead of, no.

654
01:21:19.230 --> 01:21:20.050
Faculty (Olympus): Bitcoin.

655
01:21:20.400 --> 01:21:29.220
Soumen Deb .: So maybe I'll step in, though. So NumPy also has got a sorted sort method, right? So can we use that? I mean, like, Lambda is.

656
01:21:29.220 --> 01:21:29.660
Faculty (Olympus): fallen.

657
01:21:29.660 --> 01:21:31.040
Soumen Deb .: your core Python limit.

658
01:21:34.070 --> 01:21:34.930
Faculty (Olympus): Okay.

659
01:21:35.290 --> 01:21:38.400
Faculty (Olympus): So, let me look at this, and sayâ€¦

660
01:21:41.920 --> 01:21:43.570
Faculty (Olympus): NPay.sorted.

661
01:21:44.630 --> 01:21:45.660
Faculty (Olympus): Vivek?

662
01:21:46.440 --> 01:21:47.929
Faculty (Olympus): I didn't run this cell, sorry.

663
01:21:48.320 --> 01:21:49.220
Soumen Deb .: Perfect.

664
01:21:50.660 --> 01:21:51.880
Faculty (Olympus): NP.saur.

665
01:21:52.240 --> 01:21:55.750
Faculty (Olympus): So this is going to do things that are nice for NumPy arrays.

666
01:21:55.950 --> 01:22:00.499
Faculty (Olympus): It's not going to do something nice for any arbitrary container that you have.

667
01:22:00.940 --> 01:22:02.859
Faculty (Olympus): Like, it won't work for dictionaries.

668
01:22:05.990 --> 01:22:07.870
Faculty (Olympus): And I don't think it even has a key.

669
01:22:10.870 --> 01:22:15.199
Faculty (Olympus): Does that make sense? So this will not do anything good for this particular problem.

670
01:22:16.160 --> 01:22:18.590
Faculty (Olympus): So, sorted is a very general-purpose thing.

671
01:22:19.280 --> 01:22:21.160
Siddharth Digambar Kulkarni .: Your daughter array, I think.

672
01:22:21.450 --> 01:22:35.139
Faculty (Olympus): Sorry, yeah, this will sort an array, but the nice thing is, this is NumPy-aware. So if you say axis, I want to sort along this axis, that this willâ€¦ so I have a matrix, and I say, I want you to sort along the rows, I want to sort along the columns. This is a headache, right?

673
01:22:35.410 --> 01:22:41.439
Faculty (Olympus): This is very easy to do with NumPy. So NumPy is designed for NumPy arrays. You have an array, you want to do something, you can do that.

674
01:22:43.050 --> 01:22:43.980
Faculty (Olympus): Okay?

675
01:22:44.360 --> 01:22:45.269
Ann G. .: Yes, sir, thank you.

676
01:22:45.270 --> 01:22:58.489
Faculty (Olympus): Yeah, yeah, yeah. So, that's why, so many functions, min, max, all of those functions that are in NumPy, there's also min-max built in. NumPy version will have some NumPy-specific features, and NumPy is designed not for text processing, it's designed for numerical work.

677
01:22:58.490 --> 01:23:06.210
Faculty (Olympus): With numbers, largely. It will let you do strings and stuff like that, but it's not designed as a string processor. It's a toolkit.

678
01:23:08.940 --> 01:23:10.940
Faculty (Olympus): Abhishek, last question.

679
01:23:11.360 --> 01:23:25.750
Abhishek Agrawal .: Thank you, Purth. So, I just observed, like, string.punctuation already has a backslash, included, and then string.whitespace has aâ€¦ all the slash t, slash, and all those things.

680
01:23:25.840 --> 01:23:36.989
Abhishek Agrawal .: So, what I observed is, like, when we do punctuation first, it is removing the backslashes from, like, a new string, a new line, and all those backslashes. It will remove.

681
01:23:37.870 --> 01:23:42.220
Abhishek Agrawal .: So that white space thing will then, instead of flashingâ€¦ No.

682
01:23:42.220 --> 01:23:48.779
Faculty (Olympus): No, no, no, no, slash N is not slash n is not two characters, I'm confusing this. Slash N is the special character, I think it corresponds to the ordinal 10.

683
01:23:48.780 --> 01:23:49.950
Soumen Deb .: Manage a return.

684
01:23:50.320 --> 01:23:52.360
Faculty (Olympus): Barrage return. This is tab.

685
01:23:52.690 --> 01:23:53.980
Faculty (Olympus): That is not Slash.

686
01:23:55.340 --> 01:23:56.010
Abhishek Agrawal .: Okay.

687
01:23:56.190 --> 01:23:57.380
Abhishek Agrawal .: Oh, you'reâ€¦

688
01:23:57.380 --> 01:23:58.480
Faculty (Olympus): direct the automotive.

689
01:23:58.660 --> 01:24:03.449
Abhishek Agrawal .: Yeah, okay, so when I did, read lines, theâ€¦

690
01:24:03.450 --> 01:24:05.760
Faculty (Olympus): 10 is a single character, it's not two characters.

691
01:24:06.310 --> 01:24:11.830
Faculty (Olympus): This fellow removes the slash. There's an actual backslash, C colon backslash, no backslash G.

692
01:24:13.420 --> 01:24:14.100
Abhishek Agrawal .: Okay.

693
01:24:14.300 --> 01:24:15.570
Abhishek Agrawal .: Okay, soâ€¦

694
01:24:16.080 --> 01:24:28.690
Faculty (Olympus): Beware. So this is also dumb, right? This is justâ€¦ it's going to do this. Sometimes you may say, hey, I have a name with a question mark, right? There are African names, you have a punctuation mark in that, right? You have a book like that, you should not do that.

695
01:24:29.650 --> 01:24:35.990
Faculty (Olympus): The click is, for example, a punctuation mark in some Swahili and things like that. So, you know, you can't just remove exclamation mark.

696
01:24:37.480 --> 01:24:39.759
Abhishek Agrawal .: Okay. Okay, let me try, the quota.

697
01:24:39.760 --> 01:24:45.070
Faculty (Olympus): Yeah, so this is a sort of, you know, assuming certain things about the code. It's not universal.

698
01:24:45.430 --> 01:25:00.439
Faculty (Olympus): All right, so let'sâ€¦ I have 15 minutes. I want to start off with Pandas, so that next class is not overloaded. So, Pandas is this veryâ€¦ so we've seenâ€¦ spent a lot of time on NumPy, you know, and you've seen NumPy is very powerful when you're dealing with, arrays.

699
01:25:00.590 --> 01:25:10.260
Faculty (Olympus): But we all know that when you're doing data science and things like that, it's not just a single array of values, you'll typically have many arrays. For example, if you think of your spreadsheet, you'll have

700
01:25:10.280 --> 01:25:23.870
Faculty (Olympus): multiple columns. Maybe you can think of this as a matrix, or maybe you can think of this as, you know, columns, or rows, right? But key here is, supposing you have a spreadsheet that says marks of students in courses.

701
01:25:23.870 --> 01:25:33.280
Faculty (Olympus): We'll have student name, we'll have Mark 1, Mark 2, Mark 3, Mark 4, right? These four marks correspond to the student, which means these arrays, if I were to represent everything as columns.

702
01:25:33.280 --> 01:25:44.129
Faculty (Olympus): You have to keep track that, oh, first fellow is first fellow, second fellow is second fellow, so on and so on, right? So it makes sense to have a data structure that can encapsulate this tabular data, okay?

703
01:25:44.320 --> 01:25:56.400
Faculty (Olympus): So, pandas, one of the main powerful things that we will be talking about in Pandas, there are many things in Pandas, but probably the most powerful data type in Pandas is called the data frame object. Okay, so this is the kind of object.

704
01:25:56.990 --> 01:26:14.350
Faculty (Olympus): That makes it easy to deal with tabular data. So you can think of it as a programmatic way to deal with a spreadsheet, okay? Of course, not an arbitrary spreadsheet with arbitrary things and cells, but at least a usual spreadsheet, you know, where you have multiple columns, like a CSV file, something like that, where you've loaded different things.

705
01:26:14.350 --> 01:26:19.869
Faculty (Olympus): that you can process this on the computer with, you know, Pandas. That's the idea with Pandas.

706
01:26:20.070 --> 01:26:29.850
Faculty (Olympus): Now, once you have this object, it makes it very easy to read, process, and visualize data. All these things can be done very nicely with the Panda slab, so we'll look at this in greater detail.

707
01:26:30.080 --> 01:26:36.929
Faculty (Olympus): For more details, you know, you can read the Panda's docs. This should be HTTPS. I don't know why I didn't put HTTPS.

708
01:26:39.120 --> 01:26:39.960
Faculty (Olympus): Students.

709
01:26:40.370 --> 01:26:41.509
Faculty (Olympus): Look at the docs.

710
01:26:41.650 --> 01:26:53.149
Faculty (Olympus): So, we'll start with our standard imports. The only thing is, I've introduced a new import here. Just like NumPy as MP, we have import Pandas as PD. So, PD is the short form for

711
01:26:53.630 --> 01:26:54.530
Faculty (Olympus): on busing.

712
01:26:58.170 --> 01:27:13.710
Faculty (Olympus): Okay, so again, recap of what I said. Why do we need this? Data is often tabular. So, as I said, class marks in a course or during a program, imagine population with very tight age, etc. And you can think of each student as a row, and each column as an attribute, right, of a typical spreadsheet.

713
01:27:14.020 --> 01:27:22.479
Faculty (Olympus): So, the important thing to keep here is, so this is very important, is that the columns are aligned using the row, right? So, all the columns are aligned using the row.

714
01:27:22.500 --> 01:27:41.419
Faculty (Olympus): So, for example, if you did a sorting or something, you forgot to, you know, sort the whole column, it's a mess, right? You'll be misassociating the marks of one student with something else, if you sorted just one column, right? So, this is exactly the thing that this tabular data structure allows you to do, this data frame data structure.

715
01:27:41.420 --> 01:27:48.589
Faculty (Olympus): So, with pandas, this notion of alignment of multiple different arrays is a central concept, okay?

716
01:27:49.080 --> 01:28:00.790
Faculty (Olympus): And to do this, to, you know, use data frames effectively, you need to understand, actually, 3 data structures, 3 fundamental building blocks in Python. The first is what's called the Pandas Series, PD.series.

717
01:28:01.000 --> 01:28:09.970
Faculty (Olympus): The second is pd.index, and the third is, of course, the Panda's data file itself. Okay, so these are three things, and we'll look at these things systematically in this, notebook.

718
01:28:13.160 --> 01:28:20.389
Faculty (Olympus): So the first thing we look at is series, right? And the idea here is every row you can think of

719
01:28:20.510 --> 01:28:23.090
Faculty (Olympus): As a, as a label.

720
01:28:23.240 --> 01:28:37.970
Faculty (Olympus): Right? And this label are collectively called the index. So, for example, let's say look at our class, right? We have 200 people, or whatever. So, maybe your role number, and the role number may not beâ€¦ I don't know if your role number is alphanumumeric, or is a single number, or whatever, right?

721
01:28:38.580 --> 01:28:43.939
Faculty (Olympus): whether it's alphanumumeric, for example, right? So I don't know what exactly your row number is, but

722
01:28:44.080 --> 01:28:50.450
Faculty (Olympus): Either your role number or your name, some unique number or name.

723
01:28:51.280 --> 01:28:57.670
Faculty (Olympus): You could treat Av as theâ€¦ treat as the label for that particular data entry, like, you know, the roles, students, scores.

724
01:28:58.670 --> 01:29:04.079
Faculty (Olympus): So these are called together, all of these labels together are called the index, okay?

725
01:29:04.320 --> 01:29:14.120
Faculty (Olympus): Now, series is the fundamental building block which ties together an index and a set of values. So you can think of it even as a generalization

726
01:29:14.250 --> 01:29:30.510
Faculty (Olympus): of a dictionary, right? You have keys, and you have values, okay? And so, just like dictionaries, these index values, or these labels, do not have to be contiguous, they don't have to start at zero, none of that, okay? They can even be strings, just like we have for dictionaries, okay?

727
01:29:31.270 --> 01:29:53.469
Faculty (Olympus): Now, very often, you'll find scenarios where this index is actually implicit. So, supposing I just give you our pendulum data, right? I just give you some n values of time period and length, or whatever the data set is. Here, there is no real index. Implicitly, I'm saying the first element is this, second element is this third element. So, which means there's an implicit ordering based on 0, 1, 2, 3, 4, 5, 6, right?

728
01:29:53.470 --> 01:29:56.169
Faculty (Olympus): So, which means the index can also be

729
01:29:56.170 --> 01:29:59.469
Faculty (Olympus): either implicit or explicit. So there are many cases where

730
01:29:59.470 --> 01:30:06.670
Faculty (Olympus): There's an implicit index. In many cases where, say, students with row numbers, there's an explicit index saying the wrong number is my index.

731
01:30:07.860 --> 01:30:17.579
Faculty (Olympus): But the basic idea is the following. Imagine you have an umpire array, and imagine you have this set of labels. A series objects puts these together, so that they are associated with each other.

732
01:30:17.920 --> 01:30:28.900
Faculty (Olympus): So let's look at the first simple example to create one. Here's a series object, and here I create np.random.normal. So I'm creating 5 numbers, which are random here.

733
01:30:28.940 --> 01:30:39.890
Faculty (Olympus): drawn from a normal distribution. So if I were to look at this, immediately notice there is an implicit index here, okay? 0, 1, 2, 3, 4, and these are the actual values.

734
01:30:39.940 --> 01:30:46.209
Faculty (Olympus): If I had just put npandom normal, I'd have just gotten these 1, 2, 3, 4, 5 values, and that would be stored in an umpire array.

735
01:30:46.720 --> 01:30:52.029
Faculty (Olympus): But when you create a series object, there is always this index associated with it, and this tells you there's a data type.

736
01:30:52.500 --> 01:30:54.569
Faculty (Olympus): Now, to look at the actual values.

737
01:30:54.950 --> 01:31:04.300
Faculty (Olympus): You do stn.values in this case, sn is the series, normal numbers. This is a numpyrey, so under the covers, pandas will use numpyres.

738
01:31:04.890 --> 01:31:06.680
Faculty (Olympus): And if I want to look at the index.

739
01:31:06.850 --> 01:31:18.039
Faculty (Olympus): This is a range index, so notice that this is some implicit index. I did not explicitly supply index, okay? And this basically says it starts at 0, goes to 5 in steps of 1, which is exactly what the values are, okay?

740
01:31:21.620 --> 01:31:32.160
Faculty (Olympus): Now, we'll look at a case where I explicitly supply an index. I look at the same thing with different random values, 5 numbers, but here I'm explicitly saying index is this list of A, B, C, D, and D.

741
01:31:32.400 --> 01:31:40.560
Faculty (Olympus): And now, if I looked at this fellow, notice, it is no longer 0, 1, 2, 3, 4, like this, but it is A, D, C, D, A.

742
01:31:40.930 --> 01:31:43.239
Faculty (Olympus): And these are indices, okay?

743
01:31:44.140 --> 01:31:49.920
Faculty (Olympus): Now, if I looked at SN, so notice SN is the implicit index with numbers.

744
01:31:52.240 --> 01:31:56.700
Faculty (Olympus): I now do SN of 0. This will give me the first fellow, which is this guy.

745
01:31:57.150 --> 01:32:02.599
Faculty (Olympus): Is that clear? So, to get the first element of the series, I do SN of 0.

746
01:32:03.430 --> 01:32:06.619
Faculty (Olympus): We want the second element, SN of 1, okay?

747
01:32:07.400 --> 01:32:12.930
Faculty (Olympus): But now, if I did SA of 0, let us see what it does, it'll shout at me.

748
01:32:13.700 --> 01:32:27.639
Faculty (Olympus): It will say, getItem treats keys. GetItem is the way in which you do this. This is actually calling this special method called getItem. It's treating keys as positions is deprecated. In a future version, integer keys will always be treated as labels.

749
01:32:27.640 --> 01:32:36.790
Faculty (Olympus): consistent with data framework, blah blah blah, okay? So don't worry too much about this. We will come back to this in greater detail. Notice that this is giving me a warning. Even though it returns the first element.

750
01:32:36.790 --> 01:32:44.239
Faculty (Olympus): It's saying, I don't like what you did, because there's really no zero here. The correct way to access it is a say of A.

751
01:32:44.490 --> 01:32:46.490
Faculty (Olympus): This is not Ganema. Is that clear?

752
01:32:46.490 --> 01:32:47.400
Rahul Joshi .: Is it here?

753
01:32:47.630 --> 01:32:48.649
Faculty (Olympus): What's say it's this fellow.

754
01:32:51.420 --> 01:32:52.090
Rahul Joshi .: Okay.

755
01:32:52.250 --> 01:33:02.489
Faculty (Olympus): Okay, SN is with numbers, SA is with the alphabet. Okay, I've just given the keys here. Maybe I should have used a better name, butâ€¦ So, SA is the fellow with the,

756
01:33:03.400 --> 01:33:04.959
Faculty (Olympus): Keys being A, B, C, and G.

757
01:33:05.400 --> 01:33:06.549
Rahul Joshi .: Okay, not India.

758
01:33:06.550 --> 01:33:16.009
Faculty (Olympus): Alright? So, the idea here is, notice that even though implicitly this worked and gave me the same result, this is making an assumption that the first element is zero.

759
01:33:16.320 --> 01:33:23.050
Faculty (Olympus): But the correct way to index it is to say A. Okay? Later on, we'll see that there's something called ILOC,

760
01:33:23.490 --> 01:33:26.869
Faculty (Olympus): Okay, which is a accessor toâ€¦

761
01:33:26.970 --> 01:33:43.699
Faculty (Olympus): access this same series using the actual position. So, supposing I give you a spreadsheet, and say student 1, student 2, student 3, I can either refer to, say, row number 30, that student, change the mark, right? Or I can say, Rahul Joshi, mark, change the mark, you understand? So, I can use both of these, but

762
01:33:43.730 --> 01:33:55.410
Faculty (Olympus): when you want to do that thing, you use this accessor called iLoc. We'll come to this later, okay? But for now, just be aware that series objects bundle an index and a set of values.

763
01:33:55.770 --> 01:34:10.129
Faculty (Olympus): the index could be implicit, or could be explicit, okay? And when you access an element, hang on, I'll come to you. You always access it. Typically, when you do this sort of an access with the bracket form, always try to use the label.

764
01:34:10.330 --> 01:34:19.070
Faculty (Olympus): Okay? As in, use any of the indices rather than implicitly counting from zero. Yes, you have a question?

765
01:34:19.440 --> 01:34:29.410
Rahul Joshi .: Sir, is this, label and value is veryâ€¦ especially the label, ABCD in this case, is very synonymous to the primary key of the database record?

766
01:34:30.020 --> 01:34:33.919
Faculty (Olympus): It's sort of like that, but it's not necessarily the same, but you can think of it as that.

767
01:34:36.270 --> 01:34:41.680
Faculty (Olympus): When you do operations, yes, things will be aligned according to your primary index, right? Same thing here.

768
01:34:42.960 --> 01:34:49.380
Faculty (Olympus): If you do a select, Your primary key is going to be associated with each of those indices, right?

769
01:34:51.290 --> 01:34:51.950
Rahul Joshi .: Yep.

770
01:34:53.600 --> 01:34:57.400
Faculty (Olympus): Alright, any questions at this point? We have 5 minutes.

771
01:34:57.690 --> 01:35:03.689
Rahul Joshi .: So, you said, sir, we should look for SA, and then pass the string, right, as aâ€¦ whatever is the key instrument?

772
01:35:03.690 --> 01:35:04.710
Faculty (Olympus): Pinky, yes, yes.

773
01:35:04.710 --> 01:35:07.820
Rahul Joshi .: Instead of looking at based on the sequence, 0, 1, etc.

774
01:35:07.820 --> 01:35:08.180
Faculty (Olympus): Yes.

775
01:35:08.180 --> 01:35:09.299
Rahul Joshi .: I prefer to be right here.

776
01:35:09.300 --> 01:35:09.930
Faculty (Olympus): Yes.

777
01:35:11.270 --> 01:35:14.149
Faculty (Olympus): Okay, so, few things to note.

778
01:35:14.270 --> 01:35:23.469
Faculty (Olympus): Series themselves, when you operate on them, they will behave like NumPy arrays or dictionaries, right? Notice the dictionary comes from here, right? Because I can put these keys.

779
01:35:23.940 --> 01:35:34.139
Faculty (Olympus): But the difference is, even thoughâ€¦ so, the reason I'm saying they're similar to NumPy arrays, if I say np.sine of SN, it'll actually compute the sine values of the values, okay?

780
01:35:34.490 --> 01:35:38.190
Faculty (Olympus): But whatever you do, they'll always be carrying along the index.

781
01:35:39.340 --> 01:35:40.800
Faculty (Olympus): Okay?

782
01:35:41.210 --> 01:35:56.079
Faculty (Olympus): If I want to do operations, I give you two series, and I'm going to say, add these two series, it will not do it based on the location, it will do it based on the index value. So all operations will be aligned on the label, okay?

783
01:35:56.910 --> 01:36:05.320
Faculty (Olympus): Then, the indices, or the, you know, the index values that you have, may not be even be continuous, and they may not even be integers, okay?

784
01:36:05.910 --> 01:36:12.819
Faculty (Olympus): So you can think of, you know, a series as a special dictionary keyed on index, which also behaves like a numpy array, okay?

785
01:36:13.540 --> 01:36:23.140
Faculty (Olympus): Now, supposing you have two series which are not aligned, which means they are different keys. You know, it'll use the union of the indices, okay? And finally.

786
01:36:23.300 --> 01:36:35.129
Faculty (Olympus): the special value NAN, which I will discuss very soon, will be used to refer to missing values. So we'll go through each of these. I just wanted to highlight some of these prompts, okay?

787
01:36:35.330 --> 01:36:45.469
Faculty (Olympus): So, given that series look like, very much like a dictionary, you can initialize them with a dictionary. So, for example, I can say pd.series and give it a dictionary. X is 1, A is 2, B is

788
01:36:45.580 --> 01:36:50.179
Faculty (Olympus): Whatever, okay? So notice that this gives you what Iâ€¦ what you would expect.

789
01:36:51.920 --> 01:36:55.139
Faculty (Olympus): And this is an example of what you've already seen. So notice here.

790
01:36:55.260 --> 01:37:03.719
Faculty (Olympus): I create pd.series, np.Arange5, notice the index. It's a range 100 to 110 in steps of 2, so not even contiguous.

791
01:37:04.480 --> 01:37:07.680
Faculty (Olympus): Okay, so now if I say, give me 102th element, it'll give me that.

792
01:37:08.600 --> 01:37:12.140
Faculty (Olympus): So notice that the labels here are not contiguous.

793
01:37:12.810 --> 01:37:17.899
Faculty (Olympus): In the sense that the next index is not 1 plus the previous index.

794
01:37:18.330 --> 01:37:22.580
Rahul Joshi .: But, sir, here, actually, based on the convention, we have to pass the code, right?

795
01:37:22.730 --> 01:37:23.180
Faculty (Olympus): No.

796
01:37:23.180 --> 01:37:24.330
Rahul Joshi .: 3002, right?

797
01:37:25.020 --> 01:37:27.129
Faculty (Olympus): Why? I didn't pass the code, it still worked.

798
01:37:28.010 --> 01:37:35.049
Faculty (Olympus): The index is an integer in this case, it's just that it's any integer, just like a dictionary. Dictionary, I can have 100, 200, 300, 400, right?

799
01:37:35.900 --> 01:37:39.440
Faculty (Olympus): Where did we make that assumption that there has to be a string? I didn't say it's a string.

800
01:37:41.430 --> 01:37:42.510
Rahul Joshi .: Okay, okay.

801
01:37:45.400 --> 01:37:46.610
Faculty (Olympus): Alright, so now let us.

802
01:37:46.610 --> 01:37:48.729
Rahul Joshi .: Excuse me, the above example, yeah, sorry.

803
01:37:48.740 --> 01:37:55.910
Faculty (Olympus): So let us look at this next example. I have A is a series object, and notice that the values are all ones.

804
01:37:56.150 --> 01:37:58.409
Faculty (Olympus): And the index is A, B, C, D, E.

805
01:37:59.020 --> 01:37:59.860
Faculty (Olympus): Okay?

806
01:38:00.290 --> 01:38:03.889
Faculty (Olympus): Maybe I will split this one over, so we can see here and doom.

807
01:38:07.180 --> 01:38:08.030
Faculty (Olympus): Where?

808
01:38:13.260 --> 01:38:15.290
Faculty (Olympus): Okay, so let's say A is thisâ€¦

809
01:38:15.910 --> 01:38:21.230
Faculty (Olympus): And B is this. They all have the same keys, A, B, C, T, but in different order, okay? So this is A.

810
01:38:21.990 --> 01:38:23.080
Faculty (Olympus): And this is big.

811
01:38:24.020 --> 01:38:26.790
Faculty (Olympus): So A isâ€¦ first thing is A.

812
01:38:26.890 --> 01:38:32.380
Faculty (Olympus): And B, C, D, E. Okay, this is E, D, C, D, E. Okay?

813
01:38:32.680 --> 01:38:43.239
Faculty (Olympus): Now, if I did A plus B, what do you think will happen? If I did just numpy arrays, it's a problem, right? It'll just directlyâ€¦ so if I take, for example, A.value, right? If you remember, I want to get the values.

814
01:38:52.400 --> 01:38:58.029
Faculty (Olympus): this will give me this, but this is not what I want, right? So, on the other hand, did A plus B,

815
01:38:58.260 --> 01:39:01.400
Faculty (Olympus): This will give me, in this order of the keys.

816
01:39:01.510 --> 01:39:06.420
Faculty (Olympus): So notice, A is 1 here, A is 4 here. So the sum of these two will be 5.

817
01:39:07.020 --> 01:39:22.820
Faculty (Olympus): isâ€¦ B is 1 here, B is 3 here, so the sum of these two will be 4. So even though I did a plus operation, it is not going to simply blindly take the values and do the addition. It is going to look at the values keyed on the same index, and then do the addition.

818
01:39:23.400 --> 01:39:24.729
Faculty (Olympus): I hope this is clear.

819
01:39:25.540 --> 01:39:26.320
Faculty (Olympus): Okay.

820
01:39:27.140 --> 01:39:35.139
Faculty (Olympus): And notice that the data type of A will be Float64 in this case, so this is something you want to be careful about.

821
01:39:36.710 --> 01:39:40.549
Faculty (Olympus): Every series object has a data type, just like Empire is.

822
01:39:41.830 --> 01:39:57.540
Faculty (Olympus): Okay, there seem to be some questions. Let me just finish this, and then we will, you know, look at questions, and finish this last thing. So here's a similar example, where I have A. Notice that it has the same fellow as the previous. A is 1s, right? So all of these are ones. The keys are A, B, C, D, and E.

823
01:39:57.850 --> 01:40:01.639
Faculty (Olympus): And B has only E, D, C, and B.

824
01:40:01.790 --> 01:40:10.760
Faculty (Olympus): Okay, and it has only 4 values. But now, if I did A plus B, notice it has done something very peculiar. It has said A is NAN. It's not a number.

825
01:40:11.450 --> 01:40:14.390
Faculty (Olympus): B is 4, C isâ€¦ so what it has done is.

826
01:40:14.540 --> 01:40:17.110
Faculty (Olympus): B does not actually have this value A.

827
01:40:18.310 --> 01:40:31.620
Faculty (Olympus): does not have any index key, but you forced me to add these two. So when it does that, it says, look, B didn't have a value. You asked me to add something that didn't have a value to this. I'm going to tell you that whatever the result of that is also going to be not a value, because there was no value in B.

828
01:40:32.220 --> 01:40:43.220
Faculty (Olympus): So, this is how, basically, Pandas keeps track of missing values, by using this NAN sent in. Now, it's a number. We will look at NAN in the next class. So, I'll stop here, because it's 11.

829
01:40:43.590 --> 01:40:45.349
Faculty (Olympus): And I will answer your questions.

830
01:40:47.350 --> 01:40:48.270
Faculty (Olympus): Gaurav?

831
01:40:49.070 --> 01:41:01.129
Gaurav Singh .: Yeah, Professor, so when you added, the two dicks, sorry, the two series, A and B, with, keys in the reward, first.

832
01:41:01.130 --> 01:41:01.610
Faculty (Olympus): Give us all.

833
01:41:01.610 --> 01:41:09.249
Gaurav Singh .: and then once with the reverse order. After addition, it's given in the ABCD. So, does it, like, short theâ€¦

834
01:41:09.400 --> 01:41:11.460
Gaurav Singh .: Index value internally, like,

835
01:41:11.460 --> 01:41:28.510
Faculty (Olympus): That is an internal implementation detail which I cannot comment on. I don't want. And it'll change in version to version or whatever, but that is irrelevant to us. For us, what we want, what matters for us is, given that I have a series object, series objects, all operations, align on indices. That's the only thing you need to remember.

836
01:41:29.660 --> 01:41:30.380
Gaurav Singh .: Got it.

837
01:41:33.770 --> 01:41:34.610
Faculty (Olympus): Letter?

838
01:41:35.820 --> 01:41:39.879
varun kumar .: Yeah, Professor, so you talked about implicit and explicit indexes.

839
01:41:39.990 --> 01:41:49.860
varun kumar .: In Panda, correct? So, when we are explicitly putting that index as, like, A, B, C, D, E, that is called explicit indexing, correct?

840
01:41:49.860 --> 01:41:51.320
Faculty (Olympus): Yeah, basically.

841
01:41:51.510 --> 01:42:01.740
Faculty (Olympus): Yeah, correct. So in this case, for example, the first example, this was implicitlyâ€¦ so because I didn't specify an index, implicitly, you say, huh, okay, you don't give me an index, I'll assume 0123.

842
01:42:02.340 --> 01:42:03.819
Faculty (Olympus): The default index.

843
01:42:05.030 --> 01:42:11.559
varun kumar .: So, later, okay, so is index the only option to, you know, access a value, or the.

844
01:42:11.560 --> 01:42:22.159
Faculty (Olympus): No, no, no, no, there areâ€¦ you can access by location also, we'll look at that later. But I'm saying, with the series object, it's always best to access when you're using this accessor, the square bracket accessor.

845
01:42:22.310 --> 01:42:24.780
Faculty (Olympus): you useâ€¦ the index line.

846
01:42:24.940 --> 01:42:26.060
Faculty (Olympus): That's all I'm saying.

847
01:42:26.860 --> 01:42:30.310
varun kumar .: They're not explicit, it will be taken by implicit one.

848
01:42:31.410 --> 01:42:34.199
Faculty (Olympus): Yeah, and that's deprecated. You'll get a warning every time you do that.

849
01:42:35.110 --> 01:42:36.090
varun kumar .: Okay.

850
01:42:36.840 --> 01:42:38.569
Faculty (Olympus): Like, just like this, you get a warning.

851
01:42:39.150 --> 01:42:41.280
Faculty (Olympus): There'll be long warnings, though.

852
01:42:41.470 --> 01:42:42.150
Faculty (Olympus): Yep.

853
01:42:43.130 --> 01:42:44.090
Faculty (Olympus): Rahul?

854
01:42:44.700 --> 01:42:53.010
Rahul Joshi .: So, once you create the series, especially in the case of explicit indexes, can you change the indexes?

855
01:42:53.010 --> 01:42:54.900
Faculty (Olympus): Yes, you can change.

856
01:42:55.100 --> 01:42:56.850
Faculty (Olympus): But you ought to be careful doing it.

857
01:42:57.220 --> 01:43:01.070
Faculty (Olympus): I believe you can change. At least in data frames you can, but I believe in series also you can.

858
01:43:01.960 --> 01:43:08.220
Rahul Joshi .: Okay. And, the second question is, you said something is deprecated, what exactlyâ€¦ let me just say it again?

859
01:43:08.820 --> 01:43:13.759
Faculty (Olympus): you access something which has, you know, the SA, if I did SA of 0.

860
01:43:14.330 --> 01:43:15.489
Faculty (Olympus): It says this.

861
01:43:19.770 --> 01:43:21.140
Faculty (Olympus): I was just reading that.

862
01:43:21.300 --> 01:43:22.380
Faculty (Olympus): Okay, so based on theâ€¦

863
01:43:22.380 --> 01:43:24.169
Rahul Joshi .: Position, we should not access it.

864
01:43:24.170 --> 01:43:30.939
Faculty (Olympus): So right now, it works, it gives you something. At a future point, it may not work. In fact, your version of Pandas, it may not work, I don't know.

865
01:43:31.370 --> 01:43:34.780
Faculty (Olympus): So they're saying, warning, beware, beware. Sorry, just a warning.

866
01:43:38.110 --> 01:43:40.059
Savalo Naroji: Yeah, it's giving error for me.

867
01:43:40.310 --> 01:43:44.690
Faculty (Olympus): Yeah, so it might be version number has changed. Mine probably is an old version of Pandex.

868
01:43:47.330 --> 01:43:48.350
Faculty (Olympus): So, Rahul?

869
01:43:49.030 --> 01:43:49.979
Rahul Joshi .: Oh, you answered my questions.

870
01:43:49.980 --> 01:43:51.189
Faculty (Olympus): Yeah, Samar?

871
01:43:51.790 --> 01:43:58.020
Samar .: Yeah, so in the last example, where you took this unaligned TVs.

872
01:43:58.440 --> 01:44:09.130
Samar .: So, it does the union of indexes, right? Yes. Okay. If there are more missing in either side of the list, it will just do theâ€¦

873
01:44:09.130 --> 01:44:15.190
Faculty (Olympus): it will basically replace it by the missing value. Then missing values are represented in pandas as NANDs.

874
01:44:21.860 --> 01:44:22.790
Faculty (Olympus): Sachin?

875
01:44:24.580 --> 01:44:30.700
Sachin More .: Hi, Professor. On the sameâ€¦ on the same example, the NAN one, soâ€¦

876
01:44:31.510 --> 01:44:38.160
Sachin More .: If it's a union, then why doesn't it take the, value for A, which is 1? So, itâ€¦

877
01:44:38.160 --> 01:44:50.699
Faculty (Olympus): That is wrong, right? If I were to tell you, sum the values, and that student didn't get marks in this one, you have to at least warn me about it. We can't just say, oh, his sum is zero, or whatever, some is one value.

878
01:44:51.390 --> 01:44:58.099
Faculty (Olympus): So there are other ways to work around this. When there is a missing value, Pandas will basically say it's, man, that's all.

879
01:44:58.690 --> 01:45:02.550
Sachin More .: So even if it's present in one of the, series, it'sâ€¦

880
01:45:02.550 --> 01:45:14.470
Faculty (Olympus): There's a technical reason why this happens, and that is going to be discussed next, so maybe I'll quickly show you what happens. See, NAN is a number. NAN is actually a number in your floating-point representation.

881
01:45:14.590 --> 01:45:26.030
Faculty (Olympus): So there is an actual floating point representation that maps to NAND. Okay, so it is an actual floating point variable. This is useful because if I have a NumPy array, I can't suddenly say the NumPy array has to have all of the same type.

882
01:45:26.190 --> 01:45:29.939
Faculty (Olympus): And if I want to show a missing value here, I can't suddenly say, okay, this isâ€¦

883
01:45:30.040 --> 01:45:42.109
Faculty (Olympus): A string, right? It can't be there, can't do something like that. So NANs are fundamentally built in into your number system, okay? So NAN is a number, okay? And it's used to denote missing values. So, for example, if you just say float of

884
01:45:42.150 --> 01:45:51.319
Faculty (Olympus): 1.0, you'll get 1.0, right? If you do float of NAN, you'll get NAN, right? If you do type of float of NAN, it will be float, so it's actually a floating point.

885
01:45:51.590 --> 01:45:56.379
Faculty (Olympus): Okay? But the problem is, if I did NAND plus 1, it'll also be a NAND.

886
01:45:56.990 --> 01:45:57.690
Sachin More .: Okay.

887
01:45:57.690 --> 01:46:06.399
Faculty (Olympus): And that is the reason this thing happens here. So because this fellow is missing, it's a NAND. Now you added NAND to 1, it's gonna wipe out. So NAND is like this virus.

888
01:46:06.520 --> 01:46:11.059
Faculty (Olympus): You put a NAN, you do a mathematical operation, it's gonna wipe out the NAN.

889
01:46:11.180 --> 01:46:13.269
Faculty (Olympus): He's gonna wipe out everything else with nuts.

890
01:46:13.690 --> 01:46:24.559
Faculty (Olympus): And this is usedâ€¦ It's not a number. It's not a number. And it's mathematically defined that, or rather, the operations in the IEE number system are such that you add NAND to something, it becomes NAND.

891
01:46:26.120 --> 01:46:26.620
Sachin More .: Gotta.

892
01:46:27.410 --> 01:46:28.660
Savalo Naroji: It's like infinity.

893
01:46:29.170 --> 01:46:31.689
Faculty (Olympus): Yeah, but it's not infinity, yeah. I like that, in the.

894
01:46:31.690 --> 01:46:32.210
Savalo Naroji: Similar.

895
01:46:34.240 --> 01:46:35.680
Sachin More .: Yep. Thanks, thanks, Rufus.

896
01:46:36.160 --> 01:46:37.040
Faculty (Olympus): Sachin?

897
01:46:38.700 --> 01:46:40.549
Faculty (Olympus): Was thatâ€¦ was that you?

898
01:46:40.600 --> 01:46:42.289
Sachin More .: Yeah, you've already answered me.

899
01:46:42.290 --> 01:46:43.679
Faculty (Olympus): Okay, great. Purva?

900
01:46:44.200 --> 01:46:45.410
Purvaa Saxena .: Hello, sir.

901
01:46:45.410 --> 01:46:45.780
Faculty (Olympus): No.

902
01:46:45.780 --> 01:47:01.360
Purvaa Saxena .: I don't have a technical question, but I just wanted to ask, can you suggest any book or some, question set which we can practice? It's a question similar to what we get in a practice assignment. So, is there any book or something like that where we can

903
01:47:01.470 --> 01:47:03.470
Purvaa Saxena .: Practice questions.

904
01:47:04.010 --> 01:47:13.939
Faculty (Olympus): We unfortunately don't know the answer. There isâ€¦ there are things like Lead Code, there's Project Euler, there are many things, and I don't know if you need to go that far.

905
01:47:14.680 --> 01:47:16.220
Faculty (Olympus): Ideas?

906
01:47:16.220 --> 01:47:17.860
Purvaa Saxena .: 10 minutes are fine.

907
01:47:18.150 --> 01:47:20.680
Faculty (Olympus): Yeah, I would imagine so, butâ€¦

908
01:47:20.750 --> 01:47:26.219
Faculty (Olympus): How many problems can we give you also, right? Every time we give you some 10 to 15 problems.

909
01:47:26.260 --> 01:47:42.460
Faculty (Olympus): No, so already maybe 60 problems, or whatever you have done. So, I mean, that's not the point. The point is, okay, you haveâ€¦ by doing those exercises, at least you have basic familiarity. Then you'll get more and more familiarity by doing more things. Hopefully, you'll do more useful things than solving, you know, trivial problems.

910
01:47:43.110 --> 01:47:43.940
Purvaa Saxena .: Oh, boy.

911
01:47:43.940 --> 01:47:57.719
Faculty (Olympus): So, it's okay, don't worry too much about it, but make sure you understand the syntax. See, another way to do programming learning is, every time you see a line of code, you try and understand what's happening. Say, oh, left-hand side is an assignment, this is an assignment statement.

912
01:47:57.720 --> 01:48:16.539
Faculty (Olympus): Okay, this is nowâ€¦ okay, we are creating an object, right? This is pd.series. Oh, this is actually a function call. The function call, what does it do? It returns. What does it return? What is the type of this fellow? Oh, this is a, you know, a NumPy array with integer values. Then, what is this index? Okay, this is a list. Each of these elements is a string.

913
01:48:16.560 --> 01:48:20.510
Faculty (Olympus): Okay, and then you're done with this, right? So, when you read it like this.

914
01:48:21.040 --> 01:48:26.599
Faculty (Olympus): You're constantly exercising your brain to say, what is this? What is this? What is this? What am I doing? What am I doing?

915
01:48:26.850 --> 01:48:27.520
Purvaa Saxena .: Thank you.

916
01:48:27.520 --> 01:48:38.139
Faculty (Olympus): Right? And so, the idea is, we are pushing you to program so that you're forced to do this, but later on, it becomes just a habit. As in, you just read something, you're like, oh, okay, this is happening, and you get used to it.

917
01:48:38.690 --> 01:48:50.090
Faculty (Olympus): It's okay. And then you become better and better because you see more and more. Oh, you see an error, you see a mistake, you say, oh, this happened. The idea is that you approach it logically and not emotionally. So you see an error, you should say.

918
01:48:50.500 --> 01:49:02.099
Faculty (Olympus): Don't freeze. You're like, okay, there's an error, what does the error say? Oh, this is what? Oh, it could be that. This is the line it's saying, this is an issue. Okay, let me try and experiment. Now that works. Okay, so you basically lose your fear of

919
01:49:02.660 --> 01:49:06.140
Faculty (Olympus): computer and programming. Then you just, you know.

920
01:49:06.660 --> 01:49:09.390
Faculty (Olympus): deal with it logically. That'sâ€¦ that's the goal.

921
01:49:09.880 --> 01:49:11.299
Purvaa Saxena .: It should. Thank you.

922
01:49:11.310 --> 01:49:16.809
Faculty (Olympus): Yeah, soâ€¦ No, no, no, I think, Sachin, I've answered your question. So, Rahul?

923
01:49:17.030 --> 01:49:18.959
Rahul Joshi .: Sir, I'll go at the end, actually have a slightly different.

924
01:49:18.960 --> 01:49:19.290
Faculty (Olympus): Okay.

925
01:49:20.140 --> 01:49:20.960
Faculty (Olympus): M?

926
01:49:21.760 --> 01:49:38.320
Ann G. .: Sort of non-technical question, similar to Purva's question about the homeworks, so assignment 5, I found it, a bit difficult, so the point I want to raise was, sometimes I find it difficult to understand the language of the question. For example, in assignment.

927
01:49:38.830 --> 01:49:45.290
Ann G. .: There was a question wherein they give a 2x2, array of coordinate,

928
01:49:45.290 --> 01:50:00.979
Ann G. .: matrices, and the first question was, using np.newaxis and broadcasting, build an array of coordinate differences. Yeah. And, it should be 552. So, first of all, np.newaxis, like, I don't know where to add it.

929
01:50:01.030 --> 01:50:16.349
Ann G. .: And secondly, what coordinate differences? Is it along axis equals to 1, or axis equals to 2? So, usually, if the TA is setting the homework, he or she is doing a great job of explaining things at the end of the question.

930
01:50:16.360 --> 01:50:21.149
Ann G. .: But I don't know, I'm finding it difficult to understand the question itself.

931
01:50:21.150 --> 01:50:34.469
Faculty (Olympus): Right, so some of those questions are a bit difficult, yes, but, yeah, sometimes there's an implicit understanding thatâ€¦ or implicit expectation. So if something is difficult because of the wording, it's okay, don't worry too much about it.

932
01:50:34.580 --> 01:50:41.299
Faculty (Olympus): But in this case, you know, you can always ask the TA for anâ€¦ or you can askâ€¦ put out a, you know.

933
01:50:41.500 --> 01:50:44.690
Faculty (Olympus): ticket or whatever, saying, can you explain this a little better? That's okay.

934
01:50:44.980 --> 01:50:52.149
Faculty (Olympus): But in this case, coordinate differences areâ€¦ so typically, the reason you'd want to do something like this is, let's say I give youâ€¦

935
01:50:52.400 --> 01:50:55.300
Faculty (Olympus): 100 points, and I want pairwise differences

936
01:50:55.440 --> 01:50:59.370
Faculty (Olympus): In the distances betweenâ€¦ I want to find pairwise distances between these.

937
01:50:59.820 --> 01:51:06.719
Faculty (Olympus): It turns out, so you canâ€¦ one way of solving this is, we want to find coordinate differences. I will not take X minus Y. I will look at X

938
01:51:06.960 --> 01:51:09.149
Faculty (Olympus): my X value minus your X value.

939
01:51:10.350 --> 01:51:15.340
Faculty (Olympus): So, when you look at coordinate differences, I wantâ€¦ for each point, I want to find the difference between

940
01:51:15.910 --> 01:51:24.020
Faculty (Olympus): My value, my X coordinate, and the other point's X coordinate. Yes. In the same way, I want to find Y coordinate minus Y coordinate.

941
01:51:24.200 --> 01:51:41.270
Faculty (Olympus): then I will say, take the square of those differences, and sum those differences, or, you know, something like that, or justâ€¦ or take the square of the differences, and then add them along the dimensions. I don't know, X, so Xâ€¦ Iâ€¦ X1 minus X2, the whole squared, plus Y1 minus Y2 the whole squared.

942
01:51:41.670 --> 01:51:42.829
Faculty (Olympus): Add those two.

943
01:51:43.060 --> 01:51:44.189
Faculty (Olympus): Take the square root.

944
01:51:44.990 --> 01:51:46.150
Ann G. .: Yes,

945
01:51:46.150 --> 01:51:50.670
Faculty (Olympus): No, Iâ€¦ that makes sense, right? So, what we want to do is, I give you a set of

946
01:51:50.910 --> 01:51:57.690
Faculty (Olympus): points, right? And I now describe this set of points, you know, by your two-dimensional Are you?

947
01:51:58.960 --> 01:52:03.439
Faculty (Olympus): Okay? And now I want to say, fine, now make all pairs of differences.

948
01:52:05.190 --> 01:52:10.139
Faculty (Olympus): And so, it turns out you can do broadcasting to do this. Now, sometimes it's not obvious, soâ€¦

949
01:52:10.260 --> 01:52:11.370
Faculty (Olympus): It's okay.

950
01:52:11.370 --> 01:52:19.799
Ann G. .: I think that'sâ€¦ when it was only 2D, it was really simple. When they asked us to add np.new access, what access am I supposed to add and take.

951
01:52:19.800 --> 01:52:26.969
Faculty (Olympus): So, the reason isâ€¦ so, when you want to do the difference, you have to doâ€¦ basically, when youâ€¦ when I want pairwise differences.

952
01:52:27.660 --> 01:52:34.670
Faculty (Olympus): Remember, when youâ€¦ when I take a single one-dimensional array, and I take another simple one-dimensional array, I can simply take a difference.

953
01:52:36.010 --> 01:52:51.529
Faculty (Olympus): But now, this is difference of 1 minus this fellow. But now what I want is not 1 minus 1 fellow, I want 1 minus all fellows. So what I do is I take this fellow, put this fellow on this, right? I do a new axis to make this along this column, and now I take differences of each.

954
01:52:51.730 --> 01:52:53.940
Faculty (Olympus): Using broadcasting. Does that make sense?

955
01:52:54.410 --> 01:52:56.859
Ann G. .: A little difficult for me at this point, butâ€¦

956
01:52:56.860 --> 01:53:01.360
Faculty (Olympus): So I give youâ€¦ if I give you a oneâ€¦ so, if I give you one-dimensional array of values.

957
01:53:01.700 --> 01:53:11.299
Faculty (Olympus): And I want you to tell me the pairwise difference between each of these to every other fella. So this minus this, this minus this, this minus this, this minus this. How would you do it?

958
01:53:12.670 --> 01:53:15.269
Ann G. .: So, yeah, Iâ€¦

959
01:53:15.270 --> 01:53:26.459
Faculty (Olympus): Right? You would probably have to create aâ€¦ you would say, okay, normally you would say, I'll create a matrix of fellows, right, because I want pairwise differences. Then I will do a nested loop for I in this fellow, for J in.

960
01:53:26.460 --> 01:53:31.939
Ann G. .: The easiest would be, yeah, create a new axis and transpose, or something like that.

961
01:53:31.940 --> 01:53:34.980
Faculty (Olympus): Exactly. So that's all it is. So you take this fellow, take a new axis.

962
01:53:35.190 --> 01:53:38.170
Faculty (Olympus): And now you do the difference, it'll do actually pairwise difference.

963
01:53:38.780 --> 01:53:41.829
Ann G. .: Okay, it gets complicated for two variables, but Iâ€¦

964
01:53:41.830 --> 01:53:47.880
Faculty (Olympus): dimensions? Yeah, for two variables, you have this, and now you put a new axis in this dimension, and then you copy along this and no differences.

965
01:53:48.210 --> 01:53:50.110
Ann G. .: Okay.

966
01:53:50.110 --> 01:54:04.340
Faculty (Olympus): So the visualization does become difficult, yes. And so, in fact, this whole business of minimizing loops and doing vectorization is a pain, I grant you that. But unfortunately, it is a skill that is also very valuable, because there are many places where this is useful.

967
01:54:04.760 --> 01:54:10.450
Faculty (Olympus): You may not run into it, but it's just useful that you are at least aware that, oh, you can do these kind of complicated things.

968
01:54:10.970 --> 01:54:22.279
Ann G. .: Okay, so actually, I have run into it, I'm interested in this field. But anyways, so if the differences between X and Y is called coordinate differences, what would be the difference.

969
01:54:22.280 --> 01:54:23.460
Faculty (Olympus): Not XNY, XNX.

970
01:54:23.460 --> 01:54:28.770
Ann G. .: X1 and X2 is coordinate differences. What is the difference between X and Y, called? Like, is there a.

971
01:54:28.770 --> 01:54:33.039
Faculty (Olympus): There's no, no, no, I don't think that's what they're asking in the question. They're looking at pairwise differences.

972
01:54:33.370 --> 01:54:33.840
Rahul Joshi .: Yay.

973
01:54:33.840 --> 01:54:34.990
Ann G. .: Okay, thank you, sir.

974
01:54:35.310 --> 01:54:35.850
Faculty (Olympus): Sure.

975
01:54:35.850 --> 01:54:46.339
Ann G. .: So maybe just a request, like, if the TA couldâ€¦ like, they do a great job of elaborating the functions, or whatever we are supposed to use, if such complicated things, if they could elaborate a little.

976
01:54:46.340 --> 01:54:50.390
Faculty (Olympus): Yeah, yeah, yeah, yeah, so this broad, yeah, it's okay. I will tell her, yes.

977
01:54:50.390 --> 01:54:50.780
Ann G. .: Okay.

978
01:54:50.780 --> 01:54:55.299
Faculty (Olympus): Good point, yeah. So maybe they could have come up with a one-dimensional example and then done a two-dimensional thing.

979
01:54:55.410 --> 01:55:01.709
Faculty (Olympus): Just to expand that. That's okay. I'll tell them which time, yeah. Okay. Thank you for the feedback. Rahul?

980
01:55:01.920 --> 01:55:05.019
Rahul Joshi .: Yes, sir, I'll ask my question. Actually, my question is slightly trivial.

981
01:55:05.020 --> 01:55:09.699
Faculty (Olympus): Oh, by the way, before people leave, sorry, Rahul, wish you all the best for your quiz.

982
01:55:09.910 --> 01:55:10.670
Soumen Deb .: Thank you.

983
01:55:11.150 --> 01:55:23.330
Rahul Joshi .: No, go ahead. Yeah, yeah. So, in my notebook, actually, because you can see the complete help byâ€¦ I don't know what you do, because whenever I put a tab, I'm seeing it in a different format, actually.

984
01:55:23.470 --> 01:55:24.450
Faculty (Olympus): Shift tab.

985
01:55:24.750 --> 01:55:27.500
Faculty (Olympus): Oh, I don't know if you see what I'm seeing, huh? Do you see this?

986
01:55:28.920 --> 01:55:31.149
Faculty (Olympus): You do see it, okay. Shift-Tab.

987
01:55:31.560 --> 01:55:32.520
Faculty (Olympus): Shift down.

988
01:55:32.790 --> 01:55:37.429
Rahul Joshi .: Shift-Tab, also, I'm getting a slightly different formatting, actually, in the.

989
01:55:38.160 --> 01:55:39.080
Faculty (Olympus): Oh, okay.

990
01:55:39.080 --> 01:55:43.730
Rahul Joshi .: You're getting a very detailed help, actually. I'm getting a slightly concise help whenever I put Shift-App.

991
01:55:43.750 --> 01:55:47.109
Dinesh Devnath Yadav .: Yeah, even I faced the same thing.

992
01:55:48.520 --> 01:55:49.330
Faculty (Olympus): Oh.

993
01:55:51.370 --> 01:55:52.120
Faculty (Olympus): Okay.

994
01:55:53.270 --> 01:55:53.870
Faculty (Olympus): Hmm.

995
01:55:53.870 --> 01:56:00.490
Rahul Joshi .: And I'mâ€¦ and that Shift-Tab is not coming, let's say, if you put couple of letters of the method name.

996
01:56:00.490 --> 01:56:01.090
Faculty (Olympus): Hmm.

997
01:56:01.090 --> 01:56:05.019
Rahul Joshi .: And then you put shift, nothing is coming, actually, unless you put a complete,

998
01:56:05.380 --> 01:56:10.039
Faculty (Olympus): Yeah, yeah, you have to put theâ€¦ that you do tab to complete, otherwise I won'tâ€¦ you won't get help, right?

999
01:56:10.570 --> 01:56:24.289
Faculty (Olympus): See, you first complete the thing, and then you do Shift-A, because what it's basically doing is looking at the current word, and then doingâ€¦ seeing if there's any help documentation available for it. If that word does not correspond to anything that is there, it's not going to give you any help.

1000
01:56:24.860 --> 01:56:29.940
Faculty (Olympus): So you tabComplete first, and then you use Shift-Tab on the tab Completed object.

1001
01:56:31.340 --> 01:56:38.239
Rahul Joshi .: Yeah, so whenever you just click tab, let's say after SN, present dot, just tap.

1002
01:56:40.520 --> 01:56:42.620
Rahul Joshi .: Okay, this is what I'm also getting, okay, fine.

1003
01:56:42.620 --> 01:56:44.690
Faculty (Olympus): So you finish this, now you do shift-up.

1004
01:56:46.000 --> 01:56:52.090
Rahul Joshi .: Yeah, the shift tab is slightly giving me a different format, and I'm presuming that it is a slightlyâ€¦

1005
01:56:52.260 --> 01:56:53.859
Rahul Joshi .: less, data.

1006
01:56:53.860 --> 01:56:59.559
Faculty (Olympus): So, you see, I can't. Unfortunately, you have to minimize this. I'm sick.

1007
01:57:01.600 --> 01:57:06.100
Faculty (Olympus): Zoom on Linux is a bit of a pain. One second. So let me now do this.

1008
01:57:06.250 --> 01:57:15.650
Faculty (Olympus): I have something that gives me scrollableâ€¦ well, so I don't know, maybe your version is doing something different. Is this on the online interface, orâ€¦

1009
01:57:16.240 --> 01:57:18.880
Rahul Joshi .: No, no, it is my own. Online, I've not checked, actually, in the past.

1010
01:57:18.880 --> 01:57:25.390
Dinesh Devnath Yadav .: No, Professor, I'm checking on the online, right? So, on your notebook only, right? So, it is giving me a different one.

1011
01:57:26.100 --> 01:57:32.660
Dinesh Devnath Yadav .: So, for index, it is showing me first line is type, and under that, range index, that's it.

1012
01:57:35.620 --> 01:57:37.180
Faculty (Olympus): Or very subtle.

1013
01:57:39.070 --> 01:57:40.410
Faculty (Olympus): Jindaloâ€¦

1014
01:57:49.910 --> 01:57:52.740
Faculty (Olympus): Soâ€¦ let me see, I don't know.

1015
01:57:59.880 --> 01:58:02.179
Faculty (Olympus): Okay, so let me run this.

1016
01:58:06.090 --> 01:58:08.380
Faculty (Olympus): Okay, NP.loadText.

1017
01:58:09.330 --> 01:58:10.690
Faculty (Olympus): Oh, it's not finished.

1018
01:58:13.400 --> 01:58:17.530
Faculty (Olympus): Okay, I do have to go, so I'm shutting off my video now, just one second, soâ€¦

1019
01:58:18.750 --> 01:58:22.129
Faculty (Olympus): Okay, it's still loading, NumPy, one second, let's check this.

1020
01:58:25.350 --> 01:58:27.950
Faculty (Olympus): Okay, this is done, so NP.loadText.

1021
01:58:28.360 --> 01:58:31.940
Faculty (Olympus): So this is just long version, same thing, looks different.

1022
01:58:32.490 --> 01:58:35.830
Faculty (Olympus): It's all. But I see that all the same documentation is there.

1023
01:58:36.000 --> 01:58:40.040
Rahul Joshi .: So as soon as you click on load, your help appeared, right?

1024
01:58:40.040 --> 01:58:42.240
Faculty (Olympus): No, on Load Text and shift tab.

1025
01:58:42.600 --> 01:58:46.190
Faculty (Olympus): Then I scroll, I get all the same documentation. Pura I get.

1026
01:58:47.510 --> 01:58:48.789
Faculty (Olympus): It's just longer.

1027
01:58:50.100 --> 01:58:53.110
Rahul Joshi .: Yeah, yeah. Actually, at least the formatting is different in our case.

1028
01:58:53.110 --> 01:58:56.130
Faculty (Olympus): Something may be different, that is, I'm sure, will be the focus.

1029
01:58:56.600 --> 01:58:57.730
Faculty (Olympus): Thank you.

1030
01:58:57.730 --> 01:58:59.490
Rahul Joshi .: But I think that solves the problem for me.

1031
01:58:59.490 --> 01:59:01.059
Faculty (Olympus): Yeah, I'm gonna go in the placement.

1032
01:59:01.060 --> 01:59:03.029
Dinesh Devnath Yadav .: So, is there any setting, Professor?

1033
01:59:03.030 --> 01:59:08.520
Faculty (Olympus): I didn't do any setting for this.

1034
01:59:09.780 --> 01:59:10.650
Faculty (Olympus): Yay!

1035
01:59:19.010 --> 01:59:23.860
Faculty (Olympus): And lastâ€¦ Yes, any more questions? Last question.

1036
01:59:28.110 --> 01:59:28.980
Faculty (Olympus): Hello.

1037
01:59:29.340 --> 01:59:32.200
Siddhesh Dinesh Kadam .: So very quickly then, I'll just shoot you up.

1038
01:59:32.200 --> 01:59:32.840
Faculty (Olympus): What'sâ€¦

1039
01:59:32.840 --> 01:59:46.479
Siddhesh Dinesh Kadam .: Is there a specific meaning? Some functions start with a capital, a letter, and some with a small letter, is there any meaning? Because I did a mistake when typing small S series, I got error. That's when I realized that this.

1040
01:59:46.480 --> 01:59:48.820
Faculty (Olympus): Yeah, yeah, so there'll beâ€¦ so there may be differences.

1041
01:59:49.300 --> 01:59:54.660
Faculty (Olympus): Because Python is case sensitive, you may have libraries which have different names for different things.

1042
01:59:54.660 --> 01:59:58.719
Siddhesh Dinesh Kadam .: Is there a specific meaning behind, like, having a capital NFT model?

1043
01:59:58.720 --> 02:00:01.130
Faculty (Olympus): So usually, capital denotes an object.

1044
02:00:01.840 --> 02:00:02.639
Faculty (Olympus): Bye, Tom.

1045
02:00:02.950 --> 02:00:04.619
Faculty (Olympus): Small will be a function.

1046
02:00:05.660 --> 02:00:06.690
Faculty (Olympus): Usually.

1047
02:00:09.670 --> 02:00:15.750
Faculty (Olympus): Say, like, np.random.normal, n is small here, right? But if you look at binomial or something, it'll be capital B.

1048
02:00:16.320 --> 02:00:23.050
Faculty (Olympus): Not np.random.Dynamics. Look at scipy.stats, maybe uppercase, but sometimes I won't always say.

1049
02:00:27.700 --> 02:00:28.510
Siddhesh Dinesh Kadam .: Thank you.

1050
02:00:29.840 --> 02:00:31.190
Faculty (Olympus): Okay, so I have to go.

1051
02:00:31.190 --> 02:00:38.020
Ravi Kumar Pathak .: So, sir, one last question. So, you mentioned in between that passing is only for the final exam.

1052
02:00:38.020 --> 02:00:45.100
Faculty (Olympus): No, no, as in, yeah, you canâ€¦ yeah, yeah, passing is based on yourâ€¦ on the total score, not on this piece.

1053
02:00:45.840 --> 02:00:46.439
Ravi Kumar Pathak .: Okay.

1054
02:00:46.440 --> 02:00:46.990
Faculty (Olympus): outcome.

1055
02:00:46.990 --> 02:00:48.620
Ravi Kumar Pathak .: Thank you, sir. Thank you.

1056
02:00:49.350 --> 02:00:58.319
Faculty (Olympus): As in, he was saying that he has to pass to come to that level, but you'll have to take the full course, so you'll anyway come through and finish all the materials, soâ€¦

1057
02:00:58.790 --> 02:00:59.460
Ravi Kumar Pathak .: Sure.

1058
02:00:59.850 --> 02:01:00.690
Faculty (Olympus): This wasâ€¦

1059
02:01:00.690 --> 02:01:03.010
Ann G. .: It's not added for the final grading?

1060
02:01:04.440 --> 02:01:07.099
Ann G. .: Is this quiz not added for the final grading?

1061
02:01:07.450 --> 02:01:08.210
Faculty (Olympus): Sorry?

1062
02:01:08.590 --> 02:01:12.939
Ann G. .: This quiz, is it not, applicable to the final grading?

1063
02:01:12.940 --> 02:01:16.120
Faculty (Olympus): It is. It counts to 5 marks ofâ€¦ out of 100.

1064
02:01:16.280 --> 02:01:16.880
Ann G. .: Okay.

1065
02:01:17.250 --> 02:01:17.800
Faculty (Olympus): Yep.

1066
02:01:18.010 --> 02:01:18.949
Faculty (Olympus): It does.

1067
02:01:19.120 --> 02:01:22.699
Faculty (Olympus): That's why there's so much hoova about the Swiss. It does count.

1068
02:01:24.460 --> 02:01:28.040
Faculty (Olympus): Okay, good luck, everyone, bye!

1069
02:01:28.340 --> 02:01:29.150
Faculty (Olympus): Hello!

1070
02:01:29.150 --> 02:01:30.120
Kedar Digambar Gokhale .: Thank you, Professor.

1071
02:01:30.120 --> 02:01:30.870
Amod Kulkarni .: Thank you.

1072
02:01:30.870 --> 02:01:32.019
Amlan Sarkar .: Thank you, sir.

1073
02:01:32.020 --> 02:01:33.560
Advait Ketkar: Yeah, don't do sales.

1074
02:01:33.560 --> 02:01:34.370
Piyush Rustagi .: Thank you.

