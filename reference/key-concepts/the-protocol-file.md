---
title: The Protocol File
parent: Key Concepts
grand_parent: Reference
definition: With the Network Canvas software, the 'protocol file' is the file with the extension .netcanvas that represents your interview protocol.
---

Network Canvas protocols are stored in a file with the extension .netcanvas. They are just like any other files on your computer, meaning you can move them around, rename them, and you can (and should!) back them up.

The `.netcanvas` file contains all of the data in your protocol. So if you use any [resources](./resources.md), such as roster data, images, or video, these will be embedded within the file.

## Authoring Protocol Files

Architect will create your protocol file automatically when you [create a new protocol](../tutorials/building-using-architect.md) using it. As you add stages, edit content, or upload resources to your protocol, Architect will prompt you to save your changes. These changes will be stored within the protocol file.

Once you deploy your protocol to other applications, however, be aware that making changes effectively makes your protocol a new version. If you find that you need to make changes after deploying it, you have two options. It is recommended to save a copy of your protocol with a new name after making changes, and to import the new version to Interviewer and Server. The other option is to remove the existing protocol (and any interview data) from Server and Interviewer and upload the newer version. This is necessary to ensure compatibility across tools.

If you choose to create or edit a protocol file by hand, you will be responsible for ensuring it follows all specifications for the current [schema](../protocol-schema-information.md).

## Using Protocol Files

Once your protocol file is complete, you can then use this file in Server and Interviewer. Server and Interviewer both have [several options](../tutorials/server-workflows.md/#importing-a-protocol-to-server) for [importing a protocol](../tutorials/server-workflows.md/#importing-a-protocol-in-interviewer).