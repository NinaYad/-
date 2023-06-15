from tkinter import *
from tkinter import font
from tkinter import messagebox

okno = Tk()
okno['bg'] = '#8f8fbc'
okno.title('Калькулятор')
okno.geometry('400x400')
okno.resizable(width=False, height=False)

ramka = Frame(okno)
ramka['bg'] = '#c1c1ff'
ramka.place(relx=0.05, rely=0.05, relwidth=0.9, relheight=0.9)

title_shrift = font.Font(family='Arial', size=20)
little_shrift = font.Font(family='Arial', size=10)
shrift = font.Font(family='Arial', size=12)

def main_page():
    task_selection = Label(ramka, text='ДОСТУПНЫЕ ОПЕРАЦИИ', bg='#c1c1ff', font=title_shrift)
    task_selection.pack()

    def udalenie():
        delete = [task_selection.destroy(),
                  v_kg.destroy(),
                  v_catti.destroy(),
                  v_funti.destroy(),
                  slojenie.destroy(),
                  vichitanie.destroy(),
                  umnojenie.destroy(),
                  delenie.destroy(),
                  sravnenie.destroy(),
                  dopolnenie.destroy()]

    def V_KG():
        udalenie()
        text_V_KG = Label(ramka, text='Введите значение в гривенках', font=shrift, bg='#c1c1ff')
        text_V_KG.pack()
        vz_V_KG = Entry(ramka, font=shrift)
        vz_V_KG.pack()

        def REZULTAT_V_KG():
            a = vz_V_KG.get()
            if a.isdigit() == False:
                messagebox.showerror('Ошибка!', 'Введенное не является числом!')
            else:
                if int(a) > 8000:
                    messagebox.showerror('Ошибка!', 'Введенное число не должно превышать 10 берковец')
                else:
                    rezultat_V_KG['text'] = round(int(a) * 0.205, 3), 'кг'

        rezbtn_V_KG = Button(ramka, text='Узнать результат', font=shrift, bg='grey', command=REZULTAT_V_KG)
        rezbtn_V_KG.pack(pady=10)
        rezultat_V_KG = Label(ramka, font=shrift, bg='#c1c1ff')
        rezultat_V_KG.pack()

        def Back_V_KG():
            vz_V_KG.destroy()
            text_V_KG.destroy()
            backbtn_V_KG.destroy()
            rezbtn_V_KG.destroy()
            rezultat_V_KG.destroy()
            main_page()

        backbtn_V_KG = Button(ramka, text='Назад', bg='grey', font=shrift, command=Back_V_KG)
        backbtn_V_KG.pack(side=BOTTOM)

    def V_CATTI():
        udalenie()
        text_V_CATTI = Label(ramka, text='Введите значение в гривенках', font=shrift, bg='#c1c1ff')
        text_V_CATTI.pack()
        vz_V_CATTI = Entry(ramka, font=shrift)
        vz_V_CATTI.pack()

        def REZULTAT_V_CATTI():
            a = vz_V_CATTI.get()
            if a.isdigit() == False:
                messagebox.showerror('Ошибка!', 'Введенное не является числом!')
            else:
                if int(a) > 8000:
                    messagebox.showerror('Ошибка!', 'Введенное число не должно превышать 10 берковец')
                else:
                    rezultat_V_CATTI['text'] = round(int(a) * 0.205 * 0.605, 3), 'кэтти'

        rezbtn_V_CATTI = Button(ramka, text='Узнать результат', font=shrift, bg='grey', command=REZULTAT_V_CATTI)
        rezbtn_V_CATTI.pack(pady=10)
        rezultat_V_CATTI = Label(ramka, font=shrift, bg='#c1c1ff')
        rezultat_V_CATTI.pack()

        def Back_V_CATTI():
            vz_V_CATTI.destroy()
            text_V_CATTI.destroy()
            backbtn_V_CATTI.destroy()
            rezbtn_V_CATTI.destroy()
            rezultat_V_CATTI.destroy()
            main_page()

        backbtn_V_CATTI = Button(ramka, text='Назад', bg='grey', font=shrift, command=Back_V_CATTI)
        backbtn_V_CATTI.pack(side=BOTTOM)

    def V_FUNTI():
        udalenie()
        text_V_FUNTI = Label(ramka, text='Введите значение в гривенках', font=shrift, bg='#c1c1ff')
        text_V_FUNTI.pack()
        vz_V_FUNTI = Entry(ramka, font=shrift)
        vz_V_FUNTI.pack()

        def REZULTAT_V_FUNTI():
            a = vz_V_FUNTI.get()
            if a.isdigit() == False:
                messagebox.showerror('Ошибка!', 'Введенное не является числом!')
            else:
                if int(a) > 8000:
                    messagebox.showerror('Ошибка!', 'Введенное число не должно превышать 10 берковец')
                else:
                    rezultat_V_FUNTI['text'] = round(int(a) * 0.205 * 0.454, 3), 'фунтов'

        rezbtn_V_FUNTI = Button(ramka, text='Узнать результат', font=shrift, bg='grey', command=REZULTAT_V_FUNTI)
        rezbtn_V_FUNTI.pack(pady=10)
        rezultat_V_FUNTI = Label(ramka, font=shrift, bg='#c1c1ff')
        rezultat_V_FUNTI.pack()

        def Back_V_FUNTI():
            vz_V_FUNTI.destroy()
            text_V_FUNTI.destroy()
            backbtn_V_FUNTI.destroy()
            rezbtn_V_FUNTI.destroy()
            rezultat_V_FUNTI.destroy()
            main_page()

        backbtn_V_FUNTI = Button(ramka, text='Назад', bg='grey', font=shrift, command=Back_V_FUNTI)
        backbtn_V_FUNTI.pack(side=BOTTOM)

    def SLOJENIE():
        udalenie()
        text_1_slag = Label(ramka, text='ПЕРВОЕ ЗНАЧЕНИЕ', font=shrift, bg='#c1c1ff')
        text_1_slag.place(relwidth=0.5)
        text_2_slag = Label(ramka, text='ВТОРОЕ ЗНАЧЕНИЕ', font=shrift, bg='#c1c1ff')
        text_2_slag.place(relwidth=0.5, relx=0.5)

        text_berk = Label(ramka, text='Количество берковцев:', font=little_shrift, bg='#c1c1ff')
        text_berk.place(relwidth=1, rely=0.1)
        entry_1_berk = Entry(ramka, font=little_shrift)
        entry_1_berk.place(relwidth=0.25, rely=0.15, relx=0.125)
        entry_2_berk = Entry(ramka, font=little_shrift)
        entry_2_berk.place(relwidth=0.25, rely=0.15, relx=0.625)

        text_pud = Label(ramka, text='Количество пудов:', font=little_shrift, bg='#c1c1ff')
        text_pud.place(relwidth=1, rely=0.2)
        entry_1_pud = Entry(ramka, font=little_shrift)
        entry_1_pud.place(relwidth=0.25, rely=0.25, relx=0.125)
        entry_2_pud = Entry(ramka, font=little_shrift)
        entry_2_pud.place(relwidth=0.25, rely=0.25, relx=0.625)

        text_bezm = Label(ramka, text='Количество безменов:', font=little_shrift, bg='#c1c1ff')
        text_bezm.place(relwidth=1, rely=0.3)
        entry_1_bezm = Entry(ramka, font=little_shrift)
        entry_1_bezm.place(relwidth=0.25, rely=0.35, relx=0.125)
        entry_2_bezm = Entry(ramka, font=little_shrift)
        entry_2_bezm.place(relwidth=0.25, rely=0.35, relx=0.625)

        text_griv = Label(ramka, text='Количество гривенок:', font=little_shrift, bg='#c1c1ff')
        text_griv.place(relwidth=1, rely=0.4)
        entry_1_griv = Entry(ramka, font=little_shrift)
        entry_1_griv.place(relwidth=0.25, rely=0.45, relx=0.125)
        entry_2_griv = Entry(ramka, font=little_shrift)
        entry_2_griv.place(relwidth=0.25, rely=0.45, relx=0.625)

        def REZULTAT_SLOJENIE():
            _1_berk = entry_1_berk.get()
            _1_pud = entry_1_pud.get()
            _1_bezm = entry_1_bezm.get()
            _1_griv = entry_1_griv.get()
            _2_berk = entry_2_berk.get()
            _2_pud = entry_2_pud.get()
            _2_bezm = entry_2_bezm.get()
            _2_griv = entry_2_griv.get()
            if _1_berk.isdigit() == False\
               or _1_pud.isdigit() == False\
               or _1_bezm.isdigit() == False\
               or _1_griv.isdigit() == False \
               or _2_berk.isdigit() == False \
               or _2_pud.isdigit() == False \
               or _2_bezm.isdigit() == False \
               or _2_griv.isdigit() == False:
                messagebox.showerror('Ошибка!', 'Введенное не является числом!')
            else:
                a = (int(_1_berk) * 800
                     + int(_1_pud) * 80
                     + int(_1_bezm) * 5
                     + int(_1_griv)
                     + int(_2_berk) * 800
                     + int(_2_pud) * 80
                     + int(_2_bezm) * 5
                     + int(_2_griv))
                if a > 8000:
                    messagebox.showerror('Ошибка!', 'Введенное число не должно превышать 10 берковец')
                else:
                    rezultat_SLOJENIE['text'] = obratniy_perevod(a)

        def obratniy_perevod(a):
            b = a // 5
            c = b // 16
            d = c // 10
            e = a % 5
            f = b % 16
            g = c % 10
            if d % 10 == 1:
                h = 'берковец'
            elif d % 10 == 2 or d % 10 == 3 or d % 10 == 4:
                h = 'берковца'
            else:
                h = 'берковцев'
            if g % 10 == 1:
                i = 'пуд'
            elif g % 10 == 2 or g % 10 == 3 or g % 10 == 4:
                i = 'пуда'
            else:
                i = 'пудов'
            if f >= 10:
                j = 'безменов'
            elif f % 10 == 1:
                j = 'безмен'
            elif f % 10 == 2 or f % 10 == 3 or f % 10 == 4:
                j = 'безмена'
            else:
                j = 'безменов'
            if e % 10 == 1:
                k = 'гривенка'
            elif e % 10 == 2 or e % 10 == 3 or e % 10 == 4:
                k = 'гривенки'
            else:
                k = 'гривенок'
            return d, h, g, i, f, j, e, k

        rezultat_SLOJENIE = Label(ramka, font=shrift, bg='#c1c1ff')
        rezultat_SLOJENIE.place(relwidth=1, rely=0.7)

        rezbtn_SLOJENIE = Button(ramka, text='Узнать результат', font=shrift, bg='grey', command=REZULTAT_SLOJENIE)
        rezbtn_SLOJENIE.place(rely=0.55, relx=0.305)

        def Back_SLOJENIE():
            text_1_slag.destroy(),
            text_2_slag.destroy(),
            text_berk.destroy(),
            text_pud.destroy(),
            text_bezm.destroy(),
            text_griv.destroy(),
            entry_1_berk.destroy(),
            entry_2_berk.destroy(),
            entry_1_pud.destroy(),
            entry_2_pud.destroy(),
            entry_1_bezm.destroy(),
            entry_2_bezm.destroy(),
            entry_1_griv.destroy(),
            entry_2_griv.destroy()
            backbtn_SLOJENIE.destroy()
            rezbtn_SLOJENIE.destroy()
            rezultat_SLOJENIE.destroy()
            main_page()

        backbtn_SLOJENIE = Button(ramka, text='Назад', bg='grey', font=shrift, command=Back_SLOJENIE)
        backbtn_SLOJENIE.pack(side=BOTTOM)

    def VICHITANIE():
        udalenie()
        text_1_slag = Label(ramka, text='ПЕРВОЕ ЗНАЧЕНИЕ', font=shrift, bg='#c1c1ff')
        text_1_slag.place(relwidth=0.5)
        text_2_slag = Label(ramka, text='ВТОРОЕ ЗНАЧЕНИЕ', font=shrift, bg='#c1c1ff')
        text_2_slag.place(relwidth=0.5, relx=0.5)

        text_berk = Label(ramka, text='Количество берковцев:', font=little_shrift, bg='#c1c1ff')
        text_berk.place(relwidth=1, rely=0.1)
        entry_1_berk = Entry(ramka, font=little_shrift)
        entry_1_berk.place(relwidth=0.25, rely=0.15, relx=0.125)
        entry_2_berk = Entry(ramka, font=little_shrift)
        entry_2_berk.place(relwidth=0.25, rely=0.15, relx=0.625)

        text_pud = Label(ramka, text='Количество пудов:', font=little_shrift, bg='#c1c1ff')
        text_pud.place(relwidth=1, rely=0.2)
        entry_1_pud = Entry(ramka, font=little_shrift)
        entry_1_pud.place(relwidth=0.25, rely=0.25, relx=0.125)
        entry_2_pud = Entry(ramka, font=little_shrift)
        entry_2_pud.place(relwidth=0.25, rely=0.25, relx=0.625)

        text_bezm = Label(ramka, text='Количество безменов:', font=little_shrift, bg='#c1c1ff')
        text_bezm.place(relwidth=1, rely=0.3)
        entry_1_bezm = Entry(ramka, font=little_shrift)
        entry_1_bezm.place(relwidth=0.25, rely=0.35, relx=0.125)
        entry_2_bezm = Entry(ramka, font=little_shrift)
        entry_2_bezm.place(relwidth=0.25, rely=0.35, relx=0.625)

        text_griv = Label(ramka, text='Количество гривенок:', font=little_shrift, bg='#c1c1ff')
        text_griv.place(relwidth=1, rely=0.4)
        entry_1_griv = Entry(ramka, font=little_shrift)
        entry_1_griv.place(relwidth=0.25, rely=0.45, relx=0.125)
        entry_2_griv = Entry(ramka, font=little_shrift)
        entry_2_griv.place(relwidth=0.25, rely=0.45, relx=0.625)

        def REZULTAT_VICHITANIE():
            _1_berk = entry_1_berk.get()
            _1_pud = entry_1_pud.get()
            _1_bezm = entry_1_bezm.get()
            _1_griv = entry_1_griv.get()
            _2_berk = entry_2_berk.get()
            _2_pud = entry_2_pud.get()
            _2_bezm = entry_2_bezm.get()
            _2_griv = entry_2_griv.get()
            if _1_berk.isdigit() == False \
                    or _1_pud.isdigit() == False \
                    or _1_bezm.isdigit() == False \
                    or _1_griv.isdigit() == False \
                    or _2_berk.isdigit() == False \
                    or _2_pud.isdigit() == False \
                    or _2_bezm.isdigit() == False \
                    or _2_griv.isdigit() == False:
                messagebox.showerror('Ошибка!', 'Введенное не является числом!')
            else:
                a = (int(_1_berk) * 800
                     + int(_1_pud) * 80
                     + int(_1_bezm) * 5
                     + int(_1_griv)
                     - (int(_2_berk) * 800
                     + int(_2_pud) * 80
                     + int(_2_bezm) * 5
                     + int(_2_griv)))
                if a > 8000:
                    messagebox.showerror('Ошибка!', 'Введенное число не должно превышать 10 берковец')
                else:
                    rezultat_VICHITANIE['text'] = obratniy_perevod(a)

        def obratniy_perevod(a):
            b = a // 5
            c = b // 16
            d = c // 10
            e = a % 5
            f = b % 16
            g = c % 10
            if d % 10 == 1:
                h = 'берковец'
            elif d % 10 == 2 or d % 10 == 3 or d % 10 == 4:
                h = 'берковца'
            else:
                h = 'берковцев'
            if g % 10 == 1:
                i = 'пуд'
            elif g % 10 == 2 or g % 10 == 3 or g % 10 == 4:
                i = 'пуда'
            else:
                i = 'пудов'
            if f >= 10:
                j = 'безменов'
            elif f % 10 == 1:
                j = 'безмен'
            elif f % 10 == 2 or f % 10 == 3 or f % 10 == 4:
                j = 'безмена'
            else:
                j = 'безменов'
            if e % 10 == 1:
                k = 'гривенка'
            elif e % 10 == 2 or e % 10 == 3 or e % 10 == 4:
                k = 'гривенки'
            else:
                k = 'гривенок'
            return d, h, g, i, f, j, e, k

        rezultat_VICHITANIE = Label(ramka, font=shrift, bg='#c1c1ff')
        rezultat_VICHITANIE.place(relwidth=1, rely=0.7)

        rezbtn_VICHITANIE = Button(ramka, text='Узнать результат', font=shrift, bg='grey', command=REZULTAT_VICHITANIE)
        rezbtn_VICHITANIE.place(rely=0.55, relx=0.305)

        def Back_VICHITANIE():
            text_1_slag.destroy(),
            text_2_slag.destroy(),
            text_berk.destroy(),
            text_pud.destroy(),
            text_bezm.destroy(),
            text_griv.destroy(),
            entry_1_berk.destroy(),
            entry_2_berk.destroy(),
            entry_1_pud.destroy(),
            entry_2_pud.destroy(),
            entry_1_bezm.destroy(),
            entry_2_bezm.destroy(),
            entry_1_griv.destroy(),
            entry_2_griv.destroy()
            backbtn_VICHITANIE.destroy()
            rezbtn_VICHITANIE.destroy()
            rezultat_VICHITANIE.destroy()
            main_page()

        backbtn_VICHITANIE = Button(ramka, text='Назад', bg='grey', font=shrift, command=Back_VICHITANIE)
        backbtn_VICHITANIE.pack(side=BOTTOM)

    def UMNOJENIE():
        udalenie()
        text_znach = Label(ramka, text='ЗНАЧЕНИЕ', font=shrift, bg='#c1c1ff')
        text_znach.place(relwidth=0.5)
        text_mnojitel = Label(ramka, text='МНОЖИТЕЛЬ', font=shrift, bg='#c1c1ff')
        text_mnojitel.place(relwidth=0.5, relx=0.5)

        text_berk = Label(ramka, text='Количество берковцев:', font=little_shrift, bg='#c1c1ff')
        text_berk.place(relx=0.06, rely=0.1)
        entry_1_berk = Entry(ramka, font=little_shrift)
        entry_1_berk.place(relwidth=0.25, rely=0.15, relx=0.125)

        text_pud = Label(ramka, text='Количество пудов:', font=little_shrift, bg='#c1c1ff')
        text_pud.place(relx=0.09, rely=0.25)
        entry_1_pud = Entry(ramka, font=little_shrift)
        entry_1_pud.place(relwidth=0.25, rely=0.3, relx=0.125)

        text_bezm = Label(ramka, text='Количество безменов:', font=little_shrift, bg='#c1c1ff')
        text_bezm.place(relx=0.07, rely=0.4)
        entry_1_bezm = Entry(ramka, font=little_shrift)
        entry_1_bezm.place(relwidth=0.25, rely=0.45, relx=0.125)

        text_griv = Label(ramka, text='Количество гривенок:', font=little_shrift, bg='#c1c1ff')
        text_griv.place(relx=0.07, rely=0.55)
        entry_1_griv = Entry(ramka, font=little_shrift)
        entry_1_griv.place(relwidth=0.25, rely=0.6, relx=0.125)

        entry_mnojitel = Entry(ramka, font=little_shrift)
        entry_mnojitel.place(relwidth=0.25, rely=0.1, relx=0.625)

        def REZULTAT_UMNOJENIE():
            _1_berk = entry_1_berk.get()
            _1_pud = entry_1_pud.get()
            _1_bezm = entry_1_bezm.get()
            _1_griv = entry_1_griv.get()
            _mnojitel = entry_mnojitel.get()
            if _1_berk.isdigit() == False \
                    or _1_pud.isdigit() == False \
                    or _1_bezm.isdigit() == False \
                    or _1_griv.isdigit() == False \
                    or _mnojitel.replace(".", "", 1).isdigit() == False:
                messagebox.showerror('Ошибка!', 'Введенное не является числом!')
            else:
                a = round((int(_1_berk) * 800
                 + int(_1_pud) * 80
                 + int(_1_bezm) * 5
                 + int(_1_griv)) * float(_mnojitel))
                if a > 8000:
                    messagebox.showerror('Ошибка!', 'Введенное число не должно превышать 10 берковец')
                else:
                    rezultat_UMNOJENIE['text'] = obratniy_perevod(a)

        def obratniy_perevod(a):
            b = a // 5
            c = b // 16
            d = c // 10
            e = a % 5
            f = b % 16
            g = c % 10
            if d % 10 == 1:
                h = 'берковец'
            elif d % 10 == 2 or d % 10 == 3 or d % 10 == 4:
                h = 'берковца'
            else:
                h = 'берковцев'
            if g % 10 == 1:
                i = 'пуд'
            elif g % 10 == 2 or g % 10 == 3 or g % 10 == 4:
                i = 'пуда'
            else:
                i = 'пудов'
            if f >= 10:
                j = 'безменов'
            elif f % 10 == 1:
                j = 'безмен'
            elif f % 10 == 2 or f % 10 == 3 or f % 10 == 4:
                j = 'безмена'
            else:
                j = 'безменов'
            if e % 10 == 1:
                k = 'гривенка'
            elif e % 10 == 2 or e % 10 == 3 or e % 10 == 4:
                k = 'гривенки'
            else:
                k = 'гривенок'
            return d, h, g, i, f, j, e, k

        rezultat_UMNOJENIE = Label(ramka, font=shrift, bg='#c1c1ff')
        rezultat_UMNOJENIE.place(relwidth=1, rely=0.75)

        rezbtn_UMNOJENIE = Button(ramka, text='Узнать\nрезультат', font=shrift, bg='grey', command=REZULTAT_UMNOJENIE)
        rezbtn_UMNOJENIE.place(rely=0.35, relx=0.63)

        def Back_UMNOJENIE():
            text_znach.destroy()
            text_mnojitel.destroy()
            text_berk.destroy()
            text_pud.destroy()
            text_bezm.destroy()
            text_griv.destroy()
            entry_mnojitel.destroy()
            entry_1_berk.destroy()
            entry_1_pud.destroy()
            entry_1_bezm.destroy()
            entry_1_griv.destroy()
            backbtn_UMNOJENIE.destroy()
            rezbtn_UMNOJENIE.destroy()
            rezultat_UMNOJENIE.destroy()
            main_page()

        backbtn_UMNOJENIE = Button(ramka, text='Назад', bg='grey', font=shrift, command=Back_UMNOJENIE)
        backbtn_UMNOJENIE.pack(side=BOTTOM)

    def DELENIE():
        udalenie()
        text_znach = Label(ramka, text='ЗНАЧЕНИЕ', font=shrift, bg='#c1c1ff')
        text_znach.place(relwidth=0.5)
        text_delitel = Label(ramka, text='ДЕЛИТЕЛЬ', font=shrift, bg='#c1c1ff')
        text_delitel.place(relwidth=0.5, relx=0.5)

        text_berk = Label(ramka, text='Количество берковцев:', font=little_shrift, bg='#c1c1ff')
        text_berk.place(relx=0.06, rely=0.1)
        entry_1_berk = Entry(ramka, font=little_shrift)
        entry_1_berk.place(relwidth=0.25, rely=0.15, relx=0.125)

        text_pud = Label(ramka, text='Количество пудов:', font=little_shrift, bg='#c1c1ff')
        text_pud.place(relx=0.09, rely=0.25)
        entry_1_pud = Entry(ramka, font=little_shrift)
        entry_1_pud.place(relwidth=0.25, rely=0.3, relx=0.125)

        text_bezm = Label(ramka, text='Количество безменов:', font=little_shrift, bg='#c1c1ff')
        text_bezm.place(relx=0.07, rely=0.4)
        entry_1_bezm = Entry(ramka, font=little_shrift)
        entry_1_bezm.place(relwidth=0.25, rely=0.45, relx=0.125)

        text_griv = Label(ramka, text='Количество гривенок:', font=little_shrift, bg='#c1c1ff')
        text_griv.place(relx=0.07, rely=0.55)
        entry_1_griv = Entry(ramka, font=little_shrift)
        entry_1_griv.place(relwidth=0.25, rely=0.6, relx=0.125)

        entry_delitel = Entry(ramka, font=little_shrift)
        entry_delitel.place(relwidth=0.25, rely=0.1, relx=0.625)

        def REZULTAT_DELENIE():
            _1_berk = entry_1_berk.get()
            _1_pud = entry_1_pud.get()
            _1_bezm = entry_1_bezm.get()
            _1_griv = entry_1_griv.get()
            _delitel = entry_delitel.get()
            if _1_berk.isdigit() == False \
                    or _1_pud.isdigit() == False \
                    or _1_bezm.isdigit() == False \
                    or _1_griv.isdigit() == False \
                    or _delitel.replace(".", "", 1).isdigit() == False:
                messagebox.showerror('Ошибка!', 'Введенное не является числом!')
            else:
                a = round((int(_1_berk) * 800
                           + int(_1_pud) * 80
                           + int(_1_bezm) * 5
                           + int(_1_griv)) / float(_delitel))
                if a > 8000:
                    messagebox.showerror('Ошибка!', 'Введенное число не должно превышать 10 берковец')
                else:
                    rezultat_DELENIE['text'] = obratniy_perevod(a)

        def obratniy_perevod(a):
            b = a // 5
            c = b // 16
            d = c // 10
            e = a % 5
            f = b % 16
            g = c % 10
            if d % 10 == 1:
                h = 'берковец'
            elif d % 10 == 2 or d % 10 == 3 or d % 10 == 4:
                h = 'берковца'
            else:
                h = 'берковцев'
            if g % 10 == 1:
                i = 'пуд'
            elif g % 10 == 2 or g % 10 == 3 or g % 10 == 4:
                i = 'пуда'
            else:
                i = 'пудов'
            if f >= 10:
                j = 'безменов'
            elif f % 10 == 1:
                j = 'безмен'
            elif f % 10 == 2 or f % 10 == 3 or f % 10 == 4:
                j = 'безмена'
            else:
                j = 'безменов'
            if e % 10 == 1:
                k = 'гривенка'
            elif e % 10 == 2 or e % 10 == 3 or e % 10 == 4:
                k = 'гривенки'
            else:
                k = 'гривенок'
            return d, h, g, i, f, j, e, k

        rezultat_DELENIE = Label(ramka, font=shrift, bg='#c1c1ff')
        rezultat_DELENIE.place(relwidth=1, rely=0.75)

        rezbtn_DELENIE = Button(ramka, text='Узнать\nрезультат', font=shrift, bg='grey', command=REZULTAT_DELENIE)
        rezbtn_DELENIE.place(rely=0.35, relx=0.63)

        def Back_DELENIE():
            text_znach.destroy()
            text_delitel.destroy()
            text_berk.destroy()
            text_pud.destroy()
            text_bezm.destroy()
            text_griv.destroy()
            entry_delitel.destroy()
            entry_1_berk.destroy()
            entry_1_pud.destroy()
            entry_1_bezm.destroy()
            entry_1_griv.destroy()
            backbtn_DELENIE.destroy()
            rezbtn_DELENIE.destroy()
            rezultat_DELENIE.destroy()
            main_page()

        backbtn_DELENIE = Button(ramka, text='Назад', bg='grey', font=shrift, command=Back_DELENIE)
        backbtn_DELENIE.pack(side=BOTTOM)

    def SRAVNENIE():
        udalenie()
        text_1_slag = Label(ramka, text='ПЕРВОЕ ЗНАЧЕНИЕ', font=shrift, bg='#c1c1ff')
        text_1_slag.place(relwidth=0.5)
        text_2_slag = Label(ramka, text='ВТОРОЕ ЗНАЧЕНИЕ', font=shrift, bg='#c1c1ff')
        text_2_slag.place(relwidth=0.5, relx=0.5)

        text_berk = Label(ramka, text='Количество берковцев:', font=little_shrift, bg='#c1c1ff')
        text_berk.place(relwidth=1, rely=0.1)
        entry_1_berk = Entry(ramka, font=little_shrift)
        entry_1_berk.place(relwidth=0.25, rely=0.15, relx=0.125)
        entry_2_berk = Entry(ramka, font=little_shrift)
        entry_2_berk.place(relwidth=0.25, rely=0.15, relx=0.625)

        text_pud = Label(ramka, text='Количество пудов:', font=little_shrift, bg='#c1c1ff')
        text_pud.place(relwidth=1, rely=0.2)
        entry_1_pud = Entry(ramka, font=little_shrift)
        entry_1_pud.place(relwidth=0.25, rely=0.25, relx=0.125)
        entry_2_pud = Entry(ramka, font=little_shrift)
        entry_2_pud.place(relwidth=0.25, rely=0.25, relx=0.625)

        text_bezm = Label(ramka, text='Количество безменов:', font=little_shrift, bg='#c1c1ff')
        text_bezm.place(relwidth=1, rely=0.3)
        entry_1_bezm = Entry(ramka, font=little_shrift)
        entry_1_bezm.place(relwidth=0.25, rely=0.35, relx=0.125)
        entry_2_bezm = Entry(ramka, font=little_shrift)
        entry_2_bezm.place(relwidth=0.25, rely=0.35, relx=0.625)

        text_griv = Label(ramka, text='Количество гривенок:', font=little_shrift, bg='#c1c1ff')
        text_griv.place(relwidth=1, rely=0.4)
        entry_1_griv = Entry(ramka, font=little_shrift)
        entry_1_griv.place(relwidth=0.25, rely=0.45, relx=0.125)
        entry_2_griv = Entry(ramka, font=little_shrift)
        entry_2_griv.place(relwidth=0.25, rely=0.45, relx=0.625)

        def REZULTAT_SRAVNENIE():
            _1_berk = entry_1_berk.get()
            _1_pud = entry_1_pud.get()
            _1_bezm = entry_1_bezm.get()
            _1_griv = entry_1_griv.get()
            _2_berk = entry_2_berk.get()
            _2_pud = entry_2_pud.get()
            _2_bezm = entry_2_bezm.get()
            _2_griv = entry_2_griv.get()
            if _1_berk.isdigit() == False \
                    or _1_pud.isdigit() == False \
                    or _1_bezm.isdigit() == False \
                    or _1_griv.isdigit() == False \
                    or _2_berk.isdigit() == False \
                    or _2_pud.isdigit() == False \
                    or _2_bezm.isdigit() == False \
                    or _2_griv.isdigit() == False:
                messagebox.showerror('Ошибка!', 'Введенное не является числом!')
            else:
                a = (int(entry_1_berk.get()) * 800
                     + int(entry_1_pud.get()) * 80
                     + int(entry_1_bezm.get()) * 5
                     + int(entry_1_griv.get()))
                A = (int(entry_2_berk.get()) * 800
                     + int(entry_2_pud.get()) * 80
                     + int(entry_2_bezm.get()) * 5
                     + int(entry_2_griv.get()))
                if a > 8000 or A > 8000:
                    messagebox.showerror('Ошибка!', 'Введенное число не должно превышать 10 берковец')
                else:
                    rezultat_SRAVNENIE['text'] = bolshe_menshe_ravno(a, A)

        def bolshe_menshe_ravno(a, A):
            if a > A:
                return 'Первое число БОЛЬШЕ второго'
            elif A > a:
                return 'Первое число МЕНЬШЕ второго'
            else:
                return 'Числа РАВНЫ между собой'

        rezultat_SRAVNENIE = Label(ramka, font=shrift, bg='#c1c1ff')
        rezultat_SRAVNENIE.place(relwidth=1, rely=0.7)

        rezbtn_SRAVNENIE = Button(ramka, text='Узнать результат', font=shrift, bg='grey', command=REZULTAT_SRAVNENIE)
        rezbtn_SRAVNENIE.place(rely=0.55, relx=0.305)

        def Back_SRAVNENIE():
            text_1_slag.destroy(),
            text_2_slag.destroy(),
            text_berk.destroy(),
            text_pud.destroy(),
            text_bezm.destroy(),
            text_griv.destroy(),
            entry_1_berk.destroy(),
            entry_2_berk.destroy(),
            entry_1_pud.destroy(),
            entry_2_pud.destroy(),
            entry_1_bezm.destroy(),
            entry_2_bezm.destroy(),
            entry_1_griv.destroy(),
            entry_2_griv.destroy()
            backbtn_SRAVNENIE.destroy()
            rezbtn_SRAVNENIE.destroy()
            rezultat_SRAVNENIE.destroy()
            main_page()

        backbtn_SRAVNENIE = Button(ramka, text='Назад', bg='grey', font=shrift, command=Back_SRAVNENIE)
        backbtn_SRAVNENIE.pack(side=BOTTOM)

    def DOPOLNENIE():
        udalenie()
        text_znach = Label(ramka, text='Введите значение веса', font=shrift, bg='#c1c1ff')
        text_znach.pack()

        text_pud = Label(ramka, text='Количество пудов:', font=little_shrift, bg='#c1c1ff')
        text_pud.pack()
        entry_1_pud = Entry(ramka, font=little_shrift)
        entry_1_pud.pack()

        text_bezm = Label(ramka, text='Количество безменов:', font=little_shrift, bg='#c1c1ff')
        text_bezm.pack()
        entry_1_bezm = Entry(ramka, font=little_shrift)
        entry_1_bezm.pack()

        text_griv = Label(ramka, text='Количество гривенок:', font=little_shrift, bg='#c1c1ff')
        text_griv.pack()
        entry_1_griv = Entry(ramka, font=little_shrift)
        entry_1_griv.pack()

        def REZULTAT_DOPOLNENIE():
            _1_pud = entry_1_pud.get()
            _1_bezm = entry_1_bezm.get()
            _1_griv = entry_1_griv.get()
            if _1_pud.isdigit() == False \
               or _1_bezm.isdigit() == False \
               or _1_griv.isdigit() == False:
                messagebox.showerror('Ошибка!', 'Введенное не является числом!')
            else:
                a = 800 - (int(entry_1_pud.get()) * 80
                    + int(entry_1_bezm.get()) * 5
                    + int(entry_1_griv.get()))
                if a < 0:
                    messagebox.showerror('Ошибка!', 'Введенное значение больше одного берковца')
                else:
                    rezultat_DOPOLNENIE['text'] = obratniy_perevod(a)

        def obratniy_perevod(a):
            b = a // 5
            c = b // 16
            e = a % 5
            f = b % 16
            g = c % 10
            q = 'До берковца не хватает\n'
            if g % 10 == 1:
                i = 'пуд'
            elif g % 10 == 2 or g % 10 == 3 or g % 10 == 4:
                i = 'пуда'
            else:
                i = 'пудов'
            if f >= 10:
                j = 'безменов'
            elif f % 10 == 1:
                j = 'безмен'
            elif f % 10 == 2 or f % 10 == 3 or f % 10 == 4:
                j = 'безмена'
            else:
                j = 'безменов'
            if e % 10 == 1:
                k = 'гривенка'
            elif e % 10 == 2 or e % 10 == 3 or e % 10 == 4:
                k = 'гривенки'
            else:
                k = 'гривенок'
            return q, g, i, f, j, e, k

        rezultat_DOPOLNENIE = Label(ramka, font=shrift, bg='#c1c1ff')
        rezultat_DOPOLNENIE.place(relwidth=1, rely=0.75)

        rezbtn_DOPOLNENIE = Button(ramka, text='Узнать результат', font=shrift, bg='grey', command=REZULTAT_DOPOLNENIE)
        rezbtn_DOPOLNENIE.pack()

        def Back_DOPOLNENIE():
            text_znach.destroy()
            text_pud.destroy()
            text_bezm.destroy()
            text_griv.destroy()
            entry_1_pud.destroy()
            entry_1_bezm.destroy()
            entry_1_griv.destroy()
            backbtn_DOPOLNENIE.destroy()
            rezbtn_DOPOLNENIE.destroy()
            rezultat_DOPOLNENIE.destroy()
            main_page()

        backbtn_DOPOLNENIE = Button(ramka, text='Назад', bg='grey', font=shrift, command=Back_DOPOLNENIE)
        backbtn_DOPOLNENIE.pack(side=BOTTOM)

    v_kg = Button(ramka, text='Перевод в килограммы', bg='grey', font=shrift, width=30, command=V_KG)
    v_kg.pack()
    v_catti = Button(ramka, text='Перевод в кэтти', bg='grey', font=shrift, width=30, command=V_CATTI)
    v_catti.pack()
    v_funti = Button(ramka, text='Перевод в фунты', bg='grey', font=shrift, width=30, command=V_FUNTI)
    v_funti.pack()
    slojenie = Button(ramka, text='Сложение', bg='grey', font=shrift, width=30, command=SLOJENIE)
    slojenie.pack()
    vichitanie = Button(ramka, text='Вычитание', bg='grey', font=shrift, width=30, command=VICHITANIE)
    vichitanie.pack()
    umnojenie = Button(ramka, text='Умножение на число', bg='grey', font=shrift, width=30, command=UMNOJENIE)
    umnojenie.pack()
    delenie = Button(ramka, text='Деление на число', bg='grey', font=shrift, width=30, command=DELENIE)
    delenie.pack()
    sravnenie = Button(ramka, text='Сравнение', bg='grey', font=shrift, width=30, command=SRAVNENIE)
    sravnenie.pack()
    dopolnenie = Button(ramka, text='Дополнение до берковца', bg='grey', font=shrift, width=30, command=DOPOLNENIE)
    dopolnenie.pack()

main_page()
okno.mainloop()
