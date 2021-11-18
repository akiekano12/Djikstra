# Algoritma-Dijkstra

Algoritma Dijkstra, (dinamai menurut penemunya, seorang ilmuwan komputer, Edsger Dijkstra), adalah sebuah algoritme rakus (greedy algorithm) yang dipakai dalam memecahkan permasalahan jarak terpendek (shortest path problem) untuk sebuah graf berarah (directed graph) dengan bobot-bobot sisi (edge weights) yang bernilai tak-negatif.
Misalnya, bila vertices dari sebuah graf melambangkan kota-kota dan bobot sisi (edge weights) melambangkan jarak antara kota-kota tersebut, maka algoritme Dijkstra dapat digunakan untuk menemukan jarak terpendek antara dua kota.
Input algoritme ini adalah sebuah graf berarah yang berbobot (weighted directed graph) G dan sebuah sumber vertex s dalam G dan Vadalah himpunan semua vertices dalam graph G.
Setiap sisi dari graf ini adalah pasangan vertices (u,v) yang melambangkan hubungan dari vertex u ke vertex v. Himpunan semua tepi disebut E.
Bobot (weights) dari semua sisi dihitung dengan fungsi

w: E → [0, ∞)

jadi w(u,v) adalah jarak tak-negatif dari vertex u ke vertex v.
Ongkos (cost) dari sebuah sisi dapat dianggap sebagai jarak antara dua vertex, yaitu jumlah jarak semua sisi dalam jalur tersebut. Untuk sepasang vertex s dan t dalam V, algoritme ini menghitung jarak terpendek dari s ke t.
https://id.wikipedia.org/wiki/Algoritme_Dijkstra
