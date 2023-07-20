for n in range(10000, 100000):
    n = str(n)
    m1 = int(n[0])
    m2 = int(n[2])
    m3 = int(n[4])
    m4 = m1 + m2 + m3
    u1 = int(n[1])
    u2 = int(n[3])
    u3 = u1 + u2
    if u3 < m4:
        u3 = str(u3)
        m4 = str(m4)
        if u3 + m4 == '621':
            print(n)
            break
    else:
        u3 = str(u3)
        m4 = str(m4)
        if m4 + u3 == '621':
            print(n)
            break
