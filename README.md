本專案以 MOTIP 為基底，改成 HiMOT 風格的多目標追蹤流程：逐幀 DETR 偵測、使用 decoder 最後一層 track embedding 作為身份表徵，並以軌跡解碼器預測下一幀的 embedding / bbox 來進行配對與更新。整體管線包含訓練與推論，支援 DanceTrack 等資料集的評估與視覺化。
