# KoGPT-Joong-2
[🤗 Huggingface Hosted Model & Tokenizer](https://huggingface.co/snoop2head/KoGPT-Joong-2)

### KoGPT-Joong-2's Acrostic Poem Generation Examples (N행시 예시)

```
[연세대(1)]
연민이라는 것은 양날의 검과 같다 
세기의 악연일수도..
대가는 혹독할것이다 연기의 끝은 상처다

[연세대(2)]
연약한 마음으로 강한 척하지 말고 강한 마음을 먹자
세 마디 말보다 한마디 말이 더 진정성 있어 보인다.
대시 하지 마라.
```

```
[자탄풍]
자그마하게 
탄식의 강을 건너고 
풍경의 나무를 넘어가네
```

### KoGPT-Joong-2's Phrase Generation Examples
```
[너는 나의]
- 너는 나의 거짓말. 나는 너의 참말. 너를 잊었다는 나와 나를 잊었다는 너의 차이.
- 너는 나의 옷자락이고 머릿결이고 꿈결이고 나를 헤집던 사정없는 풍속이었다
```

```
[그대 왜 내 꿈에]
- 그대 왜 내 꿈에 나오지 않는 걸까요, 내 꿈 속에서도 그대 사라지면 어쩌나요
- 그대 왜 내 꿈에 불시착했는가.
```
---

### How to use KoGPT-Joong-2
```python
from transformers import AutoTokenizer, AutoModelWithLMHead
  
tokenizer = AutoTokenizer.from_pretrained("snoop2head/KoGPT-Joong-2")
model = AutoModelWithLMHead.from_pretrained("snoop2head/KoGPT-Joong-2")
```

For specific inference codes, please refer to [inference_finetuned_35000-step.ipynb file](https://github.com/snoop2head/KoGPT-Joong-2/blob/main/inference_finetuned_35000-step.ipynb)

### Dependencies Installation

```bash
pip install -r requirements.txt
```
---

### Dataset finetuned on

- [가사 데이터셋](_clones/char-rnn-tensorflow/data/lyricskor/input.txt)
- [글스타그램 데이터셋](https://github.com/Keracorn/geulstagram)

### References

- [KoGPT2-Transformers huggingface 활용 예시](https://github.com/taeminlee/KoGPT2-Transformers)
- [SKT-AI의 KoGPT2와 pytorch를 이용해 소설을 생성하는 GPT-2 모델.](https://github.com/shbictai/narrativeKoGPT2)
- [인공지능 수필 작가 블로그 글](https://jeinalog.tistory.com/entry/AI-x-Bookathon-%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5%EC%9D%84-%EC%88%98%ED%95%84-%EC%9E%91%EA%B0%80%EB%A1%9C-%ED%95%99%EC%8A%B5%EC%8B%9C%EC%BC%9C%EB%B3%B4%EC%9E%90) | [인공지능 수필 작가 코드](https://github.dev/jeina7/GPT2-essay-writer)
