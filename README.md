


# dephi_devexpress_vcl_pesian_farsi_loclale_all_tools

notice : for this function i use the trial version plz buy main full component  from devexpress.com

من برای این منظور از نسخه آزمایش دولاپر اکسپرس استفاده کردم لظفا خود کامپوننت را از شرکت سازنده خریداری فرمایید .

add cx locle into your project and fallow the code.. in files 
procedure langer(val: integer = 1065); // farsi

begin

  try
    fm_c.locale.FileName := c:\farsi.ini';
    fm_c.locale.Active := true;
    fm_c.locale.locale := val
  except
  //  showmessage('مشکل در فراخواني تنظيمات زبان');
  end;
  /// /

end;
