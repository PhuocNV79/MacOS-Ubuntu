1. `rmdir Ten-Thu-Muc` : Xoa 1 thu muc rong.
2. `rm -r Ten-Thu-Muc`: Xoa 1 thu muc va cac thu muc, file trong thu muc do.
3. `mkdir Ten-Thu-Muc`: Tao 1 thu muc.
4. `mkdir Ten-Thu-Muc/Ten-Thu-Muc-Con1//Ten-Thu-Muc-Con2 -p`: Tao cac thu muc con.
5. `touch Ten-File`: Tao ra 1 file va khong co noi dung ben trong.
6. `vi Ten-File`: Tao 1 file o che do Command Mode, chua luu file.
7. Khi open 1 file bang Vim thi file do se co 2 che do: Command Mode va Insert Mode
 -  Command Mode: Thuc hien cac cau lenh doi voi file do.
 -  Insert mode: Thuc hien edit file do.
8. `:q`: thoat file trong vim.
9. `:q!`: thoat file va khong luu noi dung thay doi.
10. `:wq`: luu va thoat file.
11. `:x`: luu va thoat file
12. `cat Ten-File`: doc 1 file va in noi dung ra man hinh terminal. (stout standar output)
13. `cat Ten-File1 Ten-File2`: Doc va in noi dung 2 file ra man hinh terminal
14. `cat Ten-File1 Ten-File2 > Ten-File3`: Doc noi dung file1, 2 va ghi vao file 3.
15. `echo cauText`: in cauText ra man hinh terminal.
16. `echo cauText > Ten-File.abc`: ghi de noi dung cauText vao file Ten-File.abc.
17. `echo cauText >> Ten-File.abc`: Ghi them noi dung vao cuoi file.
18. `tail Ten-File`: doc 10 dong cuoi cua file in ra terminal.
19. `tail -n So-Luong-Dong Ten-File`: doc So-Luong-Dong dong cuoi cua file in ra terminal.
20. `grep`: thuong ket hop voi stout.
21. `echo "nguyen van phuoc" | grep phuoc`: hien chu phuoc dc highlight
22. `cat concat.html index.html | grep "noi"`: tim noi dung o nhieu file.
23. `cp Ten-File Ten-File-Moi`: copy file ra file moi.
24. `cp -r Ten-Thu-Muc Ten-Thu-Muc-Muon-Dat`: copy thu muc va noi dung trong do.
25. `chmod`: change mode, dung de thay doi quyen cua file, thu muc
26. Giai thich y nghia cac ky tu colum1 cua `ls -l`:
 - xYYYZZZTTT:
  + x: Loai tep tin: d: directory, l: shortcut, -: file
  + YYY: quyen cua rootuser, r: read, w: write, x: excute, -: none
  + ZZZ: quyen cua group
  + TTT: quyen cua other

27. `chown`: change owner.
28. `wget`: dung de tai 1 file voi duong dan truc tiep.
29. `kill`: dung de tat 1 ung dung dang chay.
30. `ps aux`: xem cac chuong trinh dang chay.
