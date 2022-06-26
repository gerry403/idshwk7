使用变换颜色最后一个bit的位数来隐藏信息。
使用github上项目LSB-Steganography
使用以下命令加解密info文件内容为57119323 葛誉炜
python3 LSBSteg.py encode -i test.png -o output2.png -f info.txt
python3 LSBSteg.py decode -i output2.png -o info2.txt
结果正确。