# Merge-Sort-Projesi 

patika.dev linkim: https://app.patika.dev/cmilakonur <br />

[16,21,11,8,12,22] -> Merge Sort <br />
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. <br />

Başlangıçta dizimizi ikiye bölüyoruz. Bölünen dizileri tekrar bölüyoruz. <br />

1.Adım : Diziyi ikiye bölerek yeniden yazıyoruz. &emsp; &emsp;&emsp;  &emsp;&emsp;&emsp;          [16,21,11,8,12,22] <br />
2.Adım : Sol ve sağdaki dizileri tekrar ikiye böluyoruz. &emsp;&emsp;&emsp;  [16,21,11] • [8,12,22]  <br />
3.Adım : Tek eleman kalana kadar bir kez daha bölüyoruz. &emsp;	 [16,21] • 11 • 8 • [12,22] <br />
Bölme işlemi bitikten sonra, tek elemanlı dizilerimizi ikili ikili birleştiriyoruz. <br />
4.Adım : &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 16 • 21 • 11 • 8 • 12 • 22  <br />
5.Adım : ikili ikili ikili sıralayarak birleştiriyoruz. &emsp; [16,21] • 11 • 8 • [12,22] <br />
6.Adım : Tekrar ikili ikili sıralayarak birleştiriyoruz. &emsp;  [11,16,21] • [8,12,22] <br />
7.Adım : Son birleştirmede dizimizi elde ediyoruz. &emsp;     [8,11,12,16,21,22] <br />

Big-O gösterimini yazınız. <br />
O(n*(logn)) --> O(6*(log6))  
