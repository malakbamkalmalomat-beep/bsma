<!doctype html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>نظام معالجة بصمات الموظفين بنظام 24 ساعة مع تصفية الأوقات</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --primary: #0d47a1;
    --secondary: #1976d2;
    --success: #388e3c;
    --warning: #f57c00;
    --danger: #d32f2f;
    --light: #f5f5f5;
    --dark: #1a237e;
    --purple: #7b1fa2;
    --cyan: #0097a7;
    --orange: #ff9800;
    --teal: #00796b;
    --indigo: #303f9f;
  }
  
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
  body {
    font-family: 'Cairo', 'Segoe UI', Tahoma, Arial, sans-serif;
    background: linear-gradient(135deg, #1a237e 0%, #0d47a1 100%);
    color: #333;
    line-height: 1.6;
    padding: 15px;
    min-height: 100vh;
  }
  
  .container {
    max-width: 1800px;
    margin: 0 auto;
    background: white;
    border-radius: 20px;
    padding: 25px;
    box-shadow: 0 20px 50px rgba(0, 0, 0, 0.3);
  }
  
  .header {
    text-align: center;
    margin-bottom: 35px;
    padding: 30px;
    background: linear-gradient(135deg, var(--dark) 0%, var(--primary) 100%);
    border-radius: 18px;
    color: white;
    box-shadow: 0 15px 35px rgba(0,0,0,0.2);
    position: relative;
    overflow: hidden;
  }
  
  .header::before {
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(45deg, transparent 30%, rgba(255,255,255,0.1) 50%, transparent 70%);
    animation: shine 3s infinite linear;
  }
  
  @keyframes shine {
    0% { transform: translateX(100%); }
    100% { transform: translateX(-100%); }
  }
  
  .header h1 {
    font-size: 36px;
    margin-bottom: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 20px;
    position: relative;
    z-index: 1;
  }
  
  .header h1 i {
    color: var(--cyan);
    animation: pulse 2s infinite;
  }
  
  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.1); }
    100% { transform: scale(1); }
  }
  
  .subtitle {
    font-size: 18px;
    max-width: 1000px;
    margin: 0 auto;
    opacity: 0.95;
    position: relative;
    z-index: 1;
  }
  
  .card {
    background: white;
    border-radius: 18px;
    padding: 30px;
    margin-bottom: 30px;
    box-shadow: 0 8px 25px rgba(0,0,0,0.1);
    transition: all 0.4s ease;
    border: 1px solid #e0e0e0;
    position: relative;
    overflow: hidden;
  }
  
  .card::before {
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    width: 8px;
    height: 100%;
    background: linear-gradient(to bottom, var(--primary), var(--cyan));
  }
  
  .card:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 35px rgba(0,0,0,0.15);
  }
  
  .card-title {
    font-size: 26px;
    color: var(--primary);
    margin-bottom: 25px;
    padding-bottom: 15px;
    border-bottom: 3px solid var(--light);
    display: flex;
    align-items: center;
    gap: 15px;
  }
  
  .upload-area {
    border: 4px dashed #bdbdbd;
    border-radius: 15px;
    padding: 50px 30px;
    text-align: center;
    background: linear-gradient(135deg, #f5f5f5 0%, #eeeeee 100%);
    cursor: pointer;
    transition: all 0.4s;
    margin-bottom: 25px;
    position: relative;
    overflow: hidden;
  }
  
  .upload-area:hover, .upload-area.dragover {
    border-color: var(--secondary);
    background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
    transform: scale(1.01);
  }
  
  .upload-area i {
    font-size: 70px;
    color: var(--primary);
    margin-bottom: 20px;
    transition: all 0.4s;
  }
  
  .upload-area:hover i {
    transform: translateY(-5px) rotate(10deg);
  }
  
  .upload-text {
    font-size: 22px;
    color: #424242;
    margin-bottom: 15px;
    font-weight: 600;
  }
  
  .upload-note {
    font-size: 16px;
    color: #616161;
    max-width: 1000px;
    margin: 20px auto 0;
    background: linear-gradient(135deg, #fff3e0 0%, #ffecb3 100%);
    padding: 20px;
    border-radius: 12px;
    border-right: 6px solid var(--warning);
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
  }
  
  .controls {
    display: flex;
    flex-wrap: wrap;
    gap: 25px;
    align-items: center;
    margin-top: 25px;
  }
  
  .control-group {
    display: flex;
    flex-direction: column;
    gap: 12px;
    flex: 1;
    min-width: 250px;
  }
  
  .control-label {
    font-weight: bold;
    color: #424242;
    font-size: 16px;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  
  .btn {
    padding: 15px 30px;
    border-radius: 12px;
    border: none;
    font-weight: bold;
    cursor: pointer;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
    transition: all 0.3s;
    font-size: 17px;
    box-shadow: 0 6px 12px rgba(50, 50, 93, 0.15);
    position: relative;
    overflow: hidden;
  }
  
  .btn::after {
    content: '';
    position: absolute;
    top: 50%;
    right: 50%;
    width: 5px;
    height: 5px;
    background: rgba(255, 255, 255, 0.5);
    opacity: 0;
    border-radius: 100%;
    transform: scale(1, 1) translate(-50%);
    transform-origin: 50% 50%;
  }
  
  .btn:active::after {
    animation: ripple 0.6s ease-out;
  }
  
  @keyframes ripple {
    0% {
      transform: scale(0, 0);
      opacity: 1;
    }
    100% {
      transform: scale(40, 40);
      opacity: 0;
    }
  }
  
  .btn-primary {
    background: linear-gradient(135deg, var(--primary) 0%, #1565c0 100%);
    color: white;
  }
  
  .btn-primary:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 25px rgba(50, 50, 93, 0.2);
  }
  
  .btn-success {
    background: linear-gradient(135deg, var(--success) 0%, #2e7d32 100%);
    color: white;
  }
  
  .btn-success:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 25px rgba(50, 50, 93, 0.2);
  }
  
  .btn-warning {
    background: linear-gradient(135deg, var(--warning) 0%, #ef6c00 100%);
    color: white;
  }
  
  .btn-warning:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 25px rgba(50, 50, 93, 0.2);
  }
  
  .btn-danger {
    background: linear-gradient(135deg, var(--danger) 0%, #c62828 100%);
    color: white;
  }
  
  .btn-danger:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 25px rgba(50, 50, 93, 0.2);
  }
  
  .btn-secondary {
    background: linear-gradient(135deg, #546e7a 0%, #37474f 100%);
    color: white;
  }
  
  .btn-purple {
    background: linear-gradient(135deg, var(--purple) 0%, #6a1b9a 100%);
    color: white;
  }
  
  .btn-purple:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 25px rgba(50, 50, 93, 0.2);
  }
  
  .btn-teal {
    background: linear-gradient(135deg, var(--teal) 0%, #00695c 100%);
    color: white;
  }
  
  .btn-teal:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 25px rgba(50, 50, 93, 0.2);
  }
  
  .btn-orange {
    background: linear-gradient(135deg, var(--orange) 0%, #f57c00 100%);
    color: white;
  }
  
  .btn-orange:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 25px rgba(50, 50, 93, 0.2);
  }
  
  .btn-indigo {
    background: linear-gradient(135deg, var(--indigo) 0%, #283593 100%);
    color: white;
  }
  
  .btn-indigo:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 25px rgba(50, 50,93, 0.2);
  }
  
  .btn:disabled {
    background: #bdbdbd;
    cursor: not-allowed;
    transform: none;
    box-shadow: none;
  }
  
  .select-box, .input-box, textarea {
    padding: 15px 20px;
    border-radius: 10px;
    border: 2px solid #e0e0e0;
    font-size: 17px;
    background: white;
    transition: all 0.3s;
    font-family: 'Cairo', sans-serif;
    box-shadow: 0 3px 10px rgba(0,0,0,0.05);
  }
  
  textarea {
    resize: vertical;
    min-height: 120px;
  }
  
  .select-box:focus, .input-box:focus, textarea:focus {
    outline: none;
    border-color: var(--secondary);
    box-shadow: 0 0 0 4px rgba(25, 118, 210, 0.15);
  }
  
  .checkbox-label, .radio-label {
    display: flex;
    align-items: center;
    gap: 12px;
    cursor: pointer;
    padding: 15px;
    background: #f5f5f5;
    border-radius: 10px;
    transition: all 0.3s;
    border: 2px solid transparent;
  }
  
  .checkbox-label:hover, .radio-label:hover {
    background: #e3f2fd;
    border-color: var(--secondary);
  }
  
  .checkbox-label input, .radio-label input {
    width: 22px;
    height: 22px;
    cursor: pointer;
  }
  
  .stats {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-bottom: 30px;
  }
  
  .stat-card {
    background: white;
    border-radius: 15px;
    padding: 25px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.08);
    border-top: 6px solid;
    transition: all 0.4s;
    position: relative;
    overflow: hidden;
  }
  
  .stat-card::before {
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    width: 100%;
    height: 5px;
    background: linear-gradient(to left, transparent, rgba(255,255,255,0.5), transparent);
    animation: shimmer 2s infinite;
  }
  
  @keyframes shimmer {
    0% { transform: translateX(-100%); }
    100% { transform: translateX(100%); }
  }
  
  .stat-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 35px rgba(0,0,0,0.12);
  }
  
  .stat-card.total { border-color: var(--primary); }
  .stat-card.present { border-color: var(--success); }
  .stat-card.late { border-color: var(--warning); }
  .stat-card.absent { border-color: var(--danger); }
  .stat-card.check { border-color: var(--purple); }
  .stat-card.message { border-color: var(--cyan); }
  .stat-card.single { border-color: var(--orange); }
  .stat-card.filtered { border-color: var(--indigo); }
  
  .stat-value {
    font-size: 42px;
    font-weight: bold;
    margin: 15px 0;
  }
  
  .total .stat-value { color: var(--primary); }
  .present .stat-value { color: var(--success); }
  .late .stat-value { color: var(--warning); }
  .absent .stat-value { color: var(--danger); }
  .check .stat-value { color: var(--purple); }
  .message .stat-value { color: var(--cyan); }
  .single .stat-value { color: var(--orange); }
  .filtered .stat-value { color: var(--indigo); }
  
  .stat-label {
    font-size: 18px;
    color: #616161;
    font-weight: 600;
  }
  
  .stat-icon {
    font-size: 40px;
    margin-bottom: 15px;
  }
  
  .table-container {
    overflow-x: auto;
    margin-top: 25px;
    border-radius: 12px;
    box-shadow: 0 8px 25px rgba(0,0,0,0.08);
    border: 1px solid #e0e0e0;
  }
  
  table {
    width: 100%;
    border-collapse: collapse;
    min-width: 1600px;
  }
  
  th {
    background: linear-gradient(135deg, var(--primary) 0%, #1565c0 100%);
    color: white;
    padding: 20px;
    text-align: center;
    font-weight: 700;
    font-size: 17px;
    position: sticky;
    top: 0;
    white-space: nowrap;
    border-bottom: 3px solid var(--light);
  }
  
  td {
    padding: 18px 20px;
    border-bottom: 1px solid #eee;
    text-align: center;
    font-size: 16px;
    transition: all 0.2s;
  }
  
  tr:hover td {
    background-color: #f9f9f9;
  }
  
  .status-badge {
    display: inline-block;
    padding: 8px 20px;
    border-radius: 25px;
    font-weight: bold;
    font-size: 15px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: all 0.3s;
  }
  
  .status-badge:hover {
    transform: scale(1.05);
  }
  
  .status-present { background: #e8f5e9; color: var(--success); border: 2px solid #c8e6c9; }
  .status-late { background: #fff3e0; color: var(--warning); border: 2px solid #ffe0b2; }
  .status-absent { background: #ffebee; color: var(--danger); border: 2px solid #ffcdd2; }
  .status-check { background: #f3e5f5; color: var(--purple); border: 2px solid #e1bee7; }
  .status-single { background: #fff8e1; color: var(--orange); border: 2px solid #ffecb3; }
  
  .whatsapp-modal {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.85);
    display: none;
    justify-content: center;
    align-items: center;
    z-index: 2000;
    animation: fadeIn 0.3s ease;
  }
  
  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }
  
  .modal-content {
    background: white;
    border-radius: 20px;
    width: 90%;
    max-width: 800px;
    padding: 35px;
    box-shadow: 0 25px 75px rgba(0,0,0,0.4);
    animation: modalSlideIn 0.4s ease;
  }
  
  @keyframes modalSlideIn {
    from {
      opacity: 0;
      transform: translateY(-60px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  
  .modal-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 25px;
    padding-bottom: 20px;
    border-bottom: 2px solid #f0f0f0;
  }
  
  .close-modal {
    background: none;
    border: none;
    font-size: 30px;
    cursor: pointer;
    color: #757575;
    transition: all 0.3s;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .close-modal:hover {
    background: #f5f5f5;
    color: var(--danger);
    transform: rotate(90deg);
  }
  
  .message-preview {
    background: linear-gradient(135deg, #f9f9f9 0%, #f0f0f0 100%);
    border-radius: 12px;
    padding: 25px;
    margin: 25px 0;
    border-right: 6px solid var(--success);
  }
  
  .progress-bar {
    width: 100%;
    height: 12px;
    background: #e0e0e0;
    border-radius: 6px;
    margin: 25px 0;
    overflow: hidden;
    box-shadow: inset 0 2px 5px rgba(0,0,0,0.1);
  }
  
  .progress-fill {
    height: 100%;
    background: linear-gradient(90deg, var(--success) 0%, #4caf50 100%);
    width: 0%;
    transition: width 0.5s;
    border-radius: 6px;
  }
  
  .alert {
    padding: 20px;
    border-radius: 12px;
    margin: 20px 0;
    display: flex;
    align-items: center;
    gap: 20px;
    animation: slideIn 0.4s ease;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
  }
  
  @keyframes slideIn {
    from {
      opacity: 0;
      transform: translateX(-30px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }
  
  .alert-success {
    background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%);
    color: var(--success);
    border-right: 6px solid var(--success);
  }
  
  .alert-warning {
    background: linear-gradient(135deg, #fff3e0 0%, #ffe0b2 100%);
    color: var(--warning);
    border-right: 6px solid var(--warning);
  }
  
  .alert-info {
    background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
    color: var(--secondary);
    border-right: 6px solid var(--secondary);
  }
  
  .alert-danger {
    background: linear-gradient(135deg, #ffebee 0%, #ffcdd2 100%);
    color: var(--danger);
    border-right: 6px solid var(--danger);
  }
  
  .alert-purple {
    background: linear-gradient(135deg, #f3e5f5 0%, #e1bee7 100%);
    color: var(--purple);
    border-right: 6px solid var(--purple);
  }
  
  .footer {
    text-align: center;
    margin-top: 50px;
    padding: 25px;
    color: #616161;
    font-size: 16px;
    border-top: 2px solid #f0f0f0;
    background: linear-gradient(135deg, #fafafa 0%, #f5f5f5 100%);
    border-radius: 15px;
  }
  
  .time-settings-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    margin: 25px 0;
    padding: 30px;
    background: linear-gradient(135deg, #f5f5f5 0%, #eeeeee 100%);
    border-radius: 15px;
  }
  
  .employee-info {
    background: #f9f9f9;
    border-radius: 10px;
    padding: 15px;
    margin: 12px 0;
    border-right: 4px solid var(--secondary);
  }
  
  .file-info-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }
  
  .file-info-item {
    background: white;
    padding: 20px;
    border-radius: 10px;
    border: 2px solid #e0e0e0;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    transition: all 0.3s;
  }
  
  .file-info-item:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.1);
  }
  
  .file-info-label {
    font-size: 14px;
    color: #757575;
    margin-bottom: 10px;
    font-weight: 600;
  }
  
  .file-info-value {
    font-weight: bold;
    color: var(--primary);
    font-size: 18px;
  }
  
  .tabs {
    display: flex;
    background: white;
    border-radius: 15px;
    margin-bottom: 30px;
    box-shadow: 0 5px 20px rgba(0,0,0,0.08);
    overflow: hidden;
  }
  
  .tab {
    padding: 20px 40px;
    cursor: pointer;
    font-weight: 700;
    font-size: 18px;
    transition: all 0.3s;
    border-bottom: 4px solid transparent;
    display: flex;
    align-items: center;
    gap: 12px;
  }
  
  .tab:hover {
    background: #f5f5f5;
    color: var(--primary);
  }
  
  .tab.active {
    background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
    color: var(--primary);
    border-bottom: 4px solid var(--primary);
  }
  
  .tab-content {
    display: none;
  }
  
  .tab-content.active {
    display: block;
  }
  
  .phone-validation {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-top: 10px;
  }
  
  .phone-status {
    padding: 6px 15px;
    border-radius: 20px;
    font-size: 13px;
    font-weight: bold;
    box-shadow: 0 3px 8px rgba(0,0,0,0.1);
  }
  
  .phone-valid {
    background: #e8f5e9;
    color: var(--success);
    border: 2px solid #c8e6c9;
  }
  
  .phone-invalid {
    background: #ffebee;
    color: var(--danger);
    border: 2px solid #ffcdd2;
  }
  
  .employee-badge {
    display: inline-block;
    padding: 5px 15px;
    background: var(--primary);
    color: white;
    border-radius: 20px;
    font-size: 14px;
    font-weight: bold;
    margin-right: 10px;
  }
  
  .fingerprint-icon {
    color: var(--primary);
    animation: fingerprint 2s infinite alternate;
  }
  
  @keyframes fingerprint {
    0% { transform: scale(1); }
    100% { transform: scale(1.1); }
  }
  
  .time-info {
    background: linear-gradient(135deg, #f5f5f5 0%, #eeeeee 100%);
    border-radius: 10px;
    padding: 20px;
    margin: 20px 0;
    border-right: 5px solid var(--cyan);
  }
  
  .time-slots {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 15px;
    margin-top: 15px;
  }
  
  .time-slot {
    background: white;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.08);
    border: 2px solid #e0e0e0;
    transition: all 0.3s;
  }
  
  .time-slot:hover {
    transform: translateY(-3px);
    border-color: var(--secondary);
  }
  
  .time-slot-label {
    font-size: 14px;
    color: #757575;
    margin-bottom: 8px;
  }
  
  .time-slot-value {
    font-weight: bold;
    color: var(--primary);
    font-size: 18px;
  }
  
  .clock-icon {
    color: var(--cyan);
    animation: clock 2s infinite linear;
  }
  
  @keyframes clock {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }
  
  .attendance-rules {
    background: linear-gradient(135deg, #fff3e0 0%, #ffecb3 100%);
    border-radius: 12px;
    padding: 25px;
    margin: 25px 0;
    border-right: 6px solid var(--warning);
  }
  
  .rule-item {
    display: flex;
    align-items: center;
    gap: 15px;
    margin-bottom: 15px;
    padding: 15px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.05);
  }
  
  .rule-icon {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 20px;
    color: white;
  }
  
  .rule-present { background: var(--success); }
  .rule-late { background: var(--warning); }
  .rule-absent { background: var(--danger); }
  .rule-single { background: var(--orange); }
  .rule-filtered { background: var(--indigo); }
  
  .rule-text {
    flex: 1;
  }
  
  .date-filter {
    background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
    border-radius: 12px;
    padding: 25px;
    margin: 25px 0;
    border-right: 5px solid var(--indigo);
  }
  
  .date-range {
    display: flex;
    gap: 20px;
    align-items: center;
    flex-wrap: wrap;
  }
  
  .date-input-group {
    flex: 1;
    min-width: 200px;
  }
  
  .month-navigation {
    display: flex;
    align-items: center;
    gap: 15px;
    justify-content: center;
    margin-top: 20px;
  }
  
  .month-btn {
    background: var(--primary);
    color: white;
    border: none;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
    transition: all 0.3s;
  }
  
  .month-btn:hover {
    background: var(--secondary);
    transform: scale(1.1);
  }
  
  .current-month {
    font-weight: bold;
    color: var(--primary);
    font-size: 18px;
  }
  
  .date-summary {
    background: linear-gradient(135deg, #f5f5f5 0%, #eeeeee 100%);
    border-radius: 10px;
    padding: 20px;
    margin: 20px 0;
    border-right: 5px solid var(--purple);
  }
  
  .summary-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    margin-top: 15px;
  }
  
  .summary-item {
    background: white;
    padding: 15px;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 3px 10px rgba(0,0,0,0.08);
  }
  
  .summary-label {
    font-size: 14px;
    color: #757575;
    margin-bottom: 8px;
  }
  
  .summary-value {
    font-weight: bold;
    color: var(--primary);
    font-size: 18px;
  }
  
  /* حقوق الملكية */
  .copyright {
    text-align: center;
    font-size: 14px;
    color: #666;
    margin: 15px 0;
    padding: 10px;
    border-top: 1px solid #eee;
  }
  
  .copyright-name {
    color: var(--primary);
    font-weight: bold;
    font-size: 16px;
  }
  
  /* Print Styles */
  @media print {
    body * {
      visibility: hidden;
    }
    
    .print-section, .print-section * {
      visibility: visible;
    }
    
    .print-section {
      position: absolute;
      left: 0;
      top: 0;
      width: 100%;
      padding: 10px;
      font-family: 'Cairo', sans-serif;
    }
    
    .print-header {
      text-align: center;
      margin-bottom: 20px;
      padding-bottom: 15px;
      border-bottom: 3px solid #000;
    }
    
    .print-title {
      font-size: 28px;
      color: #000;
      margin-bottom: 10px;
    }
    
    .print-subtitle {
      font-size: 16px;
      color: #666;
      margin-bottom: 15px;
    }
    
    .print-date {
      font-size: 14px;
      color: #333;
      margin-bottom: 10px;
    }
    
    .print-table {
      width: 100%;
      border-collapse: collapse;
      margin: 15px 0;
      font-size: 12px;
    }
    
    .print-table th {
      background-color: #f0f0f0;
      border: 1px solid #000;
      padding: 8px;
      text-align: center;
      font-weight: bold;
    }
    
    .print-table td {
      border: 1px solid #000;
      padding: 6px;
      text-align: center;
    }
    
    .print-status {
      padding: 4px 8px;
      border-radius: 4px;
      font-weight: bold;
      font-size: 11px;
    }
    
    .status-present-print { background-color: #e8f5e9; color: #2e7d32; }
    .status-late-print { background-color: #fff3e0; color: #ef6c00; }
    .status-absent-print { background-color: #ffebee; color: #c62828; }
    .status-single-print { background-color: #fff8e1; color: #ff9800; }
    
    .print-copyright {
      text-align: center;
      font-size: 10px;
      color: #666;
      margin-top: 20px;
      padding-top: 10px;
      border-top: 1px solid #ccc;
    }
    
    .page-break {
      page-break-after: always;
    }
    
    .no-print {
      display: none !important;
    }
    
    @page {
      size: landscape;
      margin: 0.5cm;
    }
  }
  
  @media (max-width: 1200px) {
    .container {
      padding: 20px;
    }
    
    .header {
      padding: 25px;
    }
    
    .header h1 {
      font-size: 32px;
    }
    
    .tab {
      padding: 15px 25px;
    }
  }
  
  @media (max-width: 768px) {
    body {
      padding: 10px;
    }
    
    .header h1 {
      font-size: 28px;
      flex-direction: column;
      gap: 10px;
    }
    
    .controls {
      flex-direction: column;
      align-items: stretch;
    }
    
    .control-group {
      width: 100%;
    }
    
    .select-box, .input-box, textarea {
      width: 100%;
    }
    
    .stats {
      grid-template-columns: repeat(2, 1fr);
    }
    
    table {
      min-width: 1400px;
    }
    
    .tabs {
      flex-wrap: wrap;
    }
    
    .tab {
      flex: 1;
      text-align: center;
      padding: 15px;
      font-size: 16px;
    }
    
    .btn {
      width: 100%;
      justify-content: center;
    }
    
    .modal-content {
      width: 95%;
      padding: 25px;
    }
    
    .time-settings-grid {
      grid-template-columns: 1fr;
    }
    
    .date-range {
      flex-direction: column;
    }
  }
  
  @media (max-width: 480px) {
    .stats {
      grid-template-columns: 1fr;
    }
    
    .header {
      padding: 20px;
    }
    
    .header h1 {
      font-size: 24px;
    }
    
    .subtitle {
      font-size: 16px;
    }
    
    .card {
      padding: 20px;
    }
    
    .stat-card {
      padding: 20px;
    }
    
    .stat-value {
      font-size: 36px;
    }
  }
</style>
</head>
<body>
<div class="container">
  <!-- Header -->
  <div class="header">
    <h1><i class="fas fa-fingerprint fingerprint-icon"></i> نظام معالجة البصمات بنظام 24 ساعة</h1>
    <p class="subtitle">رفع ملف Excel يحتوي على بصمات الموظفين، وسيقوم النظام بحساب التأخير والغياب بناءً على نظام 24 ساعة مع تصفية الأوقات غير المسموح بها</p>
    <div class="copyright" style="color: white; opacity: 0.8; margin-top: 15px;">
      <i class="fas fa-copyright"></i> حقوق الملكية 2025 - <span class="copyright-name">Zaid Mazin</span>
    </div>
  </div>
  
  <!-- Tabs -->
  <div class="tabs">
    <div class="tab active" data-tab="upload">
      <i class="fas fa-upload"></i> رفع البيانات
    </div>
    <div class="tab" data-tab="timesettings">
      <i class="fas fa-clock clock-icon"></i> إعدادات الأوقات
    </div>
    <div class="tab" data-tab="report">
      <i class="fas fa-chart-bar"></i> التقرير
    </div>
    <div class="tab" data-tab="messages">
      <i class="fas fa-comments"></i> الرسائل
    </div>
  </div>
  
  <!-- Upload Tab -->
  <div class="tab-content active" id="uploadTab">
    <div class="card">
      <h2 class="card-title"><i class="fas fa-file-upload"></i> رفع ملف بصمات الموظفين</h2>
      
      <div class="upload-area" id="dropArea">
        <i class="fas fa-file-excel"></i>
        <div class="upload-text">اسحب ملف بصمات الموظفين (Excel) وأفلته هنا أو انقر للاختيار</div>
        <div class="upload-note">
          <strong>ملاحظة هامة:</strong> يجب أن يحتوي الملف على الأعمدة التالية (يمكن أن تكون في أي ترتيب):<br>
          1. اسم الموظف 2. رقم البصمة/الهوية 3. تاريخ البصمة 4. وقت البصمة (نظام 24 ساعة)<br>
          <strong>يمكن أن يكون التاريخ والوقت في نفس العمود (مثال: 2024-01-01 08:00)</strong>
        </div>
        <input type="file" id="fileInput" accept=".xlsx,.xls,.csv" hidden>
        <div style="margin-top: 30px;">
          <button class="btn btn-primary" id="browseBtn"><i class="fas fa-folder-open"></i> اختر ملف البصمات</button>
          <button class="btn btn-teal" id="downloadTemplate" style="margin-right: 15px;">
            <i class="fas fa-download"></i> تحميل نموذج Excel
          </button>
        </div>
      </div>
      
      <!-- File Info -->
      <div id="fileInfo" style="display: none; margin-top: 25px;">
        <div style="display: flex; align-items: center; justify-content: space-between; margin-bottom: 20px; padding: 20px; background: linear-gradient(135deg, #f5f5f5 0%, #eeeeee 100%); border-radius: 15px;">
          <div style="display: flex; align-items: center; gap: 20px;">
            <i class="fas fa-file-excel" style="font-size: 50px; color: #1d6f42;"></i>
            <div>
              <div id="fileName" style="font-weight: bold; font-size: 22px; color: var(--primary);"></div>
              <div id="fileSize" style="color: #757575; font-size: 16px;"></div>
            </div>
          </div>
          <button class="btn btn-danger" id="removeFile"><i class="fas fa-times"></i> إزالة الملف</button>
        </div>
        
        <div id="fileDetails" style="display: none;">
          <div class="file-info-grid">
            <div class="file-info-item">
              <div class="file-info-label">عدد السجلات</div>
              <div class="file-info-value" id="fileRecords">0</div>
            </div>
            <div class="file-info-item">
              <div class="file-info-label">عدد الموظفين</div>
              <div class="file-info-value" id="fileEmployees">0</div>
            </div>
            <div class="file-info-item">
              <div class="file-info-label">عدد الأيام</div>
              <div class="file-info-value" id="fileDays">0</div>
            </div>
            <div class="file-info-item">
              <div class="file-info-label">حالة الملف</div>
              <div class="file-info-value" id="fileStatus" style="color: var(--success);">جاهز للمعالجة</div>
            </div>
          </div>
          
          <div id="dateRangeInfo" style="display: none; margin-top: 25px; padding: 20px; background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%); border-radius: 12px; border-right: 5px solid var(--indigo);">
            <h3 style="margin-bottom: 15px; color: var(--indigo);"><i class="fas fa-calendar-alt"></i> نطاق التواريخ في الملف</h3>
            <div style="display: flex; gap: 30px; flex-wrap: wrap;">
              <div>
                <div style="font-weight: bold; color: #555; margin-bottom: 5px;">من تاريخ</div>
                <div style="font-size: 18px; color: var(--primary); font-weight: bold;" id="fileDateFrom">--/--/----</div>
              </div>
              <div>
                <div style="font-weight: bold; color: #555; margin-bottom: 5px;">إلى تاريخ</div>
                <div style="font-size: 18px; color: var(--primary); font-weight: bold;" id="fileDateTo">--/--/----</div>
              </div>
            </div>
          </div>
        </div>
      </div>
      
      <!-- Process Button -->
      <div style="text-align: center; margin-top: 35px;">
        <button class="btn btn-primary" id="processBtn" style="padding: 18px 60px; font-size: 20px;" disabled>
          <i class="fas fa-cogs"></i> معالجة البصمات وإنشاء التقرير
        </button>
      </div>
    </div>
  </div>
  
  <!-- Time Settings Tab -->
  <div class="tab-content" id="timesettingsTab">
    <div class="card">
      <h2 class="card-title"><i class="fas fa-clock clock-icon"></i> إعدادات نظام 24 ساعة للبصمات</h2>
      
      <div class="attendance-rules">
        <h3 style="margin-bottom: 20px; color: var(--warning);"><i class="fas fa-exclamation-triangle"></i> قواعد احتساب الحضور والغياب (الإصدار المحدث)</h3>
        <div class="rule-item">
          <div class="rule-icon rule-present"><i class="fas fa-check"></i></div>
          <div class="rule-text">حضور طبيعي: أول دخول في وقت الحضور + آخر خروج في وقت الخروج المسائي</div>
        </div>
        <div class="rule-item">
          <div class="rule-icon rule-late"><i class="fas fa-clock"></i></div>
          <div class="rule-text">تأخير صباحي: أول دخول بعد وقت التأخير مع وجود أكثر من بصمة في اليوم (لديه بصمة خروج)</div>
        </div>
        <div class="rule-item">
          <div class="rule-icon rule-single"><i class="fas fa-fingerprint"></i></div>
          <div class="rule-text">بصمة واحدة: موظف لديه بصمة واحدة فقط في اليوم (سواء كانت قبل أو بعد وقت التأخير)</div>
        </div>
        <div class="rule-item">
          <div class="rule-icon rule-absent"><i class="fas fa-times"></i></div>
          <div class="rule-text">غياب كامل: عدم وجود أي بصمة للموظف في اليوم</div>
        </div>
        <div class="rule-item">
          <div class="rule-icon rule-filtered"><i class="fas fa-filter"></i></div>
          <div class="rule-text"><strong>الإضافة الجديدة:</strong> البصمات خارج الأوقات المحددة سيتم تجاهلها ولن تحتسب في التقرير</div>
        </div>
      </div>
      
      <div class="time-settings-grid">
        <div class="control-group">
          <label class="control-label"><i class="fas fa-sun"></i> وقت بداية الدخول الصباحي:</label>
          <input type="time" class="input-box" id="morningStart" value="08:00">
          <small style="color: #757575; margin-top: 8px;">بداية وقت الحضور الطبيعي (24 ساعة)</small>
        </div>
        
        <div class="control-group">
          <label class="control-label"><i class="fas fa-stopwatch"></i> بداية وقت التأخير:</label>
          <input type="time" class="input-box" id="lateStart" value="08:15">
          <small style="color: #757575; margin-top: 8px;">بداية احتساب التأخير للدخول الصباحي</small>
        </div>
        
        <div class="control-group">
          <label class="control-label"><i class="fas fa-ban"></i> نهاية وقت الدخول الصباحي:</label>
          <input type="time" class="input-box" id="morningEnd" value="09:00">
          <small style="color: #757575; margin-top: 8px;">آخر وقت لقبول بصمة الدخول الصباحي</small>
        </div>
        
        <div class="control-group">
          <label class="control-label"><i class="fas fa-door-open"></i> بداية وقت الخروج المسائي:</label>
          <input type="time" class="input-box" id="eveningStart" value="16:00">
          <small style="color: #757575; margin-top: 8px;">بداية وقت الخروج المسائي الطبيعي</small>
        </div>
        
        <div class="control-group">
          <label class="control-label"><i class="fas fa-door-closed"></i> نهاية وقت الخروج المسائي:</label>
          <input type="time" class="input-box" id="eveningEnd" value="17:00">
          <small style="color: #757575; margin-top: 8px;">آخر وقت لقبول بصمة الخروج المسائي</small>
        </div>
      </div>
      
      <div class="time-info">
        <h3 style="margin-bottom: 15px; color: var(--cyan);"><i class="fas fa-info-circle"></i> ملاحظات هامة (الإصدار المحدث):</h3>
        <ul style="padding-right: 20px; line-height: 1.8;">
          <li>النظام يعمل بنظام 24 ساعة (00:00 إلى 23:59)</li>
          <li>يتم أخذ أول بصمة في اليوم كوقت دخول وأخر بصمة كوقت خروج <strong>فقط إذا كانت داخل الأوقات المسموح بها</strong></li>
          <li><strong>التعديل الجديد:</strong> البصمات خارج الأوقات المحددة (مثل 10:00 صباحًا أو 14:00 ظهرًا) سيتم تجاهلها تمامًا</li>
          <li><strong>التعديل الجديد:</strong> إذا كان للموظف بصمة واحدة فقط في اليوم (سواء كانت قبل أو بعد وقت التأخير): تعتبر "بصمة واحدة"</li>
          <li><strong>التعديل الجديد:</strong> إذا كان للموظف أكثر من بصمة وأول دخول بعد وقت التأخير: تعتبر "تأخير صباحي" (لأن لديه بصمة خروج)</li>
          <li>إلغاء نظام الحضور المبكر - الحضور قبل الموعد يعتبر حضور طبيعي</li>
          <li>يتم حساب عدد الساعات بين أول دخول وآخر خروج من البصمات الصحيحة فقط</li>
          <li>إذا كان هناك بصمتين صباحيتين في نفس الوقت بالضبط، يتم أخذ بصمة واحدة فقط</li>
          <li><strong>الهدف من التعديل:</strong> الموظف الذي يصمم خارج أوقات الدوام لن تحتسب بصمته في التقرير النهائي</li>
        </ul>
      </div>
    </div>
  </div>
  
  <!-- Report Tab -->
  <div class="tab-content" id="reportTab">
    <!-- Stats Card -->
    <div class="card" id="statsCard" style="display: none;">
      <h2 class="card-title"><i class="fas fa-chart-pie"></i> إحصائيات التقرير التفصيلي</h2>
      <div class="stats">
        <div class="stat-card total">
          <div class="stat-icon"><i class="fas fa-users"></i></div>
          <div class="stat-label">إجمالي السجلات</div>
          <div class="stat-value" id="totalRecords">0</div>
        </div>
        <div class="stat-card present">
          <div class="stat-icon"><i class="fas fa-check-circle"></i></div>
          <div class="stat-label">حاضرين طبيعي</div>
          <div class="stat-value" id="presentCount">0</div>
        </div>
        <div class="stat-card late">
          <div class="stat-icon"><i class="fas fa-clock"></i></div>
          <div class="stat-label">تأخير صباحي</div>
          <div class="stat-value" id="lateCount">0</div>
        </div>
        <div class="stat-card absent">
          <div class="stat-icon"><i class="fas fa-times-circle"></i></div>
          <div class="stat-label">غياب كامل</div>
          <div class="stat-value" id="absentCount">0</div>
        </div>
        <div class="stat-card single">
          <div class="stat-icon"><i class="fas fa-fingerprint"></i></div>
          <div class="stat-label">بصمة واحدة</div>
          <div class="stat-value" id="singleCount">0</div>
        </div>
        <div class="stat-card filtered">
          <div class="stat-icon"><i class="fas fa-filter"></i></div>
          <div class="stat-label">بصمات مُهملة</div>
          <div class="stat-value" id="filteredCount">0</div>
        </div>
      </div>
    </div>
    
    <!-- Date Filter Card -->
    <div class="card" id="dateFilterCard" style="display: none;">
      <h2 class="card-title"><i class="fas fa-filter"></i> تصفية حسب التاريخ</h2>
      
      <div class="date-filter">
        <div class="date-range">
          <div class="date-input-group">
            <label class="control-label"><i class="fas fa-calendar-plus"></i> من تاريخ:</label>
            <input type="date" class="input-box" id="dateFrom">
          </div>
          
          <div class="date-input-group">
            <label class="control-label"><i class="fas fa-calendar-minus"></i> إلى تاريخ:</label>
            <input type="date" class="input-box" id="dateTo">
          </div>
          
          <div class="date-input-group">
            <label class="control-label"><i class="fas fa-user"></i> الموظف:</label>
            <select class="select-box" id="employeeSelect">
              <option value="all">جميع الموظفين</option>
            </select>
          </div>
        </div>
        
        <div style="text-align: center; margin-top: 25px;">
          <button class="btn btn-primary" id="applyFilter"><i class="fas fa-filter"></i> تطبيق التصفية</button>
          <button class="btn btn-secondary" id="resetFilter" style="margin-right: 15px;"><i class="fas fa-redo"></i> إعادة تعيين</button>
        </div>
      </div>
      
      <div class="date-summary" id="dateSummary" style="display: none;">
        <h3 style="margin-bottom: 15px; color: var(--purple);"><i class="fas fa-chart-bar"></i> ملخص الفترة المحددة</h3>
        <div class="summary-grid">
          <div class="summary-item">
            <div class="summary-label">عدد الأيام</div>
            <div class="summary-value" id="summaryDays">0</div>
          </div>
          <div class="summary-item">
            <div class="summary-label">عدد السجلات</div>
            <div class="summary-value" id="summaryRecords">0</div>
          </div>
          <div class="summary-item">
            <div class="summary-label">متوسط الحضور</div>
            <div class="summary-value" id="summaryAttendance">0%</div>
          </div>
          <div class="summary-item">
            <div class="summary-label">إجمالي الساعات</div>
            <div class="summary-value" id="summaryHours">0</div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Report Card -->
    <div class="card" id="reportCard" style="display: none;">
      <h2 class="card-title"><i class="fas fa-file-alt"></i> تقرير الحضور والانصراف التفصيلي</h2>
      
      <!-- Controls -->
      <div class="controls" style="margin-bottom: 25px;">
        <div class="control-group">
          <label class="control-label">تصفية حسب الحالة:</label>
          <select class="select-box" id="statusSelect">
            <option value="all">جميع الحالات</option>
            <option value="present">الحاضرين فقط</option>
            <option value="late">المتأخرين فقط</option>
            <option value="absent">الغياب الكامل</option>
            <option value="single">بصمة واحدة</option>
          </select>
        </div>
        
        <div class="control-group">
          <label class="control-label">بحث سريع:</label>
          <input type="text" class="input-box" id="searchInput" placeholder="ابحث بالاسم أو الرقم...">
        </div>
        
        <button class="btn btn-success" id="downloadCSV"><i class="fas fa-file-csv"></i> تصدير CSV</button>
        <button class="btn btn-secondary" id="printReport"><i class="fas fa-print"></i> طباعة</button>
      </div>
      
      <!-- Table -->
      <div class="table-container">
        <table id="reportTable">
          <thead>
            <tr>
              <th>#</th>
              <th>التاريخ</th>
              <th>اسم الموظف</th>
              <th>رقم البصمة</th>
              <th>أوقات البصمات</th>
              <th>وقت الدخول</th>
              <th>وقت الخروج</th>
              <th>عدد الساعات</th>
              <th>حالة الحضور</th>
              <th>عدد البصمات</th>
            </tr>
          </thead>
          <tbody id="reportBody">
          </tbody>
        </table>
      </div>
      
      <!-- Pagination -->
      <div id="pagination" style="display: none; margin-top: 30px; text-align: center;">
        <div style="display: flex; justify-content: center; align-items: center; gap: 15px;">
          <button class="btn btn-secondary" id="prevPage"><i class="fas fa-chevron-right"></i> السابق</button>
          <div style="display: flex; gap: 10px; align-items: center;">
            <span id="pageInfo">الصفحة 1 من 1</span>
            <select class="select-box" id="pageSize" style="width: auto; padding: 8px 15px;">
              <option value="10">10 صفوف</option>
              <option value="25">25 صفوف</option>
              <option value="50">50 صفوف</option>
              <option value="100">100 صفوف</option>
            </select>
          </div>
          <button class="btn btn-secondary" id="nextPage">التالي <i class="fas fa-chevron-left"></i></button>
        </div>
      </div>
    </div>
  </div>
  
  <!-- Messages Tab -->
  <div class="tab-content" id="messagesTab">
    <div class="card">
      <h2 class="card-title"><i class="fas fa-comment-dots"></i> إرسال تنبيهات للموظفين</h2>
      
      <div class="alert alert-info">
        <i class="fas fa-info-circle"></i>
        <div>هذه الخاصية تتطلب إضافة أرقام هواتف الموظفين في ملف البصمات. يمكنك تحديث الملف وإعادة معالجته.</div>
      </div>
      
      <div class="control-group" style="margin-bottom: 25px;">
        <label class="control-label">نص الرسالة:</label>
        <textarea class="input-box" id="messageText" rows="6" placeholder="اكتب نص الرسالة هنا...">مرحبا {اسم_الموظف}،

نود إعلامك بأن سجل بصماتك بتاريخ {التاريخ} يظهر {الحالة}.

أوقات البصمات: {أوقات_البصمات}
وقت الدخول: {وقت_الدخول}
وقت الخروج: {وقت_الخروج}
عدد الساعات: {عدد_الساعات}

الرجاء الالتزام بمواعيد الدوام الرسمية.

مع التحية،
الإدارة</textarea>
      </div>
      
      <div class="controls" style="margin-top: 25px;">
        <button class="btn btn-success" id="downloadReport"><i class="fas fa-file-excel"></i> تحميل تقرير كامل</button>
        <button class="btn btn-warning" id="showAllData"><i class="fas fa-eye"></i> عرض كل البيانات</button>
      </div>
    </div>
  </div>
  
  <!-- Footer -->
  <div class="footer">
    <p>نظام معالجة بصمات الموظفين بنظام 24 ساعة | الإصدار 6.0 | يدعم معالجة بيانات شهر كامل وتحليل الحضور والانصراف مع تصفية الأوقات</p>
    <div class="copyright">
      <i class="fas fa-copyright"></i> جميع الحقوق محفوظة 2025 - <span class="copyright-name">Zaid Mazin</span>
    </div>
  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/xlsx/dist/xlsx.full.min.js"></script>
<script>
// متغيرات النظام
let attendanceData = [];
let filteredData = [];
let allAttendanceData = [];
let fileData = null;
let currentPage = 1;
let pageSize = 10;
let totalPages = 1;
let dateRange = { from: null, to: null };
let filteredFingerprintsCount = 0;

// إعدادات النظام بنظام 24 ساعة
let settings = {
  morningStart: '08:00',
  lateStart: '08:15',
  morningEnd: '09:00',
  eveningStart: '16:00',
  eveningEnd: '17:00'
};

// ============== نظام التبويبات ==============
document.querySelectorAll('.tab').forEach(tab => {
  tab.addEventListener('click', () => {
    document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
    document.querySelectorAll('.tab-content').forEach(c => c.classList.remove('active'));
    
    tab.classList.add('active');
    const tabId = tab.getAttribute('data-tab');
    document.getElementById(`${tabId}Tab`).classList.add('active');
  });
});

// ============== التحكم في الملفات ==============
document.getElementById('browseBtn').addEventListener('click', () => document.getElementById('fileInput').click());
document.getElementById('fileInput').addEventListener('change', handleFileSelect);

// تحميل نموذج Excel مع التاريخ
document.getElementById('downloadTemplate').addEventListener('click', () => {
  const today = new Date();
  const yesterday = new Date(today);
  yesterday.setDate(yesterday.getDate() - 1);
  
  const formatDate = (date) => {
    return date.toISOString().split('T')[0];
  };
  
  const template = `# حقوق الملكية © ${new Date().getFullYear()} Zaid Mazin - جميع الحقوق محفوظة
اسم الموظف,رقم البصمة,التاريخ/الوقت
أحمد محمد,1001,${formatDate(yesterday)} 08:05
أحمد محمد,1001,${formatDate(yesterday)} 10:00
أحمد محمد,1001,${formatDate(yesterday)} 13:05
أحمد محمد,1001,${formatDate(yesterday)} 16:30
سارة خالد,1002,${formatDate(today)} 08:20
سارة خالد,1002,${formatDate(today)} 12:30
سارة خالد,1002,${formatDate(today)} 13:15
سارة خالد,1002,${formatDate(today)} 16:00
محمد علي,1003,${formatDate(today)} 08:45
محمد علي,1003,${formatDate(today)} 14:00
محمد علي,1003,${formatDate(today)} 17:00
فاطمة حسن,1004,${formatDate(today)} 07:55
فاطمة حسن,1004,${formatDate(today)} 11:45
فاطمة حسن,1004,${formatDate(today)} 12:45
فاطمة حسن,1004,${formatDate(today)} 15:50
علي كريم,1005,${formatDate(today)} 08:15
علي كريم,1005,${formatDate(today)} 12:00
علي كريم,1005,${formatDate(today)} 17:15
نور أحمد,1006,${formatDate(today)} 10:30
نور أحمد,1006,${formatDate(today)} 16:30
خالد محمود,1007,${formatDate(today)} 16:30
ليلى سالم,1008,${formatDate(today)} 08:20
ليلى سالم,1008,${formatDate(today)} 12:10
ليلى سالم,1008,${formatDate(today)} 13:05
ليلى سالم,1008,${formatDate(today)} 16:45
عمر سعيد,1009,${formatDate(today)} 08:10
عمر سعيد,1009,${formatDate(today)} 12:30
عمر سعيد,1009,${formatDate(today)} 13:20
عمر سعيد,1009,${formatDate(today)} 16:20
ريم عبدالله,1010,${formatDate(today)} 09:30
ريم عبدالله,1010,${formatDate(today)} 13:00
ريم عبدالله,1010,${formatDate(today)} 17:30`;

  const blob = new Blob(['\uFEFF' + template], { type: 'text/csv;charset=utf-8;' });
  const url = URL.createObjectURL(blob);
  const link = document.createElement('a');
  link.href = url;
  link.download = 'نموذج_بصمات_الموظفين_ZaidMazin.csv';
  link.click();
  URL.revokeObjectURL(url);
  
  showAlert('تم تحميل النموذج بنجاح', 'success');
});

// سحب وإفلات الملفات
document.getElementById('dropArea').addEventListener('dragover', (e) => {
  e.preventDefault();
  document.getElementById('dropArea').classList.add('dragover');
});

document.getElementById('dropArea').addEventListener('dragleave', () => {
  document.getElementById('dropArea').classList.remove('dragover');
});

document.getElementById('dropArea').addEventListener('drop', (e) => {
  e.preventDefault();
  document.getElementById('dropArea').classList.remove('dragover');
  
  if (e.dataTransfer.files.length) {
    document.getElementById('fileInput').files = e.dataTransfer.files;
    handleFileSelect();
  }
});

// معالجة اختيار الملف
async function handleFileSelect() {
  const fileInput = document.getElementById('fileInput');
  if (fileInput.files.length) {
    const file = fileInput.files[0];
    document.getElementById('fileName').textContent = file.name;
    document.getElementById('fileSize').textContent = formatFileSize(file.size);
    document.getElementById('fileInfo').style.display = 'block';
    document.getElementById('processBtn').disabled = false;
    fileData = file;
    
    try {
      const data = await readExcelFile(file);
      document.getElementById('fileDetails').style.display = 'block';
      document.getElementById('fileRecords').textContent = data.length;
      
      // تحليل التواريخ
      const columns = detectColumns(data[0]);
      let dates = new Set();
      let employees = new Set();
      let minDate = null;
      let maxDate = null;
      
      data.forEach(row => {
        const name = row[columns.name] || '';
        const badge = row[columns.badge] || '';
        const dateTimeStr = row[columns.date] || '';
        
        if (name && badge) {
          employees.add(`${name}_${badge}`);
        }
        
        // تحليل التاريخ والوقت
        if (dateTimeStr) {
          let date;
          if (columns.date === columns.time) {
            // التاريخ والوقت في نفس العمود
            const parts = dateTimeStr.toString().split(' ');
            if (parts[0]) {
              date = parseDate(parts[0]);
            }
          } else {
            date = parseDate(dateTimeStr);
          }
          
          if (date) {
            dates.add(date.toDateString());
            
            if (!minDate || date < minDate) {
              minDate = date;
            }
            if (!maxDate || date > maxDate) {
              maxDate = date;
            }
          }
        }
      });
      
      document.getElementById('fileEmployees').textContent = employees.size;
      document.getElementById('fileDays').textContent = dates.size;
      
      if (minDate && maxDate) {
        document.getElementById('fileDateFrom').textContent = formatArabicDate(minDate);
        document.getElementById('fileDateTo').textContent = formatArabicDate(maxDate);
        document.getElementById('dateRangeInfo').style.display = 'block';
      }
      
      document.getElementById('fileStatus').textContent = 'جاهز للمعالجة';
      document.getElementById('fileStatus').style.color = '#388e3c';
      
    } catch (error) {
      document.getElementById('fileStatus').textContent = 'خطأ في قراءة الملف';
      document.getElementById('fileStatus').style.color = '#d32f2f';
      console.error(error);
    }
  }
}

// تحليل التاريخ
function parseDate(dateStr) {
  if (!dateStr) return null;
  
  try {
    // تحويل من Excel serial date إذا لزم الأمر
    if (typeof dateStr === 'number') {
      const excelEpoch = new Date(1899, 11, 30);
      const date = new Date(excelEpoch.getTime() + dateStr * 24 * 60 * 60 * 1000);
      return date;
    }
    
    // تحويل من نص
    const date = new Date(dateStr);
    if (!isNaN(date.getTime())) {
      return date;
    }
    
    // تجربة تنسيقات أخرى
    const parts = dateStr.toString().split(/[/\-.]/);
    if (parts.length === 3) {
      const year = parts[0].length === 4 ? parseInt(parts[0]) : parseInt(parts[2]);
      const month = parseInt(parts[1]) - 1;
      const day = parseInt(parts[0].length === 4 ? parts[2] : parts[0]);
      const newDate = new Date(year, month, day);
      if (!isNaN(newDate.getTime())) {
        return newDate;
      }
    }
    
    return null;
  } catch (e) {
    return null;
  }
}

// تحليل الوقت من نص التاريخ والوقت
function parseTimeFromDateTime(dateTimeStr) {
  if (!dateTimeStr) return null;
  
  try {
    // إذا كان التاريخ والوقت في نفس السلسلة
    if (dateTimeStr.includes(' ')) {
      const parts = dateTimeStr.split(' ');
      const timePart = parts[parts.length - 1];
      return parseTime(timePart);
    }
    
    // إذا كان الوقت فقط
    return parseTime(dateTimeStr);
  } catch (e) {
    return null;
  }
}

// تحليل الوقت
function parseTime(timeStr) {
  if (!timeStr) return null;
  
  const clean = timeStr.toString().trim().replace(/[^0-9:.]/g, '');
  if (!clean) return null;
  
  const normalized = clean.replace('.', ':');
  
  // تنسيق HH:MM
  const match = normalized.match(/^(\d{1,2}):(\d{2})$/);
  if (match) {
    const hours = parseInt(match[1]);
    const minutes = parseInt(match[2]);
    
    if (hours >= 0 && hours < 24 && minutes >= 0 && minutes < 60) {
      return { hours, minutes };
    }
  }
  
  // تنسيق 4 أرقام (HHMM)
  if (/^\d{3,4}$/.test(normalized)) {
    const padded = normalized.padStart(4, '0');
    const hours = parseInt(padded.substring(0, 2));
    const minutes = parseInt(padded.substring(2, 4));
    
    if (hours >= 0 && hours < 24 && minutes >= 0 && minutes < 60) {
      return { hours, minutes };
    }
  }
  
  return null;
}

// تنسيق التاريخ عربي
function formatArabicDate(date) {
  if (!date) return '--/--/----';
  
  const day = date.getDate().toString().padStart(2, '0');
  const month = (date.getMonth() + 1).toString().padStart(2, '0');
  const year = date.getFullYear();
  
  return `${day}/${month}/${year}`;
}

// إزالة الملف
document.getElementById('removeFile').addEventListener('click', () => {
  document.getElementById('fileInput').value = '';
  document.getElementById('fileInfo').style.display = 'none';
  document.getElementById('fileDetails').style.display = 'none';
  document.getElementById('dateRangeInfo').style.display = 'none';
  document.getElementById('processBtn').disabled = true;
  fileData = null;
});

// تنسيق حجم الملف
function formatFileSize(bytes) {
  if (bytes === 0) return '0 بايت';
  const k = 1024;
  const sizes = ['بايت', 'كيلوبايت', 'ميجابايت', 'جيجابايت'];
  const i = Math.floor(Math.log(bytes) / Math.log(k));
  return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
}

// ============== الدوال المساعدة للتصفية ==============
// تحويل نص الوقت إلى دقائق
function timeToMinutes(timeStr) {
  if (!timeStr) return 0;
  const [hours, minutes] = timeStr.split(':').map(Number);
  return hours * 60 + minutes;
}

// تحويل الوقت إلى نص
function timeToString(timeObj) {
  if (!timeObj) return '--:--';
  
  const hours = timeObj.hours.toString().padStart(2, '0');
  const minutes = timeObj.minutes.toString().padStart(2, '0');
  return `${hours}:${minutes}`;
}

// دالة جديدة: تصفية البصمات بناءً على الأوقات المسموح بها
function filterValidFingerprints(records) {
  const morningStart = timeToMinutes(settings.morningStart);
  const morningEnd = timeToMinutes(settings.morningEnd);
  const eveningStart = timeToMinutes(settings.eveningStart);
  const eveningEnd = timeToMinutes(settings.eveningEnd);
  
  const filteredRecords = [];
  const ignoredRecords = [];
  
  records.forEach(record => {
    const recordMinutes = record.time.hours * 60 + record.time.minutes;
    const isMorningRecord = (recordMinutes >= morningStart && recordMinutes <= morningEnd);
    const isEveningRecord = (recordMinutes >= eveningStart && recordMinutes <= eveningEnd);
    
    if (isMorningRecord || isEveningRecord) {
      filteredRecords.push(record);
    } else {
      ignoredRecords.push(record);
    }
  });
  
  return {
    valid: filteredRecords,
    ignored: ignoredRecords
  };
}

// ============== معالجة البيانات ==============
document.getElementById('processBtn').addEventListener('click', async () => {
  if (!fileData) {
    showAlert('الرجاء اختيار ملف أولاً', 'warning');
    return;
  }
  
  updateSettings();
  
  const processBtn = document.getElementById('processBtn');
  processBtn.innerHTML = '<i class="fas fa-spinner fa-spin"></i> جاري معالجة البصمات...';
  processBtn.disabled = true;
  
  try {
    const data = await readExcelFile(fileData);
    await processAttendanceData(data);
    updateStatistics();
    setupDateFilter();
    
    document.getElementById('statsCard').style.display = 'block';
    document.getElementById('dateFilterCard').style.display = 'block';
    document.getElementById('reportCard').style.display = 'block';
    document.getElementById('pagination').style.display = 'block';
    
    renderTable();
    
    document.querySelector('[data-tab="report"]').click();
    
    showAlert(`تم معالجة ${attendanceData.length} سجل بنجاح (تم تجاهل ${filteredFingerprintsCount} بصمة خارج الأوقات)`, 'success');
  } catch (error) {
    showAlert(`خطأ في معالجة الملف: ${error.message}`, 'danger');
    console.error(error);
  } finally {
    processBtn.innerHTML = '<i class="fas fa-cogs"></i> معالجة البصمات وإنشاء التقرير';
    processBtn.disabled = false;
  }
});

// تحديث الإعدادات
function updateSettings() {
  settings.morningStart = document.getElementById('morningStart').value;
  settings.lateStart = document.getElementById('lateStart').value;
  settings.morningEnd = document.getElementById('morningEnd').value;
  settings.eveningStart = document.getElementById('eveningStart').value;
  settings.eveningEnd = document.getElementById('eveningEnd').value;
}

// قراءة ملف Excel
function readExcelFile(file) {
  return new Promise((resolve, reject) => {
    const reader = new FileReader();
    
    reader.onload = (e) => {
      try {
        const data = new Uint8Array(e.target.result);
        const workbook = XLSX.read(data, { 
          type: 'array', 
          cellDates: true,
          dateNF: 'yyyy-mm-dd',
          raw: false
        });
        
        const firstSheet = workbook.Sheets[workbook.SheetNames[0]];
        const jsonData = XLSX.utils.sheet_to_json(firstSheet, { 
          defval: '',
          raw: false
        });
        
        if (!jsonData.length) {
          reject(new Error('الملف فارغ أو لا يحتوي على بيانات'));
          return;
        }
        
        resolve(jsonData);
      } catch (error) {
        reject(error);
      }
    };
    
    reader.onerror = () => {
      reject(new Error('فشل في قراءة الملف'));
    };
    
    reader.readAsArrayBuffer(file);
  });
}

// اكتشاف الأعمدة تلقائياً
function detectColumns(row) {
  const columns = {
    name: null,
    badge: null,
    date: null,
    time: null
  };
  
  const keys = Object.keys(row);
  
  keys.forEach(key => {
    const lowerKey = key.toLowerCase().trim();
    
    if (!columns.name && (
      lowerKey.includes('اسم') || 
      lowerKey.includes('name') || 
      lowerKey.includes('موظف') ||
      lowerKey.includes('employee')
    )) {
      columns.name = key;
    }
    
    if (!columns.badge && (
      lowerKey.includes('بصمة') || 
      lowerKey.includes('badge') || 
      lowerKey.includes('id') || 
      lowerKey.includes('رقم') ||
      lowerKey.includes('كود') ||
      lowerKey.includes('هوية')
    )) {
      columns.badge = key;
    }
    
    if (!columns.date && (
      lowerKey.includes('تاريخ') || 
      lowerKey.includes('date') || 
      lowerKey.includes('يوم') ||
      lowerKey.includes('time') ||
      lowerKey.includes('وقت')
    )) {
      columns.date = key;
      columns.time = key; // افتراضيًا نفس العمود للتاريخ والوقت
    }
  });
  
  // قيم افتراضية
  if (!columns.name && keys.length > 0) columns.name = keys[0];
  if (!columns.badge && keys.length > 1) columns.badge = keys[1];
  if (!columns.date && keys.length > 2) columns.date = keys[2];
  
  return columns;
}

// تحليل بصمات الموظف لكل تاريخ - النسخة المعدلة حسب المتطلبات الجديدة
function analyzeEmployeeAttendance(records) {
  const lateStart = timeToMinutes(settings.lateStart);
  const morningEnd = timeToMinutes(settings.morningEnd);
  
  // التعديل الجديد: تصفية البصمات أولاً
  const filtered = filterValidFingerprints(records);
  const validRecords = filtered.valid;
  
  // تحديث العداد العالمي للبصمات المهملة
  filteredFingerprintsCount += filtered.ignored.length;
  
  // تجميع الأوقات لكل تاريخ مع تجاهل التكرار
  const dateMap = new Map();
  
  validRecords.forEach(record => {
    const date = record.date;
    const time = record.time;
    
    if (!date || !time) return;
    
    const dateKey = date.toDateString();
    const timeKey = `${time.hours}:${time.minutes}`;
    
    if (!dateMap.has(dateKey)) {
      dateMap.set(dateKey, {
        date: date,
        times: [],
        timeStrings: [],
        uniqueTimes: new Set() // لتجنب التكرار
      });
    }
    
    const dateData = dateMap.get(dateKey);
    
    // التحقق من أن الوقت غير مكرر
    if (!dateData.uniqueTimes.has(timeKey)) {
      dateData.uniqueTimes.add(timeKey);
      dateData.times.push(time);
      dateData.timeStrings.push(timeToString(time));
    }
  });
  
  const results = [];
  
  for (const [dateStr, data] of dateMap) {
    const times = data.times;
    const timeStrings = data.timeStrings;
    const date = data.date;
    
    if (times.length === 0) {
      // لا توجد بصمات صحيحة - غياب كامل
      results.push({
        date: date,
        dateStr: formatArabicDate(date),
        times: [],
        timeStrings: [],
        firstIn: null,
        lastOut: null,
        hours: 0,
        status: 'absent',
        fingerprintsText: 'لا توجد بصمات صحيحة',
        fingerprintCount: 0
      });
      continue;
    }
    
    // ترتيب الأوقات
    const sortedTimes = [...times].sort((a, b) => {
      const aMinutes = a.hours * 60 + a.minutes;
      const bMinutes = b.hours * 60 + b.minutes;
      return aMinutes - bMinutes;
    });
    
    const firstIn = sortedTimes[0];
    const lastOut = sortedTimes[sortedTimes.length - 1];
    
    // حساب عدد الساعات
    const startMinutes = firstIn.hours * 60 + firstIn.minutes;
    const endMinutes = lastOut.hours * 60 + lastOut.minutes;
    let hours = 0;
    
    // التأكد من أن وقت الخروج بعد وقت الدخول
    if (endMinutes > startMinutes) {
      hours = (endMinutes - startMinutes) / 60;
    } else {
      // إذا كان وقت الخروج قبل وقت الدخول (عبر منتصف الليل)
      hours = ((24 * 60) - startMinutes + endMinutes) / 60;
    }
    
    // تحديد الحالة حسب التعديلات المطلوبة
    let status = 'present';
    const firstInMinutes = firstIn.hours * 60 + firstIn.minutes;
    
    // التعديل الجديد: إذا كان لديه بصمة واحدة فقط (سواء كانت قبل أو بعد وقت التأخير) = بصمة واحدة
    if (times.length === 1) {
      status = 'single'; // بصمة واحدة سواء متأخر أو لا
    } else if (firstInMinutes >= lateStart && firstInMinutes <= morningEnd) {
      // تأخير (لديه أكثر من بصمة - أي لديه بصمة خروج)
      status = 'late';
    }
    // إذا كان الحضور قبل وقت التأخير = حاضر طبيعي (حتى لو كان مبكراً)
    
    results.push({
      date: date,
      dateStr: formatArabicDate(date),
      times: sortedTimes,
      timeStrings: timeStrings,
      firstIn: firstIn,
      lastOut: lastOut,
      hours: Math.round(hours * 100) / 100,
      status: status,
      fingerprintsText: timeStrings.join(' - '),
      fingerprintCount: times.length
    });
  }
  
  return results;
}

// معالجة بيانات الحضور
async function processAttendanceData(jsonData) {
  attendanceData = [];
  filteredData = [];
  allAttendanceData = [];
  filteredFingerprintsCount = 0; // إعادة تعيين العداد
  
  if (!jsonData || jsonData.length === 0) {
    showAlert('لا توجد بيانات للمعالجة', 'warning');
    return;
  }
  
  const columns = detectColumns(jsonData[0]);
  
  // تجميع البيانات حسب الموظف
  const employeeMap = new Map();
  
  jsonData.forEach((row, index) => {
    const name = row[columns.name] || `موظف ${index + 1}`;
    const badge = row[columns.badge] || (index + 1000);
    const dateTimeStr = row[columns.date] || '';
    
    let date = null;
    let time = null;
    
    if (columns.date === columns.time) {
      // التاريخ والوقت في نفس العمود
      const parts = dateTimeStr.toString().split(' ');
      if (parts[0]) {
        date = parseDate(parts[0]);
      }
      if (parts[1]) {
        time = parseTime(parts[1]);
      } else {
        // إذا لم يكن هناك وقت منفصل، حاول تحليل التاريخ الكامل
        const fullDate = parseDate(dateTimeStr);
        if (fullDate) {
          date = new Date(fullDate.getFullYear(), fullDate.getMonth(), fullDate.getDate());
          time = {
            hours: fullDate.getHours(),
            minutes: fullDate.getMinutes()
          };
        }
      }
    } else {
      date = parseDate(row[columns.date]);
      time = parseTime(row[columns.time]);
    }
    
    if (!date || !time) return;
    
    const key = `${name}_${badge}`;
    
    if (!employeeMap.has(key)) {
      employeeMap.set(key, {
        name: name,
        badge: badge,
        records: []
      });
    }
    
    employeeMap.get(key).records.push({
      date: date,
      time: time
    });
  });
  
  // معالجة كل موظف
  let idCounter = 1;
  for (const [key, empData] of employeeMap) {
    const attendanceResults = analyzeEmployeeAttendance(empData.records);
    
    // إضافة كل تاريخ كسجل منفصل
    attendanceResults.forEach(result => {
      allAttendanceData.push({
        id: idCounter++,
        name: empData.name,
        badge: empData.badge,
        date: result.date,
        dateStr: result.dateStr,
        times: result.times,
        timeStrings: result.timeStrings,
        firstIn: result.firstIn,
        lastOut: result.lastOut,
        hours: result.hours,
        status: result.status,
        fingerprintsText: result.fingerprintsText,
        fingerprintCount: result.fingerprintCount
      });
    });
  }
  
  // حفظ نسخة كاملة من البيانات
  attendanceData = [...allAttendanceData];
  filteredData = [...allAttendanceData];
}

// تحديث الإحصائيات
function updateStatistics() {
  const total = attendanceData.length;
  const present = attendanceData.filter(e => e.status === 'present').length;
  const late = attendanceData.filter(e => e.status === 'late').length;
  const absent = attendanceData.filter(e => e.status === 'absent').length;
  const single = attendanceData.filter(e => e.status === 'single').length;
  
  document.getElementById('totalRecords').textContent = total;
  document.getElementById('presentCount').textContent = present;
  document.getElementById('lateCount').textContent = late;
  document.getElementById('absentCount').textContent = absent;
  document.getElementById('singleCount').textContent = single;
  document.getElementById('filteredCount').textContent = filteredFingerprintsCount;
}

// إعداد تصفية التواريخ
function setupDateFilter() {
  // الحصول على نطاق التواريخ من البيانات
  let minDate = null;
  let maxDate = null;
  
  allAttendanceData.forEach(record => {
    if (!minDate || record.date < minDate) {
      minDate = record.date;
    }
    if (!maxDate || record.date > maxDate) {
      maxDate = record.date;
    }
  });
  
  if (minDate && maxDate) {
    document.getElementById('dateFrom').valueAsDate = minDate;
    document.getElementById('dateTo').valueAsDate = maxDate;
    dateRange.from = minDate;
    dateRange.to = maxDate;
  }
  
  // ملء قائمة الموظفين
  fillEmployeeSelect();
}

// ملء قائمة الموظفين
function fillEmployeeSelect() {
  const select = document.getElementById('employeeSelect');
  select.innerHTML = '<option value="all">جميع الموظفين</option>';
  
  const employees = new Set();
  allAttendanceData.forEach(record => {
    employees.add(`${record.name} (${record.badge})`);
  });
  
  employees.forEach(employee => {
    const option = document.createElement('option');
    option.value = employee;
    option.textContent = employee;
    select.appendChild(option);
  });
}

// عرض الجدول
function renderTable() {
  const tbody = document.getElementById('reportBody');
  const statusFilter = document.getElementById('statusSelect').value;
  const searchTerm = document.getElementById('searchInput').value.toLowerCase();
  
  // تطبيق التصفية
  filteredData = allAttendanceData.filter(record => {
    // تصفية حسب الحالة
    if (statusFilter !== 'all' && record.status !== statusFilter) {
      return false;
    }
    
    // تصفية حسب البحث
    if (searchTerm) {
      const nameMatch = record.name.toLowerCase().includes(searchTerm);
      const badgeMatch = record.badge.toString().toLowerCase().includes(searchTerm);
      
      if (!nameMatch && !badgeMatch) {
        return false;
      }
    }
    
    // تصفية حسب التاريخ
    if (dateRange.from && dateRange.to) {
      if (record.date < dateRange.from || record.date > dateRange.to) {
        return false;
      }
    }
    
    // تصفية حسب الموظف
    const selectedEmployee = document.getElementById('employeeSelect').value;
    if (selectedEmployee !== 'all') {
      const employeeName = `${record.name} (${record.badge})`;
      if (employeeName !== selectedEmployee) {
        return false;
      }
    }
    
    return true;
  });
  
  // تحديث الإحصائيات
  updateDateSummary();
  
  // حساب الترقيم
  totalPages = Math.ceil(filteredData.length / pageSize);
  if (currentPage > totalPages) {
    currentPage = totalPages || 1;
  }
  
  // الحصول على البيانات للصفحة الحالية
  const startIndex = (currentPage - 1) * pageSize;
  const endIndex = startIndex + pageSize;
  const pageData = filteredData.slice(startIndex, endIndex);
  
  tbody.innerHTML = '';
  
  pageData.forEach((record, index) => {
    const row = document.createElement('tr');
    
    let statusText = '';
    let statusClass = '';
    
    switch (record.status) {
      case 'present':
        statusText = 'حاضر';
        statusClass = 'status-present';
        break;
      case 'late':
        statusText = 'تأخير صباحي';
        statusClass = 'status-late';
        break;
      case 'absent':
        statusText = 'غياب كامل';
        statusClass = 'status-absent';
        break;
      case 'single':
        statusText = 'بصمة واحدة';
        statusClass = 'status-single';
        break;
    }
    
    const cells = [
      startIndex + index + 1,
      `<div class="employee-info" style="font-weight: bold;">${record.dateStr}</div>`,
      `<div>
        <strong>${record.name}</strong>
        <div class="employee-badge">${record.badge}</div>
      </div>`,
      record.badge,
      `<div class="employee-info">${record.fingerprintsText}</div>`,
      `<div class="employee-info" style="font-weight: bold;">${timeToString(record.firstIn)}</div>`,
      `<div class="employee-info" style="font-weight: bold;">${timeToString(record.lastOut)}</div>`,
      record.hours > 0 ? `${record.hours} ساعة` : '--',
      `<span class="status-badge ${statusClass}">${statusText}</span>`,
      record.fingerprintCount
    ];
    
    cells.forEach(cellContent => {
      const cell = document.createElement('td');
      cell.innerHTML = cellContent;
      row.appendChild(cell);
    });
    
    tbody.appendChild(row);
  });
  
  // تحديث معلومات الصفحة
  document.getElementById('pageInfo').textContent = `الصفحة ${currentPage} من ${totalPages}`;
  document.getElementById('prevPage').disabled = currentPage === 1;
  document.getElementById('nextPage').disabled = currentPage === totalPages;
}

// تحديث ملخص الفترة
function updateDateSummary() {
  if (filteredData.length === 0) {
    document.getElementById('dateSummary').style.display = 'none';
    return;
  }
  
  document.getElementById('dateSummary').style.display = 'block';
  
  // حساب الأيام الفريدة
  const uniqueDates = new Set();
  filteredData.forEach(record => {
    uniqueDates.add(record.date.toDateString());
  });
  
  const days = uniqueDates.size;
  const records = filteredData.length;
  
  // حساب نسبة الحضور
  const presentCount = filteredData.filter(r => r.status === 'present' || r.status === 'late' || r.status === 'single').length;
  const attendanceRate = records > 0 ? Math.round((presentCount / records) * 100) : 0;
  
  // حساب إجمالي الساعات
  const totalHours = filteredData.reduce((sum, record) => sum + record.hours, 0);
  
  document.getElementById('summaryDays').textContent = days;
  document.getElementById('summaryRecords').textContent = records;
  document.getElementById('summaryAttendance').textContent = `${attendanceRate}%`;
  document.getElementById('summaryHours').textContent = Math.round(totalHours * 100) / 100;
}

// ============== تصفية التواريخ ==============
document.getElementById('applyFilter').addEventListener('click', () => {
  const fromDate = document.getElementById('dateFrom').valueAsDate;
  const toDate = document.getElementById('dateTo').valueAsDate;
  
  if (fromDate && toDate) {
    if (fromDate > toDate) {
      showAlert('تاريخ البداية يجب أن يكون قبل تاريخ النهاية', 'warning');
      return;
    }
    
    dateRange.from = fromDate;
    dateRange.to = toDate;
    currentPage = 1;
    renderTable();
    
    showAlert('تم تطبيق التصفية بنجاح', 'success');
  }
});

document.getElementById('resetFilter').addEventListener('click', () => {
  // إعادة تعيين إلى كل التواريخ
  let minDate = null;
  let maxDate = null;
  
  allAttendanceData.forEach(record => {
    if (!minDate || record.date < minDate) {
      minDate = record.date;
    }
    if (!maxDate || record.date > maxDate) {
      maxDate = record.date;
    }
  });
  
  if (minDate && maxDate) {
    document.getElementById('dateFrom').valueAsDate = minDate;
    document.getElementById('dateTo').valueAsDate = maxDate;
    dateRange.from = minDate;
    dateRange.to = maxDate;
  }
  
  document.getElementById('employeeSelect').value = 'all';
  document.getElementById('statusSelect').value = 'all';
  document.getElementById('searchInput').value = '';
  
  currentPage = 1;
  renderTable();
  
  showAlert('تم إعادة تعيين التصفية', 'success');
});

// ============== التصفح بين الصفحات ==============
document.getElementById('prevPage').addEventListener('click', () => {
  if (currentPage > 1) {
    currentPage--;
    renderTable();
  }
});

document.getElementById('nextPage').addEventListener('click', () => {
  if (currentPage < totalPages) {
    currentPage++;
    renderTable();
  }
});

document.getElementById('pageSize').addEventListener('change', () => {
  pageSize = parseInt(document.getElementById('pageSize').value);
  currentPage = 1;
  renderTable();
});

// ============== تصدير CSV مع حقوق الملكية ==============
document.getElementById('downloadCSV').addEventListener('click', () => {
  if (filteredData.length === 0) {
    showAlert('لا توجد بيانات لتصديرها', 'warning');
    return;
  }
  
  let csvContent = `# حقوق الملكية © ${new Date().getFullYear()} Zaid Mazin - جميع الحقوق محفوظة\n`;
  csvContent += '# نظام معالجة بصمات الموظفين بنظام 24 ساعة - الإصدار 6.0\n';
  csvContent += '# تاريخ التصدير: ' + new Date().toLocaleDateString('ar-EG') + '\n';
  csvContent += 'رقم,التاريخ,اسم الموظف,رقم البصمة,أوقات البصمات,وقت الدخول,وقت الخروج,عدد الساعات,الحالة,عدد البصمات\n';
  
  filteredData.forEach((record, index) => {
    const row = [
      index + 1,
      record.dateStr,
      `"${record.name}"`,
      record.badge,
      `"${record.fingerprintsText}"`,
      timeToString(record.firstIn),
      timeToString(record.lastOut),
      record.hours,
      record.status === 'present' ? 'حاضر' : 
      record.status === 'late' ? 'تأخير صباحي' : 
      record.status === 'absent' ? 'غياب كامل' : 'بصمة واحدة',
      record.fingerprintCount
    ];
    
    csvContent += row.join(',') + '\n';
  });
  
  const blob = new Blob(['\uFEFF' + csvContent], { type: 'text/csv;charset=utf-8;' });
  const url = URL.createObjectURL(blob);
  const link = document.createElement('a');
  link.href = url;
  link.download = `تقرير_بصمات_ZaidMazin_${new Date().toISOString().split('T')[0]}.csv`;
  link.click();
  URL.revokeObjectURL(url);
  
  showAlert('تم تحميل الملف بنجاح', 'success');
});

// تحميل تقرير كامل مع حقوق الملكية
document.getElementById('downloadReport').addEventListener('click', () => {
  if (allAttendanceData.length === 0) {
    showAlert('لا توجد بيانات لتصديرها', 'warning');
    return;
  }
  
  let csvContent = `# حقوق الملكية © ${new Date().getFullYear()} Zaid Mazin - جميع الحقوق محفوظة\n`;
  csvContent += '# نظام معالجة بصمات الموظفين بنظام 24 ساعة - الإصدار 6.0\n';
  csvContent += '# تاريخ التصدير: ' + new Date().toLocaleDateString('ar-EG') + '\n';
  csvContent += '# البصمات المهملة (خارج الأوقات): ' + filteredFingerprintsCount + '\n';
  csvContent += 'رقم,التاريخ,اسم الموظف,رقم البصمة,أوقات البصمات,وقت الدخول,وقت الخروج,عدد الساعات,الحالة,عدد البصمات\n';
  
  allAttendanceData.forEach((record, index) => {
    const row = [
      index + 1,
      record.dateStr,
      `"${record.name}"`,
      record.badge,
      `"${record.fingerprintsText}"`,
      timeToString(record.firstIn),
      timeToString(record.lastOut),
      record.hours,
      record.status === 'present' ? 'حاضر' : 
      record.status === 'late' ? 'تأخير صباحي' : 
      record.status === 'absent' ? 'غياب كامل' : 'بصمة واحدة',
      record.fingerprintCount
    ];
    
    csvContent += row.join(',') + '\n';
  });
  
  const blob = new Blob(['\uFEFF' + csvContent], { type: 'text/csv;charset=utf-8;' });
  const url = URL.createObjectURL(blob);
  const link = document.createElement('a');
  link.href = url;
  link.download = `تقرير_بصمات_كامل_ZaidMazin_${new Date().toISOString().split('T')[0]}.csv`;
  link.click();
  URL.revokeObjectURL(url);
  
  showAlert('تم تحميل التقرير الكامل بنجاح', 'success');
});

// عرض كل البيانات
document.getElementById('showAllData').addEventListener('click', () => {
  filteredData = [...allAttendanceData];
  dateRange.from = null;
  dateRange.to = null;
  
  // إعادة تعيين التصفية
  let minDate = null;
  let maxDate = null;
  
  allAttendanceData.forEach(record => {
    if (!minDate || record.date < minDate) {
      minDate = record.date;
    }
    if (!maxDate || record.date > maxDate) {
      maxDate = record.date;
    }
  });
  
  if (minDate && maxDate) {
    document.getElementById('dateFrom').valueAsDate = minDate;
    document.getElementById('dateTo').valueAsDate = maxDate;
  }
  
  document.getElementById('employeeSelect').value = 'all';
  document.getElementById('statusSelect').value = 'all';
  document.getElementById('searchInput').value = '';
  
  currentPage = 1;
  renderTable();
  
  document.querySelector('[data-tab="report"]').click();
  
  showAlert('تم عرض جميع البيانات', 'success');
});

// ============== طباعة التقرير مع حقوق الملكية ==============
document.getElementById('printReport').addEventListener('click', () => {
  if (filteredData.length === 0) {
    showAlert('لا توجد بيانات للطباعة', 'warning');
    return;
  }
  
  // ترتيب البيانات حسب الموظف والتاريخ
  const sortedData = [...filteredData].sort((a, b) => {
    if (a.name === b.name) {
      return a.date - b.date;
    }
    return a.name.localeCompare(b.name);
  });
  
  // تقسيم البيانات إلى صفحات (20 موظف في كل صفحة)
  const recordsPerPage = 20;
  const totalPages = Math.ceil(sortedData.length / recordsPerPage);
  
  // إنشاء محتوى الطباعة
  let printContent = '';
  
  for (let page = 0; page < totalPages; page++) {
    const startIndex = page * recordsPerPage;
    const endIndex = Math.min(startIndex + recordsPerPage, sortedData.length);
    const pageData = sortedData.slice(startIndex, endIndex);
    
    // بداية الصفحة
    printContent += `
      <div class="print-section" style="${page > 0 ? 'page-break-before: always;' : ''}">
        <div class="print-header">
          <h1 class="print-title">تقرير بصمات الموظفين بنظام 24 ساعة</h1>
          <div class="print-subtitle">الإصدار 6.0 - نظام معالجة البصمات مع تصفية الأوقات</div>
          <div class="print-date">
            تاريخ الطباعة: ${new Date().toLocaleDateString('ar-EG')} | 
            عدد السجلات: ${sortedData.length} | 
            البصمات المهملة: ${filteredFingerprintsCount}
          </div>
        </div>
        
        <table class="print-table">
          <thead>
            <tr>
              <th>#</th>
              <th>التاريخ</th>
              <th>اسم الموظف</th>
              <th>رقم البصمة</th>
              <th>أوقات البصمات</th>
              <th>وقت الدخول</th>
              <th>وقت الخروج</th>
              <th>عدد الساعات</th>
              <th>حالة الحضور</th>
              <th>عدد البصمات</th>
            </tr>
          </thead>
          <tbody>
    `;
    
    // إضافة بيانات الصفحة
    pageData.forEach((record, index) => {
      const globalIndex = startIndex + index + 1;
      
      let statusText = '';
      let statusClass = '';
      
      switch (record.status) {
        case 'present':
          statusText = 'حاضر';
          statusClass = 'status-present-print';
          break;
        case 'late':
          statusText = 'تأخير صباحي';
          statusClass = 'status-late-print';
          break;
        case 'absent':
          statusText = 'غياب كامل';
          statusClass = 'status-absent-print';
          break;
        case 'single':
          statusText = 'بصمة واحدة';
          statusClass = 'status-single-print';
          break;
      }
      
      printContent += `
        <tr>
          <td>${globalIndex}</td>
          <td>${record.dateStr}</td>
          <td>${record.name}</td>
          <td>${record.badge}</td>
          <td>${record.fingerprintsText}</td>
          <td>${timeToString(record.firstIn)}</td>
          <td>${timeToString(record.lastOut)}</td>
          <td>${record.hours > 0 ? record.hours + ' ساعة' : '--'}</td>
          <td><span class="print-status ${statusClass}">${statusText}</span></td>
          <td>${record.fingerprintCount}</td>
        </tr>
      `;
    });
    
    // نهاية الصفحة مع حقوق الملكية
    printContent += `
          </tbody>
        </table>
        
        <div style="margin-top: 20px; text-align: center; font-size: 12px; color: #666;">
          الصفحة ${page + 1} من ${totalPages} | 
          تاريخ الإصدار: ${new Date().toLocaleDateString('ar-EG')} | 
          نظام معالجة البصمات الإلكترونية
        </div>
        <div class="print-copyright">
          <i class="fas fa-copyright"></i> جميع الحقوق محفوظة ${new Date().getFullYear()} - <strong>Zaid Mazin</strong>
        </div>
      </div>
    `;
  }
  
  // طباعة التقرير
  const printWindow = window.open('', '_blank');
  printWindow.document.write(`
    <!DOCTYPE html>
    <html dir="rtl" lang="ar">
    <head>
      <meta charset="UTF-8">
      <title>تقرير بصمات الموظفين - Zaid Mazin</title>
      <style>
        @media print {
          @page {
            size: landscape;
            margin: 0.5cm;
          }
          
          body {
            font-family: 'Cairo', 'Segoe UI', Tahoma, Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: white;
            color: black;
          }
          
          .print-section {
            width: 100%;
            padding: 10px;
          }
          
          .print-header {
            text-align: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 3px solid #000;
          }
          
          .print-title {
            font-size: 28px;
            color: #000;
            margin-bottom: 10px;
          }
          
          .print-subtitle {
            font-size: 16px;
            color: #666;
            margin-bottom: 15px;
          }
          
          .print-date {
            font-size: 14px;
            color: #333;
            margin-bottom: 10px;
          }
          
          .print-table {
            width: 100%;
            border-collapse: collapse;
            margin: 15px 0;
            font-size: 12px;
          }
          
          .print-table th {
            background-color: #f0f0f0;
            border: 1px solid #000;
            padding: 8px;
            text-align: center;
            font-weight: bold;
          }
          
          .print-table td {
            border: 1px solid #000;
            padding: 6px;
            text-align: center;
          }
          
          .print-status {
            padding: 4px 8px;
            border-radius: 4px;
            font-weight: bold;
            font-size: 11px;
            display: inline-block;
          }
          
          .status-present-print { background-color: #e8f5e9; color: #2e7d32; }
          .status-late-print { background-color: #fff3e0; color: #ef6c00; }
          .status-absent-print { background-color: #ffebee; color: #c62828; }
          .status-single-print { background-color: #fff8e1; color: #ff9800; }
          
          .print-copyright {
            text-align: center;
            font-size: 10px;
            color: #666;
            margin-top: 20px;
            padding-top: 10px;
            border-top: 1px solid #ccc;
          }
          
          .page-break {
            page-break-after: always;
          }
        }
        
        @media screen {
          body {
            font-family: 'Cairo', 'Segoe UI', Tahoma, Arial, sans-serif;
            padding: 20px;
            background: #f5f5f5;
          }
          
          .print-section {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 5px;
          }
          
          .print-header {
            text-align: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 3px solid #000;
          }
          
          .print-title {
            font-size: 28px;
            color: #000;
            margin-bottom: 10px;
          }
          
          .print-subtitle {
            font-size: 16px;
            color: #666;
            margin-bottom: 15px;
          }
          
          .print-date {
            font-size: 14px;
            color: #333;
            margin-bottom: 10px;
          }
          
          .print-table {
            width: 100%;
            border-collapse: collapse;
            margin: 15px 0;
            font-size: 12px;
          }
          
          .print-table th {
            background-color: #f0f0f0;
            border: 1px solid #000;
            padding: 8px;
            text-align: center;
            font-weight: bold;
          }
          
          .print-table td {
            border: 1px solid #000;
            padding: 6px;
            text-align: center;
          }
          
          .print-status {
            padding: 4px 8px;
            border-radius: 4px;
            font-weight: bold;
            font-size: 11px;
            display: inline-block;
          }
          
          .status-present-print { background-color: #e8f5e9; color: #2e7d32; }
          .status-late-print { background-color: #fff3e0; color: #ef6c00; }
          .status-absent-print { background-color: #ffebee; color: #c62828; }
          .status-single-print { background-color: #fff8e1; color: #ff9800; }
          
          button {
            display: block;
            margin: 20px auto;
            padding: 10px 30px;
            background: #0d47a1;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            font-family: 'Cairo', sans-serif;
          }
        }
      </style>
      <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    </head>
    <body>
      ${printContent}
      <button onclick="window.print()" style="display: block; margin: 20px auto; padding: 10px 30px; background: #0d47a1; color: white; border: none; border-radius: 5px; cursor: pointer; font-size: 16px; font-family: 'Cairo', sans-serif;">
        طباعة التقرير
      </button>
    </body>
    </html>
  `);
  
  printWindow.document.close();
  printWindow.focus();
});

// ============== التنبيهات ==============
function showAlert(message, type) {
  const alert = document.createElement('div');
  alert.className = `alert alert-${type}`;
  alert.innerHTML = `
    <i class="fas fa-${type === 'success' ? 'check-circle' : type === 'warning' ? 'exclamation-triangle' : type === 'danger' ? 'times-circle' : 'info-circle'}"></i>
    <div>${message}</div>
  `;
  
  const container = document.querySelector('.container');
  container.insertBefore(alert, container.firstChild);
  
  setTimeout(() => {
    alert.style.opacity = '0';
    alert.style.transform = 'translateX(30px)';
    setTimeout(() => {
      if (alert.parentNode) {
        alert.parentNode.removeChild(alert);
      }
    }, 300);
  }, 5000);
}

// ============== مستمعي الأحداث ==============
document.getElementById('statusSelect').addEventListener('change', () => {
  currentPage = 1;
  renderTable();
});

document.getElementById('searchInput').addEventListener('input', () => {
  currentPage = 1;
  renderTable();
});

// ============== تهيئة النظام ==============
function initializeSystem() {
  // تعيين تواريخ افتراضية
  const today = new Date();
  const firstDay = new Date(today.getFullYear(), today.getMonth(), 1);
  const lastDay = new Date(today.getFullYear(), today.getMonth() + 1, 0);
  
  document.getElementById('dateFrom').valueAsDate = firstDay;
  document.getElementById('dateTo').valueAsDate = lastDay;
  
  // تعيين التاريخ في نموذج التحميل
  const currentDate = new Date();
  const formattedDate = currentDate.toLocaleDateString('ar-EG');
  console.log(`نظام معالجة البصمات بنظام 24 ساعة - الإصدار 6.0`);
  console.log(`حقوق الملكية © ${currentDate.getFullYear()} Zaid Mazin`);
  console.log(`تاريخ التشغيل: ${formattedDate}`);
  
  showAlert('مرحباً! النظام جاهز لمعالجة بصمات الموظفين بنظام 24 ساعة مع تصفية الأوقات - الإصدار المحدث', 'info');
}

window.addEventListener('DOMContentLoaded', initializeSystem);
</script>
</body>
</html>
