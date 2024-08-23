# Enclosed

**Enclosed** is a minimalistic web application designed for sending private and secure notes. 

All notes are end-to-end encrypted, ensuring that the server and storage have zero knowledge of the content. Users can set a password, define an expiration period (TTL), and choose to have the note self-destruct after being read.

A live instance is available at [enclosed.cc](https://enclosed.cc).

## Features

- **End-to-End Encryption**: Your notes are encrypted on the client side, and only the intended recipient can decrypt them.
- **Zero Knowledge**: The server does not have access to the content of the notes.
- **Configurable Security Options**: Set a password, expiration time, and choose self-destruction after the note is read.
- **Minimalistic UI**: Simple and intuitive user interface for quick note sharing.

## Installation

// TODO

## Usage

1. Visit the application URL.
2. Create a new note by entering the content.
3. (Optional) Set a password and expiration time.
4. Save the note, and you will receive a unique link.
5. Share the link with the intended recipient.

## Project Structure

This project is organized as a monorepo using `pnpm` workspaces. The structure is as follows:

- **packages/app-client**: Frontend application built with SolidJS.
- **packages/app-server**: Backend application using HonoJS.

## Contributing

Contributions are welcome! Please refer to the `CONTRIBUTING.md` file for guidelines on how to get started, report issues, and submit pull requests.

## License

This project is licensed under the Apache 2.0 License. See the `LICENSE` file for more details.

## Credits and Acknowledgements

### Frontend

- **SolidJS**: A declarative JavaScript library for building user interfaces.
- **shadcn-solid.com**: UI components library for SolidJS.
- **Tabler Icons**: A set of open-source icons.

### Backend

- **HonoJS**: A small, fast, and lightweight web framework for building APIs.
- **unstorage**: A universal storage API.
- **Zod**: A TypeScript-first schema declaration and validation library.

### Inspiration

- **[PrivateBin](https://github.com/PrivateBin/PrivateBin)**: A minimalist, open-source online pastebin where the server has zero knowledge of pasted data.
- **[Bitwarden Send](https://bitwarden.com/products/send/)**: A secure and ephemeral way to share sensitive information.
- The [shadcn playground](https://ui.shadcn.com/examples/playground) for the ui

## Contact Information

Please use the issue tracker on GitHub for any questions or feedback.