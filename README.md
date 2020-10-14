# Awful AI
**Awful AI** is a curated list to track *current* scary usages of AI - hoping to raise awareness to its misuses in society

Artificial intelligence in its current state is [unfair](https://github.com/rockita/criticalML), [easily susceptible to attacks](http://www.cleverhans.io/security/privacy/ml/2016/12/16/breaking-things-is-easy.html) and [notoriously difficult to control](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vRPiprOaC3HsCf5Tuum8bRfzYUiKLRqJmbOoC-32JorNdfyTiRRsR7Ea5eWtvsWzuxo8bjOxCG84dAg/pubhtml). Often, AI systems and predictions [amplify existing systematic biases](https://twitter.com/kaiwei_chang/status/1274845029933084673) even when the data is balanced. Nevertheless, more and more concerning the uses of AI technology are appearing in the wild. This list aims to track *all of them*. We hope that *Awful AI* can be a platform to spur discussion for the development of possible preventive technology (to fight back!).

---

## Discrimination

[AI-based Gaydar](https://osf.io/zn79k/) - Artificial intelligence can accurately guess whether people are gay or straight based on photos of their faces, according to new research that suggests machines can have significantly better “gaydar” than humans. [[summary](https://www.theguardian.com/technology/2017/sep/07/new-artificial-intelligence-can-tell-whether-youre-gay-or-straight-from-a-photograph)]

[Infer Genetic Disease From Your Face](https://edition.cnn.com/2019/01/08/health/ai-technology-to-identify-genetic-disorder-from-facial-image-intl/index.html?no-st=1549146304) - DeepGestalt can accurately identify some rare genetic disorders using a photograph of a patient's face. This could lead to payers and employers potentially analyzing facial images and discriminating against individuals who have pre-existing conditions or developing medical complications. [[Nature Paper](https://www.nature.com/articles/s41591-018-0279-0.epdf?referrer_access_token=sF7zVVP51xQLnVUf3rpN09RgN0jAjWel9jnR3ZoTv0Os8H3z_P0FWM-ifOxgr_-D2EAOzSQNIaycjlyuCb2S8AGUIz1lwjJUTHXwXVO8I-FR_1SaryaQEMOiWiGdq9-Or0FcRDRHUv73m_pMRw6NINspOmyW0M_1un4KEiWrDmy-ncDDdRK_i38HeVnEgDbcrr79VUfW055SbD_CCuhoFZ24qZWOMZiZHEyJxNSiYg6df9_7QjUF7jCkr2y-qi2XQI6_ppSz6K0kuxLwezmPSZIEQGdOCqMNYUGpSKAm7ap0Xtf9DGaayEVXDc9NdJhelQEtp02wvxU7lRzbp40qAQ%3D%3D&tracking_referrer=edition.cnn.com)]

[Racist Chat Bots](https://www.theguardian.com/technology/2016/mar/24/tay-microsofts-ai-chatbot-gets-a-crash-course-in-racism-from-twitter) - Microsoft chatbot called Tay spent a day learning from Twitter and began spouting antisemitic messages.

[Racist Auto Tag and Recognition](https://www.theguardian.com/technology/2015/jul/01/google-sorry-racist-auto-tag-photo-app) - a Google image recognition program labeled the faces of several black people as gorillas. Amazon's Rekognition labeled darker-skinned women as men 31 percent of the time. Lighter-skinned women were misidentified 7 per cent of the time. Rekognition helps the Washington County Sheriff Office in Oregon speed up how long it took to identify suspects from hundreds of thousands of photo records. [Zoom's face recognition](https://twitter.com/colinmadland/status/1307111816250748933) as well as many others struggle to recognize black faces. [[ABC report on Rekognition bias](https://abcnews.go.com/Technology/wireStory/researchers-amazon-face-detection-technology-shows-bias-60630589?cid=social_twitter_abcn)] [[Wired story on recognizing black faces](https://www.wired.com/story/best-algorithms-struggle-recognize-black-faces-equally/)]

[Depixelizer](https://www.theverge.com/21298762/face-depixelizer-ai-machine-learning-tool-pulse-stylegan-obama-bias) - An algorithm that transforms a low-resolution image into a depixelized one, always transforms Obama into a white person due to bias.

[Twitter autocrop](https://www.vice.com/en/article/ep4e4w/what-twitters-preference-for-ted-cruz-with-big-anime-boobs-says-about-ai-bias) - Twitter takes the user image and crops it to have a preview of the image. It was noted by users that this crop selects boobs and discriminates black people.  

[Autograding](https://www.theverge.com/2020/8/17/21372045/uk-a-level-results-algorithm-biased-coronavirus-covid-19-pandemic-university-applications) - An algorithm used to predict grades in UK based on the beginning of the semester and historical data, was found to be biased against students of poor backgrounds.

[Sexist Recruiting](https://www.telegraph.co.uk/technology/2018/10/10/amazon-scraps-sexist-ai-recruiting-tool-showed-bias-against/) - AI-based recruiting tools such as [HireVue](https://www.hirevue.com/), [PredictiveHire](https://www.technologyreview.com/2020/07/24/1005602/ai-hiring-promises-bias-free-job-hopping-prediction/), or an Amazon internal software, scans [various features such as video or voice data of job applicants](https://www.inc.com/minda-zetlin/ai-is-now-analyzing-candidates-facial-expressions-during-video-job-interviews.html) and their CVs to tell whether they're worth hiring. In the case of Amazon, the algorithm quickly taught itself to prefer male candidates over female ones, penalizing CVs that included the word "women's," such as "women's chess club captain." It also reportedly downgraded graduates of two women's colleges. [[summary](https://www.reuters.com/article/us-amazon-com-jobs-automation-insight/amazon-scraps-secret-ai-recruiting-tool-that-showed-bias-against-women-idUSKCN1MK08G)][[Post article about HireVue](https://www.washingtonpost.com/technology/2019/10/22/ai-hiring-face-scanning-algorithm-increasingly-decides-whether-you-deserve-job/)]

[Gender Detection from Names](https://www.theverge.com/2020/7/29/21346310/ai-service-gender-verification-identification-genderify) - Genderify was a biased service that promised to identify someone’s gender by analyzing their name, email address, or username with the help of AI. According to Genderify, Meghan Smith is a woman, but Dr. Meghan Smith is a man.

[PredPol](http://www.predpol.com/) - PredPol, a program for police departments that predicts hotspots where future crime might occur, could potentially get stuck in a feedback loop of over-policing majority black and brown neighbourhoods. [[summary](https://www.themarshallproject.org/2016/02/03/policing-the-future?ref=hp-2-111#.UyhBLnmlj)]

[COMPAS](http://www.equivant.com/challenges/supervision-and-compliance-monitoring) - is a risk assessment algorithm used in legal courts by the state of Wisconsin to predict the risk of recidivism. Its manufacturer refuses to disclose the proprietary algorithm and only the final risk assessment score is known. The algorithm is biased against blacks (COMPAS performs worse than a human evaluator). [[summary](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)][[NYT opinion](https://www.nytimes.com/2017/10/26/opinion/algorithm-compas-sentencing-bias.html)]

[Infer Criminality From Your Face](https://arxiv.org/abs/1611.04135) - A program that judges if you’re a criminal from your facial features. [[summary](https://www.technologyreview.com/s/602955/neural-network-learns-to-identify-criminals-by-their-faces/)]

[Homeland Security](https://theintercept.com/2018/12/03/air-travel-surveillance-homeland-security/) - Homeland security, with [DataRobot](https://www.datarobot.com/), is creating a terrorist-predicting algorithm trying to predict if a passenger or a group of passengers are high-risk by looking at age, domestic address, destination and/or transit airports, route information (one-way or round trip), duration of the stay, and luggage information, etc., and comparing with known instances.

[iBorderCtrl](https://ec.europa.eu/research/infocentre/article_en.cfm?artid=49726) - AI-based polygraph test for travellers entering the European Union (trial phase). Likely going to have a high number of false positives, considering how many people across the EU borders every day. Furthermore, facial recognition algorithms are prone to racial bias. [[summary](https://gizmodo.com/an-ai-lie-detector-is-going-to-start-questioning-travel-1830126881)]

[Faception](https://www.faception.com/) - Based on facial features, Faception claims that it can reveal personality traits e.g. "Extrovert, a person with High IQ, Professional Poker Player or a threat". They build models that classify faces into categories such as Pedophile, Terrorist, White-Collar Offenders and Bingo Players without prior knowledge. [[classifiers](https://www.faception.com/our-technology)][[video pitch](https://www.youtube.com/watch?v=x1QsDiWCV-o)]

[Persecuting ethnic minorities](https://www.theguardian.com/news/2019/apr/11/china-hi-tech-war-on-muslim-minority-xinjiang-uighurs-surveillance-face-recognition) - Chinese start-ups have built algorithms that allow the government of the People’s Republic of China to automatically track Uyghur people. This AI technology ends up in products like the AI Camera from [Hikvision](https://ipvm.com/reports/hikvision-uyghur), which has marketed a camera that automatically identifies Uyghurs, one of the world's most persecuted minorities. [[NYT opinion](https://www.nytimes.com/2019/04/14/technology/china-surveillance-artificial-intelligence-racial-profiling.html)]

[SyRI](https://nos.nl/artikel/2308110-rechtszaak-over-fraudebestrijding-overheid-burgers-bij-voorbaat-verdacht.html) - 'Systeem Risico Indicatie' or 'Risk Identification System' was an AI-based anti-fraud system used by the Dutch government from 2008 to 2020. This system used large amounts of personal data provided by the government to see if an individual was more likely to be a fraud. If the system found an individual that deemed to be a fraud, they would be recorded in a special list that could block an individual from accessing certain services from the government. SyRI was discriminatory in it's judgement and never catched an individual that was proven to be a fraud. The Dutch court ruled in Feburary 2020 that the use of SyRI [violated human rights](https://uitspraken.rechtspraak.nl/inziendocument?id=ECLI:NL:RBDHA:2020:1878). [[amicus curiae](https://www.ohchr.org/Documents/Issues/Poverty/Amicusfinalversionsigned.pdf)]

## Influencing, disinformation, and fakes

[Cambridge Analytica](https://cambridgeanalytica.org/) - Cambridge Analytica uses Facebook data to change audience behaviour for political and commercial causes. [[Guardian article](https://www.theguardian.com/news/2018/mar/26/the-cambridge-analytica-files-the-story-so-far)]

[Deep Fakes](https://www.deepfakes.club/) - Deep Fakes is an artificial intelligence-based human image synthesis technique. It is used to combine and superimpose existing images and videos onto source images or videos. Deepfakes may be used to create [fake celebrity pornographic videos and revenge porn](https://www.vice.com/en_us/article/bj5and/ai-assisted-fake-porn-is-here-and-were-all-fucked) or [scam businesses](https://gizmodo.com/scammer-successfully-deepfaked-ceos-voice-to-fool-under-1837835066) [[CNN Interactive Report](https://www.cnn.com/interactive/2019/01/business/pentagons-race-against-deepfakes)][[Deep Nudes](https://www.theverge.com/2019/6/27/18760896/deepfake-nude-ai-app-women-deepnude-non-consensual-pornography)][[DreamPower](https://github.com/dreamnettech/dreampower)]

[Fake News Bots](https://www.technologyreview.com/s/608561/first-evidence-that-social-bots-play-a-major-role-in-spreading-fake-news/) - Automated accounts are being programmed to spread fake news. In recent times, fake news has been used to manipulate stock markets, make people choose dangerous health-care options, and manipulate elections, including the 2016 US presidential election. [[summary](https://www.wired.com/story/internet-freedom-2017/)][[NYT Article](https://www.nytimes.com/interactive/2019/06/07/technology/ai-text-disinformation.html)]

[Attention Engineering](https://www.ted.com/talks/tristan_harris_the_manipulative_tricks_tech_companies_use_to_capture_your_attention) - From Facebook notifications to Snapstreaks to YouTube auto-plays, they're all competing for one thing: your attention. Companies prey on our psychology for their profit.

[Social Media Propaganda](https://www.theguardian.com/world/2014/jul/08/darpa-social-networks-research-twitter-influence-studies) - The Military is studying and using data-driven social media propaganda to manipulate news feeds to change the perceptions of military actions. [[Guardian article](https://www.theguardian.com/world/2014/jul/08/darpa-social-networks-research-twitter-influence-studies)]

## Surveillance

[Anyvision Facial Recognition](https://www.anyvision.co/) - Facial recognition software previously funded by Microsoft which has [become infamous](https://dropanyvision.org/) for its use by the Israeli Government to survey, track, and identify those living under military occupation throughout the West Bank. The system is also used at Israeli [army checkpoints](https://www.haaretz.com/israel-news/business/.premium-this-israeli-face-recognition-startup-is-secretly-tracking-palestinians-1.7500359) that enclose occupied Palestine.

[Clearview.ai](https://clearview.ai/) - Clearview AI build a facial recognition database of billions of people by scanning their social media profiles. The application is currently used [by law enforcement](https://www.nytimes.com/2020/01/18/technology/clearview-privacy-facial-recognition.html) to extract names and addresses from potential suspects, and as [a secret plaything for the rich](https://www.nytimes.com/2020/03/05/technology/clearview-investors.html) to let them spy on customers and dates.

[Predicting Mass Protests](https://motherboard.vice.com/en_us/article/7x3g4x/pentagon-wants-to-predict-anti-trump-protests-using-social-media-surveillance) - The US Pentagon funds and uses technologies such as [social media surveillance](http://apollo2.cs.illinois.edu/index.html) and [satellite imagery](https://www.iarpa.gov/index.php/newsroom/iarpa-in-the-news/2015/461-the-embers-project-can-predict-the-future-with-twitter) to [forecast civil disobedience](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.302.323&rep=rep1&type=pdf) and infer [location of protesters](https://patents.google.com/patent/US20170310772A1/en) [via their social networks](https://web.archive.org/web/20181019110722/http://jurgens.people.si.umich.edu/docs/icwsm-2013-slides.pdf) around the world. There are indications that this technology is increasingly used to [target Anti-Trump protests](https://link.springer.com/chapter/10.1007/978-3-319-97885-7_27), [leftwing groups](https://www.theguardian.com/us-news/2018/sep/15/massachusetts-police-tweet-leftwing-surveillance-boston) and [activists of color](https://medium.com/@ACLU_NorCal/police-use-of-social-media-surveillance-software-is-escalating-and-activists-are-in-the-digital-d29d8f89c48#.fowkro6dy). 

[Gait Analysis](https://royalsociety.org/~/media/about-us/programmes/science-and-law/royal-society-forensic-gait-analysis-primer-for-courts.pdf) - Your gait is highly complex, very much unique and hard, if not impossible, to mask in this era of CCTV. Your gait only needs to be recorded once and associated with your identity, for you to be tracked in real-time. [In China](https://www.theatlantic.com/magazine/archive/2018/04/big-in-china-machines-that-scan-your-face/554075/) this kind of surveillance is already deployed. Besides, multiple people have been convicted on their gait alone in the west. We can no longer stay even modestly anonymous in public.

[SenseTime](https://www.sensetime.com/intelligentVideo/84) & [Megvii](https://megvii.com/)- Based on Face Recognition technology powered by deep learning algorithm, SenseFace and Megvii provides integrated solutions of intelligent video analysis, which functions in target surveillance, trajectory analysis, population management. [[summary](https://www.reuters.com/article/us-china-facialrecognition-analysis/backing-big-brother-chinese-facial-recognition-firms-appeal-to-funds-idUSKBN1DD00A)][[forbes](https://www.forbes.com/sites/shuchingjeanchen/2018/03/07/the-faces-behind-chinas-omniscient-video-surveillance-technology/#54401e4f4afc)][[The Economist (video)](https://www.youtube.com/watch?v=lH2gMNrUuEY)]

[Uber](https://www.forbes.com/sites/kashmirhill/2014/10/03/god-view-uber-allegedly-stalked-users-for-party-goers-viewing-pleasure/#70a9f7a43141) - Uber's "God View" let Uber employees see all of the Ubers in a city and the silhouettes of waiting for Uber users who have flagged cars - including names. The data collected by Uber was then used by its researchers to analyze private intent such as meeting up with a sexual partner. [[rides of glory](https://rideofglory.wordpress.com/)]

[Palantir](http://www.palantir.com/) - A billion-dollar startup that focuses on predictive policies, intelligence and ai-powered military defense systems. [[summary](https://www.theverge.com/2018/3/10/17104878/palantir-us-army-contract-peter-thiel-data-intelligence-distributed-common-ground-system-tech)]

[Censorship](https://www.technologyreview.com/s/613962/how-wechat-censors-private-conversations-automatically-in-real-time/) - WeChat, a messaging app used by millions of people in China, uses automatic analysis to censor text and images within private messaging in real-time. Using optical character recognition, the images are examined for harmful content — including anything about international or domestic politics deemed undesirable by the Chinese Communist Party. It’s a self-reinforcing system that’s growing with every image sent. [[research summary](https://citizenlab.ca/2019/07/cant-picture-this-2-an-analysis-of-wechats-realtime-image-filtering-in-chats/)]

## Social credit systems

[Social Credit System](https://en.wikipedia.org/wiki/Social_Credit_System) - Using a secret algorithm, Sesame credit constantly scores people from 350 to 950, and its ratings are based on factors including considerations of “interpersonal relationships” and consumer habits. [[summary](https://www.theguardian.com/commentisfree/2018/mar/05/algorithms-rate-credit-scores-finances-data)][[Foreign Correspondent (video)](https://www.youtube.com/watch?v=eViswN602_k)][[travel ban](https://www.telegraph.co.uk/news/2018/03/24/chinas-social-credit-system-bans-millions-travelling/)]

[Health Insurance Credit System](https://www.theguardian.com/commentisfree/2018/mar/05/algorithms-rate-credit-scores-finances-data) - Health insurance companies such as [Vitality](https://www.vitality.co.uk/media/vitality-extends-active-rewards-with-apple-watch-series-3/) offer deals based on access to data from fitness trackers. However, they also can charge more and even remove access to important medical devices if patients are determined to be non-compliant to unfair pricing. [[ProPublica](https://www.propublica.org/article/you-snooze-you-lose-insurers-make-the-old-adage-literally-true)]

## Misleading platforms, and scams

[Misleading Show Robots](https://www.forbes.com/sites/noelsharkey/2018/11/17/mama-mia-its-sophia-a-show-robot-or-dangerous-platform-to-mislead/) - Show robots such as [Sophia](https://www.hansonrobotics.com/) are being used as a platform to falsely represent the current state of AI and to actively deceive the public into believing that current AI has human-like intelligence or is very close to it. This is especially harmful as it appeared on the world's leading forum for international security policy. By giving a false impression of where AI is today, it helps defence contractors and those pushing military AI technology to sell their ideas. [[Criticism by LeCun](https://www.facebook.com/yann.lecun/posts/10155025943382143)]

[Zach](https://thespinoff.co.nz/the-best-of/06-03-2018/the-mystery-of-zach-new-zealands-all-too-miraculous-medical-ai/) - an AI, developed by the Terrible Foundation, claimed to write better reports than medical doctors. The technology generated large media attention in New Zealand but turned out to be a [misleading scam](https://thespinoff.co.nz/the-best-of/09-03-2018/the-mystery-of-zach-the-miracle-ai-continued-it-all-just-gets-terribler/) aiming to steal money from investors. 

## Autonomous weapon systems and military

[Lethal autonomous weapons systems](https://autonomousweapons.org/)- Autonomous weapons locate, select, and engage targets without human intervention. They include, for example, [armed quadcopters (video)](https://www.youtube.com/watch?v=9CO6M2HsoIA) that can search for and eliminate enemy combatants in a city using facial recognition. [[NY Times (video)](https://www.youtube.com/watch?v=GFD_Cgr2zho)]

Known current autonomous weapons projects include:
- [Automated machine gun](https://www.youtube.com/watch?v=4OqmoHBvB0c) - The Kalashnikov group presented an automatic weapon control station using AI that provides the operator with automatic recognition and target illumination and automatic tracking of ground, air and sea targets. Samsung developed and deployed [SGR-A1](https://en.wikipedia.org/wiki/SGR-A1), a robot sentry gun, which uses voice recognition and tracking.
- [Armed UAVs](http://www.globaltimes.cn/content/1149168.shtml) - Ziyan UAV develops armed autonomous drones with light machine guns and explosives that can act in swarms
- [Autonomous Tanks](https://en.wikipedia.org/wiki/Unmanned_ground_vehicle) - Uran-9 is an autonomous tank, developed by Russia, that was tested in the [Syrian Civil War](https://nationalinterest.org/blog/buzz/russias-uran-9-robot-tank-went-war-syria-it-didnt-go-very-well-40677)

---

## Awful research

> 'Creative' awful research is getting accepted in AI's top scientific conference. This section gives out the *scariest paper award* for the most unethical research at a top-venue conference. Congratulations to the authors and also to the conference for missing ethical guidelines.

### NeurIPS 2019 'scariest paper award' 🥇 
[Face Reconstruction from Voice using Generative Adversarial Networks
](https://papers.nips.cc/paper/8768-face-reconstruction-from-voice-using-generative-adversarial-networks) - This paper addresses the challenge to reconstruct someone's face from their voice. Given an audio clip spoken by an unseen person, the proposed algorithm pictures a face that has as many common elements, or associations as possible with the speaker, in terms of identity. The model can generate faces that match several biometric characteristics of the speaker and results in matching accuracies that are much better than chance. [[code](https://github.com/cmu-mlsp/reconstructing_faces_from_voices)]
**Category: Surveillance**

[Predicting the Politics of an Image Using Webly Supervised Data
](https://papers.nips.cc/paper/8621-predicting-the-politics-of-an-image-using-webly-supervised-data) - This paper collects a dataset of over one million unique images and associated news articles from left- and right-leaning news sources, and develops a method to predict and adjust the image's political leaning, outperforming strong baselines. **Category: Discrimination**

## Contestational research

> Research to create a less awful and more privacy-preserving AI

[Differential Privacy](https://blog.cryptographyengineering.com/2016/06/15/what-is-differential-privacy/) - A formal definition of privacy that allows us to make theoretical guarantees on data breaches. AI algorithms can be trained to be differentially private. [[original paper](http://people.csail.mit.edu/asmith/PS/sensitivity-tcc-final.pdf)]

[Privacy-Preservation using Trusted Hardware](https://tvm.ai/2018/10/09/ml-in-tees.html) - AI algorithms that can run inside trusted hardware enclaves (or [private blockchains](http://www.vldb.org/pvldb/vol11/p2086-hynes.pdf) that build upon it) and train without any shareholder having access to private data.

[Privacy-Preservation using Secure Computation](https://mortendahl.github.io/2017/09/19/private-image-analysis-with-mpc/) - Using secure computation techniques like secret sharing, Yao's garbled circuits, or homomorphic encryption to train and deploy private machine learning models on private data using [existing machine learning frameworks](https://arxiv.org/abs/1810.08130).

[Fair Machine Learning & Algorithm Bias](https://thegradient.pub/ai-bias/) - A subfield in AI that investigates different fairness criteria and algorithm bias. A recent [best paper (in ICLR18)](https://bair.berkeley.edu/blog/2018/05/17/delayed-impact/), e.g. shows that implementing specific criteria can have a delayed impact on fairness.

[Adversarial Machine Learning](https://blog.openai.com/adversarial-example-research/) - Adversarial examples are inputs, which cause the model to make a mistake. Research in adversarial defences includes but is not limited to adversarial training, distillation and Defense-GAN.

## Contestational tech projects

> These open-source projects try to spur discourse, offer protection or awareness to awful AI

[BLM Privacy](http://blm.stanford.edu/) - AI facial recognition models can recognize blurred faces and is used by authorities to arrest protesters. BLM Privacy tries to discourage people from trying to recognize or reconstruct pixelated faces by masking people with an opaque mask. [[code](https://github.com/StanfordMLGroup/blm)]

[AdNauseam](https://adnauseam.io/) - AdNauseam is a lightweight browser extension to fight back against tracking by advertising networks. It works like an ad-blocker (it is built atop uBlock-Origin) to silently simulate clicks on each blocked ad, confusing trackers as to one's real interests. [[code](https://github.com/dhowe/AdNauseam)]

[Snopes.com](https://www.snopes.com/) - The Snopes.com website was founded by David Mikkelson, a project begun in 1994 and has since grown into the oldest and largest fact-checking site on the Internet, one widely regarded by journalists, folklorists, and laypersons alike as one of the world’s essential resources.

[Facebook Container](https://addons.mozilla.org/de/firefox/addon/facebook-container/) - Facebook Container isolates your Facebook activity from the rest of your web activity to prevent Facebook from tracking you outside of the Facebook website via third-party cookies. [[code](https://github.com/mozilla/contain-facebook)]

[TrackMeNot](https://cs.nyu.edu/trackmenot/) - TrackMeNot is a browser extension (Chrome, Firefox) that helps protect your online searches by creating fake search queries. This creates noise in data that makes it harder to track and profile user behaviour. [[code](https://github.com/vtoubiana/TrackMeNot)]

[Center for Democracy & Technology](https://cdt.info/ddtool/) - Digital Decisions is an interactive graphic that helps you ask the right questions when designing/implementing or building a new algorithm.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [David Dao](http://daviddao.org/) has waived all copyright and related or neighbouring rights to this work.
