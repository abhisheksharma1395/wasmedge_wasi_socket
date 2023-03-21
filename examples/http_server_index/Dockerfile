FROM scratch
COPY http_server_index.wasm .
COPY index.html .
COPY index_250.html .
COPY index_500.html .
COPY index_750.html .
ENTRYPOINT [ "http_server_index.wasm" ]
