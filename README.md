# KoGPT-Joong-2
[π€ Huggingface Hosted Model & Tokenizer](https://huggingface.co/snoop2head/KoGPT-Joong-2)

### KoGPT-Joong-2's Acrostic Poem Generation Examples (Nνμ μμ)

```
[μ°μΈλ(1)]
μ°λ―Όμ΄λΌλ κ²μ μλ μ κ²κ³Ό κ°λ€ 
μΈκΈ°μ μμ°μΌμλ..
λκ°λ νΉλν κ²μ΄λ€ μ°κΈ°μ λμ μμ²λ€

[μ°μΈλ(2)]
μ°μ½ν λ§μμΌλ‘ κ°ν μ²νμ§ λ§κ³  κ°ν λ§μμ λ¨Ήμ
μΈ λ§λ λ§λ³΄λ€ νλ§λ λ§μ΄ λ μ§μ μ± μμ΄ λ³΄μΈλ€.
λμ νμ§ λ§λΌ.
```

```
[μνν]
μκ·Έλ§νκ² 
νμμ κ°μ κ±΄λκ³  
νκ²½μ λλ¬΄λ₯Ό λμ΄κ°λ€
```

### KoGPT-Joong-2's Phrase Generation Examples
```
[λλ λμ]
- λλ λμ κ±°μ§λ§. λλ λμ μ°Έλ§. λλ₯Ό μμλ€λ λμ λλ₯Ό μμλ€λ λμ μ°¨μ΄.
- λλ λμ νμ λ€κ° λλ λΉμ΄λ©΄ λλ λ¬λΉμλ κ·Έμμμ΄ νΌμλ€.
```

```
[κ·Έλ μ λ΄ κΏμ]
- κ·Έλ μ λ΄ κΏμ λμ€μ§ μλ κ±ΈκΉμ, λ΄ κΏ μμμλ κ·Έλ μ¬λΌμ§λ©΄ μ΄μ©λμ
- κ·Έλ μ λ΄ κΏμ λΆμμ°©νλκ°.
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

- [κ°μ¬ λ°μ΄ν°μ](https://github.com/DongjunLee/char-rnn-tensorflow/tree/master/data/lyricskor)
- [κΈμ€νκ·Έλ¨ λ°μ΄ν°μ](https://github.com/Keracorn/geulstagram)

### Pretrained Model
For the backbone model, Ko-GPT-Trinity 1.2B was used. Ko-GPT-Trinity 1.2B is a transformer model which is SK telecom's replication of the GPT-3 architecture.


### References

- [Ko-GPT-Trinity Pretrained Model](https://huggingface.co/skt/ko-gpt-trinity-1.2B-v0.5/)
- [μμ€μ μμ±νλ KoGPT λͺ¨λΈ.](https://github.com/shbictai/narrativeKoGPT2)
- [μΈκ³΅μ§λ₯ μν μκ° λΈλ‘κ·Έ κΈ](https://jeinalog.tistory.com/entry/AI-x-Bookathon-%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5%EC%9D%84-%EC%88%98%ED%95%84-%EC%9E%91%EA%B0%80%EB%A1%9C-%ED%95%99%EC%8A%B5%EC%8B%9C%EC%BC%9C%EB%B3%B4%EC%9E%90) | [μΈκ³΅μ§λ₯ μν μκ° μ½λ](https://github.dev/jeina7/GPT2-essay-writer)
