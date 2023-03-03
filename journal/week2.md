# Week 2 — Distributed Tracing

aws xray create-group \
   --group-name "Cruddur" \
   --filter-expression "service(\"backend-flask\")"