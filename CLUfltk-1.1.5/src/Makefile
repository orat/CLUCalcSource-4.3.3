#
# "$Id: Makefile,v 1.1 2004/02/18 16:10:33 chp Exp $"
#
# Library makefile for the Fast Light Tool Kit (FLTK).
#
# Copyright 1998-2003 by Bill Spitzak and others.
#
# This library is free software; you can redistribute it and/or
# modify it under the terms of the GNU Library General Public
# License as published by the Free Software Foundation; either
# version 2 of the License, or (at your option) any later version.
#
# This library is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# Library General Public License for more details.
#
# You should have received a copy of the GNU Library General Public
# License along with this library; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307
# USA.
#
# Please report all bugs and problems to "fltk-bugs@fltk.org".
#

CPPFILES = \
	Fl.cxx \
	Fl_Adjuster.cxx \
	Fl_Bitmap.cxx \
	Fl_Browser.cxx \
	Fl_Browser_.cxx \
	Fl_Browser_load.cxx \
	Fl_Box.cxx \
	Fl_Button.cxx \
	Fl_Chart.cxx \
	Fl_Check_Browser.cxx \
	Fl_Check_Button.cxx \
	Fl_Choice.cxx \
	Fl_Clock.cxx \
	Fl_Color_Chooser.cxx \
	Fl_Counter.cxx \
	Fl_Dial.cxx \
	Fl_Double_Window.cxx \
	Fl_File_Browser.cxx \
	Fl_File_Chooser.cxx \
	Fl_File_Chooser2.cxx \
	Fl_File_Icon.cxx \
	Fl_File_Input.cxx \
	Fl_Group.cxx \
	Fl_Help_View.cxx \
	Fl_Image.cxx \
	Fl_Input.cxx \
	Fl_Input_.cxx \
	Fl_Light_Button.cxx \
	Fl_Menu.cxx \
	Fl_Menu_.cxx \
	Fl_Menu_Bar.cxx \
	Fl_Menu_Button.cxx \
	Fl_Menu_Window.cxx \
	Fl_Menu_add.cxx \
	Fl_Menu_global.cxx \
	Fl_Multi_Label.cxx \
	Fl_Overlay_Window.cxx \
	Fl_Pack.cxx \
	Fl_Pixmap.cxx \
	Fl_Positioner.cxx \
	Fl_Preferences.cxx \
	Fl_Progress.cxx \
	Fl_Repeat_Button.cxx \
	Fl_Return_Button.cxx \
	Fl_Roller.cxx \
	Fl_Round_Button.cxx \
	Fl_Scroll.cxx \
	Fl_Scrollbar.cxx \
	Fl_Shared_Image.cxx \
	Fl_Single_Window.cxx \
	Fl_Slider.cxx \
	Fl_Tabs.cxx \
	Fl_Text_Buffer.cxx \
	Fl_Text_Display.cxx \
	Fl_Text_Editor.cxx \
	Fl_Tile.cxx \
	Fl_Tiled_Image.cxx \
	Fl_Tooltip.cxx \
	Fl_Valuator.cxx \
	Fl_Value_Input.cxx \
	Fl_Value_Output.cxx \
	Fl_Value_Slider.cxx \
	Fl_Widget.cxx \
	Fl_Window.cxx \
	Fl_Window_fullscreen.cxx \
	Fl_Window_hotspot.cxx \
	Fl_Window_iconize.cxx \
	Fl_Wizard.cxx \
	Fl_XBM_Image.cxx \
	Fl_XPM_Image.cxx \
	Fl_abort.cxx \
	Fl_add_idle.cxx \
	Fl_arg.cxx \
	Fl_compose.cxx \
	Fl_display.cxx \
	Fl_get_key.cxx \
	Fl_get_system_colors.cxx \
	Fl_grab.cxx \
	Fl_lock.cxx \
	Fl_own_colormap.cxx \
	Fl_visual.cxx \
	Fl_x.cxx \
	filename_absolute.cxx \
	filename_expand.cxx \
	filename_ext.cxx \
	filename_isdir.cxx \
	filename_list.cxx \
	filename_match.cxx \
	filename_setext.cxx \
	fl_arc.cxx \
	fl_arci.cxx \
	fl_ask.cxx \
	fl_boxtype.cxx \
	fl_color.cxx \
	fl_cursor.cxx \
	fl_curve.cxx \
	fl_diamond_box.cxx \
	fl_dnd.cxx \
	fl_draw.cxx \
	fl_draw_image.cxx \
	fl_draw_pixmap.cxx \
	fl_engraved_label.cxx \
	fl_file_dir.cxx \
	fl_font.cxx \
	fl_labeltype.cxx \
	fl_line_style.cxx \
	fl_oval_box.cxx \
	fl_overlay.cxx \
	fl_overlay_visual.cxx \
	fl_plastic.cxx \
	fl_read_image.cxx \
	fl_rect.cxx \
	fl_round_box.cxx \
	fl_rounded_box.cxx \
	fl_set_font.cxx \
	fl_set_fonts.cxx \
	fl_scroll_area.cxx \
	fl_shadow_box.cxx \
	fl_shortcut.cxx \
	fl_show_colormap.cxx \
	fl_symbols.cxx \
	fl_vertex.cxx

FLCPPFILES = \
	forms_compatability.cxx \
	forms_bitmap.cxx \
	forms_free.cxx \
	forms_fselect.cxx \
	forms_pixmap.cxx \
	forms_timer.cxx

GLCPPFILES = \
	Fl_Gl_Choice.cxx \
	Fl_Gl_Overlay.cxx \
	Fl_Gl_Window.cxx \
	gl_draw.cxx \
	gl_start.cxx \
	glut_compatability.cxx \
	glut_font.cxx

IMGCPPFILES = \
	fl_images_core.cxx \
	Fl_BMP_Image.cxx \
	Fl_File_Icon2.cxx \
	Fl_GIF_Image.cxx \
	Fl_Help_Dialog.cxx \
	Fl_JPEG_Image.cxx \
	Fl_PNG_Image.cxx \
	Fl_PNM_Image.cxx

CFILES = fl_call_main.c flstring.c scandir.c numericsort.c vsnprintf.c

CLEAN =	core* cmap

################################################################

include ../makeinclude

OBJECTS = $(CPPFILES:.cxx=.o) $(CFILES:.c=.o)
GLOBJECTS = $(GLCPPFILES:.cxx=.o)
FLOBJECTS = $(FLCPPFILES:.cxx=.o)
IMGOBJECTS = $(IMGCPPFILES:.cxx=.o)

all:	$(LIBNAME) $(DSONAME) \
	$(FLLIBNAME) $(FLDSONAME) \
	$(GLLIBNAME) $(GLDSONAME) \
	$(IMGLIBNAME) $(IMGDSONAME)

$(LIBNAME): $(OBJECTS)
	echo $(LIBCOMMAND) $@ ...
	-$(RM) $@
	$(LIBCOMMAND) $@ $(OBJECTS)
	$(RANLIB) $@

libfltk.so.1.1: $(OBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(OBJECTS) $(IMAGELIBS)
	-$(RM) libfltk.so
	$(LN) libfltk.so.1.1 libfltk.so

libfltk.sl.1.1: $(OBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(OBJECTS) $(IMAGELIBS)
	-$(RM) libfltk.sl
	$(LN) libfltk.sl.1.1 libfltk.sl

libfltk.1.1.dylib: $(OBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(OBJECTS) $(IMAGELIBS)
	-$(RM) libfltk.dylib
	$(LN) libfltk.1.1.dylib libfltk.dylib

libfltk_s.a: $(OBJECTS)
	echo $(DSOCOMMAND) libfltk_s.o ...
	$(DSOCOMMAND) libfltk_s.o $(OBJECTS) $(IMAGELIBS)
	echo $(LIBCOMMAND) libfltk_s.a libfltk_s.o
	-$(RM) $@
	$(LIBCOMMAND) libfltk_s.a libfltk_s.o
	$(CHMOD) +x libfltk_s.a

$(FLLIBNAME): $(FLOBJECTS)
	echo $(LIBCOMMAND) $@ ...
	-$(RM) $@
	$(LIBCOMMAND) $@ $(FLOBJECTS)
	$(RANLIB) $@

libfltk_forms.so.1.1: $(FLOBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(FLOBJECTS)
	-$(RM) libfltk_forms.so
	$(LN) libfltk_forms.so.1.1 libfltk_forms.so

libfltk_forms.sl.1.1: $(FLOBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(FLOBJECTS)
	-$(RM) libfltk_forms.sl
	$(LN) libfltk_forms.sl.1.1 libfltk_forms.sl

libfltk_forms.1.1.dylib: $(FLOBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(FLOBJECTS)
	-$(RM) libfltk_forms.dylib
	$(LN) libfltk_forms.1.1.dylib libfltk_forms.dylib

libfltk_forms_s.a: $(FLOBJECTS)
	echo $(DSOCOMMAND) libfltk_forms_s.o ...
	$(DSOCOMMAND) libfltk_forms_s.o $(FLOBJECTS)
	echo $(LIBCOMMAND) libfltk_forms_s.a libfltk_forms_s.o
	-$(RM) $@
	$(LIBCOMMAND) libfltk_forms_s.a libfltk_forms_s.o
	$(CHMOD) +x libfltk_forms_s.a

$(GLLIBNAME): $(GLOBJECTS)
	echo $(LIBCOMMAND) $@ ...
	-$(RM) $@
	$(LIBCOMMAND) $@ $(GLOBJECTS)
	$(RANLIB) $@

libfltk_gl.so.1.1: $(GLOBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(GLOBJECTS)
	-$(RM) libfltk_gl.so
	$(LN) libfltk_gl.so.1.1 libfltk_gl.so

libfltk_gl.sl.1.1: $(GLOBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(GLOBJECTS)
	-$(RM) libfltk_gl.sl
	$(LN) libfltk_gl.sl.1.1 libfltk_gl.sl

libfltk_gl.1.1.dylib: $(GLOBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(GLOBJECTS)
	-$(RM) libfltk_gl.dylib
	$(LN) libfltk_gl.1.1.dylib libfltk_gl.dylib

libfltk_gl_s.a: $(GLOBJECTS)
	echo $(DSOCOMMAND) libfltk_gl_s.o ...
	$(DSOCOMMAND) libfltk_gl_s.o $(GLOBJECTS)
	echo $(LIBCOMMAND) libfltk_gl_s.a libfltk_gl_s.o
	-$(RM) $@
	$(LIBCOMMAND) libfltk_gl_s.a libfltk_gl_s.o
	$(CHMOD) +x libfltk_gl_s.a

$(IMGLIBNAME): $(IMGOBJECTS)
	echo $(LIBCOMMAND) $@ ...
	-$(RM) $@
	$(LIBCOMMAND) $@ $(IMGOBJECTS)
	$(RANLIB) $@

libfltk_images.so.1.1: $(IMGOBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(IMGOBJECTS)
	-$(RM) libfltk_images.so
	$(LN) libfltk_images.so.1.1 libfltk_images.so

libfltk_images.sl.1.1: $(IMGOBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(IMGOBJECTS)
	-$(RM) libfltk_images.sl
	$(LN) libfltk_images.sl.1.1 libfltk_images.sl

libfltk_images.1.1.dylib: $(IMGOBJECTS)
	echo $(DSOCOMMAND) $@ ...
	$(DSOCOMMAND) $@ $(IMGOBJECTS)
	-$(RM) libfltk_images.dylib
	$(LN) libfltk_images.1.1.dylib libfltk_images.dylib

libfltk_images_s.a: $(IMGOBJECTS)
	echo $(DSOCOMMAND) libfltk_images_s.o ...
	$(DSOCOMMAND) libfltk_images_s.o $(IMGOBJECTS)
	echo $(LIBCOMMAND) libfltk_images_s.a libfltk_images_s.o
	-$(RM) $@
	$(LIBCOMMAND) libfltk_images_s.a libfltk_images_s.o
	$(CHMOD) +x libfltk_images_s.a


clean :
	-@ $(RM) *.o $(DSONAME) $(FLDSONAME) $(GLDSONAME) $(IMGDSONAME) \
		../lib/$(LIBNAME) ../lib/$(FLLIBNAME) ../lib/$(GLLIBNAME) \
		../lib/$(IMGLIBNAME) \
		libfltk.so libfltk_forms.so libfltk_gl.so libfltk_images.so \
		libfltk.sl libfltk_forms.sl libfltk_gl.sl libfltk_images.sl \
		libfltk.dylib libfltk_forms.dylib \
		libfltk_gl.dylib libfltk_images.dylib \
		$(CLEAN)

depend:	$(CPPFILES) $(FLCPPFILES) $(GLCPPFILES) $(IMGCPPFILES) $(CFILES)
	makedepend -Y -I.. -f makedepend $(CPPFILES) $(FLCPPFILES) \
		$(GLCPPFILES) $(IMGCPPFILES) $(CFILES)

# Automatically generated dependencies...
include makedepend

# These dependencies aren't part of the makedepend file since
# they are part of the WIN32 and MacOS code base...
Fl_get_key.o:	Fl_get_key_mac.cxx Fl_get_key_win32.cxx
Fl_x.o:		Fl_mac.cxx Fl_win32.cxx
fl_color.o:	fl_color_mac.cxx fl_color_win32.cxx
fl_dnd.o:	fl_dnd_mac.cxx fl_dnd_win32.cxx fl_dnd_x.cxx
fl_draw_image.o: fl_draw_image_mac.cxx fl_draw_image_win32.cxx
fl_font.o:	fl_font_mac.cxx fl_font_x.cxx fl_font_xft.cxx fl_font_win32.cxx
fl_read_image.o: fl_read_image_mac.cxx fl_read_image_win32.cxx
fl_set_fonts.o:	fl_set_fonts_mac.cxx fl_set_fonts_x.cxx \
		fl_set_fonts_xft.cxx fl_set_fonts_win32.cxx

fl_arci.o:	../FL/mac.H ../FL/win32.H
Fl_arg.o:	../FL/mac.H ../FL/win32.H
fl_ask.o:	../FL/mac.H ../FL/win32.H
Fl_Bitmap.o:	../FL/mac.H ../FL/win32.H
fl_color.o:	../FL/mac.H ../FL/win32.H
fl_cursor.o:	../FL/mac.H ../FL/win32.H
fl_dnd.o:	../FL/mac.H ../FL/win32.H
Fl.o:	../FL/mac.H ../FL/win32.H
Fl_Double_Window.o:	../FL/mac.H ../FL/win32.H
fl_draw_image.o:	../FL/mac.H ../FL/win32.H
fl_draw_image_mac.o:	../FL/mac.H ../FL/win32.H
fl_draw_image_win32.o:	../FL/mac.H ../FL/win32.H
fl_draw_pixmap.o:	../FL/mac.H ../FL/win32.H
Fl_File_Chooser2.o:	../FL/mac.H ../FL/win32.H
fl_font.o:	../FL/mac.H ../FL/win32.H
Fl_get_key.o:	../FL/mac.H ../FL/win32.H
Fl_get_system_colors.o:	../FL/mac.H ../FL/win32.H
Fl_Gl_Choice.o:	../FL/mac.H ../FL/win32.H
Fl_Gl_Overlay.o:	../FL/mac.H ../FL/win32.H
Fl_Gl_Window.o:	../FL/mac.H ../FL/win32.H
Fl_grab.o:	../FL/mac.H ../FL/win32.H
Fl_Image.o:	../FL/mac.H ../FL/win32.H
fl_line_style.o:	../FL/mac.H ../FL/win32.H
Fl_mac.o:	../FL/mac.H ../FL/win32.H
Fl_Menu_Window.o:	../FL/mac.H ../FL/win32.H
fl_overlay.o:	../FL/mac.H ../FL/win32.H
fl_overlay_visual.o:	../FL/mac.H ../FL/win32.H
Fl_Overlay_Window.o:	../FL/mac.H ../FL/win32.H
Fl_own_colormap.o:	../FL/mac.H ../FL/win32.H
Fl_Pixmap.o:	../FL/mac.H ../FL/win32.H
fl_read_image.o:	../FL/mac.H ../FL/win32.H
fl_read_image_mac.o:	../FL/mac.H ../FL/win32.H
fl_read_image_win32.o:	../FL/mac.H ../FL/win32.H
fl_rect.o:	../FL/mac.H ../FL/win32.H
fl_scroll_area.o:	../FL/mac.H ../FL/win32.H
fl_set_font.o:	../FL/mac.H ../FL/win32.H
fl_set_fonts.o:	../FL/mac.H ../FL/win32.H
fl_shortcut.o:	../FL/mac.H ../FL/win32.H
fl_vertex.o:	../FL/mac.H ../FL/win32.H
Fl_visual.o:	../FL/mac.H ../FL/win32.H
Fl_Window_fullscreen.o:	../FL/mac.H ../FL/win32.H
Fl_Window_iconize.o:	../FL/mac.H ../FL/win32.H
Fl_x.o:	../FL/mac.H ../FL/win32.H
gl_draw.o:	../FL/mac.H ../FL/win32.H
gl_start.o:	../FL/mac.H ../FL/win32.H

################################################################

install: $(LIBNAME) $(DSONAME) \
	$(FLLIBNAME) $(FLDSONAME) \
	$(GLLIBNAME) $(GLDSONAME) \
	$(IMGLIBNAME) $(IMGDSONAME)
	echo "Installing libraries in $(libdir)..."
	-$(MKDIR) $(libdir)
	$(RM) $(libdir)/$(LIBNAME)
	-$(CP) $(LIBNAME) $(FLLIBNAME) $(GLLIBNAME) $(IMGLIBNAME) $(libdir)
	$(RANLIB) $(libdir)/$(LIBNAME)
	$(RANLIB) $(libdir)/$(FLLIBNAME)
	if test x$(GLLIBNAME) != x; then \
		$(RANLIB) $(libdir)/$(GLLIBNAME); \
	fi
	$(RANLIB) $(libdir)/$(IMGLIBNAME)
	if test x$(DSONAME) = xlibfltk.so.1.1; then\
		$(RM) $(libdir)/libfltk.so*;\
		$(CP) libfltk.so.1.1 $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk.so.1.1; \
		$(LN) libfltk.so.1.1 $(libdir)/libfltk.so;\
	fi
	if test x$(DSONAME) = xlibfltk.sl.1.1; then\
		$(RM) $(libdir)/libfltk.sl*;\
		$(CP) libfltk.sl.1.1 $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk.sl.1.1; \
		$(LN) libfltk.sl.1.1 $(libdir)/libfltk.sl;\
	fi
	if test x$(DSONAME) = xlibfltk.1.1.dylib; then\
		$(RM) $(libdir)/libfltk.*dylib;\
		$(CP) libfltk.1.1.dylib $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk.1.1.dylib; \
		$(LN) libfltk.1.1.dylib $(libdir)/libfltk.dylib;\
	fi
	if test x$(DSONAME) = xlibfltk_s.a; then\
		$(RM) $(libdir)/libfltk_s.a;\
		$(CP) libfltk_s.a $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_s.a; \
	fi
	if test x$(FLDSONAME) = xlibfltk_forms.so.1.1; then\
		$(RM) $(libdir)/libfltk_forms.so*;\
		$(CP) libfltk_forms.so.1.1 $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_forms.so.1.1; \
		$(LN) libfltk_forms.so.1.1 $(libdir)/libfltk_forms.so;\
	fi
	if test x$(FLDSONAME) = xlibfltk_forms.sl.1.1; then\
		$(RM) $(libdir)/libfltk_forms.sl*;\
		$(CP) libfltk_forms.sl.1.1 $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_forms.sl.1.1; \
		$(LN) libfltk_forms.sl.1.1 $(libdir)/libfltk_forms.sl;\
	fi
	if test x$(FLDSONAME) = xlibfltk_forms.1.1.dylib; then\
		$(RM) $(libdir)/libfltk_forms.*dylib;\
		$(CP) libfltk_forms.1.1.dylib $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_forms.1.1.dylib; \
		$(LN) libfltk_forms.1.1.dylib $(libdir)/libfltk_forms.dylib;\
	fi
	if test x$(FLDSONAME) = xlibfltk_forms_s.a; then\
		$(RM) $(libdir)/libfltk_forms_s.a;\
		$(CP) libfltk_forms_s.a $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_forms.a; \
	fi
	if test x$(GLDSONAME) = xlibfltk_gl.so.1.1; then\
		$(RM) $(libdir)/libfltk_gl.so*;\
		$(CP) libfltk_gl.so.1.1 $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_gl.so.1.1; \
		$(LN) libfltk_gl.so.1.1 $(libdir)/libfltk_gl.so;\
	fi
	if test x$(GLDSONAME) = xlibfltk_gl.sl.1.1; then\
		$(RM) $(libdir)/libfltk_gl.sl*;\
		$(CP) libfltk_gl.sl.1.1 $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_gl.sl.1.1; \
		$(LN) libfltk_gl.sl.1.1 $(libdir)/libfltk_gl.sl;\
	fi
	if test x$(GLDSONAME) = xlibfltk_gl.1.1.dylib; then\
		$(RM) $(libdir)/libfltk_gl.*dylib;\
		$(CP) libfltk_gl.1.1.dylib $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_gl.1.1.dylib; \
		$(LN) libfltk_gl.1.1.dylib $(libdir)/libfltk_gl.dylib;\
	fi
	if test x$(GLDSONAME) = xlibfltk_gl_s.a; then\
		$(RM) $(libdir)/libfltk_gl_s.a;\
		$(CP) libfltk_gl_s.a $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_gl.a; \
	fi
	if test x$(IMGDSONAME) = xlibfltk_images.so.1.1; then\
		$(RM) $(libdir)/libfltk_images.so*;\
		$(CP) libfltk_images.so.1.1 $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_images.so.1.1; \
		$(LN) libfltk_images.so.1.1 $(libdir)/libfltk_images.so;\
	fi
	if test x$(IMGDSONAME) = xlibfltk_images.sl.1.1; then\
		$(RM) $(libdir)/libfltk_images.sl*;\
		$(CP) libfltk_images.sl.1.1 $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_images.sl.1.1; \
		$(LN) libfltk_images.sl.1.1 $(libdir)/libfltk_images.sl;\
	fi
	if test x$(IMGDSONAME) = xlibfltk_images.1.1.dylib; then\
		$(RM) $(libdir)/libfltk_images.*dylib;\
		$(CP) libfltk_images.1.1.dylib $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_images.1.1.dylib; \
		$(LN) libfltk_images.1.1.dylib $(libdir)/libfltk_images.dylib;\
	fi
	if test x$(IMGDSONAME) = xlibfltk_images_s.a; then\
		$(RM) $(libdir)/libfltk_images_s.a;\
		$(CP) libfltk_images_s.a $(libdir); \
		$(CHMOD) 755 $(libdir)/libfltk_images.a; \
	fi

uninstall:
	echo "Uninstalling libraries..."
	$(RM) $(libdir)/$(LIBNAME)
	if test x$(DSONAME) = xlibfltk.so.1.1; then\
		$(RM) $(libdir)/libfltk.so*;\
	fi
	if test x$(DSONAME) = xlibfltk.sl.1.1; then\
		$(RM) $(libdir)/libfltk.sl*;\
	fi
	if test x$(DSONAME) = xlibfltk.1.1.dylib; then\
		$(RM) $(libdir)/libfltk.*dylib;\
	fi
	if test x$(DSONAME) = xlibfltk_s.a; then\
		$(RM) $(libdir)/libfltk_s.a;\
	fi
	$(RM) $(libdir)/$(FLLIBNAME);
	if test x$(FLDSONAME) = xlibfltk_forms.so.1.1; then\
		$(RM) $(libdir)/libfltk_forms.so*;\
	fi
	if test x$(FLDSONAME) = xlibfltk_forms.sl.1.1; then\
		$(RM) $(libdir)/libfltk_forms.sl*;\
	fi
	if test x$(FLDSONAME) = xlibfltk_forms.1.1.dylib; then\
		$(RM) $(libdir)/libfltk_forms.*dylib;\
	fi
	if test x$(FLDSONAME) = xlibfltk_forms_s.a; then\
		$(RM) $(libdir)/libfltk_forms_s.a;\
	fi
	if test x$(GLLIBNAME) != x; then\
		$(RM) $(libdir)/$(GLLIBNAME);\
	fi
	if test x$(GLDSONAME) = xlibfltk_gl.so.1.1; then\
		$(RM) $(libdir)/libfltk_gl.so*;\
	fi
	if test x$(GLDSONAME) = xlibfltk_gl.sl.1.1; then\
		$(RM) $(libdir)/libfltk_gl.sl*;\
	fi
	if test x$(GLDSONAME) = xlibfltk_gl.1.1.dylib; then\
		$(RM) $(libdir)/libfltk_gl.*dylib;\
	fi
	if test x$(GLDSONAME) = xlibfltk_gl_s.a; then\
		$(RM) $(libdir)/libfltk_gl_s.a;\
	fi
	if test x$(IMGLIBNAME) != x; then\
		$(RM) $(libdir)/$(IMGLIBNAME);\
	fi
	if test x$(IMGDSONAME) = xlibfltk_images.so.1.1; then\
		$(RM) $(libdir)/libfltk_images.so*;\
	fi
	if test x$(IMGDSONAME) = xlibfltk_images.sl.1.1; then\
		$(RM) $(libdir)/libfltk_images.sl*;\
	fi
	if test x$(IMGDSONAME) = xlibfltk_images.1.1.dylib; then\
		$(RM) $(libdir)/libfltk_images.*dylib;\
	fi
	if test x$(IMGDSONAME) = xlibfltk_images_s.a; then\
		$(RM) $(libdir)/libfltk_images_s.a;\
	fi


#
# End of "$Id: Makefile,v 1.1 2004/02/18 16:10:33 chp Exp $".
#
