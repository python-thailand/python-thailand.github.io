---
layout: default
---

# ระบบปฏิบัติการที่รองรับ

---

<br>

โปรแกรมไพธอนสามารถรันได้บนระบบปฏิบัติการ (Operating System หรือ OS) ตามข้อตกลงของชุมชนไพธอน PEP หมายเลข 0011 ได้กล่าวถึงระบบปฏิบัติการที่ตัวภาษารองรับ [อ่านเพิ่มเติมได้ที่นี่][pep-0011] 

[pep-0011]: https://www.python.org/dev/peps/pep-0011/#supporting-platforms

ตารางด้านล่างแสดง OS ที่ไพธอนรองรับ

Platform | sys.platform | os.name
---------|--------------|--------
AIX      | aix5, aix6, aix7 | posix
Cygwin   | cygwin | ?
FreeBSD  | freebsd5, freebsd6, ... | posix
Java     | java (with a suffix?) | ?
Linux    | linux on Python 3, linux2 on Python 2 (*) | posix
macOS    | darwin | posix
NetBSD   | netbsd (with a suffix?) | posix
OpenBSD  | openbsd5 | posix
Solaris  | sunos5 | posix
Windows  | win32 | nt
