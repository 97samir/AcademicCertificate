# 🎓 AcademicCertificateNFT

Este proyecto permite emitir, verificar y revocar certificados académicos digitales en forma de NFT, garantizando su autenticidad y trazabilidad en una red blockchain (como Polygon o Ethereum).

## 🚀 Descripción
El contrato inteligente **AcademicCertificate** fue desarrollado en Solidity y utiliza la librería **OpenZeppelin** para implementar el estándar ERC-721 (NFTs).  
Su objetivo es permitir que una institución educativa emita certificados únicos e inalterables a estudiantes, manteniendo la transparencia y validez de cada título emitido.

## 🧱 Funcionalidades principales
- **Emitir certificado:** Crea un NFT con los datos del estudiante y el curso.
- **Revocar certificado:** Permite invalidar un certificado si se detecta un error o fraude.
- **Verificar validez:** Cualquier persona puede consultar si un certificado sigue siendo válido.

## ⚙️ Requisitos
- **Remix IDE** o entorno de desarrollo Solidity.
- **MetaMask** conectado a la red de prueba (como Polygon Amoy).
- **MATIC o ETH de prueba** para realizar las transacciones.

## 🧩 Tecnologías utilizadas
- **Solidity 0.8.20**  
- **OpenZeppelin Contracts 4.9.3**  
- **ERC721 (NFT)**  
- **Ownable (control de propiedad del contrato)**  

## 🧠 Cómo usarlo
1. Compila el contrato en Remix.
2. Conéctate con MetaMask (Polygon Amoy Testnet).
3. Despliega el contrato (`Deploy`).
4. Usa las funciones disponibles:
   - `issueCertificate()` → emitir nuevo certificado.
        to (destino),tokenURI (hash),studentName,institutionName,courseName
   - `revokeCertificate()` → revocar certificado. = tokenId
   - `isCertificateValid()` → consultar si sigue activo. = tokenId

## 📜 Licencia
Este proyecto usa la licencia **MIT**, lo que permite su uso y adaptación libremente para fines educativos o de desarrollo.

---

## 👤 Autor
Desarrollado por **[Tu nombre]**  
Proyecto académico basado en certificación blockchain.
