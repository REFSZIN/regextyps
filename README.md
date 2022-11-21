# regextyps
{
    "cnpj": [
        {
            "regex": "([0-9]{2}[\\.]?[0-9]{3}[\\.]?[0-9]{3}[\\/]?[0-9]{4}[-]?[0-9]{2})|([0-9]{3}[\\.]?[0-9]{3}[\\.]?[0-9]{3}[-]?[0-9]{2})",
            "description": "Cadastro Nacional da Pessoa Jurídica"
        }
    ],
    "cpf": [
        {
            "regex": "[0-9]{3}\\.?[0-9]{3}\\.?[0-9]{3}\\-?[0-9]{2}",
            "description": "Cadastro de Pessoas Físicas"
        }
    ],
    "rg": [
        {
            "regex": "(\\d{1,2}\\.?)(\\d{3}\\.?)(\\d{3})(\\-?[0-9Xx]{1})",
            "description": "Registro Geral"
        }
    ],
    "cnh": [
        {
            "regex": "((cnh.*[0-9]{11})|(CNH.*[0-9]{11})|(habilitação.*[0-9]{11})|(carteira.*[0-9]{11}))",
            "description": "Carteira Nacional de Habilitação"
        }
    ],
    "cep": [
        {
            "regex": "(^[0-9]{5})-?([0-9]{3}$)",
            "description": "Código de Endereçamento Postal "
        }
    ],
    "rne": [
        {
            "regex": "(RNE)([A-Z\\d])(\\d{6})([A-Z\\d])",
            "description": "Registro Nacional de Estrangeiro"
        }
    ],
    "renavam": [
        {
            "regex": "((\\d{4})[.](\\d{6})-(\\d{1})|(\\d{4})(\\d{6})(\\d{1}))",
            "description": "Registro Nacional de Veículos Automotores"
        }
    ],
    "boleto": [
        {
            "regex": "(\\d{5}[\\.]\\d{5}[\\s]\\d{5}[\\.]\\d{6}[\\s]\\d{5}[\\.]\\d{6}[\\s]\\d[\\s]\\d{14})|(\\d{47,48})|(\\d{12} \\d{12} \\d{12} \\d{12})",
            "description": "Boleto Bancário e Linha Digitável"
        }
    ],
    "pixChaveRandom": [
        {
            "regex": "([a-z\\d]{8})\\-([a-z\\d]{4})\\-([a-z\\d]{4})\\-([a-z\\d]{4})\\-([a-z\\d]{12})",
            "description": "Chave PIX Aleatória"
        }
    ],
    "crm": [
        {
            "regex": "([0-9-\/]{5,11})(?i)[a-z]{2}",
            "description": "Conselho Federal de Medicina"
        }
    ],
    "telefone": [
        {
            "regex": "(?:(?:\\+|00)?(55)\\s?)?(?:\\(?([1-9][0-9])\\)?\\s?)(?:((?:9\\d|[2-9])\\d{3})\\-?(\\d{4}))",
            "description": "Telefone Brasil"
        }
    ],
    "bitcoin": [
        {
            "regex": "^(bc1|[13])[a-zA-HJ-NP-Z0-9]{25,39}$",
            "description": "Endereço wallet bitcoin"
        }
    ],
    "url": [
        {
            "regex": "https?:\\/\\/(www\\.)?[-a-zA-Z0-9@:%._\\+~#=]{1,256}\\.[a-zA-Z0-9()]{1,6}\\b([-a-zA-Z0-9()!@:%_\\+.~#?&\\/\\/=]*)",
            "description": "URL - Uniform Resource Locator"
        }
    ],
    "email": [
        {
            "regex": "[^@ \\t\\r\\n]+@[^@ \\t\\r\\n]+\\.[^@ \\t\\r\\n]+",
            "description": "Endereço de email"
        }
    ],
    "ip": [
        {
            "regex": "[[:digit:]]{1,3}\\.[[:digit:]]{1,3}\\.[[:digit:]]{1,3}\\.[[:digit:]]{1,3}",
            "description": "IP - Internet Protocol"
        }
    ]
}
