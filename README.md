# UMUSP at SemEval-2026 Task 9: Mitigating Cross-Lingual Interference
via Selective Multilingual and Multitask Specialization
UMUSP at SemEval-2026 Task 9: Mitigating Cross-Lingual Interference via Selective Multilingual and Multitask Specialization
This paper proposes a selective multilingual
and multitask fine-tuning strategy for online po-
larization detection that improves cross-lingual
stability over fully joint training. Covering
all three subtasks — polarization detection
(POLARDETECT), polarization type classifi-
cation (POLARTYPE), and rhetorical mani-
festation identification (POLARMANIFEST) —
across all 22 languages of the shared task, the
approach introduces controlled specialization,
where languages and subtasks are grouped em-
pirically and separate specialist models are
fine-tuned for each subset. Restricting parame-
ter sharing substantially improves performance
even without ensemble averaging, whereas en-
sembling jointly trained models fails to mit-
igate instability. The final specialist ensem-
ble improves Task 3 macro-F1 from 0.3330
to 0.4920 and reduces cross-lingual dispersion
(CV: 0.613 → 0.321). Under the official rank-
ing framework, the system ranks 7th among
16 submissions with complete multilingual and
multitask coverage and remains within 5% of
the best system in 37.70% of evaluation condi-
tions.
