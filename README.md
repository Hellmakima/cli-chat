# CLI ChatRoom

Minimal CLI chat and voice chat server and client implemented with **FastAPI**.

## Quick Start (local)

_This project uses `uv` package manager._

1. Initialize the project

   ```sh
   uv sync
   ```

2. Run the server

   ```sh
   cd server
   uv run server.py
   # or: uv run uvicorn server:app --reload --port 8000
   ```

3. Run the client (in another terminal)

   ```sh
   cd client
   uv run client.py 1234 Alice
   ```

4. Open another client and join the same room:
   ```sh
   uv run client.py 1234 Bob
   ```

## References

- [Weechat](https://weechat.org/)
- [Simplex](https://simplex.chat/docs/cli.html)

## License

MIT
