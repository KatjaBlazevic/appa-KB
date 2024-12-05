# appa-KB

https://github.com/KatjaBlazevic/appa-KB.git

SELECT k.naslov FROM knjiga k
JOIN autor a ON k.autor = a.id
WHERE a.prezime_ime = 'Andrić Ivo' 
ORDER BY k.naslov ASC;
