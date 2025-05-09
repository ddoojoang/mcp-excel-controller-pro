# ExcelController

ExcelController is a **Model Context Protocol (MCP) server** that allows you to read, write, and modify Excel files.  
It runs in a Node.js environment and offers powerful Excel file manipulation features.

---

## ✨ Features (English)

- 📄 **Excel file reading**: Read contents from Excel files at specified paths
- ✍️ **Excel file writing**: Save data to Excel files (supports single/multiple sheets)
- 🧩 **Excel file modification**: Update specific cells in existing Excel files
- 📂 **Excel file opening**: Open files with the Excel application
- 📑 **Sheet management**: Add or delete sheets in Excel files
- 🎨 **Cell styling**: Format font, color, border, alignment, etc.
- 🔍 **Data filtering/sorting**: Filter and sort data by condition
- 📊 **Chart creation**: Generate charts and graphs from data
- 🧹 **Data validation/cleaning**: Remove duplicates, validate formats, clean empty cells
- 🔧 **Open file handling**: Modify Excel files even while open

---

## ✨ 주요 기능 (한국어)

- 📄 **엑셀 파일 읽기**: 특정 경로에서 엑셀 파일의 내용을 읽어옵니다
- ✍️ **엑셀 파일 쓰기**: 데이터를 엑셀 파일로 저장 (단일/다중 시트 지원)
- 🧩 **엑셀 파일 수정**: 기존 엑셀 파일의 셀 내용을 업데이트
- 📂 **엑셀 파일 열기**: Excel 애플리케이션으로 파일을 실행
- 📑 **시트 추가/삭제**: 엑셀 파일에 시트를 추가하거나 제거
- 🎨 **셀 스타일링**: 폰트, 색상, 테두리, 정렬 등 셀 서식 설정
- 🔍 **데이터 필터링 및 정렬**: 조건 기반 정렬 및 필터
- 📊 **차트 및 그래프 생성**: 데이터를 기반으로 차트 생성
- 🧹 **데이터 검증 및 정리**: 중복 제거, 형식 검증, 빈 셀 처리
- 🔧 **열린 파일 처리**: Excel에서 열려있는 파일도 수정 가능

---

## 📦 Installation

### Requirements

- Microsoft Excel installed on your system

### Setup in MCP Config

Add the following to your MCP configuration file:

```json
{
  "mcpServers": {
    "excel-controller": {
      "command": "npx",
      "args": [
        "-y",
        "mcp-excel-controller-pro",
        "mcp-excel-controller-pro",
        "C:\\Users\\user\\Desktop"
      ]
    }
  }
}
