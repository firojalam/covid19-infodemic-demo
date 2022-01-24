# API Services for COVID-19 related Information
This repository contains scripts and instructions to access API services of COVID-19-infodemic system.
The API services consists of seven different questions (discussed in **["Fighting the COVID-19 Infodemic: Modeling the Perspective of Journalists, Fact-Checkers, Social Media Platforms, Policy Makers, and the Society"](https://aclanthology.org/2021.findings-emnlp.56/)**) that are of interest to journalists, fact-checkers, social media platforms, policymakers, and society as a whole. The models associated with API services include binary and fine-grained classification of tweets in four different languages: Arabic, Bulgarian, Dutch, and English.

## How to use?
Please check the [client.ipynb](#client.ipynb).

## Resources
- API endpoints: [https://app.swaggerhub.com/apis/yifan2019/Tanbih/0.8.0#/default/post_covid19disformation__language__](https://app.swaggerhub.com/apis/yifan2019/Tanbih/0.8.0#/default/post_covid19disformation__language__)
- Online Demo: [https://covid19.tanbih.org](https://covid19.tanbih.org)

## Related References
Please also cite the following papers if you are using the API services for your work.

1. *Firoj Alam and Shaden Shaar and Fahim Dalvi and Hassan Sajjad and Alex Nikolov and Hamdy Mubarak and Giovanni Da San Martino and Ahmed Abdelali and Nadir Durrani and Kareem Darwish and Abdulaziz Al-Homaid and Wajdi Zaghouani and Tommaso Caselli and Gijs Danoe and Friso Stolk and Britt Bruntink and Preslav Nakov, "Fighting the COVID-19 Infodemic: Modeling the Perspective of Journalists, Fact-Checkers, Social Media Platforms, Policy Makers, and the Society", Findings of EMNLP 2021,  [download](https://arxiv.org/abs/2005.00033).*

2. *Firoj Alam, Fahim Dalvi, Shaden Shaar, Nadir Durrani, Hamdy Mubarak, Alex Nikolov, Giovanni Da San Martino,3Ahmed Abdelali,1Hassan Sajjad,1Kareem Darwish,1Preslav Nakov, "Fighting the COVID-19 Infodemic in Social Media: A Holistic Perspective and a Call to Arms", Proceedings of the International AAAI Conference on Web and Social Media. (Vol. 15, pp. 913-922). 2021. [download](https://ojs.aaai.org/index.php/ICWSM/article/view/18114/17917).*

```bib
@inproceedings{alam2020fighting,
    title={Fighting the {COVID}-19 Infodemic: Modeling the Perspective of Journalists, Fact-Checkers, Social Media Platforms, Policy Makers, and the Society},
    author={Firoj Alam and Shaden Shaar and Fahim Dalvi and Hassan Sajjad and Alex Nikolov and Hamdy Mubarak and Giovanni Da San Martino and Ahmed Abdelali and Nadir Durrani and Kareem Darwish and Abdulaziz Al-Homaid and Wajdi Zaghouani and Tommaso Caselli and Gijs Danoe and Friso Stolk and Britt Bruntink and Preslav Nakov},
    booktitle = {Findings of EMNLP 2021},
    year={2021},
    url={https://aclanthology.org/2021.findings-emnlp.56/}
}

@InProceedings{alam2020call2arms,
  title		= {Fighting the {COVID}-19 Infodemic in Social Media: A
		  Holistic Perspective and a Call to Arms},
  author	= {Alam, Firoj and Dalvi, Fahim and Shaar, Shaden and
		  Durrani, Nadir and Mubarak, Hamdy and Nikolov, Alex and {Da
		  San Martino}, Giovanni and Abdelali, Ahmed and Sajjad,
		  Hassan and Darwish, Kareem and Nakov, Preslav},
  year		= {2021},
  pages		= {913-922},
  month	= {May},
  volume	= {15},
  booktitle	= {Proceedings of the International {AAAI} Conference on Web
		  and Social Media},
  series	= {ICWSM~'21},
  url		= {https://ojs.aaai.org/index.php/ICWSM/article/view/18114}
}
```
