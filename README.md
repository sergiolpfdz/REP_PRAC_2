# REP_PRAC_2
#ejemplo 1 import mx
app = wx.App (clearSigInt = True) # clearSigInt para permitir la terminación del programa con CTRL + C frame = wx.Frame (parent = None, title = "") ## main window object panel = wx.Panel (parent = frame ) text = wx.StaticText (parent = panel, label = "Hola, desde wxPython !!", pos = (40,50)) frame.Show () app.MainLoop ()
![image](https://user-images.githubusercontent.com/79875888/112390646-3f611780-8cbc-11eb-883c-0ff1d451bf7a.png

#ejemplo 2 import wx import 
clase MyApp (wx.App): def init (self): super (). init (clearSigInt = True

 # init frame
    self.InitFrame()

def InitFrame(self):
    frame = MyFrame(parent=None, title="Basic Frame", pos=(100, 100))
    frame.Show(True
   
 class MyFrame (wx.Frame): # subclase de wx.Window; El marco es una ventana de nivel superior # Un marco es una ventana cuyo tamaño y posición pueden (normalmente) ser cambiados por el usuario. # Por lo general, representa la primera ventana principal que verá un usuario def init (self, parent, title, pos = pos): super (). init (padre = padre, título = título, pos = pos 
