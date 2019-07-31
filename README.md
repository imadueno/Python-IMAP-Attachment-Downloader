# Python-IMAP-Attachment-Downloader
Download attachments from IMAP server using Python script
## Cómo se usa?
Segun la versión de Pyhon que tengamos instalada, se ejecuta el siguiente comando en terminal.
```bash
$ pip install attachment-downloader
```
En mi caso, tengo Python3.
```bash
$ pip3 install attachment-downloader
```
## Descarga de adjuntos
Para realizar la descarga debemos especificar los siguientes parametros
```bash
$ attachment-downloader --host imap.example.com --username mail@example.com --password pa55word \\
    --imap-folder invoices --output ~/Downloads
```
