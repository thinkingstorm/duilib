#------------------------------------------------------------------------------#
# This makefile was generated by 'cbp2make' tool rev.147                       #
#------------------------------------------------------------------------------#


WORKDIR = `pwd`

CC = gcc
CXX = g++
AR = ar
LD = g++
WINDRES = windres

INC = 
CFLAGS = `pkg-config --cflags gtk+-3.0` -Wconversion
RESINC = 
LIBDIR = 
LIB = 
LDFLAGS = `pkg-config --libs gtk+-3.0`

INC_BUILD = $(INC)
CFLAGS_BUILD = $(CFLAGS) -Wall -g -W -O0 -D_DEBUG -D_LIB
RESINC_BUILD = $(RESINC)
RCFLAGS_BUILD = $(RCFLAGS)
LIBDIR_BUILD = $(LIBDIR)
LIB_BUILD = $(LIB)
LDFLAGS_BUILD = $(LDFLAGS)
OBJDIR_BUILD = build
DEP_BUILD = 
OUT_BUILD = ./libdui.a

INC_RELEASE = $(INC)
CFLAGS_RELEASE = $(CFLAGS) -O2 -W -DNDEBUG -D_LIB
RESINC_RELEASE = $(RESINC)
RCFLAGS_RELEASE = $(RCFLAGS)
LIBDIR_RELEASE = $(LIBDIR)
LIB_RELEASE = $(LIB)
LDFLAGS_RELEASE = $(LDFLAGS)
OBJDIR_RELEASE = Release
DEP_RELEASE = 
OUT_RELEASE = ./libdui.a

OBJ_BUILD = $(OBJDIR_BUILD)/UIRender.o $(OBJDIR_BUILD)/UIScrollBar.o $(OBJDIR_BUILD)/UISlider.o $(OBJDIR_BUILD)/UIString.o $(OBJDIR_BUILD)/UITabLayout.o $(OBJDIR_BUILD)/UIText.o $(OBJDIR_BUILD)/UITileLayout.o $(OBJDIR_BUILD)/UIUtils.o $(OBJDIR_BUILD)/UIVerticalLayout.o $(OBJDIR_BUILD)/UIWindow.o $(OBJDIR_BUILD)/WindowImpBase.o $(OBJDIR_BUILD)/pugixml.o $(OBJDIR_BUILD)/stdafx.o $(OBJDIR_BUILD)/NotifyPump.o $(OBJDIR_BUILD)/ResourceMgr.o $(OBJDIR_BUILD)/UIButton.o $(OBJDIR_BUILD)/UIChildLayout.o $(OBJDIR_BUILD)/UIContainer.o $(OBJDIR_BUILD)/UIControl.o $(OBJDIR_BUILD)/DialogBuilder.o $(OBJDIR_BUILD)/UIEvent.o $(OBJDIR_BUILD)/UIFont.o $(OBJDIR_BUILD)/UIHorizontalLayout.o $(OBJDIR_BUILD)/UILabel.o $(OBJDIR_BUILD)/UIList.o $(OBJDIR_BUILD)/UIOption.o $(OBJDIR_BUILD)/UIProgress.o

OBJ_RELEASE = $(OBJDIR_RELEASE)/UIRender.o $(OBJDIR_RELEASE)/UIScrollBar.o $(OBJDIR_RELEASE)/UISlider.o $(OBJDIR_RELEASE)/UIString.o $(OBJDIR_RELEASE)/UITabLayout.o $(OBJDIR_RELEASE)/UIText.o $(OBJDIR_RELEASE)/UITileLayout.o $(OBJDIR_RELEASE)/UIUtils.o $(OBJDIR_RELEASE)/UIVerticalLayout.o $(OBJDIR_RELEASE)/UIWindow.o $(OBJDIR_RELEASE)/WindowImpBase.o $(OBJDIR_RELEASE)/pugixml.o $(OBJDIR_RELEASE)/stdafx.o $(OBJDIR_RELEASE)/NotifyPump.o $(OBJDIR_RELEASE)/ResourceMgr.o $(OBJDIR_RELEASE)/UIButton.o $(OBJDIR_RELEASE)/UIChildLayout.o $(OBJDIR_RELEASE)/UIContainer.o $(OBJDIR_RELEASE)/UIControl.o $(OBJDIR_RELEASE)/DialogBuilder.o $(OBJDIR_RELEASE)/UIEvent.o $(OBJDIR_RELEASE)/UIFont.o $(OBJDIR_RELEASE)/UIHorizontalLayout.o $(OBJDIR_RELEASE)/UILabel.o $(OBJDIR_RELEASE)/UIList.o $(OBJDIR_RELEASE)/UIOption.o $(OBJDIR_RELEASE)/UIProgress.o

all: build release

clean: clean_build clean_release

before_build: 
	test -d $(OBJDIR_BUILD) || mkdir -p $(OBJDIR_BUILD)

after_build: 

build: before_build out_build after_build

out_build: before_build $(OBJ_BUILD) $(DEP_BUILD)
	$(AR) rcs $(OUT_BUILD) $(OBJ_BUILD)

$(OBJDIR_BUILD)/UIRender.o: UIRender.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIRender.cpp -o $(OBJDIR_BUILD)/UIRender.o

$(OBJDIR_BUILD)/UIScrollBar.o: UIScrollBar.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIScrollBar.cpp -o $(OBJDIR_BUILD)/UIScrollBar.o

$(OBJDIR_BUILD)/UISlider.o: UISlider.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UISlider.cpp -o $(OBJDIR_BUILD)/UISlider.o

$(OBJDIR_BUILD)/UIString.o: UIString.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIString.cpp -o $(OBJDIR_BUILD)/UIString.o

$(OBJDIR_BUILD)/UITabLayout.o: UITabLayout.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UITabLayout.cpp -o $(OBJDIR_BUILD)/UITabLayout.o

$(OBJDIR_BUILD)/UIText.o: UIText.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIText.cpp -o $(OBJDIR_BUILD)/UIText.o

$(OBJDIR_BUILD)/UITileLayout.o: UITileLayout.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UITileLayout.cpp -o $(OBJDIR_BUILD)/UITileLayout.o

$(OBJDIR_BUILD)/UIUtils.o: UIUtils.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIUtils.cpp -o $(OBJDIR_BUILD)/UIUtils.o

$(OBJDIR_BUILD)/UIVerticalLayout.o: UIVerticalLayout.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIVerticalLayout.cpp -o $(OBJDIR_BUILD)/UIVerticalLayout.o

$(OBJDIR_BUILD)/UIWindow.o: UIWindow.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIWindow.cpp -o $(OBJDIR_BUILD)/UIWindow.o

$(OBJDIR_BUILD)/WindowImpBase.o: WindowImpBase.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c WindowImpBase.cpp -o $(OBJDIR_BUILD)/WindowImpBase.o

$(OBJDIR_BUILD)/pugixml.o: pugixml.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c pugixml.cpp -o $(OBJDIR_BUILD)/pugixml.o

$(OBJDIR_BUILD)/stdafx.o: stdafx.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c stdafx.cpp -o $(OBJDIR_BUILD)/stdafx.o

$(OBJDIR_BUILD)/NotifyPump.o: NotifyPump.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c NotifyPump.cpp -o $(OBJDIR_BUILD)/NotifyPump.o

$(OBJDIR_BUILD)/ResourceMgr.o: ResourceMgr.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c ResourceMgr.cpp -o $(OBJDIR_BUILD)/ResourceMgr.o

$(OBJDIR_BUILD)/UIButton.o: UIButton.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIButton.cpp -o $(OBJDIR_BUILD)/UIButton.o

$(OBJDIR_BUILD)/UIChildLayout.o: UIChildLayout.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIChildLayout.cpp -o $(OBJDIR_BUILD)/UIChildLayout.o

$(OBJDIR_BUILD)/UIContainer.o: UIContainer.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIContainer.cpp -o $(OBJDIR_BUILD)/UIContainer.o

$(OBJDIR_BUILD)/UIControl.o: UIControl.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIControl.cpp -o $(OBJDIR_BUILD)/UIControl.o

$(OBJDIR_BUILD)/DialogBuilder.o: DialogBuilder.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c DialogBuilder.cpp -o $(OBJDIR_BUILD)/DialogBuilder.o

$(OBJDIR_BUILD)/UIEvent.o: UIEvent.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIEvent.cpp -o $(OBJDIR_BUILD)/UIEvent.o

$(OBJDIR_BUILD)/UIFont.o: UIFont.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIFont.cpp -o $(OBJDIR_BUILD)/UIFont.o

$(OBJDIR_BUILD)/UIHorizontalLayout.o: UIHorizontalLayout.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIHorizontalLayout.cpp -o $(OBJDIR_BUILD)/UIHorizontalLayout.o

$(OBJDIR_BUILD)/UILabel.o: UILabel.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UILabel.cpp -o $(OBJDIR_BUILD)/UILabel.o

$(OBJDIR_BUILD)/UIList.o: UIList.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIList.cpp -o $(OBJDIR_BUILD)/UIList.o

$(OBJDIR_BUILD)/UIOption.o: UIOption.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIOption.cpp -o $(OBJDIR_BUILD)/UIOption.o

$(OBJDIR_BUILD)/UIProgress.o: UIProgress.cpp
	$(CXX) $(CFLAGS_BUILD) $(INC_BUILD) -c UIProgress.cpp -o $(OBJDIR_BUILD)/UIProgress.o

clean_build: 
	rm -f $(OBJ_BUILD) $(OUT_BUILD)
	rm -rf $(OBJDIR_BUILD)

before_release: 
	test -d $(OBJDIR_RELEASE) || mkdir -p $(OBJDIR_RELEASE)

after_release: 

release: before_release out_release after_release

out_release: before_release $(OBJ_RELEASE) $(DEP_RELEASE)
	$(AR) rcs $(OUT_RELEASE) $(OBJ_RELEASE)

$(OBJDIR_RELEASE)/UIRender.o: UIRender.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIRender.cpp -o $(OBJDIR_RELEASE)/UIRender.o

$(OBJDIR_RELEASE)/UIScrollBar.o: UIScrollBar.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIScrollBar.cpp -o $(OBJDIR_RELEASE)/UIScrollBar.o

$(OBJDIR_RELEASE)/UISlider.o: UISlider.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UISlider.cpp -o $(OBJDIR_RELEASE)/UISlider.o

$(OBJDIR_RELEASE)/UIString.o: UIString.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIString.cpp -o $(OBJDIR_RELEASE)/UIString.o

$(OBJDIR_RELEASE)/UITabLayout.o: UITabLayout.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UITabLayout.cpp -o $(OBJDIR_RELEASE)/UITabLayout.o

$(OBJDIR_RELEASE)/UIText.o: UIText.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIText.cpp -o $(OBJDIR_RELEASE)/UIText.o

$(OBJDIR_RELEASE)/UITileLayout.o: UITileLayout.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UITileLayout.cpp -o $(OBJDIR_RELEASE)/UITileLayout.o

$(OBJDIR_RELEASE)/UIUtils.o: UIUtils.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIUtils.cpp -o $(OBJDIR_RELEASE)/UIUtils.o

$(OBJDIR_RELEASE)/UIVerticalLayout.o: UIVerticalLayout.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIVerticalLayout.cpp -o $(OBJDIR_RELEASE)/UIVerticalLayout.o

$(OBJDIR_RELEASE)/UIWindow.o: UIWindow.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIWindow.cpp -o $(OBJDIR_RELEASE)/UIWindow.o

$(OBJDIR_RELEASE)/WindowImpBase.o: WindowImpBase.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c WindowImpBase.cpp -o $(OBJDIR_RELEASE)/WindowImpBase.o

$(OBJDIR_RELEASE)/pugixml.o: pugixml.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c pugixml.cpp -o $(OBJDIR_RELEASE)/pugixml.o

$(OBJDIR_RELEASE)/stdafx.o: stdafx.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c stdafx.cpp -o $(OBJDIR_RELEASE)/stdafx.o

$(OBJDIR_RELEASE)/NotifyPump.o: NotifyPump.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c NotifyPump.cpp -o $(OBJDIR_RELEASE)/NotifyPump.o

$(OBJDIR_RELEASE)/ResourceMgr.o: ResourceMgr.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c ResourceMgr.cpp -o $(OBJDIR_RELEASE)/ResourceMgr.o

$(OBJDIR_RELEASE)/UIButton.o: UIButton.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIButton.cpp -o $(OBJDIR_RELEASE)/UIButton.o

$(OBJDIR_RELEASE)/UIChildLayout.o: UIChildLayout.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIChildLayout.cpp -o $(OBJDIR_RELEASE)/UIChildLayout.o

$(OBJDIR_RELEASE)/UIContainer.o: UIContainer.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIContainer.cpp -o $(OBJDIR_RELEASE)/UIContainer.o

$(OBJDIR_RELEASE)/UIControl.o: UIControl.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIControl.cpp -o $(OBJDIR_RELEASE)/UIControl.o

$(OBJDIR_RELEASE)/DialogBuilder.o: DialogBuilder.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c DialogBuilder.cpp -o $(OBJDIR_RELEASE)/DialogBuilder.o

$(OBJDIR_RELEASE)/UIEvent.o: UIEvent.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIEvent.cpp -o $(OBJDIR_RELEASE)/UIEvent.o

$(OBJDIR_RELEASE)/UIFont.o: UIFont.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIFont.cpp -o $(OBJDIR_RELEASE)/UIFont.o

$(OBJDIR_RELEASE)/UIHorizontalLayout.o: UIHorizontalLayout.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIHorizontalLayout.cpp -o $(OBJDIR_RELEASE)/UIHorizontalLayout.o

$(OBJDIR_RELEASE)/UILabel.o: UILabel.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UILabel.cpp -o $(OBJDIR_RELEASE)/UILabel.o

$(OBJDIR_RELEASE)/UIList.o: UIList.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIList.cpp -o $(OBJDIR_RELEASE)/UIList.o

$(OBJDIR_RELEASE)/UIOption.o: UIOption.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIOption.cpp -o $(OBJDIR_RELEASE)/UIOption.o

$(OBJDIR_RELEASE)/UIProgress.o: UIProgress.cpp
	$(CXX) $(CFLAGS_RELEASE) $(INC_RELEASE) -c UIProgress.cpp -o $(OBJDIR_RELEASE)/UIProgress.o

clean_release: 
	rm -f $(OBJ_RELEASE) $(OUT_RELEASE)
	rm -rf $(OBJDIR_RELEASE)

.PHONY: before_build after_build clean_build before_release after_release clean_release

