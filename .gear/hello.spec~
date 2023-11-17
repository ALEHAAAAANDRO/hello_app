Name: hello_app
Version: 0.0.1
Release: alt1
Summary: Hello app
License: GPL-3.0
Group: Other
Source0: %name-%version.tar
%description
A simple hello world application
%prep
%setup
%build
make
%install
mkdir -p %buildroot
install -D hello %buildroot/%_bindir/hello
%files
%_bindir/hello
