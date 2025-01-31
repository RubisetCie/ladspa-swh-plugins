# Steve Harris LADSPA Plugins

## Compiling

You will need libfftw version 2 or 3 installed with 32 bit float support (eg. for FFTW3 use `--enable-float`), for FFTW recommend you specify the appropriate SIMD instruction set for your CPU with `--enable-sse`, `--enable-sse2`, `--enable-k7` or `--enable-altivec`.
You can get FFTW from http://www.fftw.org/.

Install with:

```
autoreconf -i
./configure
make
sudo make install
```

This code is normally built from XML source, using Perl and XML::Parser.
You will need a copy of Perl and XML::Parser installed.

## Homepage and docs

The homepage for this project is http://plugin.org.uk/

## Bug reports

Please send bug reports or comments to steve@plugin.org.uk, except for bugs relating to the gverb plugin, for that please send bug reports etc. to Juhana Sadeharju, kouhia_at_nic.funet.fi.
