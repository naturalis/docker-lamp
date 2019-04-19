FROM httpd:2.4

RUN sed -i \
		-e 's/^#\(LoadModule .*mod_speling.so\)/\1/' \
		-e 's/^#\(LoadModule .*mod_rewrite.so\)/\1/' \
		conf/httpd.conf
