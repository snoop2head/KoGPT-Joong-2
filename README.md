### Wandb Log

https://wandb.ai/snoop2head/huggingface/runs/303yd9c0

### 문학적 운율과 의미를 지닌 데이터셋

**Dataset to finetune on**

- [가사 데이터셋](_clones/char-rnn-tensorflow/data/lyricskor/input.txt)
- [인스타그램 데이터셋](https://drive.google.com/drive/u/0/folders/1KNbBE5ENNzwT6A_GyAmyaofJUyBcFkQ4)

### 사용할 Generative 모델들

**Transformer based generative models**
The project will compare each generative models' outcome.

- [KoGPT by KakaoBrain](https://github.com/kakaobrain/kogpt)
- [KoBART](https://github.com/SKT-AI/KoBART)
- [KoGPT3](https://huggingface.co/skt/ko-gpt-trinity-1.2B-v0.5)
- [KoGPT2](https://huggingface.co/taeminlee/kogpt2)
- [KoElectra](https://github.com/monologg/KoELECTRA)
- [Tunib Electra](https://github.com/tunib-ai/tunib-electra)
- [KCElectra](https://huggingface.co/beomi/KcELECTRA-base)
- [klue/roberta-large](https://huggingface.co/klue/roberta-large)

### Installation

```bash
pip install -r requirements.txt
```

### References

- [KoGPT2-Transformers huggingface 활용 예시](https://github.com/taeminlee/KoGPT2-Transformers)
- [Simple Chit-Chat based on KoGPT2](https://github.com/haven-jeon/KoGPT2-chatbot)
- [KoGPT2-FineTuning](https://github.com/gyunggyung/KoGPT2-FineTuning)
- [SKT-AI의 KoGPT2와 pytorch를 이용해 소설을 생성하는 GPT-2 모델.](https://github.com/shbictai/narrativeKoGPT2)
- [가사 작사 KoGPT2](https://github.com/forus-ai/KoGPT2-Lyrics-Generation-FineTuning-Version1)
- [인공지능 수필 작가 블로그 글](https://jeinalog.tistory.com/entry/AI-x-Bookathon-%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5%EC%9D%84-%EC%88%98%ED%95%84-%EC%9E%91%EA%B0%80%EB%A1%9C-%ED%95%99%EC%8A%B5%EC%8B%9C%EC%BC%9C%EB%B3%B4%EC%9E%90) | [인공지능 수필 작가 코드](https://github.dev/jeina7/GPT2-essay-writer)
