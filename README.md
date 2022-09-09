# ATTENTION!!
## All models and their derivatives provided on this page are prohibited from commercial use!
## 本页面提供的所有模型及其衍生物严禁商用！

# Tacotron2
Remember to change this line in ./inference.ipynb
```python
sequence = np.array(text_to_sequence(text, ['japanese_cleaners']))[None, :]
```
## Sanoba Witch

### Ayachi Nene 

| Cleaners  Classes | Model |
| ----------- | ----------- |
| japanese_cleaners      | [Model 1](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/ESltqOvyK3ZPsLMQwpv5FH0BoX8slLVsz3eUKwHHKkg9ww?e=vc5fdd) |
| japanese_tokenization_cleaners   | [Model 2](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/ETNLDYH_ZRpMmNR0VGALhNQB5-LiJOqTaWQz8tXtbvCV-g?e=7nf2Ec) |
|japanese_accent_cleaners| [Model 3](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/Eb0WROtOsYBInTmQQZHf36IBSXmyVd4JiCF7OnQjOZkjGg?e=qbbsv4) |



### Inaba Meguru

| Cleaners  Classes | Model |
| ----------- | ----------- |
| japanese_tokenization_cleaners | [Model 1](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/Ed29Owd-E1NKstl_EFGZFVABe-F-a65jSAefeW_uEQuWxw?e=J628nT)|
| japanese_tokenization_cleaners | [Model 2](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/ER8C2tiu4-RPi_MtQ3TCuTkBVRvO1MgJOPAKpAUD4ZLiow?e=ktT81t) |



## Senren Banka
### Tomotake Yoshino

| Cleaners Classes| Model |
| ----------- | ----------- |
| japanese_tokenization_cleaners| [Model 1](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EdfFetSH3tpMr7nkiqAKzwEBXjuCRICcvgUortEvE4pdjw?e=UyvkyI)|
| japanese_phrase_cleaners| [Model 2](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EeE4h5teC5xKms1VRnaNiW8BuqslFeR8VW7bCk7SWh2r8w?e=qADqbu)|


### Murasame

| Cleaners Classes| Model |
| ----------- | ----------- |
| japanese_accent_cleaners| [Model 1](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EVXUY5tNA4JOqsVL7of8GrEB4WFPrcZPRWX0MP_7G0RXfg?e=5wzBlw)|



## RIDDLE JOKER
### Arihara Nanami

| Cleaners Classes| Model |
| ----------- | ----------- |
| japanese_accent_cleaners|[Model 1](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EdxWxcjx5XdAncOdoTjtyK0BUvrigdcBb2LPmzL48q4smw?e=OlAU66)|

# VITS
## Online demo
- Integrated into [Huggingface Spaces 🤗](https://huggingface.co/spaces) using [Gradio](https://github.com/gradio-app/gradio). Try it out [![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/skytnt/moe-japanese-tts)
- Integrated into Azure Cloud Function by [fumiama](https://github.com/fumiama), see API [here](https://github.com/fumiama/MoeGoe).
- Integrated into Android APP using Azure Cloud Function API by [fumiama](https://github.com/fumiama) [![MoeGoe-Android](https://img.shields.io/badge/MoeGoe-Android-orange)](https://github.com/fumiama/MoeGoe-Android)
## Japanese
### Nene + Meguru + Yoshino + Mako + Murasame + Koharu + Nanami
Download [Config File](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/Ed7PXqaBdllAki0TPpeZorgBFdnxirbX_AYGUIiIcWAYNg?e=avxkWs)

Download [Model](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EXTQrTj-UJpItH3BmgIUvhgBNZk88P1tT_7GPNr4yegNyw?e=5mcwgl) (365 epochs)

Download [Model](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EYH0aVcuLbVAgdTVRjmNNDgB8xSSBINAIHByWL1tp97hWg?e=ZvegdK) (H excluded)
### Hiyori + Kano + Asumi + Sio + Ameri + Miri + Hiromu + Ririko
Download [Config File](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EbYG4z3PmwhKibN59Sb8GTkBHr7gvbz6tWtsuwkmtqB8oA?e=cbxH86)

Download [Model](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/ERNCwIXf51JGrkDODZ2Iy5oBpPKDPEvnd486ypQQyGmzZQ?e=1sSIED) (604 epochs)
### Zero no tsukaima
Download [Config File](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EYMl9Cv8Dh5PqVSv-0FwjQIB87UiayTKrx7WtsDu822SfQ?e=kzwdX9)

Download [Model](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EccGCxaWPs9LlYrtiQuQX-UBU7EmBXeMPL_oLS22xNtTrg?e=294P0A) (200 epochs)
## Korean
### Sua + Mimiru + Arin + Yeonhwa + Yuhwa + Seonbae
Download [Config File](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EYXC9IqILZFJqe0kyFjb9XwBuLldZnQBEMGJxI3h_iYX3w?e=Q4GrVH)

Download [Model](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/ERPxoGsG12lOn4LihxnwkGEBw3qil75tW__z-GAptnO2Iw?e=d077MU) (1164 epochs)
## Chinese & Japanese
### Nene + Nanami + Rong + Tang
Download [Config File](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EYZfZuW5jtxIqIesYOpFuB4BVWtItUIO2f9YxGQZelRxaQ?e=MCZPCL)

Download [Model](https://sjtueducn-my.sharepoint.com/:u:/g/personal/cjang_cjengh_sjtu_edu_cn/EQ0IKHchgzZAt0E6GryW17EBsIlIkmby6BcO9FtoODjwNQ?e=5uzWtj) (1374 epochs)
