# REP_PRAC_2
#ejemplo 1 import mx
app = wx.App (clearSigInt = True) # clearSigInt para permitir la terminación del programa con CTRL + C frame = wx.Frame (parent = None, title = "") ## main window object panel = wx.Panel (parent = frame ) text = wx.StaticText (parent = panel, label = "Hola, desde wxPython !!", pos = (40,50)) frame.Show () app.MainLoop ()
![image](https://user-images.githubusercontent.com/79875888/112390646-3f611780-8cbc-11eb-883c-0ff1d451bf7a.png)
