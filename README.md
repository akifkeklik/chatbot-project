# Karar Destek Sistemleri Projesi

Bu proje, Karar Destek Sistemleri dersi kapsamında geliştirilmiş basit bir yapay zeka tabanlı soru-cevap uygulamasıdır.  
Bir teknoloji mağazasına ait temel bilgiler kullanılarak kullanıcı sorularına kontrollü cevaplar üretilmesi amaçlanmıştır.


## Proje Amacı

Projenin amacı, verilen dokümanlara dayalı çalışan bir karar destek sistemi geliştirmek ve RAG yaklaşımını uygulamalı olarak göstermektir.

---

## Kullanılan Yöntem

- Google Gemma 2B modeli LoRA yöntemi ile fine-tune edilmiştir.
- Mağaza politikaları vektör veritabanında tutulmuştur.
- Kullanıcı soruları, ilgili dokümanlar ile eşleştirilerek cevaplanmıştır.
- Alakasız sorular için sistem cevap üretmemektedir.

---

## Kullanılan Teknolojiler

- Python  
- Hugging Face Transformers  
- PEFT (LoRA)  
- LangChain  
- FAISS  
- Gradio  

---

## Sonuç

Bu çalışmada, karar destek sistemleri kapsamında basit bir yapay zeka destekli soru-cevap sistemi geliştirilmiş ve RAG yaklaşımı uygulanmıştır.
