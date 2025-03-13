# dephi_devexpress_vcl_pesian_farsi_loclale_all_tools

add cx locle into your project and falow the cod... in files 
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
