ARG VARIANT=20-bookworm
FROM mcr.microsoft.com/devcontainers/typescript-node:1-${VARIANT}

RUN corepack enable pnpm

RUN su node -c "pnpm setup"
