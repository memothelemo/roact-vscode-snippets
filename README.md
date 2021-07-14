<div align="center">
    <img src="assets/logo/index.png" alt="Roact" height="180">
    <h1>Roact Snippets</h1>
</div>

## About

Snippets for Roact (a ROBLOX library made by ROBLOX itself inspired by React)
with Rodux snippets provided

## Warning

If you installed React snippets, please disable it before using this extension otherwise it will overwrite the snippets and can have issues later on.

If you don't mean to install Roact snippets, I think you've spelled React wrong.

This is an experimental extension. I'm too new to VSCode extensions and stuff. If you have suggestions then I will be mostly happy to accept it.

## Usage

When using Luau:

<img src="assets/gifs/luau-demonstration.gif" alt="luau demonstration" width="500">

---

When using TSX (with roblox-ts and @rbxts/roact installed):

<img src="assets/gifs/rbxtsx-demonstration.gif" alt="rbxts demonstration" width="500">

---

## Snippets

Below is a list of available snippets and the triggers of each one.
Seperated with Lua and TSX

### TSX:

| Trigger | About                                              |
| ------- | -------------------------------------------------- |
| `rfc`   | Function component                                 |
| `rfcp`  | Function component with props configured           |
| `rpc`   | Pure component                                     |
| `rpcp`  | Pure component with props configured               |
| `rpcsp` | Pure component with props and state configured     |
| `rrpc`  | Pure component with Rodux implementation           |
| `rcc`   | Stateful component                                 |
| `rccp`  | Stateful component with props configured           |
| `rccsp` | Stateful component with props and state configured |
| `rrcc`  | Stateful component with Rodux implementation       |

---

### Luau:

| Trigger         | About                                          |
| --------------- | ---------------------------------------------- |
| `roact`         | Shortcut for importing Roact                   |
| `element`       | Shortcut for Roact.createElement               |
| `fragment`      | Shortcut for Roact.createFragment              |
| `context`       | Shortcut for Roact.createContext               |
| `componentinit` | Shortcut for Component:init() function         |
| `shouldUpdate`  | Shortcut for Component:shouldUpdate() function |
| `willUpdate`    | Shortcut for Component:willUpdate() function   |
| `didUpdate`     | Shortcut for Component:didUpdate() function    |
| `didMount`      | Shortcut for Component:didMount() function     |
| `willUnmount`   | Shortcut for Component:willUnmount() function  |
| `setstate`      | Shortcut for self:setState({}) function        |
| `state`         | Shortcut for self.state                        |
| `props`         | Shortcut for self.props                        |
| `rcc`           | Stateful component                             |
| `rfc`           | Function component                             |
| `rpc`           | Pure component                                 |
| `rrcc`          | Stateful component with Rodux implementation   |
| `rrpc`          | Pure component with Rodux implementation       |
| `roactrodux`    | Shortcut for importing RoactRodux              |
| `storeprovider` | Shortcut for RoactRodux.StoreProvider element  |
