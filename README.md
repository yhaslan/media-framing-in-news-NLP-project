# Media Framing in News NLP Project
Media framing in news on Israeli Occupation in Gaza in 2023

This analysis was performed for the final project of Empirical Methods course of Master 2 in Economie du Développement Durable of Univesité de Paris 1 Panthéon-Sorbonne in collaboration with Elif Çanga.

### :warning: Content Warning: Sensitive Material :warning:
The content analyzed in this repository may contain historically and culturally sensitive terms as well as references to violent themes, consequences of genocide, death and human suffering. Reader discretion is advised. The information provided may be distressing or triggering to some individuals. Proceeding further acknowledges your understanding and acceptance of encountering such sensitive subject matter.

## Research Question
The purpose of this analysis is to explore how two media from two different countries covered the events following the 7 October in their news, and to feed the discussions on how the reality can be constructed in the media in different ways by using different NLP techniques in the context of what was described as genocide by the UN Commission of Inquiry a year after our analysis. In this regard, we conducted a media framing analysis, examining the news of the Qatari media Al-Jazeera and the British media BBC, in which we detected differences in their reporting strategies.

## Why This Question?

As far as the occupation is concerned, whose origins go back to 1948, the issue has always received a good share of international media coverage. However, 7 October attacks signaled beginning of a new phase, which was to be marked also by an unprecedented battle over controling the narrative, and gaining legitimacy in public opinion. Hence,  the language and discourses in the news coverage became more important than ever.

An analysis conducted by the [Glasgow Media Group in 2011](https://www.glasgowmediagroup.org/downloads/17-war-and-conflict) compared the language used by journalists for Israelis and Palestinians reviewing the BBC's news broadcasts. They found that while terms such as “brutal murder”, “mass murder”, and “massacre” were used to describe the deaths of Israelis, Palestinians were linked with "terrorism".

Our data comes from and compare these two sources:
- A Qatari news giant Al-Jazeera, with an openly pro-Palestine position
- and BBC News, which [has recently been criticized](https://thewire.in/media/dead-versus-killed-a-closer-look-at-the-media-bias-in-reporting-israel-palestine-conflict) for an allegedly deliberate narrative differences when reporting Palestinian vs Israeli fatalities.

Taking into account those recent controversies and the discussions about media framing from the exising literature, and leveraging the NLP and Machine Learning techniques, this study aims to assess quantitatively whether those news coverages cited by the critics were isolated cases or whether they represent a systemmatic reporting strategy in the coverage.

## Organization of this Repository:
In this repository you will find:
- _Web Scraping_ folder showing our code for scraping and storing the news from 7 October to 31 December 2023 on this issue from BBC and Aljazeera news websites
- media_framing_in_news.ipynb for our analyses and visualizations
- _data_ folder containing the cleaned version of our main data all_news.json, a subset of the data (df_death.json) which we used for media framing in reporting of fatalities, and a labeled version of that subset by the algorithm we trained (df_death_pred.json)
- _Model_ folder where you can find the notebook for our sentence classification algorithm which we trained on AI-generated data to predict whether a sentence (given that it makes reference to deaths) reports Palestinian fatalities or Israeli fatalities
- NLP_project-Elif&Yagmur.pdf file where you can see our poster for the course.
