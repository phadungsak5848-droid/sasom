# sasom
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio Hub</title>
    <!-- นำเข้า Bootstrap และ Icon -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
    <style>
        /* ตกแต่งความสวยงามเพิ่มเติม */
        body { 
            background-color: #121212; 
            color: #ffffff; 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .profile-card { 
            background-color: #1e1e1e; 
            border-radius: 20px; 
            border: 1px solid #333; 
        }
        .link-btn { 
            border-radius: 12px; 
            transition: all 0.3s ease; 
            border-width: 2px;
        }
        .link-btn:hover { 
            transform: translateY(-4px); 
            box-shadow: 0 5px 15px rgba(0, 255, 200, 0.2); 
        }
    </style>
</head>
<body>
    <div class="container py-5">
        <div class="row justify-content-center">
            <div class="col-md-8 col-lg-6">
                
                <!-- ส่วนหัวโปรไฟล์ -->
                <div class="profile-card p-4 text-center mb-5 shadow-lg">
                    <!-- รูปโปรไฟล์แบบสุ่มตัวอักษร สามารถเปลี่ยนลิงก์รูปตัวเองได้ภ��[...]
                    <img src="https://ui-avatars.com/api/?name=My+Space&background=0D8ABC&color=fff&size=120" class="rounded-circle mb-3 border border-3 border-info" alt="Profile">
                    <h2 class="fw-bold mb-2">ยินดีต้อนรับสู่พื้นที่ของผม</h2>
                    <p class="text-info mb-2"><i class="bi bi-cpu"></i> Engineering Student @ SUT</p>
                    <p class="text-secondary small mb-0">Electronics | Automation | Programming</p>
                </div>

                <!-- ส่วนปุ่มเชื่อมโยง (Link Nodes) -->
                <h6 class="text-center text-uppercase text-secondary mb-3 fw-bold pb-2 border-bottom border-secondary">
                    <i class="bi bi-folder2-open"></i> แหล่งรวบรวมผลงาน
                </h6>
                
                <div class="d-grid gap-3">
                    
                    <!-- โหนดที่ 1: ไปไฟล์โค้ด -->
                    <a href="gemini-code-1790593387726.html" class="btn btn-outline-info btn-lg link-btn d-flex align-items-center justify-content-between px-4 py-3">
                        <span><i class="bi bi-code-slash me-2 text-info"></i> สคริปต์ & โค้ดโปรเจกต์</span>
                        <i class="bi bi-arrow-right"></i>
                    </a>
                    
                    <!-- โหนดที่ 2: ไปไฟล์บทความ -->
                    <a href="mindset_life.html" class="btn btn-outline-light btn-lg link-btn d-flex align-items-center justify-content-between px-4 py-3">
                        <span><i class="bi bi-journal-text me-2"></i> บันทึกบทความ (Mindset Life)</span>
                        <i class="bi bi-arrow-right"></i>
                    </a>

                    <!-- โหนดที่ 3: ปุ่มเตรียมไว้สำหรับอนาคต (ยังกดไม่ได้) -->
                    <a href="#" class="btn btn-outline-success btn-lg link-btn d-flex align-items-center justify-content-between px-4 py-3">
                        <span><i class="bi bi-lightning-charge me-2 text-success"></i> Lab Report & Circuit Design</span>
                        <i class="bi bi-lock text-secondary"></i>
                    </a>

                </div>
                
                <!-- ส่วนท้าย -->
                <div class="text-center mt-5 text-secondary small">
                    <p>© 2026 Powered by GitHub Pages</p>
                </div>

            </div>
        </div>
    </div>
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
