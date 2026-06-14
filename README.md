## 👋 About Me

業務では React + Laravel / React + Hono などの構成で、フロントエンド・バックエンド・AWS インフラ(Terraform)・GitHub Actions による CI/CD まで幅広く扱っています。

---

## 🛠 Projects

### PromptHub — https://www.prompthub.jp
AI プロンプトの投稿・共有プラットフォーム(個人開発・運営中)。Next.js 16 + Supabase(PostgreSQL)+ Stripe で構築し、**AWS Amplify(S3 + CloudFront)** にホスティングしています。Google OAuth 認証 / プロンプト投稿 / いいね・ブックマーク・フォロー / 買い切り決済までを一通り実装しています。

### シフトン — https://shiftmanagements.com
小規模チーム向けのシフト管理アプリ(個人開発・運営中)。**「メンバーはサインアップ不要 — 代表者だけが Google ログインし、メンバーはメールで届く専用 URL から自分のシフトを閲覧できる」** のが最大の特徴です。Next.js 15.5 + Cloudflare Workers(D1 / OpenNext)+ Stripe で構築し、Google OAuth 認証(代表者)/ 推測不可能なトークン URL によるメンバー閲覧(ログイン不要)/ **Cloudflare Cron Triggers + Resend** による前日リマインドメール / Stripe サブスクリプション / 3本構成の GitHub Actions(deploy・migrate・secrets 注入)による CI/CD までを実装しています。

### [react-laravel-practice-public](https://github.com/0000masa/react-laravel-practice-public) 
React + Laravel + Terraform を 1 リポジトリで統合した、フルスタック AWS デプロイの自己学習プロジェクト。ECS Fargate / SQS / EventBridge / OIDC ベースの GitHub Actions / ecspresso による ECS Blue-Green デプロイなど、本番相当の構成を実装しています。

### [react-hono-practice](https://github.com/0000masa/react-hono-practice) 
React + Hono によるサーバーレス Web アプリの自己学習プロジェクト。AWS Lambda + API Gateway + RDS Proxy + SQS + EventBridge の構成で、QR コード生成(同期/非同期)・日次バッチ・Google OAuth 認証などを実装しています。
