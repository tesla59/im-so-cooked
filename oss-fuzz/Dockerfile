FROM gcr.io/oss-fuzz-base/base-builder-go

COPY . $SRC/go-fuzz-sample

COPY ./oss-fuzz/build.sh $SRC/

ENV FUZZING_LANGUAGE=go

WORKDIR $SRC/go-fuzz-sample
