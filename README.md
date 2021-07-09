[cleaned_dataset.zip](https://github.com/hannousse/Cleaned-PHP-Webshell-dataset/files/6792868/cleaned_dataset.zip)

[php_webshell_dataset.csv](https://github.com/hannousse/Cleaned-PHP-Webshell-dataset/files/6790823/php_webshell_dataset.csv)
# Cleaned-PHP-Webshell-dataset
This dataset is collected from available Github repositories. It incorporates a balanced number of PHP benign files and webshells. They are firstly cleaned using MD5 where eaach two files with the same MD5 hashes are considered duplicates. Afterwords, opcode sequences of the remaining files are generated, MD5 is applied to those sequences and duplicates with the same opcode sequences are removed. This may provide higher distinctive samples to be used for fair evaluation of automatic webshell detectors. The final dataset includes: 992 samples for each category. 
