# Vytvoří seznam ze zkopírovaného seznamu
models = ["Chat GPT", "Claude", "Bard", "Gemini"]

kamiony = [
    "Scania R500",
    "Scania S730",
    "Volvo FH16",
    "Volvo FMX",
    "MAN TGX 18.640",
    "MAN TGS 26.480",
    "Mercedes-Benz Actros 1863",
    "Mercedes-Benz Arocs 3251",
    "DAF XF 530",
    "DAF CF 480",
    "Iveco S-Way 570",
    "Iveco Stralis 510",
    "Renault T High 520",
    "Renault C 480",
    "Kamaz 54901",
    "Tatra Phoenix 158",
    "Freightliner Cascadia",
    "Kenworth W990",
    "Peterbilt 579",
    "Mack Anthem"
]

# Přidám do listu další položku
kamiony.append("Iveco X-Way 600")

# Odstraní z listu první prvek
kamiony.pop(0)

# Vypíše délku seznamu
print(f"Délka seznamu: {len(kamiony)}")

# Vypíše celý seznam
print(kamiony)
