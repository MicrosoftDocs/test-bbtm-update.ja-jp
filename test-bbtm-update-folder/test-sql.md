---
title: Microsoft SQL データベースの接続ライブラリ | Microsoft Docs
description: 各種のクライアント プログラミング言語から Microsoft SQL Server および Azure SQL Database への接続を可能にするモジュールのダウンロード リンクを示します。
author: MightyPen
ms.prod: sql
ms.technology: ''
ms.custom: ''
ms.topic: article
ms.date: 06/18/2018
ms.author: genemi
ms.openlocfilehash: f5ecdaad82d0426ebb43ee27908af0fbf4618140
ms.sourcegitcommit: 5c5db3d286fe554884e0e24340468e3fa5e3bea9
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/09/2020
ms.locfileid: "91898852"
---
# <a name="connection-modules-for-microsoft-sql-databases"></a><span data-ttu-id="dba69-103">Microsoft SQL データベースの接続モジュール</span><span class="sxs-lookup"><span data-stu-id="dba69-103">Connection modules for Microsoft SQL databases</span></span>

<span data-ttu-id="dba69-104">この記事では、クライアントプログラムがとの対話に使用できる接続モジュールまたは *ドライバー* のダウンロードリンクと、クラウド [Azure SQL Database](https://docs.microsoft.com/azure/sql-database/)でのツインについて説明します。</span><span class="sxs-lookup"><span data-stu-id="dba69-104">This article provides download links to connection modules or *drivers* that your client programs can use for interacting with, and with its twin in the cloud [Azure SQL Database](https://docs.microsoft.com/azure/sql-database/).</span></span> <span data-ttu-id="dba69-105">次のオペレーティング システムで実行されるさまざまなプログラミング言語用のドライバーが用意されています。</span><span class="sxs-lookup"><span data-stu-id="dba69-105">Drivers are available for a variety of programming languages, running on the following operating systems:</span></span>

- <span data-ttu-id="dba69-106">Linux</span><span class="sxs-lookup"><span data-stu-id="dba69-106">Linux</span></span>
- <span data-ttu-id="dba69-107">MacOS</span><span class="sxs-lookup"><span data-stu-id="dba69-107">MacOS</span></span>
- <span data-ttu-id="dba69-108">Windows</span><span class="sxs-lookup"><span data-stu-id="dba69-108">Windows</span></span>


## <a name="drivers-for-orm-access"></a><span data-ttu-id="dba69-109">ORM アクセス用のドライバー</span><span class="sxs-lookup"><span data-stu-id="dba69-109">Drivers for ORM access</span></span>


<span data-ttu-id="dba69-110">次の表は、クライアントアプリケーションが Microsoft SQL データベースに接続するために使用するオブジェクト リレーショナル マッピング (ORM) フレームワークの例を示しています。</span><span class="sxs-lookup"><span data-stu-id="dba69-110">The following table lists examples of Object Relational Mapping (ORM) frameworks that client applications use to connect to Microsoft SQL databases.</span></span>


| <span data-ttu-id="dba69-111">Language</span><span class="sxs-lookup"><span data-stu-id="dba69-111">Language</span></span> | <span data-ttu-id="dba69-112">ORM ドライバーのダウンロード</span><span class="sxs-lookup"><span data-stu-id="dba69-112">ORM driver download</span></span> |
| :------- | :------------------ |
| <span data-ttu-id="dba69-113">C#</span><span class="sxs-lookup"><span data-stu-id="dba69-113">C#</span></span> | [<span data-ttu-id="dba69-114">Entity Framework Core</span><span class="sxs-lookup"><span data-stu-id="dba69-114">Entity Framework Core</span></span>](https://docs.microsoft.com/ef/core/)<br />[<span data-ttu-id="dba69-115">Entity Framework (6.x 以降)</span><span class="sxs-lookup"><span data-stu-id="dba69-115">Entity Framework (6.x or later)</span></span>](https://docs.microsoft.com/ef/) |
| <span data-ttu-id="dba69-116">Java</span><span class="sxs-lookup"><span data-stu-id="dba69-116">Java</span></span> | [<span data-ttu-id="dba69-117">Hibernate ORM</span><span class="sxs-lookup"><span data-stu-id="dba69-117">Hibernate ORM</span></span>](https://hibernate.org/orm)|
| <span data-ttu-id="dba69-118">PHP</span><span class="sxs-lookup"><span data-stu-id="dba69-118">PHP</span></span> | [<span data-ttu-id="dba69-119">Eloquent ORM (Laravel のインストールに含まれています)</span><span class="sxs-lookup"><span data-stu-id="dba69-119">Eloquent ORM, included in Laravel install</span></span>](https://laravel.com/docs/) |
| <span data-ttu-id="dba69-120">Node.js</span><span class="sxs-lookup"><span data-stu-id="dba69-120">Node.js</span></span> | [<span data-ttu-id="dba69-121">Sequelize ORM</span><span class="sxs-lookup"><span data-stu-id="dba69-121">Sequelize ORM</span></span>](https://docs.sequelizejs.com) |
| <span data-ttu-id="dba69-122">Python</span><span class="sxs-lookup"><span data-stu-id="dba69-122">Python</span></span> | [<span data-ttu-id="dba69-123">Django</span><span class="sxs-lookup"><span data-stu-id="dba69-123">Django</span></span>](https://www.djangoproject.com/) |
| <span data-ttu-id="dba69-124">Ruby</span><span class="sxs-lookup"><span data-stu-id="dba69-124">Ruby</span></span> | [<span data-ttu-id="dba69-125">Ruby on Rails</span><span class="sxs-lookup"><span data-stu-id="dba69-125">Ruby on Rails</span></span>](https://rubyonrails.org/) |

