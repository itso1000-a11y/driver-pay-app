# Driver Pay App - Vercel-ready

## What changed
- Day type is now clean: Work day / Holiday day / Off day.
- Holiday day does not count hours, bonuses, night out, split break, or food allowance.
- Holiday day only uses the Holiday pay field as taxable pay.
- Off day is pure no-pay / no-shift.
- Work day keeps hours, overtime, bonuses, night out, split break and allowances.

## Deploy to Vercel
1. Go to your Vercel dashboard.
2. Add New Project.
3. Upload/import this folder.
4. Framework preset: Vite.
5. Build command: `npm run build`
6. Output directory: `dist`
7. Deploy.

## Local test
```bash
npm install
npm run dev
```
