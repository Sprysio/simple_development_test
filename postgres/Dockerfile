FROM postgres:16

EXPOSE 5432

HEALTHCHECK --interval=10s --timeout=5s --retries=3 \
    CMD pg_isready -U postgres -d testdb || exit 1