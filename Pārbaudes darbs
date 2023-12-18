def izrekinat_linoleja_cenu(cena_par_m^2, rulla_platums, telpas_platums, telpas_garums):
    laukums = telpas_platums * telpas_garums
    kopeja_izmaksa = cena_par_m^2 * laukums / rulla_garums
    return kopeja_izmaksa

def get_valid_input(prompt):
    while True:
        user_input = input(prompt)
        try:
            user_input = float(user_input)
            if user_input >= 0:
                return user_input
            else:
            print("Lūdzu, ievadiet pozitīvu skaitli.")
        except ValueError:
            print("Lūdzu, ievadiet skaitli.")

cena_par_m^2 = get_valid_input("Ievadiet linoleja cenu par kvadrātmetru (EUR/m²): ")
rulla_platums = get_valid_input("Ievadiet linoleja ruļļa platumu (m): ")
telpas_platums = get_valid_input("Ievadiet telpas platumu (m): ")
telpas_garums = get_valid_input("Ievadiet telpas garumu (m): ")

kopeja_cena = (price_per_sqm, roll_width, room_width, room_length)
print("Linoleja kopējās izmaksas telpā ir {total_cost:.2f} EUR.")

