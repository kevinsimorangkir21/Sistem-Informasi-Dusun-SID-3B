<div align="center">
<h1> Sistem Informasi Dusun (SID) 3B </h1>

[![Github Commit](https://img.shields.io/github/commit-activity/m/kevinsimorangkir21/Sistem-Informasi-Dusun-SID-3B)](#)
[![Github Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg)](#)

</div>

## **Table Of Contents**

[Introduction Website](#introduction-website)

[Features Website](#features-website)

[Installation Steps](#installation-steps)

[License](#license)

[Screenshot](#screenshot)

[Presentation Video](#presentation-video)

## **Introduction Website**

The Dusun 3B Information System, abbreviated as SID 3B, is an Information System aimed at Hamlet 3B in Karang Anyar Village, Jati Agung District, South Lampung. SID38 is based on a CMS (<i>Content Management System</i>) using Laravel 5 and Bootstrap framework. SID 3B contains several news, management structures, galleries, and others.

## **Features Website**

<li> <b>Dashboard</b> : A feature that aims to organize the content/material on the SID38 website </li> <li><b>Structure</b> : This feature aims to find out the existing management structure in Hamlet 3B <li> <b>News </b> : A feature created with the aim of displaying news in Hamlet 3B <li><b>Galery</b> : A feature created with the aim of displaying a gallery of activities in Hamlet 3B </li>

## **Installation Steps**

There are 2 different installation stages, namely <b> Pre Install</b> and <b> Intra Install </b>.

### **Pre-Install**

At this stage is the stage of preparing several tools, especially frameworks and tools that will later be needed for this project. The following is needed for this project:

<li> Composer :</li>

```bash
https://getcomposer.org/download/
```

<li> Laravel 5 :</li>

```bash
https://laravel.com/docs/10.x
```

<li> XAMPP :</li>

```bash
https://www.apachefriends.org/download.html
```

<li> Git Bash :</li>

```bash
https://git-scm.com/downloads
```

### **Intra-Install**

At this stage is the installation stage of this project with the available steps. Here are the installation steps:

<li> Run GitBash and <i>clone</i> this GitHub repository</li>

```bash
https://github.com/kevinsimorangkir21/Sistem-Informasi-Dusun-SID-3B.git
```

<li> Open Visual Studio Code / Other Code Editors </li>

<li> Run Command Prompt / Terminal similar </li>

```bash
composer update
```

<li> Run XAMPP, create a database. Can be accessed at the following link </li>

```bash
http://localhost/phpmyadmin
```

<li> Copy .env.example / run CLI with command</li>

```bash
cp .env.example .env
```

<li> Change the file name .env.example to .env</li>

```bash
http://localhost/phpmyadmin
```

<li> Access the .env file again and change DB_DATABASE to the name of the database that was created on LocalHost </li>

<li> Run Command Prompt/Terminal again and enter</li>

```bash
php artisan migrate:fresh --seed
```

```bash
php artisan vendor:publish
```

```bash
php artisan key:generate
```

<li> To access this project on the web, run the command</li>

```bash
php artisan serve
```

## **License**
MIT License

Copyright (c) 2023 Bagason

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## **Screenshot**
The following is the appearance of the Dusun 3B website. This website has been prepared with a perfect structure according to the plot

<img src="public/assets/img/documentation1.png" />

## **Presentation Video**
