# Chatbot Projesi

Bu proje, Karar Destek Sistemleri dersi kapsamında Google Gemma-2b dil modeli ile geliştirilmiş yapay zeka tabanlı bir soru-cevap sistemidir.  
Bir teknoloji mağazasına ait temel politika bilgileri kullanılarak kullanıcı sorularına kontrollü cevaplar üretilmesi amaçlanmıştır.


## Projenin Amacı

Bu çalışmanın amacı, yapay zeka destekli bir karar destek sistemi geliştirerek **fine-tuning** ve **RAG (Retrieval-Augmented Generation)** yaklaşımlarını basit bir senaryo üzerinde uygulamaktır.

---

## Kullanılan Yöntemler

- **Fine-Tuning (LoRA):**  
  Dil modelinin mağaza asistanı gibi cevap verebilmesi için örnek soru-cevaplar ile eğitilmesi amacıyla kullanılmıştır.

- **RAG (Retrieval-Augmented Generation):**  
  Modelin cevap üretirken yalnızca mağaza dokümanlarını kullanmasını sağlamak ve alakasız sorular için cevap üretmesini engellemek amacıyla uygulanmıştır.

---

## Kullanılan Teknolojiler

- **Python:** Projenin geliştirildiği programlama dili  
- **Hugging Face Transformers:** Dil modelinin yüklenmesi ve metin üretimi  
- **PEFT (LoRA):** Modelin düşük maliyetle fine-tune edilmesi  
- **FAISS:** Dokümanlar üzerinde benzerlik araması yapılması  
- **Gradio:** Kullanıcı etkileşimi için web arayüzü  
- **LangChain (yardımcı bileşenler):** Metin bölme ve embedding işlemleri  

---

## Sonuç

Bu projede, karar destek sistemleri kapsamında **fine-tune edilmiş** ve **RAG destekli** bir yapay zeka soru-cevap sistemi geliştirilmiştir.  
Sistem, yalnızca verilen dokümanlara dayalı cevap üretmekte ve kontrolsüz bilgi üretimini engellemektedir.
