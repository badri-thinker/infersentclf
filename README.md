# infersentclf
embedding for email body for classification
two modifications needed in the models.py file 
in get_w2v and get_w2v_k  add encoding="utf-8" in open()
to avoid stride errors  modify this line sent_len_sorted=sent_len_sorted.copy()   to avoid stride errors
