# 実践サイバーセキュリティ入門 現場に残された痕跡からハッカーの攻撃を暴け 正誤表

※ページ番号は初版時点のものです

| ページ | 誤 | 正 | 発生刷 | 登録日 |
| ---- | ---- | ---- | ---- | ---- |
| 080 | 図 2.4 環境寄生型（LotL）攻撃 | 図 2.5 環境寄生型（LotL）攻撃, ※図番号の誤り | 1刷 | 2025.08.25 | 
| 343 | 図 8.1 MAST（やるべきこと） | 図 8.1 MUST（やるべきこと）, ※図中のMUST記載の綴り誤り | 1刷 | 2025.08.27 |
| 156 | $ awk '{print $12\\}' access.log \| tr -d '"' \| sort \| uniq -c \| sort -nr | $ awk '{print $12}' access.log \| tr -d '"' \| sort \| uniq -c \| sort -nr, ※入力 4.8の'{print $12}'箇所に不要な「\」記号の挿入 | 1刷 | 2025.09.09 |
| 161 | $ grep '14/Jan/2021:05' access.log \| grep -E '119.241.22.121 \| 168.22.54.119' \| awk '{print $6\\}' \| cut -b 2-15 \| sort \| uniq -c | $ grep '14/Jan/2021:05' access.log \| grep -E '119.241.22.121 \| 168.22.54.119' \| awk '{print $6\}' \| cut -b 2-15 \| sort \| uniq -c, ※入力 4.12の'{print $6}'箇所に不要な「\」記号の挿入 | 1刷 | 2025.09.09 |
| 161 | $ grep '14/Jan/2021:05' access.log \| grep -E '119.241.22.121 \| 168.22.54.119' \| awk '{print $4\\}' \| cut -b 2-18 \| sort \| uniq -c | $ grep '14/Jan/2021:05' access.log \| grep -E '119.241.22.121 \| 168.22.54.119' \| awk '{print $4\}' \| cut -b 2-18 \| sort \| uniq -c, ※入力 4.13の'{print $4}'箇所に不要な「\」記号の挿入 | 1刷 | 2025.09.09 |
| 161 | $ grep '14/Jan/2021:05' access.log \| grep -E '119.241.22.121 \| 168.22.54.119' \| awk -F '"' '{print $2\\}' \| sort \| uniq -c \| sort -r \| head -n 20 | $ grep '14/Jan/2021:05' access.log \| grep -E '119.241.22.121 \| 168.22.54.119' \| awk -F '"' '{print $2\}' \| sort \| uniq -c \| sort -r \| head -n 20, ※入力 4.14の'{print $2}'箇所に不要な「\」記号の挿入 | 1刷 | 2025.09.09 |
| 163 | $ grep '14/Jan/2021:06' access.log \| grep 'POST' \| grep -v '403' \| awk '{print $1\\}' \| sort \| uniq -c \| sort -nr | $ grep '14/Jan/2021:06' access.log \| grep 'POST' \| grep -v '403' \| awk '{print $1\}' \| sort \| uniq -c \| sort -nr, ※入力 4.16の'{print $1}'箇所に不要な「\」記号の挿入 | 1刷 | 2025.09.09 |
| 152 | $ cat access.log \| awk '{print $1\\}' \| sort \| uniq -c \| sort | $ cat access.log \| awk '{print $1\}' \| sort \| uniq -c \| sort, ※入力 4.4の'{print $1}'箇所に不要な「\」記号の挿入 | 1刷 | 2025.09.09 |