installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = TuxboxPlugins CutListEditor PicturePlayer MediaScanner MediaPlayer GraphMultiEPG SocketMMI DVDBurn \
        BhWeather BhEpgBackup BhFastEpg BhFullBackup BhPersonalBackup

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

install_PYTHON =	\
	__init__.py
