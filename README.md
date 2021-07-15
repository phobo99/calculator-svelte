# Svelte Calculator

## Cài đặt extention Svelte 

npm install

npm run dev
___

`rollup.config.js:` Svelte sử dụng công cụ bundle gọi là Rollup, và đây là file bạn có thể tùy chỉnh cài đặt để bundle source code của mình.

README.md: File thông tin project của bạn (dành cho user đọc) nếu bạn publish lên GitHub

`package.json:` File thông tin project của bạn (dành cho dev đọc), cũng chứa các dependency để phát triển, deploy project của bạn.

`.gitignore:` Như tên gọi, file này để bỏ qua các `file/folder` mà bạn không muốn commit lên git.

`src:` Thư mục chứa source code

`main.js:` File đầu vào của cả cái web app. Lưu ý là nếu thay đổi tên file, bạn cần cài đặt lại tương ứng trong rollup.config.js.

`App.svelte:` Component viết bằng cú pháp của Svelte.

`scripts/setupTypeScript.js:` File để cài đặt TypeScript thay cho JavaScript, chạy câu lệnh `node scripts/setupTypeScript.js` để cài đặt.

`public:` Thư mục để deploy.
