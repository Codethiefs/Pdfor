# Pdfor
> �汾 1.0.333

PdforΪһ���ƽ̨��pdfת������
���԰�doc��docx��xls��xlsx��ppt��pptx ��html��txt ���ļ�ת��Ϊpdf��ʽ��
ͨ��http api��ʽ�����ṩ����,�ӿڵ�ַΪ /Pdfor/ConvertToPdf��
���л���Ϊnet core 2.1��


linuxƽ̨֧��LibReOffice������
windowsƽ̨֧��ʹ��Office �� LibReOffice������



# docker����
pdfor����ͨ��docker����docker�����ַΪ sersms/pdfor

``` bash

# ǰ̨���� 
docker run -it --rm -p 4301:4301 sersms/pdfor


# ��̨���� 
docker run --name=pdfor --restart=always -p 4301:4301 sersms/pdfor

# ��������� http://ip:4301

```



