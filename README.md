# My WinUI Rust App

這是一個使用 **Rust** 與 [WinUI](https://zhuanlan.zhihu.com/p/2046321138091963376) 構建的原生 Windows 桌面應用程式。本專案基於微軟官方的 [Windows Reactor](https://zhuanlan.zhihu.com/p/2046321138091963376) 框架，旨在提供極致的效能、低記憶體佔用以及流暢的宣告式 UI 開發體驗。

## 🚀 核心優勢

* **極致效能**：得益於 Rust 與 [Windows Reactor](https://zhuanlan.zhihu.com/p/2046321138091963376) 的結合，擁有比 C# 版本更快的啟動時間與更低的記憶體消耗。
* **原生體驗**：直接對接 Windows 原生 UI 平台，與 Windows 11 風格完美契合。
* **宣告式開發**：無需複雜的 XAML，使用類似 React 的 Builder DSL 與 Hook 系統編寫 UI。
* **輕量部署**：編譯產出單文件執行檔（約 3MB），無需依賴龐大的運行時框架。

## 🛠 開發環境要求

在開始之前，請確保你的開發環境已滿足以下條件：

1. **Rust 工具鏈**：安裝最新的 [Rust](https://www.rust-lang.org/)。
2. **Windows SDK**：安裝 Windows 10/11 SDK（透過 Visual Studio Installer 獲取）。
3. **編譯環境**：確保配置了正確的 `LIB` 路徑與系統環境變數。

## 📦 快速開始

### 1. 克隆專案

```bash
git clone <你的倉庫地址>
cd my-winui-app

```

### 2. 執行應用

```bash
cargo run

```

## 🏗 專案結構

* `src/main.rs`: 應用的入口與主要 UI 組件定義。
* `Cargo.toml`: 專案依賴管理（包含 `windows` 與 `windows-reactor` 依賴）。
* `assets/`: 應用程式圖示與其他資源文件。

## 💡 關於 Windows Reactor

本專案使用了基於 [windows-rs](https://zhuanlan.zhihu.com/p/2046321138091963376) 的 [Windows Reactor](https://zhuanlan.zhihu.com/p/2046321138091963376) 技術，這是目前微軟推動 Rust 改造 [Windows 11](https://zhuanlan.zhihu.com/p/2046321138091963376) 核心組件的官方技術棧之一。

## 📝 授權

[在此處填寫你的授權協議，例如 MIT 或 Apache 2.0]
