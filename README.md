# UTS Graf Sains Data - Recommender System (Neo4j & Python)

**Nama** : Moch Faiz Febriawan  
**NIM**  : 23031554068  
**Prodi**: S1 Sains Data, FMIPA Universitas Negeri Surabaya  

---

### Ringkasan Pengerjaan:
1. **Periode Filter Waktu**:
   - **Fold Training (P1)**: 08 Juni 2015 s.d. 10 Juni 2015 (`data/events_p1.csv`)
   - **Fold Testing (P2)** : 11 Juni 2015 s.d. 12 Juni 2015 (`data/events_p2.csv`)
2. **Model Graf**:
   - Database: Neo4j (Bipartite Graph: Visitor & Item)
   - Proyeksi Terbaik: Item-to-Item Projection (Hemat memori 35% & stabil)
3. **Hasil Evaluasi Rekomendasi k-NN (User 903378)**:
   - **Hit@5**  : **1.0000** (100% Hit pada Item 143866 di masa depan P2)
   - **NDCG@5** : **0.3869** (38.69%)
