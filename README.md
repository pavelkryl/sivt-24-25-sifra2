
# Base64

zakódujte do base64 větu "alkohol, to je prevít"

# Šifrování

navrhněte funkci encrypt_file(), která:
- vstup:
	- `key`: 32 bytový klíč zakódovaný base64 (rovnou tak jako ho vrátí generátor Fernetu)
    - `in_file`: název souboru k zašifrování
    - `out_file`: název výsledného zašifrovaného souboru
- výstup (vedlejší efekt):
    zapíše do souboru `out_file` zašifrovaný obsah pomocí knihovny Fernet

výsledný `out_file` může být textový nebo binární, napište jakou variantu jste si vybrali

ověřte funkčnost na zakódování opravdového binárního souboru


# Bonus

udělejte opačnou funkci decrypt_file(), která bude dělat dešifrování vašeho zašifrovaného souboru