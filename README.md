# BeliN
This is the official repository contains the code, data, and models of the paper titled [**"BeliN: A Novel Corpus for Bengali Religious News Headline Generation using Contextual Feature Fusion"**](https://)
## Citation
If you find this work useful for your research, please consider citing:

## Dataset Overview
![image](https://github.com/user-attachments/assets/1e271aa2-104b-4b06-9a75-26f122423d47)
![image](https://github.com/user-attachments/assets/d5182fd9-01a2-45b3-98e6-403ce097a0f0)

### Table: Descriptive statistics of the BeliN corpus
![image](https://github.com/user-attachments/assets/2ea07626-160f-4a1a-b689-c8df4f24887a)

### Table: List of Newspapers Curated for Data
| Newspaper    | URL                     |
|--------------|-------------------------|
|Prothom alo	 |https://www.prothomalo.com/religion|
|Kaler kantho	|https://www.kalerkantho.com/online/Islamic-lifestylie|
|Bangladesh pratidin|	https://www.bd-pratidin.com/islam|
|NayaDiganta	|https://www.dailynayadiganta.com/diganta-islami-jobon/133|
|Jugantor	|https://www.jugantor.com/all-news/islam-life|
|Daily Ittefaq	|https://www.ittefaq.com.bd/religion|
|Samakal	|https://samakal.com/search?q=religion|
|Dhaka Tribune	|https://www.dhakatribune.com/topic/religion|
|Bhorer Kagoj	|https://www.bhorerkagoj.com/religion|
|Jai Jai Din	|https://www.jaijaidinbd.com/islam-and-religion|
|Alokito Bnagladesh	|https://www.alokitoBengalidesh.com/islam|
|Daily Inqilab	|https://dailyinqilab.com/islamic-world|
|Daily Vorer Pata|	https://www.dailyvorerpata.com/cat.php?cd=293|
|Daily Khabar Patra	|https://khoborpatrabd.com/?s=religion|

## Model checkpoints - https://huggingface.co/mdosama39
|Approach | Model | Hugging Face API|
|------------|----------|----------|
Baseline| Bangla T5| mdosama39/banglat5-finetuned-new-method-new|
| |mBART| mdosama39/mbart-large-50-headline-base|
||mT5| mdosama39/mt5-base-headline-base|
||mT0| mdosama39/mt0-base-headline-base|
|MultiGen|Bangla T5| mdosama39/banglat5-headline-Final|
||mBART| mdosama39/mbart-large-50-headline_WithIp|
||mT5| mdosama39/mt5-base-headline_WithIp|
||mT0| mdosama39/mt0-base-headline_WithIp|

## Contributors
- Md Osama (osama_cse@baust.edu.bd)
- Ashim Dey (ashim@cuet.ac.bd)
- Kawsar Ahmed (kawsarcse18@gmail.com)
- Professor Ashad Kabir (akabir@csu.edu.au)
  
## License
Contents of this repository are restricted to only non-commercial research purposes under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). Copyright of the dataset contents belongs to the original copyright holders.

