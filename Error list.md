# Review have wrong answer
## Example 1
- I admit creating great expectations before watching because some friends mentioned it (and they are not pervs!) as a ==must see==. And it is a must see! Just don't expect to see something outbreaking. The Freudian psychoanalyzes are ==interesting== in many parts of the film, but there's just too much perversion and it doesn't stick in the end. Some of the ==good things== are the analyzes of Kieslowski's Blue, most of David Lynch's, some of Hitchcock's and perhaps a couple more I missed (I just remembered...), and I usually don't miss things unless they are too obvious or loose in the air. Other than being ==repetitive==, which makes it ==too long==, the documentary is ==enjoyable== in the sense of noticing some perversions fed by our unconscious, hence the commercial success of most thrillers studied and used as basis for this theory. I really enjoyed the ==energetic== tone of the narration and the effort of Mr. Zizek to revive Freud's theory, which has been numb for too long, specially in north America. Again, it's way ==over the top== and I believe ==not to be a completely waste of time== for I do believe most humans have a dark appreciation for death and blood.
		- True label: Negative 
		- Predict: Positive
		- Why : **Conflicting Sentiment (Mixed Reviews)**.
			- The positive weight heavily outweighed the negative weights
			- Failed on the phrase _"not to be a completely waste of time"_
				- Not and waste is too far and the model can't compare when we just do test and train the 1 and two letter near each other 
			- The ML Theory: Discourse Structure Ignorance
				- Human arguments have a structure
				- ML ignores "Discourse Structure.

## Example 2
- Farrah Fawcett gives an award nominated performance as an attempted rape victim who turns the tables on her attacker. This movie ==not== only makes you examine your own morals, it proves that Fawcett can excel as a serious actress both as a victim and victor.
		- True lable: Positive
		- Predict: Negative
		- Why : Not have Positive words, pray the dark subject
## Example 3
- Tenshu is imprisoned and sentenced to death. When he survives electrocution the government officials give him a choice to either be electrocute at a greater degree or agree to some experiments. He chooses the experimentation and is placed in a large metallic cell with a bad ass criminal who also survived the electrocution. They can have whatever the want in the room (within reason), but they can't leave. after a few days there meals are cut down to one per day and the room temp is set up too 100. After some more alarms are sounded at intervals so they can't sleep. One day a 'witch' come into their cell (albeit a glassed off portion) What happens next I'll let you find out. I may be in the minority here but I ==liked== the build up, it was ==intriguing== to me. Now ==if== the payoff was half as ==good== as the build up was I would have rated this so much ==higher==.My Grade: C+ Media Blaster's 2 DVD set Extras: Disc 1) Director's Cut; Trailers for "Versus", "Aragami", "Attack the Gas Station", and "Deadly Outlaw Rekka" Disc 2) Theatrical Cut; Commentary with Hideo Sakaki, Ryuhei Kitamura, Sakaguchi Takuand Tsutomu Takahashi; Cast and crew interview; Making of; Original Trailer; and Promo Teasers
		- True lable: Negative 
		- Predict: Positive
		- Why : Condition Conditional Statements
			-  ==if== the payoff was half as ==good== as the build up was I would have rated this so much ==higher==
## Example 4

- I've seen Branaghs Hamlet: Branagh is ==too old==, speaks frequently with a high pitched voice (unwillingly funny!) - not a convincing Hamlet, and his directors qualities - ==poor== ! (see also much ado about nothing from Branagh - the funny parts of the dialogues have mostly been cut out not speaking of the directors ==mistakes== in the dialogue cuts!) 2. I've seen Hamlet 2000: I think the scenario is an interesting idea - but such ==lousy actors== - all of them 3. Orson Welles Hamlet is OK - but this BBC Hamlet is the best! Derec Jacobi is convincing - seems a bit of a lunatic - very suitable! and Patric Stewart - wonderful, and Claire Bloom is a very attractive queen. You believe those actors what they are saying - I think this is the best compliment.
		- True label: Positive
		- Predict: Negative
		- Why : Comparison
			- The user absolutely loved the BBC version of Hamlet, but they spent 80% of their word count complaining about _other_ versions.

## Example 5
- The story of the bride fair is an ==amusing== and ==engaging== one, and it is to the filmmaker's credit that he sets out to portray rural Minnesotans with the same ==respect== ordinarily reserved for Coast-dwellers. It is weird, though, to find an independent movie, the brainchild of a single person, that is as ==unambitious== and ==clichéd©-ridden== as a committee-brewed Hollywood potboiler. The portrait of rural people is intended to be ==affectionate==, I think, but these characters don't ring true to me--I have had quite a few meals in small-town diners, but never overheard a debate on the merits of different nineteenth-century English novelists. One might suggest that writer/director Seamans has no more experience with rural culture than the Coen brothers, and considerably less satiric verve.
		- True label: Negative
		- Predict: Positive
		- Why: cannot understand **Concession**
			- Human critics often try to be polite. They start by praising the director's _intentions_ before destroying the actual _execution_ of the movie.
		- The ML Theory: Discourse Structure Ignorance & Uniform Positional Weighting
			- it values a polite word exactly the same as a critical word , completely missing the structural flow of the argument.
## Example 6
- I had known Brad Linaweaver at Florida State U in the early 70's when he was an ==inspiring==, ==inventive== writer who I thought was headed for greater ==glory==. And that is why I rented this video. Well, well, well, the time has not been kind to Mr Linaweaver. I suppose the pressures of making a living makes higher aspirations expendable. Another flower whose bloom has come and gone un-noticed in the summer breeze. Amen. There is nothing more to say. And nothing more to add. A sad epitaph to a once ==blossoming== career as stated above. But it is the price one pays for chasing shadows without a firm foundation or goals for oneself in life. Because this movie has ==no goal, no purpose==, and I kept telling myself, what happened to Brad's ==creativity==, his once ==shining genius==? Gone, gone, years of neglect has deteriorated his once shining mind.
		- True label: Negative
		- Predict: Positive
		- Why : **no concept of time or verb tense**.
			- All these positive world to predict the writer's past
			- His main ideal is talk the movie has no goal, no purpose
		- The ML Theory: Violation of Sequential Dependency
			- Standard Logistic Regression and Naive Bayes rely on treating documents as an unordered set, completely destroying Sequential Dependency
			- Model cannot track time or verb tense, it mathematically collapses past praise
			
## Example 7
- How many centuries will pass until the Japanese/Asian horror films abandon the long-haired ghost-woman shtick? Admittedly, they've managed to rip off "Ringu" a million times, and often it worked well - which just goes to show that originality isn't that much of a requirement in the horror genre (or that I'm very uncritical and easy to please?). However, this time around I found myself a little restless, somewhat bored. It's not a bad film, but it's at least half-an-hour longer than it should be, with its absurd 110 minutes length. Compared to many other Japanese horror films, ==OMC lacks atmosphere and excitement==. Plus, the ending is confusing: it makes no sense at all. As for the ring-tone: Miike ==could have come up with a melody that is more effective== than that forgettable little thing. Even though it was played a dozen times I can't even remember it - that's how scary it was. Speaking of Miike, for him this is something of a commercial venture, so if anyone thinks they might be getting perversion of the "Bijita Q" or "Audition" kind, they're wasting their time.
		- True label: Negative
		- Predict: Positive
		- Why : Detached Negation
			- _OMC lacks atmosphere and excitement"_. A human knows that "lacks excitement" means "boring.", The model sees the word _"excitement"_ and awards the review massive positive points!
			- _"could have come up with a melody that is more effective."_ The user is saying the melody was terrible. The machine just sees the words _"more effective"_ and assumes the user loved the music.
		- The ML Theory: The Feature Independence Assumption
			- For example, "lacks atmosphere and excitement" because we use logistic, each of words is independent, not link with each other
## Example 8
- for a slasher flick,this movie is actually ==better than a lot== in the genre.yes it is predictable-resident ==nut job== goes on ==killing spree==,people ==die==,yada yada yada.however there are some good positives in this film.first off,i really liked the mask the nut job wore.it is definitely creepy to say the least and possibly unique(although i haven't watched every single slasher film ever made)also,the genesis of the ==bad== due is something i haven't seen before,and he way he finally meets his end is a novel concept,as far as i know.i also really liked the weapon of choice employed by Mr sicko,for most of the murders.the murders themselves are not as graphic as most in the genre,but that'a small concern.the movie does not take itself seriously,which is something most slashers suffer from.oddly enough,while watching the movie,i was reminded of the early "Friday the 13th films,which did take themselves seriously.there are a few concerns about this movie.in several scenes,the killer suddenly bears a strong resemblance to one of our horror icons.by this,i mean his movements and his reactions upon being shot,and also the way he walked.of bigger concern,however is a scene very close to the end,where Mr crazy bears a more than striking resemblance(actually a complete rip off)of another famous horror titan.and in the very last scenes,we have our ==scumbag==,once again,looking exactly like the 1st horror icon i mentioned.in fact that last scene is almost a complete rip-off from another icon in the slasher genre. these scenes were weak and unoriginal(obviously).by the way,the movie is set in Australia,so if you're a sucker for a chick with an Aussie accent(like me)you'll be in heaven.if you not,than it just might grate on you.one other great thing about this movie:beautiful Kylie Minogoue(just don't get too attached to her)there is one non Aussie accent,courtesy of Molly Ringwald.overall,there are more reasons to watch than not.i ==enjoyed it== and had some ==fun==. So,i have to give "Cut" 8/10,which may seem too high to some people.
		- True label: Positive
		- Predict: Negative
		- Why : Users use the dark as descriptors, not as criticisms
			- applies massive negative weights to those words
		- The ML Theory: Domain Mismatch & Contextual Feature Correlation
			- The Model learn the global set of rules based on the average of all training data --> the dark words have a huge correlation with negative words


# Conclusion
- **Sarcasm & Irony:** "Oh great, another predictable ending." (The word "great" tricks the model).
- **Negation:** "The movie was not exactly a masterpiece." (The model sees "masterpiece" but misses the "not").
- **Mixed Sentiment / Long Reviews:** The user writes 10 sentences hating the actors, but 1 sentence at the end saying they still loved the movie. The model just counts the bad words and gets it wrong.
- **Out of Vocabulary:** The review uses slang, typos, or new words (like "mid" or "peak cinema") that the model never learned during training.
- Meaning of the sentence: if, talk about past or present, 



# Embending fix
## Example 1
story bride fair ==amuse== ==engage== one filmmaker credit set portray rural minnesotan ==respect== ordinarily reserve coastdwellers weird though find independent movie brainchild single person unambitious clichridden committeebrewed hollywood ==potboiler== the portrait rural people intend affectionate think character dont ring true mei quite meal smalltown diner never overhear debate merit different nineteenthcentury english novelist one might suggest writerdirector semans experience rural culture coen brother considerably less satiric verve
	- Why Logistic/Bayes Fails: the model tallies up "amuse," "engage," and "respect," and assumes it's a glowing positive review (False Positive), completely ignoring the devastating insult at the end
	- What Word2Vec Does Differently: Word Embeddings understand **Conceptual Weight**.
	    - A BoW model treats "potboiler" or "==cliché==" as a single count (-1 point).
	    - Word2Vec recognizes that "committeebrewed potboiler" is a massive, highly dense cluster of negative cinematic criticism. The mathematical vector for a complex insult like "potboiler" carries much more semantic gravity than polite filler words like "amuse," allowing the vector average to swing into the negative zone where it belongs.
## Example 2
film list make film available something weird video driver ed ==scare film== vol one thing version color swv disc earlier version film make bw wlwt television channel cincinnati either way film notorious however unlike driver ed film intend television broadcast view general public thus level ==carnage== ratchet still pretty ==grim exercise== exploitation ==bloody death== purport educational intent live cincinnati area remember thing show every year around prom time channel youre look one film demonstrate tone uniquely american film phenomenon last prom pretty typical morose hyperbolic extremely didactic heavy melodrama whether really affected teenager drive anyones guess
		- True lable: Negative 
		- Predict: Positive
		- Why Logistic/Bayes Fails: In a Bag-of-Words (BoW) model, words are just columns on a spreadsheet. The model has learned that "death," "carnage," and "electrocution" appear mostly in 1-star reviews. It mathematically penalizes the review for using "bad" words, completely failing to realize the user is just describing a horror movie or documentary.
		- What Word2Vec Does Differently: Word Embeddings understand Semantic Relationships
			- Word2Vec maps words in a 3D space. It learns that words like "blood," "carnage," and "electrocution" cluster right next to the words "thriller," "horror," and "plot."
			- It separates those words entirely from sentiment words like "terrible," "boring," and "awful." When you average the vectors, the model realizes this is a dense description of a plot, not a complaint about the director.

## Example 3
cant believe comment show show genius sure doesnt follow try true consumer always want thing thrust u shouldnt option sit back enjoy something new style realistic previous scooby doo show suppose show title shaggy scooby doo get clue part title state entire beloved cast rendition would constantly join action nowhere say theyd solve mystery cant even stand monster would im actually glad put long stand plot point work scoobydoo show still run joke clumsy hijinks quickchange outfit chase scene standard hallway gag even scooby snack fact im glad show love im even glad get rid rest team concentrate two main character villainsure ridiculous suppose sure different suppose suppose make laugh villain cheer ==idiotic== robotic butler triumph intrude ==vermin== matter size youre suppose get run roobiroo joke whole thing put together well isnt single thing think wrong write act animation ==top notch ==title music ==awesome== computer play get clue boot background music gripping 
		- **Why Logistic/Bayes Fails:** Reviewers often complain about a movie's premise before admitting they actually liked it. A basic model sees "idiotic," "vermin,"  and immediately drops the score.
		- **What Word2Vec Does Differently:** Word Embeddings understand **Synonym Stacking**.
		    - In BoW, "top notch," "awesome," and "enjoy" are three separate, unrelated columns. If they don't have high individual weights, they lose to the negative words.
	        - In Word2Vec, "top notch," "awesome," and "enjoy" point in the exact same mathematical direction. When your code averages the vectors (`np.mean`), these positive vectors stack on top of each other, creating a massive, undeniable mathematical pull toward the Positive class, easily overpowering the scattered plot complaints.