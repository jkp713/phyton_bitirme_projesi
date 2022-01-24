# phyton_bitirme_projesi
soru 1 ve 2

soru1 icin

duz_liste = []
def flatten_list(data):
    for element in data:
        if type(element) == list:
            flatten_list(element)
        else:
            duz_liste.append(element)
            
soru 2 icin

def ters(x):
    x = x[::-1]
    for i in x:
        if type(i) == list:
            ters(i)
    
    return x
