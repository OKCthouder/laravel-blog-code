###基于Laravel搭建的一个简易博客
#### 运行环境
* php7
* mysql5.7
* laravel5.7
* composer
* npm

#### 运行系统
1. 克隆项目
```
	git clone https://github.com/OKCthouder/laravel-blog-code.git
```
2. 进入项目
```
	cd laravel-blog-code
```
3. 修改.env文件
```
	php artisan key:generate
	APP_NAME=Laravel学院
	APP_ENV=production
	APP_DEBUG=false
	APP_URL=http://blog.laravelacademy.org
   ```
4. 创建本地数据库
5. 运行迁移文件生成数据表以及自动填充数据
```
	 php artisan migrate
     php artisan db:seed
```
6. 更新依赖包
```
	composer update
```
7. 安装npm依赖包
```
	npm install
```
8. 运行系统
```
	php artisan serve
```