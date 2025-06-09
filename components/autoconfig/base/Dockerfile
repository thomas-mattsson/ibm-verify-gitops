FROM python:3.13
           
RUN pip install setuptools
RUN pip install "cython<3.0.0" wheel
RUN pip install "pyyaml==5.4.1" --no-build-isolation
RUN pip install ibmvia-autoconf

CMD ["/bin/bash"]