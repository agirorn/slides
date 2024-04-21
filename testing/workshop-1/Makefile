.PHONY: setup
setup:
	pnpm install

.PHONY: dev
dev:
	 make open-slow &
	 pnpm run start

.PHONY: open-slow
open-slow:
	sleep 3
	pnpm exec open http://localhost:8000

.PHONY: build
build:
	pnpm run build

