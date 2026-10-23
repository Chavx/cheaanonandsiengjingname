ការដំឡើង Link អញ្ជើញខ្លី (Cloudflare Pages)

- Link ថ្មីមានទម្រង់ https://your-domain.pages.dev/?i=AbCdEf123456
- ឈ្មោះភ្ញៀវត្រូវរក្សាទុកក្នុង Cloudflare KV ដើម្បីអាចបើកតាម ID ខ្លី។
- QR Code, Copy Link, Telegram និង Copy Message ប្រើ Link ខ្លីថ្មី។
- Link ចាស់ដែលប្រើ ?to=... នៅតែអាចបើកបាន។

ជំហានដំឡើង៖
1. ដាក់ index.html និង folder functions/ ទាំងមូលក្នុង project Cloudflare Pages របស់អ្នក។
2. Cloudflare Dashboard > Workers & Pages > ជ្រើស project pisethandmonypenita។
3. Settings > Bindings > Add > KV namespace។
4. បង្កើត/ជ្រើស KV namespace ហើយដាក់ Variable name = INVITATIONS។
5. Save ហើយ Redeploy project។

សំខាន់៖ កុំ upload តែ index.html មួយឯកសារ។ ត្រូវ deploy folder functions/ ផង និង bind KV namespace ឈ្មោះ INVITATIONS។ បើមិនដំឡើង API/KV ទេ Link ថ្មីនឹងមិនអាចរកឈ្មោះភ្ញៀវតាម ID បាន។
