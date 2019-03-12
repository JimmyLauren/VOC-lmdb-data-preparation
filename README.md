# VOC-lmdb-data-preparation
instructions for building lmdb data from VOC formation images


D:\workspace\caffe-ssd-windows-master\build\tools\Release\convert_annoset 
--anno_type=detection 
--label_map_file='/media/liujian1/Ubuntu/DATASETS/Car_Detection/ShiPinJieGouHua-RenCheJianChe/LMDB/label_map/label_map.prototxt' 
--min_dim=0 
--max_dim=0 
--resize_height=0 --resize_width=0 
--shuffle=false 
--encode_type=jpg 
--encoded=true
/media/liujian1/Ubuntu/DATASETS/Car_Detection/ShiPinJieGouHua-RenCheJianChe/ 
'/media/liujian1/Ubuntu/DATASETS/Car_Detection/ShiPinJieGouHua-RenCheJianChe/LMDB/test1.txt' 
/media/liujian1/Ubuntu/DATASETS/Car_Detection/ShiPinJieGouHua-RenCheJianChe/LMDB/LMDB/test
