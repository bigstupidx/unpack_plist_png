en error occured when parsing my plist file with the original source file:

```
Traceback (most recent call last):
  File "unpack_plist.py", line 90, in <module>
    gen_png_from_plist( plist_filename, png_filename )
  File "unpack_plist.py", line 73, in gen_png_from_plist
    result_image.paste(rect_on_big, result_box, mask=0)
  File "/Library/Frameworks/Python.framework/Versions/2.7/lib/python2.7/site-packages/PIL/Image.py", line 1337, in paste
    self.im.paste(im, box)
ValueError: images do not match
```

So I changed some source code