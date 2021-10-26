def nextDay(s):
    month31 = ['1', '3', '5', '7', '8','10', '12']
    day, month, year = s.split("/")
    if day == '31':
        if month == '12':
            return "1/1/" + str(int(year) + 1)
        else:
            return "1/" + str(int(month) + 1) + "/" + year
    if day == '30' and month not in month31 and month != '2':
        return "1/" + str(int(month) + 1) + "/" + year
    if month == '2':
        if (day == '28' and int(year) % 4 != 0) or(day == '29'):
            return "1/3/" + year
    return str(int(day) + 1) + "/" + month + "/" + year
        
