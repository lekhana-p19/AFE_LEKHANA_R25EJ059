<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ID Card - Lekhana P</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: #eef2f3;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .id-card {
            background: #ffffff;
            width: 350px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            position: relative;
            text-align: center;
            border: 1px solid rgba(0, 0, 0, 0.05);
        }

        /* Top decorative bar */
        .card-header {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            height: 100px;
            position: relative;
        }

        /* Avatar Placeholder */
        .avatar {
            width: 90px;
            height: 90px;
            background: #ffffff;
            border-radius: 50%;
            margin: -45px auto 0 auto;
            position: relative;
            z-index: 2;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
            display: flex;
            justify-content: center;
            align-items: center;
            border: 4px solid #ffffff;
        }

        .avatar-icon {
            font-size: 40px;
            color: #2a5298;
            font-weight: bold;
        }

        /* Content Area */
        .card-body {
            padding: 25px 20px;
        }

        .name {
            font-size: 24px;
            font-weight: 700;
            color: #2c3e50;
            letter-spacing: 0.5px;
            margin-bottom: 6px;
            text-transform: uppercase;
        }

        .id-number {
            font-size: 15px;
            font-weight: 600;
            color: #7f8c8d;
            background: #f4f6f7;
            display: inline-block;
            padding: 6px 16px;
            border-radius: 20px;
            letter-spacing: 1px;
            margin-bottom: 20px;
            border: 1px solid #e2e8f0;
        }

        .meta-info {
            display: flex;
            justify-content: space-around;
            border-top: 1px solid #f1f2f6;
            padding-top: 15px;
        }

        .info-block {
            text-align: center;
        }

        .info-label {
            font-size: 11px;
            text-transform: uppercase;
            color: #bdc3c7;
            letter-spacing: 0.8px;
            margin-bottom: 4px;
        }

        .info-value {
            font-size: 14px;
            font-weight: 600;
            color: #34495e;
        }
    </style>
</head>
<body>

    <div class="id-card">
        <div class="card-header"></div>
        
        <div class="avatar">
            <!-- Uses the first letter as a clean initials logo -->
            <div class="avatar-icon">L</div>
        </div>

        <div class="card-body">
            <div class="name">Lekhana P</div>
            <div class="id-number">R25EJ059</div>
            
            <div class="meta-info">
                <div class="info-block">
                    <div class="info-label">Role</div>
                    <div class="info-value">Developer</div>
                </div>
                <div class="info-block">
                    <div class="info-label">Status</div>
                    <div class="info-value" style="color: #2ed573;">Active</div>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
