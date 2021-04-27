# igbotFix
* The Original instabot code is no longer maintaned. <br>
* Here Is some fixs I made to run this in my python-3.7.9 <br>
* This file keeps track of the changes I made to the original files. <br>


--------------------------
--------------------------
--------------------------


## 1. Total commented on 0 medias.
![NO comments](https://user-images.githubusercontent.com/71658024/116228184-c2233980-a776-11eb-986c-e0db07e8b851.jpg) <br>

I only figured out `check_media()` is always returning `False` so I commented it out from `bot_comment.py`. <br> 

#### ¯\\\_(ツ)\_/¯ <br>
![NO comments fix](https://user-images.githubusercontent.com/71658024/116227568-1bd73400-a776-11eb-9622-18c9bad56882.jpg) <br>



---
## 2. UnicodeDecodeError: 'charmap' codec can't decode
![UnicodeDecodeError](https://user-images.githubusercontent.com/71658024/116223186-19261000-a771-11eb-9819-c97063114d7c.jpg) <br>

#### added `encoding="utf8"` to File open functions..
![encoding](https://user-images.githubusercontent.com/71658024/116225178-54294300-a773-11eb-9117-a394884f076d.jpg) <br>

- in these files
    - utils.py
    - bot_stats.py
    - api.py
    - api_login.py
    - api_photo.py `x`
    - api_story.py `x`
    - api_video.py `x`
    - bot_checkpoint.py `x`
    - prepare.py
<br>

**Didn't change those opend in binary mode** marked as `x`

still showing some errors though (¬‿¬)

---
---
