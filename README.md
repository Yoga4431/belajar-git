# # # Nomor 1
# # def pythagoras(a, b, c):
# #     a, b, c = sorted([a, b, c])
# #     if a**2 + b**2 == c**2:
# #         return True
# #     else:
# #         return False
# # # Test cases
# # print(pythagoras(3, 4, 5))   # Output: True
# # print(pythagoras(12, 15, 9))  # Output: True
# # print(pythagoras(20, 10, 40)) # Output: False

# # Nomor 2
# def runner_up(a, b, c, d, e):
#     times = [a, b, c, d, e]
#     return sorted(times)[0]
# print(runner_up(9.76, 9.9, 10.0, 9.62, 9.78))

# Nomor 3
# def bobot_nilai(nilai_huruf):

#     nilai_huruf = nilai_huruf.upper() 
#     tabel_nilai = {
#         "A": 4.0,
#         "A-": 3.75,
#         "B+": 3.25,
#         "B": 3.0,
#         "B-": 2.75,
#         "C+": 2.25,
#         "C": 2.0,
#         "D": 1.0,
#         "E": 0.0
#     }
#     return tabel_nilai.get(nilai_huruf, 0)

# print(bobot_nilai("A"))
# print(bobot_nilai("C+"))
# print(bobot_nilai("X"))
# print(bobot_nilai("c"))
