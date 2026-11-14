# Olá, eu sou o Neto 

Profissional de **TI com foco em DevOps e Cloud**, com experiência em suporte e administração de ambientes Windows e Linux. Aprendo na prática: monto, quebro e conserto infraestrutura no meu próprio homelab e documento o que descubro.


📍 Brasil · 📝 Blog: [devopsr66.com](https://devopsr66.com) · 💼 [LinkedIn](https://www.linkedin.com/in/divino-sabino-moreira-neto-918844108)

---

## 🧪 O que eu construí

Um **cluster Kubernetes próprio (kubeadm, 3 nós)**, criado do zero e gerenciado como código:

- **Provisionamento:** Vagrant e Ansible criam as VMs e o cluster → [`devops-infrastructure-as-code`](https://github.com/lotechdevops/devops-infrastructure-as-code)
- **GitOps com Argo CD:** 8 aplicações de infraestrutura migradas **sem recriar nada** do que já rodava → [`gitops-homelab`](https://github.com/lotechdevops/gitops-homelab)
- **Segredos seguros no Git** com Sealed Secrets (nenhuma credencial em texto puro)
- **Observabilidade:** Prometheus, Grafana e Alertmanager com alertas no Telegram
- **Rede e TLS:** MetalLB, Traefik e cert-manager com Let's Encrypt (desafio DNS01)

```text
Vagrant ─► VMs ─► Ansible ─► cluster Kubernetes ─► Argo CD ◄── Git (gitops-homelab)
                                                      │
              MetalLB · Traefik · cert-manager · Sealed Secrets · Prometheus/Grafana
```

---

## 🛠️ Ferramentas com as quais trabalho

| Área | Ferramentas |
|---|---|
| **Cloud** | AWS | Google Cloud
| **Containers e orquestração** | Kubernetes (kubeadm), Helm, Kustomize | Docker
| **GitOps / CD** | Argo CD, Sealed Secrets |
| **Infraestrutura como código** | Ansible, Vagrant | Terraform
| **Rede e certificados** | MetalLB, Traefik, cert-manager, Cloudflare, Calico |
| **Observabilidade** | Prometheus, Grafana, Alertmanager |
| **Armazenamento** | NFS (provisionamento dinâmico) |
| **Sistemas** | Linux, Windows, Active Directory, Group Policy |
| **Segurança** | EDR | gestão de patches, gestão de segredos |

---

## 📚 Estudando agora

- ☁️ Cloud: aprofundando em serviços gerenciados da AWS
- 🔁 CI/CD e automação de pipelines
- 🌍 Idiomas

---

## ✍️ Escrevo sobre o que aprendo

No blog [**devopsr66.com**](https://devopsr66.com) publico guias e laboratórios práticos, em português, como o passo a passo de Argo CD que usei para aprender (conceitos e 8 laboratórios hands-on).

---

## 📫 Contato

- LinkedIn: [LinkeIn](https://www.linkedin.com/in/divino-sabino-moreira-neto-918844108)
- Blog: [devopsr66.com](https://devopsr66.com)