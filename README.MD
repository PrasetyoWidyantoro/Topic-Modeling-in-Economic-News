# Driving Informed Decisions: Extracting Insights from LDA Topic Modeling in Economic News

## Pengantar

- `Topic Modeling menggunakan Latent Dirichlet Allocation (LDA) pada berita ekonomi dan bisnis` merupakan pendekatan mutakhir untuk menggali pola-pola utama yang muncul dari kumpulan berita tersebut. Dalam era pertumbuhan pesat informasi digital, penting bagi perusahaan media atau analis untuk dapat mengidentifikasi dan memahami isu-isu kunci yang tengah berkembang.

- `Topic-modeling LDA` dapat membantu memahami distribusi topik utama yang muncul dari artikel berita dan menciptakan pemahaman yang lebih mendalam terhadap isu-isu ekonomi dan bisnis yang tengah dibahas. Kumpulan data ini mencakup rincian berita ekonomi dan bisnis dengan variabel target berupa topik atau kategori berita tertentu.

- Dalam konteks ini, metrik evaluasi yang relevan dapat mencakup metrik khusus topik-modeling seperti `perplexity atau coherence score` untuk mengukur kualitas model LDA. Metrik ini membantu mengidentifikasi sejauh mana model dapat memberikan interpretasi yang jelas dan konsisten terhadap topik-topik yang muncul.

- Penulis menetapkan metrik bisnis sebagai acuan proyek analisis topik ini, yaitu `nilai perplexity yang lebih rendah dan coherence score yang lebih tinggi`. Perplexity yang lebih rendah menunjukkan bahwa model dapat memberikan prediksi yang lebih baik, sementara coherence score yang lebih tinggi menunjukkan bahwa interpretasi topik lebih konsisten dan bermakna.

- Hasil dari analisis topik ini dapat membantu pemangku kepentingan, seperti perusahaan media atau analis, untuk memahami tren dan isu-isu kunci yang tengah mendominasi dalam berita ekonomi dan bisnis. Dengan fokus pada topik-topik yang paling relevan, pemangku kepentingan dapat membuat keputusan yang lebih informasional dan responsif terhadap perubahan dalam dunia ekonomi dan bisnis.

## Kesimpulan 

- LDA modeling membantu dalam mengklasifikasikan topic berdasarkan kata kata kunci yang relevan
- Perplexity Multicore:  -7.597177412978327 menandakan semakin kecil valuenya maka lda topic modeling semakin baik, namun saya sadari butuh perbandingan dengan model lain
- Coherence Score Multicore:  0.3597606398050998 menandakan hasil dari LDA kurang cukup bermakna, namun cukup membantu untuk klasifikasi topic awal
- jika dilihat dari visualisasi LDA maka topic 1, 2, dan 3 memiliki kerakteriktik yang jauh berbeda ditandai dengan jauhnya letak Intertopic Distance Map pada masing masing topic

## Further Research

- menambahkan data berita agar bahasa yang dicerna oleh mesin jauh lebih banyak
- menggunakan metode topic modeling lain untuk perbandingan
- bisa ditambahkan pula untuk analisa sentiment analysis

## Sumber
    
- https://github.com/bryanoliveira/topic-modeling-lda/blob/main/twitter-support-topic-modeling.ipynb

- https://github.com/Nolanogenn/lda_topic_modeling/blob/master/topic_modelling_lda/topic%20modeling%20with%20lda.ipynb

- https://github.com/ktnegron/NLP-BBCNews-LDA-TopicModelling/blob/main/NLP_BBC_topic_modelling_%20.ipynb

- https://github.com/rsreetech/LDATopicModelling/blob/main/LDADemo.ipynb

- https://www.cs.wm.edu/~sunil/Topic%20Modeling.html