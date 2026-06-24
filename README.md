<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Professional Evaluation UI</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    body { 
      font-family: 'Inter', sans-serif; 
      background-color: #f8fafc; /* Soft slate background to make white cards pop */
    }
  </style>
</head>
<body class="text-slate-800 p-6 md:p-12">

  <div class="max-w-7xl mx-auto space-y-8">
    
    <div>
      <h1 class="text-3xl font-bold text-slate-900 tracking-tight">Evaluation</h1>
      <p class="text-slate-500 mt-2 text-sm">Review academic performance and grade history.</p>
    </div>

    <div class="flex items-center">
      <div class="relative inline-block text-left">
        <select class="appearance-none bg-white border border-slate-300 hover:border-slate-400 text-slate-700 py-2.5 pl-4 pr-10 rounded-lg shadow-sm focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 font-medium text-sm transition-colors cursor-pointer">
          <option>SY 2023–2024</option>
          <option>SY 2024–2025</option>
          <option>SY 2025–2026</option>
        </select>
        <div class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-3 text-slate-500">
          <svg class="h-4 w-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
        </div>
      </div>
    </div>

    <div class="grid grid-cols-1 xl:grid-cols-2 gap-8">
      
      <div class="bg-white rounded-2xl shadow-sm border border-slate-200 overflow-hidden flex flex-col">
        <div class="px-6 py-5 border-b border-slate-100 bg-slate-50/50">
          <h2 class="text-lg font-semibold text-slate-800">First Semester</h2>
        </div>
        
        <div class="overflow-x-auto">
          <table class="w-full text-left border-collapse">
            <thead>
              <tr class="text-xs text-slate-500 uppercase tracking-wider border-b border-slate-100 bg-white">
                <th class="px-6 py-4 font-semibold w-1/4">Code</th>
                <th class="px-6 py-4 font-semibold w-1/2">Subject</th>
                <th class="px-6 py-4 font-semibold text-center w-1/12">Units</th>
                <th class="px-6 py-4 font-semibold text-right w-1/6">Grade</th>
              </tr>
            </thead>
            <tbody class="text-sm divide-y divide-slate-100">
              <tr class="hover:bg-slate-50 transition-colors">
                <td class="px-6 py-4 font-medium text-slate-900">FIL 1</td>
                <td class="px-6 py-4 text-slate-600">Akademiko sa Wikang Filipino</td>
                <td class="px-6 py-4 text-center text-slate-500">3</td>
                <td class="px-6 py-4 text-right font-medium text-slate-900">1.00</td>
              </tr>
              <tr class="hover:bg-slate-50 transition-colors">
                <td class="px-6 py-4 font-medium text-slate-900">GE 4</td>
                <td class="px-6 py-4 text-slate-600">Mathematics in the Modern World</td>
                <td class="px-6 py-4 text-center text-slate-500">3</td>
                <td class="px-6 py-4 text-right font-medium text-slate-900">1.00</td>
              </tr>
              <tr class="hover:bg-slate-50 transition-colors">
                <td class="px-6 py-4 font-medium text-slate-900">ITS 100</td>
                <td class="px-6 py-4 text-slate-600">Introduction to Computing</td>
                <td class="px-6 py-4 text-center text-slate-500">3</td>
                <td class="px-6 py-4 text-right font-medium text-slate-900">1.00</td>
              </tr>
              <tr class="hover:bg-slate-50 transition-colors">
                <td class="px-6 py-4 font-medium text-slate-900">ITS 101</td>
                <td class="px-6 py-4 text-slate-600">Computer Programming 1</td>
                <td class="px-6 py-4 text-center text-slate-500">3</td>
                <td class="px-6 py-4 text-right font-medium text-slate-900">1.00</td>
              </tr>
            </tbody>
          </table>
        </div>
        
        <div class="px-6 py-4 bg-slate-50/50 border-t border-slate-100 flex justify-between items-center mt-auto">
          <span class="text-sm text-slate-500">Total Units: <strong class="text-slate-900 font-semibold">23</strong></span>
          <div class="flex items-center gap-2">
            <span class="text-sm text-slate-500 font-medium">GPA:</span>
            <span class="inline-flex items-center px-2.5 py-1 rounded-md text-sm font-semibold bg-blue-50 text-blue-700 ring-1 ring-inset ring-blue-700/10">1.13</span>
          </div>
        </div>
      </div>

      <div class="bg-white rounded-2xl shadow-sm border border-slate-200 overflow-hidden flex flex-col">
        <div class="px-6 py-5 border-b border-slate-100 bg-slate-50/50">
          <h2 class="text-lg font-semibold text-slate-800">Second Semester</h2>
        </div>
        
        <div class="overflow-x-auto">
          <table class="w-full text-left border-collapse">
            <thead>
              <tr class="text-xs text-slate-500 uppercase tracking-wider border-b border-slate-100 bg-white">
                <th class="px-6 py-4 font-semibold w-1/4">Code</th>
                <th class="px-6 py-4 font-semibold w-1/2">Subject</th>
                <th class="px-6 py-4 font-semibold text-center w-1/12">Units</th>
                <th class="px-6 py-4 font-semibold text-right w-1/6">Grade</th>
              </tr>
            </thead>
            <tbody class="text-sm divide-y divide-slate-100">
              <tr class="hover:bg-slate-50 transition-colors">
                <td class="px-6 py-4 font-medium text-slate-900">GE 1</td>
                <td class="px-6 py-4 text-slate-600">Understanding the Self</td>
                <td class="px-6 py-4 text-center text-slate-500">3</td>
                <td class="px-6 py-4 text-right font-medium text-slate-900">1.00</td>
              </tr>
              <tr class="hover:bg-slate-50 transition-colors">
                <td class="px-6 py-4 font-medium text-slate-900">GE 2</td>
                <td class="px-6 py-4 text-slate-600">Readings in Philippine History</td>
                <td class="px-6 py-4 text-center text-slate-500">3</td>
                <td class="px-6 py-4 text-right font-medium text-slate-900">1.50</td>
              </tr>
              <tr class="hover:bg-slate-50 transition-colors">
                <td class="px-6 py-4 font-medium text-slate-900">ITS 103</td>
                <td class="px-6 py-4 text-slate-600">Discrete Mathematics</td>
                <td class="px-6 py-4 text-center text-slate-500">3</td>
                <td class="px-6 py-4 text-right font-medium text-slate-900">2.20</td>
              </tr>
              <tr class="hover:bg-slate-50 transition-colors">
                <td class="px-6 py-4 font-medium text-slate-900">ITS 104</td>
                <td class="px-6 py-4 text-slate-600">Computer Programming II</td>
                <td class="px-6 py-4 text-center text-slate-500">3</td>
                <td class="px-6 py-4 text-right font-medium text-slate-900">1.00</td>
              </tr>
            </tbody>
          </table>
        </div>
        
        <div class="px-6 py-4 bg-slate-50/50 border-t border-slate-100 flex justify-between items-center mt-auto">
          <span class="text-sm text-slate-500">Total Units: <strong class="text-slate-900 font-semibold">29</strong></span>
          <div class="flex items-center gap-2">
            <span class="text-sm text-slate-500 font-medium">GPA:</span>
            <span class="inline-flex items-center px-2.5 py-1 rounded-md text-sm font-semibold bg-blue-50 text-blue-700 ring-1 ring-inset ring-blue-700/10">1.31</span>
          </div>
        </div>
      </div>

    </div>
  </div>

</body>
</html>
