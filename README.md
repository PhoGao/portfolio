# portfolio
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Huỳnh Gia Bảo - Chuyên viên Logistics & Supply Chain</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --text-color: #333;
            --bg-light: #f8f9fa;
            --border-color: #ddd;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-light);
        }
        
        .container {
            max-width: 1140px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header */
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
            position: relative;
        }
        
        .profile {
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        
        .profile-info {
            flex: 1;
            min-width: 300px;
        }
        
        .profile h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .profile p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        
        .profile-photo {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            overflow: hidden;
            border: 5px solid white;
            margin-left: 2rem;
        }
        
        .profile-photo img {
            width: 100%;
            height: auto;
        }
        
        .contact-info {
            margin-top: 20px;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
            margin-right: 20px;
            display: inline-flex;
            align-items: center;
        }
        
        .contact-info a i {
            margin-right: 5px;
        }
        
        nav {
            background-color: var(--secondary-color);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
        }
        
        nav li {
            padding: 1rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
        }
        
        nav a:hover {
            color: #f1c40f;
        }
        
        /* Main Content */
        section {
            padding: 3rem 0;
            border-bottom: 1px solid var(--border-color);
        }
        
        section:last-child {
            border-bottom: none;
        }
        
        h2 {
            color: var(--primary-color);
            margin-bottom: 1.5rem;
            position: relative;
            padding-bottom: 10px;
        }
        
        h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 3px;
            background-color: var(--secondary-color);
        }
        
        .about-text {
            font-size: 1.1rem;
            margin-bottom: 2rem;
        }
        
        .objectives {
            display: flex;
            flex-wrap: wrap;
            margin: 0 -15px;
        }
        
        .objective-col {
            flex: 1;
            min-width: 300px;
            padding: 0 15px;
            margin-bottom: 1.5rem;
        }
        
        .objective-card {
            background-color: white;
            padding: 1.5rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            height: 100%;
        }
        
        .objective-card h3 {
            color: var(--secondary-color);
            margin-bottom: 1rem;
        }
        
        .exp-item {
            margin-bottom: 2rem;
            position: relative;
            padding-left: 1.5rem;
            border-left: 2px solid var(--secondary-color);
        }
        
        .exp-date {
            font-weight: bold;
            color: var(--secondary-color);
            margin-bottom: 0.5rem;
        }
        
        .exp-title {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
        }
        
        .exp-company {
            font-weight: 500;
            margin-bottom: 0.5rem;
        }
        
        .exp-desc ul {
            padding-left: 20px;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            margin: 0 -15px;
        }
        
        .skill-category {
            flex: 1;
            min-width: 250px;
            padding: 0 15px;
            margin-bottom: 1.5rem;
        }
        
        .skill-item {
            margin-bottom: 1rem;
        }
        
        .skill-name {
            font-weight: 500;
            margin-bottom: 0.3rem;
        }
        
        .skill-bar {
            height: 10px;
            background-color: #e9ecef;
            border-radius: 5px;
            overflow: hidden;
        }
        
        .skill-progress {
            height: 100%;
            background-color: var(--secondary-color);
        }
        
        .project {
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 1.5rem;
            margin-bottom: 2rem;
        }
        
        .project h3 {
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }
        
        .project-info {
            margin-bottom: 1rem;
            font-style: italic;
            color: #666;
        }
        
        .project-desc {
            margin-bottom: 1rem;
        }
        
        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 1rem;
        }
        
        .tech-tag {
            background-color: var(--secondary-color);
            color: white;
            padding: 5px 10px;
            border-radius: 3px;
            font-size: 0.9rem;
        }
        
        .education-item {
            margin-bottom: 1.5rem;
        }
        
        .edu-date {
            font-weight: bold;
            color: var(--secondary-color);
        }
        
        .edu-degree {
            font-weight: 600;
            font-size: 1.1rem;
        }
        
        .interests {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        
        .interest-item {
            display: flex;
            align-items: center;
            background-color: white;
            padding: 0.8rem 1.2rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .interest-item i {
            color: var(--secondary-color);
            margin-right: 10px;
            font-size: 1.2rem;
        }
        
        footer {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        
        .social-links {
            margin-bottom: 1rem;
        }
        
        .social-links a {
            color: white;
            font-size: 1.5rem;
            margin: 0 10px;
        }
        
        @media (max-width: 768px) {
            .profile {
                flex-direction: column;
                text-align: center;
            }
            
            .profile-photo {
                margin: 0 auto 1rem;
            }
            
            .contact-info {
                display: flex;
                flex-direction: column;
                align-items: center;
            }
            
            .contact-info a {
                margin-bottom: 10px;
            }
            
            nav ul {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <div class="profile">
                <div class="profile-info">
                    <h1>Huỳnh Gia Bảo</h1>
                    <p>Chuyên viên Logistics & Supply Chain Management</p>
                    <div class="contact-info">
                        <a href="mailto:bhp201626@gmail.com"><i class="fas fa-envelope"></i> bhp201626@gmail.com</a>
                        <a href="tel:0843124638"><i class="fas fa-phone"></i> 0843124638</a>
                        <a href="#"><i class="fas fa-map-marker-alt"></i> Thủ Đức, TP. Hồ Chí Minh</a>
                    </div>
                </div>
                <div class="profile-photo">
                    <!-- Thêm ảnh đại diện của bạn vào thư mục assets -->
                    <img src="assets/avatar.jpg" alt="Huỳnh Gia Bảo" onerror="this.src='https://via.placeholder.com/200'">
                </div>
            </div>
        </div>
    </header>
    
    <!-- Navigation -->
    <nav>
        <div class="container">
            <ul>
                <li><a href="#about">Giới thiệu</a></li>
                <li><a href="#experience">Kinh nghiệm</a></li>
                <li><a href="#projects">Dự án nổi bật</a></li>
                <li><a href="#skills">Kỹ năng</a></li>
                <li><a href="#education">Học vấn</a></li>
                <li><a href="#interests">Sở thích</a></li>
            </ul>
        </div>
    </nav>
    
    <!-- Main Content -->
    <main>
        <!-- About Section -->
        <section id="about" class="container">
            <h2>Giới thiệu</h2>
            <p class="about-text">
                Tôi là Huỳnh Gia Bảo, chuyên viên trong lĩnh vực Logistics và Quản lý chuỗi cung ứng với hơn 5 năm kinh nghiệm. Tôi đã từng quản lý và vận hành nhiều kho hàng, triển khai các dự án cải tiến quy trình và hệ thống, cũng như phát triển các giải pháp logistics hiệu quả. Hiện nay, tôi đang tìm kiếm cơ hội phát triển trong lĩnh vực xuất nhập khẩu và quản trị chuỗi cung ứng.
            </p>
            
            <div class="objectives">
                <div class="objective-col">
                    <div class="objective-card">
                        <h3>Mục tiêu ngắn hạn</h3>
                        <ul>
                            <li>Phát triển kỹ năng và kiến thức về lĩnh vực xuất nhập khẩu, quản trị chuỗi cung ứng</li>
                            <li>Tìm kiếm môi trường làm việc có cơ hội thăng tiến và công việc ổn định</li>
                        </ul>
                    </div>
                </div>
                <div class="objective-col">
                    <div class="objective-card">
                        <h3>Mục tiêu dài hạn</h3>
                        <ul>
                            <li>Thăng tiến trưởng phòng kho vận, vận hành chuỗi cung ứng trong 3 năm tiếp theo</li>
                            <li>Xây dựng nhiều mối quan hệ trong lĩnh vực logistics, chuỗi cung ứng</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Experience Section -->
        <section id="experience" class="container">
            <h2>Kinh nghiệm làm việc</h2>
            
            <div class="exp-item">
                <div class="exp-date">09/2023 - 02/2025</div>
                <div class="exp-title">DISTRIBUTION CENTER SUPERVISOR</div>
                <div class="exp-company">Công ty SEEDCOM LOGISTICS</div>
                <div class="exp-desc">
                    <ul>
                        <li>Quản lý xuất, nhập, tồn, xử lý các vấn đề liên quan về hàng hóa với khách hàng</li>
                        <li>Xây dựng và đảm bảo kế hoạch hàng tuần, tháng, quý được triển khai theo đúng dự định: nhân sự, sản lượng, vận tải</li>
                        <li>Kiểm soát, quản lý các chỉ tiêu của kho: tỷ lệ lấp đầy, SLA</li>
                        <li>Sắp xếp, điều chỉnh, phân phối nhân sự đảm bảo năng suất kho</li>
                        <li>Xây dựng quy trình cho toàn bộ kho: kiểm hàng, nhận hàng, chia chọn</li>
                        <li>Xây dựng, đề xuất cải tiến hệ thống WMS của kho</li>
                        <li>Quản lý kiểm soát quá trình vận tải từ nhà cung cấp đến kho, từ kho đến khách hàng</li>
                        <li>Triển khai công tác 5S, 3S cho toàn bộ nhân viên kho</li>
                        <li>Xây dựng dashboard, template tracking năng suất kho</li>
                    </ul>
                </div>
            </div>
            
            <div class="exp-item">
                <div class="exp-date">01/2022 - 05/2023</div>
                <div class="exp-title">WAREHOUSE SUPERVISOR</div>
                <div class="exp-company">Công ty KOINA logistics</div>
                <div class="exp-desc">
                    <ul>
                        <li>Quản lý xuất, nhập, tồn</li>
                        <li>Thống kê và kiểm soát các tiêu chí kho: năng suất, thời gian, khối lượng công việc</li>
                        <li>Triển khai, báo cáo và lên các kế hoạch của vận hành kho</li>
                        <li>Triển khai công việc (phân tuyến, sắp xếp đơn hàng) với 3PLs để đảm bảo vận hành kho</li>
                        <li>Quản lý các chi phí vận hành kho: nhân công, vận tải</li>
                        <li>Tham gia xây dựng quy trình kho</li>
                    </ul>
                </div>
            </div>
            
            <div class="exp-item">
                <div class="exp-date">03/2019 - 12/2021</div>
                <div class="exp-title">WAREHOUSE CONTROLER</div>
                <div class="exp-company">Công ty AKANO</div>
                <div class="exp-desc">
                    <ul>
                        <li>Quản lý xuất, nhập, tồn</li>
                        <li>Quản lý giỏ hàng</li>
                        <li>Xây dựng kế hoạch nhập hàng, kiểm kê theo tháng, quý</li>
                        <li>Tính toán chi phí vận hành và vận chuyển</li>
                        <li>Báo cáo cho quản lý trực tiếp</li>
                    </ul>
                </div>
            </div>
            
            <div class="exp-item">
                <div class="exp-date">05/2018 - 03/2019</div>
                <div class="exp-title">Nhân viên bán hàng</div>
                <div class="exp-company">Cửa hàng tiện lợi Ministop</div>
                <div class="exp-desc">
                    <ul>
                        <li>Xử lý hàng hoá về cửa hàng</li>
                        <li>Đặt hàng, nhận hàng và nhập kho</li>
                        <li>Đẩy mạnh các chương trình khuyến mãi</li>
                    </ul>
                </div>
            </div>
        </section>
        
        <!-- Projects Section -->
        <section id="projects" class="container">
            <h2>Dự án nổi bật</h2>
            
            <div class="project">
                <h3>Chuyển đổi kho nóng thành kho mát</h3>
                <div class="project-info">SEEDCOM LOGISTICS | 2024</div>
                <div class="project-desc">
                    <p>Dự án chuyển đổi hệ thống kho nóng sang kho mát để đáp ứng nhu cầu bảo quản hàng hóa ở điều kiện nhiệt độ thấp. Quản lý toàn bộ quá trình từ lên kế hoạch, thiết kế, thi công đến đưa vào vận hành.</p>
                    <p><strong>Thành tựu:</strong></p>
                    <ul>
                        <li>Hoàn thành dự án đúng thời hạn trong vòng 3 tháng</li>
                        <li>Tối ưu chi phí vận hành giảm 15% so với dự toán ban đầu</li>
                        <li>Duy trì nhiệt độ ổn định trong phạm vi yêu cầu</li>
                    </ul>
                </div>
                <div class="project-tech">
                    <span class="tech-tag">WMS</span>
                    <span class="tech-tag">Kho vận</span>
                    <span class="tech-tag">Cold Storage</span>
                    <span class="tech-tag">Supply Chain</span>
                </div>
            </div>
            
            <div class="project">
                <h3>Xây dựng hệ thống Dashboard theo dõi năng suất kho hàng</h3>
                <div class="project-info">SEEDCOM LOGISTICS | 2023</div>
                <div class="project-desc">
                    <p>Phát triển hệ thống dashboard để theo dõi và phân tích năng suất hoạt động của kho hàng. Sử dụng dữ liệu từ các nguồn khác nhau để tạo ra các báo cáo trực quan, giúp quản lý đưa ra quyết định dựa trên dữ liệu.</p>
                    <p><strong>Thành tựu:</strong></p>
                    <ul>
                        <li>Xây dựng được hệ thống báo cáo tự động cập nhật theo thời gian thực</li>
                        <li>Tăng năng suất kho 20% sau 3 tháng triển khai</li>
                        <li>Giảm thời gian báo cáo từ 1 ngày xuống còn 1 giờ</li>
                    </ul>
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Power BI</span>
                    <span class="tech-tag">SQL</span>
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Data Analysis</span>
                </div>
            </div>
            
            <div class="project">
                <h3>Cải tiến quy trình kho nhà cung cấp</h3>
                <div class="project-info">KOINA LOGISTICS | 2022</div>
                <div class="project-desc">
                    <p>Dự án tái cấu trúc quy trình làm việc giữa kho và nhà cung cấp, tối ưu hoá thời gian và nguồn lực. Xây dựng hệ thống liên lạc và cơ chế phản hồi mới giữa kho và nhà cung cấp.</p>
                    <p><strong>Thành tựu:</strong></p>
                    <ul>
                        <li>Giảm 30% thời gian từ khi đặt hàng đến khi hàng về kho</li>
                        <li>Tăng độ chính xác của việc giao nhận hàng lên 98%</li>
                        <li>Giảm 25% lỗi hàng hóa từ nhà cung cấp</li>
                    </ul>
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Lean Management</span>
                    <span class="tech-tag">Process Optimization</span>
                    <span class="tech-tag">WMS</span>
                    <span class="tech-tag">Supply Chain</span>
                </div>
            </div>
        </section>
        
        <!-- Skills Section -->
        <section id="skills" class="container">
            <h2>Kỹ năng</h2>
            
            <div class="skills">
                <div class="skill-category">
                    <h3>Chuyên môn</h3>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý kho vận (Warehouse Management)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 95%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý chuỗi cung ứng (Supply Chain)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý vận tải (Transportation Management)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 80%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý nhân sự</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Kiểm soát chi phí & Ngân sách</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 75%;"></div>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Công nghệ & Phần mềm</h3>
                    
                    <div class="skill-item">
                        <div class="skill-name">Microsoft Office (Word, Excel, PowerPoint)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 90%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Hệ thống WMS (Warehouse Management System)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Hệ thống TMS (Transportation Management System)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 80%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">ERP Systems</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 75%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Power BI / Google Data Studio</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 70%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">SQL & Python (Cơ bản)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 60%;"></div>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Kỹ năng mềm</h3>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý dự án</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Giải quyết vấn đề</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 90%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Làm việc nhóm</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 95%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Tiếng Anh</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 65%;"></div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Education Section -->
        <section id="education" class="container">
            <h2>Học vấn & Chứng chỉ</h2>
            
            <div class="education-item">
                <div class="edu-date">09/2022 - Hiện tại</div>
                <div class="edu-degree">Kinh Doanh Quốc Tế</div>
                <div class="edu-school">Đại học Mở</div>
                <div class="edu-desc">Đang theo học hệ từ xa</div>
            </div>
            
            <div class="education-item
            <!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Huỳnh Gia Bảo - Chuyên viên Logistics & Supply Chain</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --text-color: #333;
            --bg-light: #f8f9fa;
            --border-color: #ddd;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-light);
        }
        
        .container {
            max-width: 1140px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header */
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
            position: relative;
        }
        
        .profile {
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        
        .profile-info {
            flex: 1;
            min-width: 300px;
        }
        
        .profile h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .profile p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        
        .profile-photo {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            overflow: hidden;
            border: 5px solid white;
            margin-left: 2rem;
        }
        
        .profile-photo img {
            width: 100%;
            height: auto;
        }
        
        .contact-info {
            margin-top: 20px;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
            margin-right: 20px;
            display: inline-flex;
            align-items: center;
        }
        
        .contact-info a i {
            margin-right: 5px;
        }
        
        nav {
            background-color: var(--secondary-color);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
        }
        
        nav li {
            padding: 1rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
        }
        
        nav a:hover {
            color: #f1c40f;
        }
        
        /* Main Content */
        section {
            padding: 3rem 0;
            border-bottom: 1px solid var(--border-color);
        }
        
        section:last-child {
            border-bottom: none;
        }
        
        h2 {
            color: var(--primary-color);
            margin-bottom: 1.5rem;
            position: relative;
            padding-bottom: 10px;
        }
        
        h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 3px;
            background-color: var(--secondary-color);
        }
        
        .about-text {
            font-size: 1.1rem;
            margin-bottom: 2rem;
        }
        
        .objectives {
            display: flex;
            flex-wrap: wrap;
            margin: 0 -15px;
        }
        
        .objective-col {
            flex: 1;
            min-width: 300px;
            padding: 0 15px;
            margin-bottom: 1.5rem;
        }
        
        .objective-card {
            background-color: white;
            padding: 1.5rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            height: 100%;
        }
        
        .objective-card h3 {
            color: var(--secondary-color);
            margin-bottom: 1rem;
        }
        
        .exp-item {
            margin-bottom: 2rem;
            position: relative;
            padding-left: 1.5rem;
            border-left: 2px solid var(--secondary-color);
        }
        
        .exp-date {
            font-weight: bold;
            color: var(--secondary-color);
            margin-bottom: 0.5rem;
        }
        
        .exp-title {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
        }
        
        .exp-company {
            font-weight: 500;
            margin-bottom: 0.5rem;
        }
        
        .exp-desc ul {
            padding-left: 20px;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            margin: 0 -15px;
        }
        
        .skill-category {
            flex: 1;
            min-width: 250px;
            padding: 0 15px;
            margin-bottom: 1.5rem;
        }
        
        .skill-item {
            margin-bottom: 1rem;
        }
        
        .skill-name {
            font-weight: 500;
            margin-bottom: 0.3rem;
        }
        
        .skill-bar {
            height: 10px;
            background-color: #e9ecef;
            border-radius: 5px;
            overflow: hidden;
        }
        
        .skill-progress {
            height: 100%;
            background-color: var(--secondary-color);
        }
        
        .project {
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 1.5rem;
            margin-bottom: 2rem;
        }
        
        .project h3 {
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }
        
        .project-info {
            margin-bottom: 1rem;
            font-style: italic;
            color: #666;
        }
        
        .project-desc {
            margin-bottom: 1rem;
        }
        
        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 1rem;
        }
        
        .tech-tag {
            background-color: var(--secondary-color);
            color: white;
            padding: 5px 10px;
            border-radius: 3px;
            font-size: 0.9rem;
        }
        
        .education-item {
            margin-bottom: 1.5rem;
        }
        
        .edu-date {
            font-weight: bold;
            color: var(--secondary-color);
        }
        
        .edu-degree {
            font-weight: 600;
            font-size: 1.1rem;
        }
        
        .interests {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        
        .interest-item {
            display: flex;
            align-items: center;
            background-color: white;
            padding: 0.8rem 1.2rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .interest-item i {
            color: var(--secondary-color);
            margin-right: 10px;
            font-size: 1.2rem;
        }
        
        footer {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        
        .social-links {
            margin-bottom: 1rem;
        }
        
        .social-links a {
            color: white;
            font-size: 1.5rem;
            margin: 0 10px;
        }
        
        @media (max-width: 768px) {
            .profile {
                flex-direction: column;
                text-align: center;
            }
            
            .profile-photo {
                margin: 0 auto 1rem;
            }
            
            .contact-info {
                display: flex;
                flex-direction: column;
                align-items: center;
            }
            
            .contact-info a {
                margin-bottom: 10px;
            }
            
            nav ul {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <div class="profile">
                <div class="profile-info">
                    <h1>Huỳnh Gia Bảo</h1>
                    <p>Chuyên viên Logistics & Supply Chain Management</p>
                    <div class="contact-info">
                        <a href="mailto:bhp201626@gmail.com"><i class="fas fa-envelope"></i> bhp201626@gmail.com</a>
                        <a href="tel:0843124638"><i class="fas fa-phone"></i> 0843124638</a>
                        <a href="#"><i class="fas fa-map-marker-alt"></i> Thủ Đức, TP. Hồ Chí Minh</a>
                    </div>
                </div>
                <div class="profile-photo">
                    <!-- Thêm ảnh đại diện của bạn vào thư mục assets -->
                    <img src="assets/avatar.jpg" alt="Huỳnh Gia Bảo" onerror="this.src='https://via.placeholder.com/200'">
                </div>
            </div>
        </div>
    </header>
    
    <!-- Navigation -->
    <nav>
        <div class="container">
            <ul>
                <li><a href="#about">Giới thiệu</a></li>
                <li><a href="#experience">Kinh nghiệm</a></li>
                <li><a href="#projects">Dự án nổi bật</a></li>
                <li><a href="#skills">Kỹ năng</a></li>
                <li><a href="#education">Học vấn</a></li>
                <li><a href="#interests">Sở thích</a></li>
            </ul>
        </div>
    </nav>
    
    <!-- Main Content -->
    <main>
        <!-- About Section -->
        <section id="about" class="container">
            <h2>Giới thiệu</h2>
            <p class="about-text">
                Tôi là Huỳnh Gia Bảo, chuyên viên trong lĩnh vực Logistics và Quản lý chuỗi cung ứng với hơn 5 năm kinh nghiệm. Tôi đã từng quản lý và vận hành nhiều kho hàng, triển khai các dự án cải tiến quy trình và hệ thống, cũng như phát triển các giải pháp logistics hiệu quả. Hiện nay, tôi đang tìm kiếm cơ hội phát triển trong lĩnh vực xuất nhập khẩu và quản trị chuỗi cung ứng.
            </p>
            
            <div class="objectives">
                <div class="objective-col">
                    <div class="objective-card">
                        <h3>Mục tiêu ngắn hạn</h3>
                        <ul>
                            <li>Phát triển kỹ năng và kiến thức về lĩnh vực xuất nhập khẩu, quản trị chuỗi cung ứng</li>
                            <li>Tìm kiếm môi trường làm việc có cơ hội thăng tiến và công việc ổn định</li>
                        </ul>
                    </div>
                </div>
                <div class="objective-col">
                    <div class="objective-card">
                        <h3>Mục tiêu dài hạn</h3>
                        <ul>
                            <li>Thăng tiến trưởng phòng kho vận, vận hành chuỗi cung ứng trong 3 năm tiếp theo</li>
                            <li>Xây dựng nhiều mối quan hệ trong lĩnh vực logistics, chuỗi cung ứng</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Experience Section -->
        <section id="experience" class="container">
            <h2>Kinh nghiệm làm việc</h2>
            
            <div class="exp-item">
                <div class="exp-date">09/2023 - 02/2025</div>
                <div class="exp-title">DISTRIBUTION CENTER SUPERVISOR</div>
                <div class="exp-company">Công ty SEEDCOM LOGISTICS</div>
                <div class="exp-desc">
                    <ul>
                        <li>Quản lý xuất, nhập, tồn, xử lý các vấn đề liên quan về hàng hóa với khách hàng</li>
                        <li>Xây dựng và đảm bảo kế hoạch hàng tuần, tháng, quý được triển khai theo đúng dự định: nhân sự, sản lượng, vận tải</li>
                        <li>Kiểm soát, quản lý các chỉ tiêu của kho: tỷ lệ lấp đầy, SLA</li>
                        <li>Sắp xếp, điều chỉnh, phân phối nhân sự đảm bảo năng suất kho</li>
                        <li>Xây dựng quy trình cho toàn bộ kho: kiểm hàng, nhận hàng, chia chọn</li>
                        <li>Xây dựng, đề xuất cải tiến hệ thống WMS của kho</li>
                        <li>Quản lý kiểm soát quá trình vận tải từ nhà cung cấp đến kho, từ kho đến khách hàng</li>
                        <li>Triển khai công tác 5S, 3S cho toàn bộ nhân viên kho</li>
                        <li>Xây dựng dashboard, template tracking năng suất kho</li>
                    </ul>
                </div>
            </div>
            
            <div class="exp-item">
                <div class="exp-date">01/2022 - 05/2023</div>
                <div class="exp-title">WAREHOUSE SUPERVISOR</div>
                <div class="exp-company">Công ty KOINA logistics</div>
                <div class="exp-desc">
                    <ul>
                        <li>Quản lý xuất, nhập, tồn</li>
                        <li>Thống kê và kiểm soát các tiêu chí kho: năng suất, thời gian, khối lượng công việc</li>
                        <li>Triển khai, báo cáo và lên các kế hoạch của vận hành kho</li>
                        <li>Triển khai công việc (phân tuyến, sắp xếp đơn hàng) với 3PLs để đảm bảo vận hành kho</li>
                        <li>Quản lý các chi phí vận hành kho: nhân công, vận tải</li>
                        <li>Tham gia xây dựng quy trình kho</li>
                    </ul>
                </div>
            </div>
            
            <div class="exp-item">
                <div class="exp-date">03/2019 - 12/2021</div>
                <div class="exp-title">WAREHOUSE CONTROLER</div>
                <div class="exp-company">Công ty AKANO</div>
                <div class="exp-desc">
                    <ul>
                        <li>Quản lý xuất, nhập, tồn</li>
                        <li>Quản lý giỏ hàng</li>
                        <li>Xây dựng kế hoạch nhập hàng, kiểm kê theo tháng, quý</li>
                        <li>Tính toán chi phí vận hành và vận chuyển</li>
                        <li>Báo cáo cho quản lý trực tiếp</li>
                    </ul>
                </div>
            </div>
            
            <div class="exp-item">
                <div class="exp-date">05/2018 - 03/2019</div>
                <div class="exp-title">Nhân viên bán hàng</div>
                <div class="exp-company">Cửa hàng tiện lợi Ministop</div>
                <div class="exp-desc">
                    <ul>
                        <li>Xử lý hàng hoá về cửa hàng</li>
                        <li>Đặt hàng, nhận hàng và nhập kho</li>
                        <li>Đẩy mạnh các chương trình khuyến mãi</li>
                    </ul>
                </div>
            </div>
        </section>
        
        <!-- Projects Section -->
        <section id="projects" class="container">
            <h2>Dự án nổi bật</h2>
            
            <div class="project">
                <h3>Chuyển đổi kho nóng thành kho mát</h3>
                <div class="project-info">SEEDCOM LOGISTICS | 2024</div>
                <div class="project-desc">
                    <p>Dự án chuyển đổi hệ thống kho nóng sang kho mát để đáp ứng nhu cầu bảo quản hàng hóa ở điều kiện nhiệt độ thấp. Quản lý toàn bộ quá trình từ lên kế hoạch, thiết kế, thi công đến đưa vào vận hành.</p>
                    <p><strong>Thành tựu:</strong></p>
                    <ul>
                        <li>Hoàn thành dự án đúng thời hạn trong vòng 3 tháng</li>
                        <li>Tối ưu chi phí vận hành giảm 15% so với dự toán ban đầu</li>
                        <li>Duy trì nhiệt độ ổn định trong phạm vi yêu cầu</li>
                    </ul>
                </div>
                <div class="project-tech">
                    <span class="tech-tag">WMS</span>
                    <span class="tech-tag">Kho vận</span>
                    <span class="tech-tag">Cold Storage</span>
                    <span class="tech-tag">Supply Chain</span>
                </div>
            </div>
            
            <div class="project">
                <h3>Xây dựng hệ thống Dashboard theo dõi năng suất kho hàng</h3>
                <div class="project-info">SEEDCOM LOGISTICS | 2023</div>
                <div class="project-desc">
                    <p>Phát triển hệ thống dashboard để theo dõi và phân tích năng suất hoạt động của kho hàng. Sử dụng dữ liệu từ các nguồn khác nhau để tạo ra các báo cáo trực quan, giúp quản lý đưa ra quyết định dựa trên dữ liệu.</p>
                    <p><strong>Thành tựu:</strong></p>
                    <ul>
                        <li>Xây dựng được hệ thống báo cáo tự động cập nhật theo thời gian thực</li>
                        <li>Tăng năng suất kho 20% sau 3 tháng triển khai</li>
                        <li>Giảm thời gian báo cáo từ 1 ngày xuống còn 1 giờ</li>
                    </ul>
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Power BI</span>
                    <span class="tech-tag">SQL</span>
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Data Analysis</span>
                </div>
            </div>
            
            <div class="project">
                <h3>Cải tiến quy trình kho nhà cung cấp</h3>
                <div class="project-info">KOINA LOGISTICS | 2022</div>
                <div class="project-desc">
                    <p>Dự án tái cấu trúc quy trình làm việc giữa kho và nhà cung cấp, tối ưu hoá thời gian và nguồn lực. Xây dựng hệ thống liên lạc và cơ chế phản hồi mới giữa kho và nhà cung cấp.</p>
                    <p><strong>Thành tựu:</strong></p>
                    <ul>
                        <li>Giảm 30% thời gian từ khi đặt hàng đến khi hàng về kho</li>
                        <li>Tăng độ chính xác của việc giao nhận hàng lên 98%</li>
                        <li>Giảm 25% lỗi hàng hóa từ nhà cung cấp</li>
                    </ul>
                </div>
                <div class="project-tech">
                    <span class="tech-tag">Lean Management</span>
                    <span class="tech-tag">Process Optimization</span>
                    <span class="tech-tag">WMS</span>
                    <span class="tech-tag">Supply Chain</span>
                </div>
            </div>
        </section>
        
        <!-- Skills Section -->
        <section id="skills" class="container">
            <h2>Kỹ năng</h2>
            
            <div class="skills">
                <div class="skill-category">
                    <h3>Chuyên môn</h3>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý kho vận (Warehouse Management)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 95%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý chuỗi cung ứng (Supply Chain)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý vận tải (Transportation Management)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 80%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý nhân sự</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Kiểm soát chi phí & Ngân sách</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 75%;"></div>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Công nghệ & Phần mềm</h3>
                    
                    <div class="skill-item">
                        <div class="skill-name">Microsoft Office (Word, Excel, PowerPoint)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 90%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Hệ thống WMS (Warehouse Management System)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Hệ thống TMS (Transportation Management System)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 80%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">ERP Systems</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 75%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Power BI / Google Data Studio</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 70%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">SQL & Python (Cơ bản)</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 60%;"></div>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Kỹ năng mềm</h3>
                    
                    <div class="skill-item">
                        <div class="skill-name">Quản lý dự án</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 85%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Giải quyết vấn đề</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 90%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Làm việc nhóm</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 95%;"></div>
                        </div>
                    </div>
                    
                    <div class="skill-item">
                        <div class="skill-name">Tiếng Anh</div>
                        <div class="skill-bar">
                            <div class="skill-progress" style="width: 65%;"></div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Education Section -->
        <section id="education" class="container">
            <h2>Học vấn & Chứng chỉ</h2>
            
            <div class="education-item">
                <div class="edu-date">09/2022 - Hiện tại</div>
                <div class="edu-degree">Kinh Doanh Quốc Tế</div>
                <div class="edu-school">Đại học Mở</div>
                <div class="edu-desc">Đang theo học hệ từ xa</div>
            </div>
            
            <div class="education-item">
                <div class="edu-date">09/2016 - 06/2020</div>
                <div class="edu-degree">Công Nghệ Vật Liệu</div>
                <div class="edu-school">Đại học Khoa học tự nhiên</div>
                <div class="edu-desc">Tốt nghiệp loại Khá</div>
            </div>
            
            <div class="education-item">
                <div class="edu-date">2022</div>
                <div class="edu-degree">Chứng chỉ marketing của Meta</div>
                <div class="edu-school">Meta (Facebook)</div>
                <div class="edu-desc">Hoàn thành khóa học về digital marketing</div>
            </div>
        </section>
        
        <!-- Interests Section -->
        <section id="interests" class="container">
            <h2>Sở thích</h2>
            
            <div class="interests">
                <div class="interest-item">
                    <i class="fas fa-chart-line"></i>
                    <span>Học và nghiên cứu về data</span>
                </div>
                
                <div class="interest-item">
                    <i class="fas fa-podcast"></i>
                    <span>Nghe podcast</span>
                </div>
                
                <div class="interest-item">
                    <i class="fas fa-language"></i>
                    <span>Luy
